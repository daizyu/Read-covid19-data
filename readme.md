# Covid19 Tokyo official data reader for python3 / 東京都公式のcovid19のデータを読み込Python3 サンプル


東京都が公式で新型コロナウイルス covid19のデータと可視化ツールをgithubで公開しています。
内部的にjsonデータのため直接Pythonで読みずらいため、pandasのDataFrameとして読み込むサンプルを用意しました。

Tokyo share a covid19 system using a github.
It's good solution.
But it is little bit difficult to read for python .  
Then I made this reader samples.

## Motivation
Pythonにはとても強力なデータ解析モジュールがそろっているので、ぜひPythonで読んだ方が…と思いました。
しかし、公式のJsonの記載に少し癖があり、簡単には読めなかったのでサンプルを作って一旦公開することにしました。

このような病気の広がり方を研究することで、同様の問題が発生したときに早期に対応できる準備ができるのではないか？
と思い、少しでも興味のある人が、データ解析の手前のデータ読込で時間をかけるのは無駄なのではと思い公開させていただきました。

I think python has many powerful module for data analysis.
But python cannot read official json data directly.

I think we don't need to waste our important time for such non-value tasks.
Then I share this reader samples.

I hope , many body make good result about data analysis.

In the future , even if we will get similar accident , we can analysis our situation more correctly . Beforehand  I hope that we are able to cancel these big trouble  .

こちらが本体です↓ Please click this one.
[https://github.com/daizyu/Read-covid19-data/blob/master/Read-covid19-data.ipynb](https://github.com/daizyu/Read-covid19-data/blob/master/Read-covid19-data.ipynb)

こちらは東京都の公式です↓ This one is TOKYO official.
[[https://github.com/tokyo-metropolitan-gov/covid19](https://github.com/tokyo-metropolitan-gov/covid19)]

## 動作確認環境 / Checked environment
-   OS :Windows 10 、 Ubuntu 18
-   Jupyter ：6.0.1
-   Python :3.7.4
-   Pandas : 0.25.0 , 0.25.1 , 1.0.1

## ライセンス / License
MIT