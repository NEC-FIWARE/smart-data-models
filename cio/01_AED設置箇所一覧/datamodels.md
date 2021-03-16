# AED設置箇所一覧

AEDの設置箇所についての一覧。
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
-  `名称`: AEDが設置場所の建物等の名称を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `名称_カナ`: AEDが設置場所の建物等の名称をカナで記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `住所`: AED設置場所の住所を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `方書`: AED設置場所の住所の方書を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `緯度`: AED設置場所の緯度を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `経度`: AED設置場所の経度を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `設置位置`: AED設置場所における詳細位置を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `電話番号`: AED設置場所の連絡先（電話番号）を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `内線番号`: AED設置場所の連絡先（内線番号）を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `法人番号`: AED設置主体の法人番号を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `団体名`: AED設置主体の名称を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `利用可能曜日`: AED設置場所が利用可能な曜日を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `開始時間`: AED設置場所の開始時間（開館時間など）を記載。
   -  Attribute type: **Property**. [Time](https://schema.org/Time)
   -  Optional
-  `終了時間`: AED設置場所の終了時間（閉館時間など）を記載。
   -  Attribute type: **Property**. [Time](https://schema.org/Time)
   -  Optional
-  `利用可能日時特記事項`: 利用可能曜日、開始時間、終了時間についての特記事項・例外（祝日、年末年始の変更点など）等があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `小児対応設備の有無`: 小児対応設備の有無を記載。. One of : `有`, `無`.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `URL`: AED設置場所に関する情報源を示すサイト等を記載。
   -  Attribute type: **Property**. [URL](https://schema.org/URL)
   -  Optional
-  `備考`: 特記事項等があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `location`: location
   -  Attribute type: **Property**. [StructuredValue](https://schema.org/StructuredValue)
   -  Optional



## Examples

### OK


