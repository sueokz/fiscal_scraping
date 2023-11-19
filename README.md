# fiscal_scraping
## 概要
名古屋取引所に上場する銘柄で直近決算を行う銘柄を洗い出すコードです。

## 経緯
名古屋取引所投資コンテストに参加している中で、直近決算を行う銘柄を即座に知りたかったから。

## 言語
言語:Python<br>

## 実装した機能
スクレイピング<br>

## アップデート案
1.Tickerも取得して、株価や出来高をLINEに送る。<br>
 [analysis_f.ipynb](https://github.com/sueokz/corporate_analysis_financials/blob/main/analysis_f.ipynb)のように<br>
2.データフレーム化する<br>
データフレーム化することで、補足情報を入れることができるので後に使いまわしやすくなる。
