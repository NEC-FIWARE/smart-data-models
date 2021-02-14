# 陰性確認数

陰性確認が完了した件数を日別に集計したデータ
-  `完了_年月日`: 陰性確認が完了した年月日を記載。
   -  Attribute type: **Property**. [DateTime](https://schema.org/DateTime)
   -  Required
-  `全国地方公共団体コード`: 総務省の定める全国地方公共団体コード（6桁コード）を記載。6桁に満たない場合、先頭は0埋めとする。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `都道府県名`: 情報の管理主体である地方公共団体名について、都道府県名を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `市区町村名`: 情報の管理主体である地方公共団体名について、市区町村名を記載。※都道府県については記載不要。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `陰性確認_件数`: 陰性確認が完了した件数を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Required
-  `備考`: 備考があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional



## Examples

### OK


