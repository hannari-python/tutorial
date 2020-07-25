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
データソース候補1 https://www.stat.go.jp/data/kakei/longtime/csv/h-mon-a.csv

データソース候補2 https://www.meti.go.jp/statistics/bigdata-statistics/bigdata_pj_2019/pos_gfk_intage.html

データソース候補3: 機械学習向け　[一般ミクロデータ](https://www.nstac.go.jp/micro/cgi-bin/micro.cgi)

### データのファイル名と出典記載

- `data/ippan-microdata/ippan_2009zensho.zip`, 独立行政法人 統計センター 一般用ミクロデータ 平成21年全国消費実態調査 （十大費目）https://www.nstac.go.jp/services/ippan-microdata.html
- `data/ippan-microdata/ippan_2009zensho_s.zip`, 独立行政法人 統計センター 一般用ミクロデータ 平成21年全国消費実態調査 （詳細品目）https://www.nstac.go.jp/services/ippan-microdata.html
- `data/ippan-microdata/ippan_shugyou.zip`, 独立行政法人 統計センター 一般用ミクロデータ 就業構造基本調査 （平成４年～24年）https://www.nstac.go.jp/services/ippan-microdata.html

- 教師無し学習 (クラスタリング)
- 教師あり学習

## パート3 地理データと国勢調査
データソース1 [統計GIS](https://www.e-stat.go.jp/gis/statmap-search?type=2)

データソース2 [統計データ](https://www.e-stat.go.jp/gis/statmap-search?type=1)

- geopandas

- 教師無し学習
- 教師あり学習
