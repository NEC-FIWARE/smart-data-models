# オープンデータ一覧

オープンデータ化されているデータセットの一覧。
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
-  `データ名称`: データセット名称を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `データ概要`: データの内容について、概要を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `データ形式`: データセットのファイル形式を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `分類`: データの分類を記載。. One of : `国土・気象`, `人口・世帯`, `労働・賃金`, `農林水産業`, `鉱工業`, `商業・サービス業`, `企業・家計・経済`, `住宅・土地・建設`, `エネルギー・水`, `運輸・観光`, `情報通信・科学技術`, `教育・文化・スポーツ・生活`, `行財政`, `司法・安全・環境`, `社会保障・衛生`, `国際`, `その他`.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Required
-  `更新頻度`: データセットの更新頻度を記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `URL`: データセットのHPのURLを記載。
   -  Attribute type: **Property**. [URL](https://schema.org/URL)
   -  Optional
-  `API対応有無`: API対応の有無を記載。. One of : `有`, `無`.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `ライセンス`: ライセンスについて記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `登録日`: データセットの登録日を記載。
   -  Attribute type: **Property**. [Date](https://schema.org/Date)
   -  Optional
-  `最終更新日`: データセットの最終更新日を記載。
   -  Attribute type: **Property**. [Date](https://schema.org/Date)
   -  Required
-  `備考`: 特記事項等があれば記載。
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional



## Examples

### OK


