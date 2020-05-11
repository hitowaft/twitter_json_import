# twitter_json_import
twitterからダウンロードしたデータをpandasのDataFrameに入れる

## 前処理
tweet.jsファイルを開き、冒頭の``window.YTD.tweet.part0 = [`` という部分とファイル最下部の ``]`` を消しておきます。
