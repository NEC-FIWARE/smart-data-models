# 医療機関一覧

病院・診療所についての一覧。
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
-  `名称`: 医療機関の名称を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `名称_カナ`: 医療機関の名称をカナで記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `医療機関の種類`: 医療機関の種類を記載。. One of : `病院`, `有床診療所`, `無床診療所`.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `住所`: 医療機関の開設場所の住所を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `方書`: 医療機関の開設場所の住所の方書を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `緯度`: 医療機関の開設場所の緯度を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `経度`: 医療機関の開設場所の経度を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `電話番号`: 医療機関の連絡先（電場番号）を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `内線番号`: 医療機関の連絡先（内線番号）を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `FAX番号`: 医療機関のFAX番号を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `法人番号`: 医療機関の運営主体の法人番号を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `法人の名称`: 医療機関の運営主体の法人名称を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `医療機関コード`: 医療機関の医療機関コードを記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `診療曜日`: 医療機関の診療曜日を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `診療開始時間`: 医療機関の診療開始時間を記載。
   -  Attribute type: **Property**. [Time](https://schema.org/Time)
   -  Required
-  `診療終了時間`: 医療機関の診療終了時間を記載。
   -  Attribute type: **Property**. [Time](https://schema.org/Time)
   -  Required
-  `診療日時特記事項`: 診療曜日、診療開始時間、診療終了時間についての特記事項・例外（祝日、年末年始の変更点など）等があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `時間外における対応`: 医療機関の診療時間外における対応内容を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `診療科目`: 医療機関の診療科目を「;」（半角のセミコロン）区切りで記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `病床数`: 医療機関の病床数を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Required
-  `URL`: 医療機関のWebサイトを参照するURLを記載。
   -  Attribute type: **Property**. [URL](https://schema.org/URL)
   -  Required
-  `備考`: 特記事項等があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `location`: location
   -  Attribute type: **Property**. [StructuredValue](https://schema.org/StructuredValue)
   -  Optional



## Examples

### OK


