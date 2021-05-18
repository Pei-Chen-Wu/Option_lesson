# Option_lesson
股票課程所學
## HW1_基金
> from:給工程師的第一本理財書 :程式金融交易的118個入門關鍵
> Fund analysis.ipynb
* 抓取基金報酬率

資料來源 : MoneyDJ理財網

![image](https://user-images.githubusercontent.com/69243911/112822401-7a978800-90ba-11eb-83b6-cda02415d4e0.png)
   1. x : 原始網頁碼
   2. a :
    ![image](https://user-images.githubusercontent.com/69243911/112822463-90a54880-90ba-11eb-9ff9-11dc6a9d0d7f.png)
   3. k :
    ![image](https://user-images.githubusercontent.com/69243911/112822493-9ac74700-90ba-11eb-8c12-1fdfaf5c60bf.png)


* 分析基金的收益

藉由前者取得的指數型報酬率，接著以關鍵字取出指定報酬率，即可進行投資報酬率計算

![image](https://user-images.githubusercontent.com/69243911/112822591-b7fc1580-90ba-11eb-9565-8c441756e860.png)

![image](https://user-images.githubusercontent.com/69243911/112822761-ec6fd180-90ba-11eb-978c-554a9ca26c41.png)

結果:

![image](https://user-images.githubusercontent.com/69243911/112822791-f98cc080-90ba-11eb-803c-805c4e98f3b0.png)

![image](https://user-images.githubusercontent.com/69243911/112822804-fbef1a80-90ba-11eb-8e8f-68ad75b6234c.png)

## HW2_期權
> from:給工程師的第一本理財書 :程式金融交易的118個入門關鍵
* 簡介
* 如何進行選擇權買賣
* 買權與賣權
* 交易成本_權利金與保證金
* 概念實體化
* 四個象限(基本含義)
* 其他交易成本
* 選擇權與標的知恆等公式

## HW3_常用資料取得
> from:Python量化投資縱橫金融：從程式到現金之路
> 中國股票
* 優礦官網

![image](https://user-images.githubusercontent.com/69243911/112824606-538e8580-90bd-11eb-8acd-74ed3ee6c86f.png)

* yahoo
![image](https://user-images.githubusercontent.com/69243911/112824720-7751cb80-90bd-11eb-9515-21ca63f87a53.png)
* TuShare
![image](https://user-images.githubusercontent.com/69243911/112824764-8173ca00-90bd-11eb-89a4-a315c2ee560f.png)
* BaoStock
![image](https://user-images.githubusercontent.com/69243911/112824790-8c2e5f00-90bd-11eb-8d62-949314c7c27b.png)

## HW4_期權
> from:python期權演算法交易實務180個關鍵技巧詳解
* 選擇權商品規格
* Put call parity (選擇權平價理論)
> Put_call_parity.py

![image](https://user-images.githubusercontent.com/69243911/112825067-e4fdf780-90bd-11eb-943b-35944b37b6ba.png)

* 認識組合單
* 程式交易
* 期權常見交易資料
* K線技術指標套件安裝_Talib

## HW5_公開資訊觀測站
> 介紹公開資訊觀測站 https://mops.twse.com.tw/mops/web/index
* 首頁配置
* 全站搜尋列
* 股東會除權息日曆
* 相關連結
   * 基本市況 https://mis.twse.com.tw/
   * 申請上市資訊 https://www.twse.com.tw/zh/company/applylisting
   * 國內外相關網站 https://www.twse.com.tw/zh/page/about/links.html
* RSS
* 公告區
* 財務比較e點通 https://mopsfin.twse.com.tw/index
* 月營收資訊查詢 https://mops.twse.com.tw/mops/web/t05st10_ifrs
* XBRL平台 https://mops.twse.com.tw/mops/web/t203sb01
* 網站地圖 https://mops.twse.com.tw/mops/web/t146sb08

## HW6_證交所網站
> 介紹證交所網站 https://www.twse.com.tw/zh/
* 與公開資訊觀測站比較
* 熱門導覽 https://www.twse.com.tw/zh/page/focus/popular.html
   * 每日收盤行情
* 快捷選項
   * 臺灣創新板(TIB) https://www.twse.com.tw/zh/page/products/tib/preface.html
   * 其他選項 https://www.twse.com.tw/zh/page/focus/links.html
*  熱門查詢
*  熱門資訊統計與排行
*  細項資訊
   * 交易資訊
   * 指數資訊

## HW7_goodinfo
> 介紹goodinfo網站 https://goodinfo.tw/StockInfo/index.asp
* 個股收尋列
* 細項選擇
   * 主要資訊
   * 熱門排行
   * 智慧選股
* 熱門資訊統計與排行
* 最近瀏覽

> 介紹嗨!投資 (Hi Stock)網站 https://histock.tw/app/search.aspx

## HW8_stocker程式
> Facebook 於 2017年發表的論文 Forecasting at Scale
> 新型的時間序列預測模型Prophet，中文叫作預言家
> 可以預測一些週期性的時間序列
### 程式介紹
> from : https://github.com/grandma-tutorial/Stocker
* grandma_stocker.ipynb  : 從 Yahoo Finance 取得歷史股價
* grandma_stocker_local.ipynb : 讀取 Local 資料
> 步驟
* 安裝相關套件
![image](https://user-images.githubusercontent.com/69243911/118701618-83007980-b846-11eb-83e3-12cb8fa1dd06.png)
* 下載資料 （使用 yfinance）
![image](https://user-images.githubusercontent.com/69243911/118701668-8eec3b80-b846-11eb-9189-2d692cb689e6.png)

* 使用 Stocker 預測股價
![image](https://user-images.githubusercontent.com/69243911/118701689-957ab300-b846-11eb-9744-db1058dd88dd.png)

* 預測未來10天的股價
![image](https://user-images.githubusercontent.com/69243911/118701730-a3303880-b846-11eb-8e63-f01ffe5d0c78.png)

* 模型好壞
![image](https://user-images.githubusercontent.com/69243911/118701756-aaefdd00-b846-11eb-8c40-2d0c95baa97d.png)

* 調整參數讓模型預測有不同的表現
![image](https://user-images.githubusercontent.com/69243911/118701783-b3481800-b846-11eb-896f-39d3515496a4.png)

* 比較不同的changepoint_priors
![image](https://user-images.githubusercontent.com/69243911/118701805-b93df900-b846-11eb-9934-46c1297b846e.png)

## HW9_textblob
> from : https://textblob.readthedocs.io/en/dev/
> 用於處理文本數據
> 提供了一個簡單的API，可用於深入研究普通自然語言處理（NLP）任務，例如詞性標記、名詞短語提取、情感分析、分類、翻譯等
* 安裝
![image](https://user-images.githubusercontent.com/69243911/118701932-e094c600-b846-11eb-9ee0-2605326a6650.png)

* Sentiment Analysis_ PatternAnalyzer(默認)
   * Sentiment(polarity, subjectivity)
      * The polarity情感極性 score is a float within the range [-1.0, 1.0] 
      * The subjectivity主觀性 is a float within the range [0.0, 1.0] where 0.0 is very objective and 1.0 is very subjective
![image](https://user-images.githubusercontent.com/69243911/118702009-f609f000-b846-11eb-9ad9-84de193b8711.png)

* Sentiment Analysis_NaiveBayesAnalyzer
   * an NLTK classifier trained on a movie reviews corpus
   * Sentiment(classification, p_pos, p_neg)
      * Classification 情感分類
      * p_pos 正向分數
      * p_neg 負面分數
![image](https://user-images.githubusercontent.com/69243911/118702111-15a11880-b847-11eb-9775-52154ff7dfd4.png)

> 應用在Bulbea程式_情感方面
![image](https://user-images.githubusercontent.com/69243911/118702172-2b164280-b847-11eb-94f1-33a69c18fe99.png)

## HW10_Stock-Prediction-Models(1)
>from https://github.com/huseinzol05/Stock-Prediction-Models
> 包含許多機器學習、深度學習模型與交易策略
> 可做到交易機器人和模擬
### Models
* Deep-learning models
* Bonus
* Stacking models
### Agents (策略)
### Data Explorations
* stock market study on TESLA stock, tesla-study.ipynb
* Outliers study using K-means, SVM, and Gaussian on TESLA stock, outliers.ipynb
* Overbought-Oversold study on TESLA stock, overbought-oversold.ipynb
* Which stock you need to buy? which-stock.ipynb
![image](https://user-images.githubusercontent.com/69243911/118703374-990f3980-b848-11eb-967d-76c6072c56ff.png)

### Simulations (模擬)
* Simple Monte Carlo, monte-carlo-drift.ipynb
* Dynamic volatility Monte Carlo, monte-carlo-dynamic-volatility.ipynb
* Drift Monte Carlo, monte-carlo-drift.ipynb
* Multivariate Drift Monte Carlo BTC/USDT with Bitcurate sentiment, multivariate-drift-monte-carlo.ipynb
* Portfolio optimization, portfolio-optimization.ipynb, inspired from https://pythonforfinance.net/2017/01/21/investment-portfolio-optimisation-with-python/
![image](https://user-images.githubusercontent.com/69243911/118703391-9d3b5700-b848-11eb-88d6-f9ee2f8d544d.png)

### Tensorflow-js
LSTM Recurrent Neural Network and Simple signal rolling agent inside Tensorflow JS
### Misc
* fashion trending prediction with cross-validation, fashion-forecasting.ipynb
* Bitcoin analysis with LSTM prediction, bitcoin-analysis-lstm.ipynb
* Kijang Emas Bank Negara, kijang-emas-bank-negara.ipynb

### 程式介紹
> 環境要求 : conda install tensorflow=1.12.0 (python 3.6以下)
> DL model
* 匯入資料
![image](https://user-images.githubusercontent.com/69243911/118703669-f2776880-b848-11eb-9a89-425c3c6b8afa.png)

* cut the dataset to train and test datasets
![image](https://user-images.githubusercontent.com/69243911/118703753-09b65600-b849-11eb-92cd-086e40e5bf7c.png)

* class Model
![image](https://user-images.githubusercontent.com/69243911/118703793-120e9100-b849-11eb-9d77-5514f21e7175.png)
![image](https://user-images.githubusercontent.com/69243911/118703808-1470eb00-b849-11eb-92b8-b9f6bc7c6a1f.png)

* 輸入參數
![image](https://user-images.githubusercontent.com/69243911/118703843-1c308f80-b849-11eb-9d0b-0d4b663611d0.png)

* def forecast
* 執行
![image](https://user-images.githubusercontent.com/69243911/118703907-29e61500-b849-11eb-887a-5f24a42cf358.png)

* 輸出結果
![image](https://user-images.githubusercontent.com/69243911/118703943-336f7d00-b849-11eb-934a-482c2c6e6e48.png)





