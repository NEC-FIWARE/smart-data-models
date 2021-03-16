# 公衆トイレ一覧

公衆トイレの一覧。
-  `都道府県コード又は市区町村コード`: 情報の管理主体である地方公共団体の都道府県コード又は市区町村コードを記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `NO`: 情報の管理主体である地方公共団体内でデータが一意に決まるよう、NOを設定し記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `都道府県名`: 情報の管理主体である地方公共団体名について、都道府県名を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `市区町村名`: 情報の管理主体である地方公共団体名について、市区町村名を記載。都道府県については記載不要。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `名称`: 公衆トイレの設置施設の通称や建物等の名前を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `名称_カナ`: 公衆トイレの設置施設の通称や建物等の名前をカナで記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `名称_英語`: 公衆トイレの設置施設の通称や建物等の名前を英語で記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `住所`: 公衆トイレの設置施設の住所を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `方書`: 公衆トイレの設置施設の住所の方書を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `設置位置`: 公衆トイレの施設における詳細な設置位置を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `緯度`: 公衆トイレの設置施設の緯度を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `経度`: 公衆トイレの設置施設の経度を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `男性トイレ総数`: 男性トイレの総数を数字で記載。（便座単位）
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `男性トイレ数（小便器）`: 男性トイレの中で、小便器の総数を数字で記載。（便座単位）
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `男性トイレ数（和式）`: 男性トイレの中で、個室の和式便器の総数を数字で記載。（便座単位）
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `男性トイレ数（洋式）`: 男性トイレの中で、個室の様式便器の総数を数字で記載。（便座単位）
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `女性トイレ総数`: 女性トイレの総数を数字で記載。（便座単位）
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `女性トイレ数（和式）`: 女性トイレの中で、個室の和式便器の総数を数字で記載。（便座単位）
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `女性トイレ数（洋式）`: 女性トイレの中で、個室の様式便器の総数を数字で記載。（便座単位）
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `男女共用トイレ総数`: 男女共用トイレの総数を数字で記載。（便座単位）
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `男女共用トイレ数（和式）`: 男女共用トイレの中で、個室の和式便器の総数を数字で記載。（便座単位）
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `男女共用トイレ数（洋式）`: 男女共用トイレの中で、個室の様式便器の総数を数字で記載。（便座単位）
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `多機能トイレ数`: 多機能トイレ（注2）の総数を数字で記載。（便座単位）
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Required
-  `車椅子使用者用トイレ有無`: 車椅子使用者用トイレの設置有無を記載。. One of : `有`, `無`.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `乳幼児用設備設置トイレ有無`: 乳幼児用設備設置トイレの設置有無を記載。. One of : `有`, `無`.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `オストメイト設置トイレ有無`: オストメイト設置トイレの設置有無を記載。. One of : `有`, `無`.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `利用開始時間`: 公衆トイレが利用可能となる開始時間を記載。
   -  Attribute type: **Property**. [Time](https://schema.org/Time)
   -  Optional
-  `利用終了時間`: 公衆トイレが利用不可となる終了時間を記載。
   -  Attribute type: **Property**. [Time](https://schema.org/Time)
   -  Optional
-  `利用可能時間特記事項`: 利用開始時間、利用終了時間についての特記事項・例外（祝日、年末年始の変更点など）等があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `画像`: 画像の格納先URLを記載。
   -  Attribute type: **Property**. [URL](https://schema.org/URL)
   -  Optional
-  `画像_ライセンス`: 画像に対するライセンスについて記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `備考`: 特記事項があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `location`: location
   -  Attribute type: **Property**. [StructuredValue](https://schema.org/StructuredValue)
   -  Optional



## Examples

### OK


