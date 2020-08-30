# オープンデータを使って、Pythonでデータ分析 (PyCon JP 2020 チュートリアル)

Author: See https://github.com/hannari-python/tutorial/graphs/contributors

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hannari-python/tutorial/master) This Binder environment will receive special support on August 30th. (See https://github.com/jupyterhub/mybinder.org-deploy/issues/1560)
Thank you for the Binder project.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/hannari-python/tutorial/blob/master)

[イントロダクションのスライド](https://docs.google.com/presentation/d/1-J3urYC6e3IY30xduhTDnBEWphTbcJ2CRvHhV6fwNBw)

## このチュートリアルはどういうものか?

このチュートリアルでは、世の中の動向を可視化、予測するために必要なデータ分析の知識を習得できます。貿易収支や家計調査、境界データと国勢調査などのオープンデータをもとに、分析できるように前処理を行い、作ったデータをPlotlyとPydeckを使って可視化し、DashやStreamlitを使ってダッシュボードを作り、scikit-learnを使って機械学習を行うといった、一連のデータ分析をGoogle ColaboratoryやBinderを使用して体験できます。

PyConJP 2020のページは[こちら](https://pycon.jp/2020/tutorial/#event-two:~:text=Bot%E3%81%A8%E3%80%81Slack%E3%83%AF%E3%83%BC%E3%82%AF%E3%82%B9%E3%83%9A%E3%83%BC%E3%82%B9%E3%81%A8%E3%81%AE%E5%8F%8C%E6%96%B9%E5%90%91%E9%80%9A%E4%BF%A1%E3%81%A7%E5%88%A9%E7%94%A8%E3%81%97%E3%81%BE%E3%81%99%E3%80%82%E3%83%AD%E3%83%BC%E3%82%AB%E3%83%AB%E7%92%B0%E5%A2%83%E3%81%AE%E3%82%B5%E3%83%BC%E3%83%90%E3%83%BC%E3%82%92%E4%B8%80%E6%99%82%E7%9A%84%E3%81%AB%E5%A4%96%E9%83%A8%E3%81%B8%E5%85%AC%E9%96%8B%E3%81%A7%E3%81%8D%E3%82%8B%E3%82%B5%E3%83%BC%E3%83%93%E3%82%B9%E3%81%A7%E3%81%99%E3%80%82-,%E3%82%AA%E3%83%BC%E3%83%97%E3%83%B3%E3%83%87%E3%83%BC%E3%82%BF%E3%82%92%E4%BD%BF%E3%81%A3%E3%81%A6%E3%80%81Python%E3%81%A7%E3%83%87%E3%83%BC%E3%82%BF%E5%88%86%E6%9E%90)

## チュートリアルで使用するノートブック

* 第一部 [貿易収支データ分析](https://github.com/hannari-python/tutorial/blob/master/trade_balance/trade_balance_prepro_and_visualization_and_clustering.ipynb)
* 第二部 [家計調査データ分析](https://github.com/hannari-python/tutorial/blob/master/family_budget/family_budget.ipynb)
* 第三部 [地理データ分析](https://github.com/hannari-python/tutorial/blob/master/land_assessments/land_assessments.ipynb)

## チュートリアルのタイムテーブル

[こちらのgithub issue](https://github.com/hannari-python/tutorial/issues/20)をご参照ください。

## ライセンス (ノートブック)

ノートブックのライセンスは [CC BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ja) です。

CCライセンスについては、[クリエイティブ・コモンズ・ライセンスとは](https://creativecommons.jp/licenses/) を参照してください。

## ライセンス (データ)
データのライセンスは出典元の規約に基づきます。
下記のリンクをご確認ください。

### パート1 貿易収支

データソース
https://www.kaggle.com/zanjibar/japan-trade-statistics

### パート2 家計調査
#### データのファイル名と出典記載

- `data/ippan-microdata/ippan_2009zensho.zip`, 独立行政法人 統計センター 一般用ミクロデータ 平成21年全国消費実態調査 （十大費目）https://www.nstac.go.jp/services/ippan-microdata.html
- `data/ippan-microdata/ippan_2009zensho_s.zip`, 独立行政法人 統計センター 一般用ミクロデータ 平成21年全国消費実態調査 （詳細品目）https://www.nstac.go.jp/services/ippan-microdata.html
- `data/ippan-microdata/ippan_shugyou.zip`, 独立行政法人 統計センター 一般用ミクロデータ 就業構造基本調査 （平成４年～24年）https://www.nstac.go.jp/services/ippan-microdata.html

### パート3 地理データ
データソース1 [地価データ](https://data.city.osaka.lg.jp/data/dataset/data-00000065): 地価調査_平成30年_100ｍ_相続税路線価_データベースファイル（CSV）, 
`data/osakadata/tikatyousa_2018_100m_souzokurosenka.*` 

データソース2 [国土交通省国土数値情報ダウンロードサイト](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-P34.html): [国土数値情報 市区町村役場データ](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-P34.html), 大阪 	世界測地系 平成26年 0.01MB 	P34-14_27_GML.zip, `data/osakadata/P34-14_27_GML/*  `

データソース3 [犯罪データ](https://www.police.pref.osaka.lg.jp/seikatsu/9290.html): 大阪府警察 犯罪オープンデータサイト (https://www.police.pref.osaka.lg.jp/seikatsu/9290.html), 平成30年中の犯罪発生情報の中の自転車盗 (CSVファイル: 3.1MB), `data/osakadata/osaka_2018zitensyatou.csv`  


データソース4 [国土交通省国土数値情報ダウンロードサイト](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-N03-v2_4.html#prefecture27): [国土数値情報　行政区域データ](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-N03-v2_4.html#prefecture27), 大阪 世界測地系 平成30年 2.43MB  N03-180101_27_GML.zip, `data/osakadata/N03-180101_27_GML/*`   
