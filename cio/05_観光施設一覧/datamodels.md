# 観光施設一覧

観光施設の情報の一覧。
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
-  `名称`: 観光施設の通称や建物等の名前を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `名称_カナ`: 観光施設の通称や建物等の名前をカナで記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `名称_英語`: 観光施設の通称や建物等の名前を英語で記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `POIコード`: 観光施設のPOIコードを記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `住所`: 観光施設の住所を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `方書`: 観光施設の住所の方書を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `緯度`: 観光施設の緯度を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `経度`: 観光施設の経度を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `利用可能曜日`: 観光施設が観光できる曜日を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `開始時間`: 開始時間を記載。
   -  Attribute type: **Property**. [Time](https://schema.org/Time)
   -  Optional
-  `終了時間`: 終了時間を記載。
   -  Attribute type: **Property**. [Time](https://schema.org/Time)
   -  Optional
-  `利用可能日時特記事項`: 利用可能曜日、開始時間、終了時間についての特記事項・例外（祝日、年末年始の変更点など）等があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `料金(基本)`: 観光施設を観光するために必要な基本料金を日本円で記載。(1円単位)
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `料金(詳細)`: 観光施設を観光するために必要な各種料金を日本円で記載。(1円単位)
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `説明`: 観光施設の説明を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `説明_英語`: 観光施設の説明を英語で記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `アクセス方法`: 観光施設への公共交通や車でのアクセス方法を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `駐車場情報`: 観光施設の駐車・駐輪スペースについて記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `バリアフリー情報`: バリアフリー情報を「;」（半角のセミコロン）区切りで記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `連絡先名称`: 観光施設の管理者の問い合わせ先部署名を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `連絡先電話番号`: 観光施設の管理者の連絡先（電話番号）を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `連絡先内線番号`: 観光施設の管理者の連絡先（内線番号）を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `画像`: 画像の格納先URLを記載。
   -  Attribute type: **Property**. [URL](https://schema.org/URL)
   -  Optional
-  `画像_ライセンス`: 画像に対するライセンスについて記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `URL`: 観光施設のHPのURLを記載。
   -  Attribute type: **Property**. [URL](https://schema.org/URL)
   -  Optional
-  `備考`: 特記事項等あれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `location`: location
   -  Attribute type: **Property**. [StructuredValue](https://schema.org/StructuredValue)
   -  Optional



## Examples

### OK


