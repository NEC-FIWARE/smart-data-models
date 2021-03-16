# 消防水利施設一覧

消防水利施設の一覧。
-  `都道府県コード又は市区町村コード`: 情報の管理主体である地方公共団体の都道府県コード又は市区町村コードを記載。※記載方法について、「データ項目特記事項」シートの【共通ルール】を参照。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `NO`: 情報の管理主体である地方公共団体内でデータが一意に決まるよう、NOを設定し記載。※記載方法について、「データ項目特記事項」シートの【共通ルール】を参照。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `都道府県名`: 情報の管理主体である地方公共団体名について、都道府県名を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `市区町村名`: 情報の管理主体である地方公共団体名について、市区町村名を記載。都道府県については記載不要。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `種別`: 消防水利施設の種類を記載。※記載内容について、「データ項目特記事項」シートの【09.消防水利施設一覧】を参照。. One of : `消火栓`, `私設消火栓`, `防火水そう`, `プール`, `河川・溝等`, `濠・池等`, `海・湖`, `井戸`, `下水道`, `その他`.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `住所`: 消防水利施設の住所を記載。※記載方法について、「データ項目特記事項」シートの【共通ルール】を参照。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `方書`: 消防水利施設の住所の方書を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `緯度`: 消防水利施設の緯度を記載。※記載方法について、「データ項目特記事項」シートの【共通ルール】を参照。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `経度`: 消防水利施設の経度を記載。※記載方法について、「データ項目特記事項」シートの【共通ルール】を参照。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `口径`: 消防水利施設が対応する口径をミリメートル単位で記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `備考`: 特記事項があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `location`: location
   -  Attribute type: **Property**. [StructuredValue](https://schema.org/StructuredValue)
   -  Optional



## Examples

### OK


