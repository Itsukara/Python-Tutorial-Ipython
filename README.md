本ファイル群は、[Python チュートリアル(2.7系)](http://docs.python.jp/2.7/tutorial/index.html)をJupyter/IPython Notebook形式に変換したものです。

対話モードでは入力した内容が失われ、再入力が面倒だったりするので、一度ファイルに記載してから実行したいと思いました。そこで、対話形式のプログラム例からスクリプトを抜き出してファイルにしました([Python-Tutorial-Scripts](https://github.com/Itsukara/Python-Tutorial-Scripts))。その後、チュートリアルの文章も見れて、各プログラム例の修正・試行が容易なJupyter/IPython Notebook形式に変換しました。

手動変換なので、誤りは適宜修正頂けるとありがたいです。また、Pythonの日本サイトで取り込んでいただけると、一番ありがたいです。

なお、Pythonは、対話形式では式を入れると値が表示されますが、Jupyter/IPython Notebookでは、最後の式の値しか表示されないため、プログラム例に適宜「print」を追加しています。

また、print文で表示すると文字列の表現等が異なるため、プログラム例では、適宜、式に対して「repr」という関数を適用した結果をprintしています。

更に、一部のプログラム例は、簡易化や動作可能化を目的に修正しています。また、データファイルなどの追加も行っています。

ご参考まで。 

Itsukara
http://itsukara.hateblo.jp/
https://twitter.com/iitt21
https://github.com/


## 初めてPythonやJupyter/IPython Notebookを使う方のために
+ [Anaconda(Pythonの実行環境+ライブラリ群)をインストールする](http://pythondatascience.plavox.info/python%E3%81%AE%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB/python%E3%81%AE%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB-windows/)

+ [GitHub](https://github.com/Itsukara/Python-Tutorial-Ipython)から本ファイル群をダウンロードし解凍する。

+ 解凍したフォルダでコマンドプロンプトを開き、Jupyter/IPython Notebookを起動する：  
　```> jupyter notebook```

+ 上記により、ブラウザが開き、本ファイル群がjupyterから見れるので、Notebookファイル(tutorial-ch01.ipynb～tutorial-ch11.ipynb)クリックして開く。(閉じ方はFile -> "Close and Halt")

+ プログラム例の部分でクリックすると、中身を変更可能です。
+ プログラム例でControl-Enterを押すと、中身が実行され、下に結果が表示されます。
+ 変更した内容は、保存できます。
+ Notebookの右上にHelpメニューがあるので、詳細はそちらを参照ください。
