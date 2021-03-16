# 子育て施設一覧

幼稚園、保育園、認定こども園の一覧。
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
-  `名称`: 子育て施設（注1）の通称や建物等の名前を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `名称_カナ`: 子育て施設の通称や建物等の名前をカナで記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `種別`: 子育て施設の種別を記載。. One of : `公立幼稚園`, `私立幼稚園`, `認可公立保育所`, `認可私立保育所`, `認可外保育所`, `認定こども園（幼保連携型）`, `認定こども園（幼稚園型）`, `認定こども園（保育所型）`, `認定こども園（地方裁量型）`.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `住所`: 子育て施設の住所を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `方書`: 子育て施設の住所の方書を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `緯度`: 子育て施設の設置場所の緯度を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `経度`: 子育て施設の設置場所の経度を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `アクセス方法`: 子育て施設への公共交通や車でのアクセス方法を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `駐車場情報`: 子育て施設の駐車・駐輪スペースについて記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `電話番号`: 子育て施設の連絡先（電話番号）を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `内線番号`: 子育て施設の連絡先（内線番号）を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `FAX番号`: 子育て施設のFAX番号を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `法人番号`: 子育て施設の設置団体の法人番号を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `団体名`: 子育て施設の設置団体の名称を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `認可等年月日`: 認可又は認定をもらった時の年月日を記載。
   -  Attribute type: **Property**. [Date](https://schema.org/Date)
   -  Optional
-  `収容定員`: 収容できる定員数を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `受入年齢`: 利用可能年齢を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `利用可能曜日`: 子育て施設の利用可能な曜日を記載。
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
-  `一時預かりの有無`: 一時預かりがあるかどうかを記載。. One of : `有`, `無`.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `URL`: 施設のURLを記載。
   -  Attribute type: **Property**. [URL](https://schema.org/URL)
   -  Optional
-  `備考`: 特記事項があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `location`: location
   -  Attribute type: **Property**. [StructuredValue](https://schema.org/StructuredValue)
   -  Optional



## Examples

### OK


