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
`tikatyousa_2018_100m_souzokurosenka.csv`  

データソース2 [犯罪データ](https://www.police.pref.osaka.lg.jp/seikatsu/9290.html): 平成30年中の犯罪発生情報の中の自転車盗 (CSVファイル: 3.1MB), `osaka_2018zitensyatou.csv`  

データソース3 [全国市区町村界データ](https://www.esrij.com/products/japan-shp/), 国土地理院発行の数値地図（国土基本情報）およびESRIジャパンの全国市区町村界データ, 
`japan_ver821.zip`  
