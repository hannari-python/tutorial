# tutorial
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/hannari-python/tutorial/master)

https://scrapbox.io/hannari-python/pyconjp_tutorial

https://scrapbox.io/hannari-python/pyconjp_tutorial_%E8%B2%BF%E6%98%93%E5%8F%8E%E6%94%AF


## パート1 貿易収支
データソース(シンプル版)
https://www.customs.go.jp/toukei/shinbun/trade-st/timeseries_202005.csv

データソース(大量版)
https://www.kaggle.com/zanjibar/japan-trade-statistics

- 可視化
- 教師無し学習
- 教師あり学習

## パート2 家計調査
### データのファイル名と出典記載

- `data/ippan-microdata/ippan_2009zensho.zip`, 独立行政法人 統計センター 一般用ミクロデータ 平成21年全国消費実態調査 （十大費目）https://www.nstac.go.jp/services/ippan-microdata.html
- `data/ippan-microdata/ippan_2009zensho_s.zip`, 独立行政法人 統計センター 一般用ミクロデータ 平成21年全国消費実態調査 （詳細品目）https://www.nstac.go.jp/services/ippan-microdata.html
- `data/ippan-microdata/ippan_shugyou.zip`, 独立行政法人 統計センター 一般用ミクロデータ 就業構造基本調査 （平成４年～24年）https://www.nstac.go.jp/services/ippan-microdata.html

## パート3 地理データ
データソース1 [地価データ](https://data.city.osaka.lg.jp/data/dataset/data-00000065): 地価調査_平成30年_100ｍ_相続税路線価_データベースファイル（CSV）, 
`data/osakadata/tikatyousa_2018_100m_souzokurosenka.*` 

データソース2 [国土交通省国土数値情報ダウンロードサイト](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-P34.html): [国土数値情報 市区町村役場データ](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-P34.html), 大阪 	世界測地系 平成26年 0.01MB 	P34-14_27_GML.zip, `data/P34-14_27_GML/*  `

データソース3 [犯罪データ](https://www.police.pref.osaka.lg.jp/seikatsu/9290.html): 大阪府警察 犯罪オープンデータサイト (https://www.police.pref.osaka.lg.jp/seikatsu/9290.html), 平成30年中の犯罪発生情報の中の自転車盗 (CSVファイル: 3.1MB), `data/osakadata/osaka_2018zitensyatou.csv`  


データソース4 [国土交通省国土数値情報ダウンロードサイト](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-N03-v2_4.html#prefecture27): [国土数値情報　行政区域データ](https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-N03-v2_4.html#prefecture27), 大阪 世界測地系 平成30年 2.43MB  N03-180101_27_GML.zip, `data/osakadata/N03-180101_27_GML/*`   
