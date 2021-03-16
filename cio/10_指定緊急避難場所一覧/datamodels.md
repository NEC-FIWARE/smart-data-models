# 指定緊急避難場所一覧

市区町村から提供される指定緊急避難場所の一覧。
-  `NO`: 地方公共団体内で指定緊急避難場所が一意に決まるよう、NOを設定し、記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `名称`: 指定緊急避難場所の通称や建物等の名前を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `名称_カナ`: 指定緊急避難場所の通称や建物等の名前をカナで記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `住所`: 指定緊急避難場所の住所を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `方書`: 指定緊急避難場所の住所の方書を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `緯度`: 指定緊急避難場所の緯度を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `経度`: 指定緊急避難場所の経度を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `標高`: 指定緊急避難場所の標高をｍ単位で記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `電話番号`: 指定緊急避難場所の連絡先（電話番号）を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `内線番号`: 指定緊急避難場所の連絡先（内線番号）を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `市区町村コード`: 設置主体である市区町村コードを記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `都道府県名`: 設置主体である地方公共団体名について、都道府県名を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `市区町村名`: 設置主体である地方公共団体名について、市区町村名を記載。都道府県については記載不要。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `災害種別_洪水`: 指定緊急避難場所が対応している災害(火災)を記載。. One of : `1`, ``.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `災害種別_崖崩れ、土石流及び地滑り`: 指定緊急避難場所が対応している災害(崖崩れ、土石流及び地滑り)を記載。. One of : `1`, ``.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `災害種別_高潮`: 指定緊急避難場所が対応している災害(高潮)を記載。. One of : `1`, ``.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `災害種別_地震`: 指定緊急避難場所が対応している災害(地震)を記載。. One of : `1`, ``.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `災害種別_津波`: 指定緊急避難場所が対応している災害(津波)を記載。. One of : `1`, ``.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `災害種別_大規模な火事`: 指定緊急避難場所が対応している災害(大規模な火事)を記載。. One of : `1`, ``.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `災害種別_内水氾濫`: 指定緊急避難場所が対応している災害(内水氾濫)を記載。. One of : `1`, ``.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `災害種別_火山現象`: 指定緊急避難場所が対応している災害(火山現象)を記載。. One of : `1`, ``.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `指定避難所との重複`: 指定避難所との重複している施設の際に記載。. One of : `1`, ``.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `想定収容人数`: 指定緊急避難場所に収容可能な人数を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `対象となる町会・自治会`: 指定緊急避難場所へ避難する対象の地域等を「;」（半角のセミコロン）区切りで記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `URL`: 指定緊急避難場所のHPのURLを記載。
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


