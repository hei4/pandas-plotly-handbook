# pandas&Plotly 2D/3Dデータビジュアライゼーション実装ハンドブック

- 序章　データ可視化とインタクラティブなグラフ
- 第1章　表形式データの基本
- 第2章　表の変形と結合・分割
- 第3章　表形式データの値の操作
- 第4章　例外値への対応
- 第5章　グラフ作成の基本
- 第6章　グラフの書式設定
- 第7章　インタクラティブなグラフの作成
- 第8章　変数内の値を比較するグラフ
- 第9章　変数間の関係を表現するグラフ
- 第10章　変数の分布を表現するグラフ
- 第11章　変数の傾向や構成を表現するグラフ
- 第12章　空間を表現するグラフ
- 第13章　時間を表現するグラフ

## 対応バージョン

本書のサンプルコードは以下の環境で動作することを確認しています。

Visual Studio Code以外の統合開発環境で実行される場合はご自分の環境に合わせて設定を行ってください。

> Python 3.9.4
>
> Visual Studio Code (Version: 1.85.1)

本書のサンプルコードは以下バージョンのPythonパッケージで動作することを確認しています。

> pandas==1.5.0
>
> openpyxl==3.0.10
>
> numpy==1.23.3
>
> scipy==1.9.3
>
> scikit-learn==1.1.3
> 
> seaborn==0.12.2
>
> plotly==5.15.0
> 
> jupyter==1.0.0
>
> notebook==6.4.12
>
> ipywidgets==8.0.7

## 加工して使用した政府提供のデータ

国土交通省およびe-Statが提供するデータを加工して使用しています。また厚生労働省が提供するデータをダウンロードして使用しています。

- todofuken.geojson
  - 出典：[国土数値情報ダウンロードサイト](https://nlftp.mlit.go.jp/)
  - 「[国土数値情報（行政区域データ　「全国」データ　令和4年）](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-N03-v3_1.html)」（国土交通省）を加工して使用
- population.csv
  - 出典：[政府統計の総合窓口(e-Stat)](https://www.e-stat.go.jp/)
  - 「[社会・人口統計体系 都道府県データ 社会生活統計指標](https://www.e-stat.go.jp/dbview?sid=0000010201)」（e-Stat）を加工して使用
- newly_confirmed_cases_daily.csv
  - 出典：[データからわかる－新型コロナウイルス感染症情報－](https://covid19.mhlw.go.jp/)
  - 「[新規陽性者数の推移（日別）](https://covid19.mhlw.go.jp/public/opendata/newly_confirmed_cases_daily.csv)」（厚生労働省）を使用


## 付録

紙面に記載できなかった内容を補足しています。

- conver_geo.ipynb
  - 国土数値情報ダウンロードサイトからダウンロードした、全国行政区域データを加工するノートブックです。事前に全国行政区域データのダウンロードが必要です。
  - 加工後のファイルであるtodofuken.geojsonを本リポジトリに収録しています。
- show_color.ipynb
  - Plotlyで使用できるカラースケールを閲覧するノートブックです。


## コードの変更

コードの修正履歴を記載します。

- 20240616：初版

## サポート

サンプルプログラムの間違いや動作不具合、書籍中の誤植については本リポジトリのIssuesに投稿ください。

動作不具合についての投稿では、以下を記載ください。

- 実行プログラム名
- エラーメッセージ
- Python、pandas、Plotlyのバージョン
- 実行した統合開発環境の種類

## 正誤表

正誤表に記載されているサンプルコードの誤記は、本リポジトリのmasterブランチで修正されています。

| ページ | 誤 | 正 | 補足 |
|:-----------|:------------|:------------|:------------|
|  |  |  |  |