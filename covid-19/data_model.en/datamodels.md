# Covid19Patients


-  `patientNo`: 患者を識別できるように、データセット内で一意に定まる番号を設定し記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `municipalityCode`: 総務省の定める全国地方公共団体コード（6桁コード）を記載。6桁に満たない場合、先頭は0埋めとする。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `prefectureName`: 情報の管理主体である地方公共団体名について、都道府県名を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `cityName`: 情報の管理主体である地方公共団体名について、市区町村名を記載。※都道府県については記載不要。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `publishedAt`: 患者情報を公表した年月日を記載。
   -  Attribute type: **Property**. [DateTime](https://schema.org/DateTime)
   -  Required
-  `symptomOnsetAt`: 発症が確認された年月日を記載。
   -  Attribute type: **Property**. [DateTime](https://schema.org/DateTime)
   -  Optional
-  `patientResidence`: 患者の居住地を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `patientAge`: 患者の年代を次のいずれかの値で記載。（不明やその他公開できない場合は空欄とする）{10歳未満, 10代, 20代, 30代, 40代, 50代, 60代, 70代, 80代, 90歳以上}
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `patientGender`: 患者の性別。次のいずれかの文字列で記載。（不明やその他公開できない場合は空欄とする）{男性, 女性, その他}
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `patientOccupation`: 患者の職業を記載。（不明やその他公開できない場合は空欄とする）
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `patientCondition`: 患者の状態を次のいずれかの文字列で記載。（不明やその他公開できない場合は空欄とする）{無症状, 軽症, 中等症, 重症, 死亡}
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `patientSymptoms`: 患者の症状を記載。複数ある場合は「;」（半角のセミコロン）区切りで記載する。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `patientTravelHistory`: 以下のいずれかの値を記載（数字は半角） 海外渡航歴あり：1, 海外渡航歴なし：0,  不明：-1
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `patientDischarged`: 以下のいずれかの値を記載（数字は半角） 退院済：1, 入院中：0, 不明：-1
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `remarks`: 備考があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional



# Covid19TestPeople


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



# Covid19TestCount


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
-  `numberOfTests`: 検査を実施した件数を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `remarks`: 備考があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional



# Covid19ConfirmNegative


-  `confirmedNegativeAt`: 陰性確認が完了した年月日を記載。
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
-  `numberOfNegatives`: 陰性確認が完了した件数を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Required
-  `remarks`: 備考があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional



# Covid19CallCenter


-  `acceptedAt`: 患者情報を公表した年月日を記載。
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
-  `numberOfCalls`: コールセンターで受け付けた相談の件数を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Required
-  `remarks`: 備考があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional



## Examples

### OK


