# 陽性患者属性


-  `No`: 患者を識別できるように、データセット内で一意に定まる番号を設定し記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `全国地方公共団体コード`: 総務省の定める全国地方公共団体コード（6桁コード）を記載。6桁に満たない場合、先頭は0埋めとする。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `都道府県名`: 情報の管理主体である地方公共団体名について、都道府県名を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `市区町村名`: 情報の管理主体である地方公共団体名について、市区町村名を記載。※都道府県については記載不要。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `公表_年月日`: 患者情報を公表した年月日を記載。
   -  Attribute type: **Property**. [DateTime](https://schema.org/DateTime)
   -  Required
-  `発症_年月日`: 発症が確認された年月日を記載。
   -  Attribute type: **Property**. [DateTime](https://schema.org/DateTime)
   -  Optional
-  `患者_居住地`: 患者の居住地を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `患者_年代`: 患者の年代を次のいずれかの値で記載。（不明やその他公開できない場合は空欄とする）{10歳未満, 10代, 20代, 30代, 40代, 50代, 60代, 70代, 80代, 90歳以上}
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `患者_性別`: 患者の性別。次のいずれかの文字列で記載。（不明やその他公開できない場合は空欄とする）{男性, 女性, その他}
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `患者_職業`: 患者の職業を記載。（不明やその他公開できない場合は空欄とする）
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `患者_状態`: 患者の状態を次のいずれかの文字列で記載。（不明やその他公開できない場合は空欄とする）{無症状, 軽症, 中等症, 重症, 死亡}
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `患者_症状`: 患者の症状を記載。複数ある場合は「;」（半角のセミコロン）区切りで記載する。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `患者_渡航歴の有無フラグ`: 以下のいずれかの値を記載（数字は半角） 海外渡航歴あり：1 海外渡航歴なし：0 不明：（空のまま）
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `患者_退院済フラグ`: 以下のいずれかの値を記載（数字は半角） 退院済：1 入院中：0 不明：（空のまま）
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `備考`: 備考があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional



# 検査実施人数


-  `実施_年月日`: 検査を実施した年月日を記載。
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
-  `検査実施_人数`: 検査を受けた人の数を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Required
-  `備考`: 備考があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional



# 検査実施件数


-  `実施_年月日`: 検査を実施した年月日を記載。
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
-  `検査実施_件数`: 検査を実施した件数を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Required
-  `備考`: 備考があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional



# 陰性確認数


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



# コールセンター相談件数


-  `受付_年月日`: 患者情報を公表した年月日を記載。
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
-  `相談件数`: コールセンターで受け付けた相談の件数を記載。
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Required
-  `備考`: 備考があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional



# 支援制度


-  `制度番号`: 制度を識別するための番号を各地方公共団体で設定し入力する。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `全国地方公共団体コード`: 総務省の定める全国地方公共団体コード（6桁コード）を記載。6桁に満たない場合、先頭は0埋めとする。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `法人番号`: （支援制度情報の提供主体が法人の場合）法人番号（13桁）を入力。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `元制度番号`: 国や都道府県の制度を元として地方公共団体が内容拡充したり名称変更した場合に、元となった制度の番号を入力。不明な場合は空欄とする。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `制度変更区分`: 国や都道府県の制度を元として地方公共団体が内容拡充したり名称変更した場合に、どのような変更を行ったか、以下の3種類から選択して入力。 0: 分かりやすくする目的で内容を変えずに書き換えを実施 1: 元の内容に追記 2: 条件による詳細化
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Optional
-  `タイトル（制度名）`: 支援制度のタイトル（制度名）を入力。40文字以内で、改行や半角カナは含めないようにする。（40文字を超えるときにはサブタイトルを活用）
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `サブタイトル（通称）`: 支援制度にサブタイトルがある場合に入力。40文字以内で、改行や半角カナは含めないようにする。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `対象者`: 支援制度の対象者の情報を500文字以内で入力。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `用途・対象物`: 支援制度に用途や対象物に限定などがある場合に200文字以内で入力。「〇〇を除く」のように除外するものがある場合にも、この項目に入力。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `対象地域`: 都道府県名を入力。市区町村限定の場合も属する都道府県名を入力する。複数都道府県が対象の場合、“;” （半角セミコロン）区切りで入力する。全都道府県の場合は空欄とする。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `対象地域群`: 市区町村名を入力。複数市区町村が対象の場合、“;” （半角セミコロン）区切りで入力する。都道府県下全域の場合は空欄とする。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `概要`: 支援制度の概要を200文字以内で入力。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `内容`: 支援制度の内容（詳細）を5000文字以内で入力。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `利用・申請方法`: 利用・申請方法を500文字以内で入力。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `受付開始日`: 受付開始の年月日を入力。
   -  Attribute type: **Property**. [DateTime](https://schema.org/DateTime)
   -  Optional
-  `受付終了日`: 受付終了の年月日を入力。未定や常時受付の場合は空欄とする。
   -  Attribute type: **Property**. [DateTime](https://schema.org/DateTime)
   -  Optional
-  `受付備考`: 受付開始日、終了日に関する備考がある場合に入力。改行は含めないようにする。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `根拠法令`: 根拠法令名を500文字以内で入力。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `詳細参照先`: 詳細情報を提供するWebページ等、詳細な参照先がある場合に、500文字以内で入力。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `実施組織・支援機関`: 実施機関・支援機関の名称を100文字以内で入力。複数機関がある場合には、“;” （半角セミコロン）区切りで入力する。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `お問い合わせ先`: お問い合わせ先情報を1000文字以内で入力。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `電子申請URL`: 電子申請が可能な場合はURLを入力。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `標準産業分類`: 支援制度の対象となる産業が指定されている場合、標準産業分類の大分類または中分類のコードを入力。複数の場合は “;” （半角セミコロン）区切りで入力する（上限：10個）。特に指定が無い場合は空欄とする。参照先シート：06-c1.標準産業分類
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `（事業者対象）事業ステージ分類`: 支援制度が対象とする事業ステージが想定されている場合、事業ステージ分類のコードを入力。複数の場合は “;” （半角セミコロン）区切りで入力する。参照先シート：06-c2.事業ステージ
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `（事業者対象）行政サービス分類`: 支援制度が提供する行政サービスの大分類または中分類のコードを入力。複数の場合は “;” （半角セミコロン）区切りで入力する。参照先シート：06-c3.行政サービス
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `（事業者対象）お困りごと分類`: 支援制度が想定している事業者の「お困りごと」のコードを入力。複数の場合は “;” （半角セミコロン）区切りで入力する。参照先シート：06-c4.お困りごと
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `（個人対象）ライフステージ分類`: 支援制度が対象とするライフステージが指定されている場合には、ライフステージ分類のコードを入力。複数の場合は “;” （半角セミコロン）区切りで入力する。参照先シート：06-c5.ライフステージ
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `（個人対象）行政サービス分類`: 支援制度が提供する行政サービス（個人向け）のコードを入力。複数の場合は “;” （半角セミコロン）区切りで入力する。参照先シート：06-c6.行政サービス（個人）
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `（個人対象）お困りごと分類`: 支援制度が想定している個人利用者の「お困りごと」のコードを入力。複数の場合は “;” （半角セミコロン）区切りで入力する。参照先シート：06-c7.お困りごと（個人）
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `災害名`: 災害に特化する制度である場合、災害名を入力。今回の新型コロナウイルス感染症の特別制度の場合は「新型コロナウイルス」と入力。複数の場合は “;” （半角セミコロン）区切りで入力する（上限：10個）。災害や今回の感染症対策以外で使える制度の場合は空欄とする。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `キーワード`: 支援制度を表すキーワードを入力。複数の場合は “;” （半角セミコロン）区切りで入力する（上限：5個）。1キーワードあたりの文字数は20文字まで。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `制度集`: 紙で配布する制度集から転載したものは、制度集の名前を入力。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `公開日`: 情報を公開した年月日を入力。
   -  Attribute type: **Property**. [DateTime](https://schema.org/DateTime)
   -  Optional
-  `公開終了日`: 情報の公開を終了する予定の年月日を入力。
   -  Attribute type: **Property**. [DateTime](https://schema.org/DateTime)
   -  Optional



## Examples

### OK


