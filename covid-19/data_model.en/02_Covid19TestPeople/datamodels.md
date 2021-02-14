# Covid19TestPeople

PCR検査を受けた人の数を日別に集計したデータ
-  `testedAt`: 検査を実施した年月日を記載。
   -  Attribute type: **Property**. [DateTime](https://schema.org/DateTime)
   -  Required
-  `municipalityCode`: 総務省の定める全国地方公共団体コード（6桁コード）を記載。6桁に満たない場合、先頭は0埋めとする。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `prefectureName`: 情報の管理主体である地方公共団体名について、都道府県名を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `cityName`: 情報の管理主体である地方公共団体名について、市区町村名を記載。※都道府県については記載不要。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `numberOfTestedPeople`: 検査を受けた人の数を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Required
-  `remarks`: 備考があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional



## Examples

### OK


