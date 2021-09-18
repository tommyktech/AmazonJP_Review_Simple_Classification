# Amazon JP Review Simple Classification
アマゾンのレビューの☆数をレビュー文から予測するシンプルなコード集です。  
レビューを取得し、それをNaive BayesやNN、LSTM、BERTで分類予測を行います。  
コンペで使うようなテクニックは含まれていません。単純にテキストをモデルに入れて訓練・予測するだけです。

## ファイルの説明
* collect_amazon_reviews.ipynb  
  アマゾンのレビューデータを収集するスクリプト  
* train_amazon_reviews_naive_bayes_and_tensorflow.ipynb  
  レビューデータを各種アルゴリズムで分類するスクリプト  


#### アマゾンのレビューのスクレイピングについて
アマゾンの利用規約ではいわゆるスクレイピングは許可されていませんが、本スクリプトで取得するレビューは利用規約に同意することなくアクセスできる部分に限定しており、レビューデータの再配布も行っておりません。  

スクレイピングの法的な立ち位置については以下のサイトを参考にしました:  
https://pig-data.jp/news_columns/scrapinglaw/
