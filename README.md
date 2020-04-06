# AI---Voice-Recognition

説明
=======

MSの人工知能が翻訳をして逆翻訳をすれば、同じ結果が出るだろうか。 という気がして確認してみた。
----------
MSのLUISという人工知能を使って作りました。  
--------------
音声認識コードなので重要な写真がありません。 コードを説明します。
---------------

<img width="800" src="https://user-images.githubusercontent.com/44941601/78568519-2f5ae880-785d-11ea-9645-e99d245d36c9.png">
<img width="800" src="https://user-images.githubusercontent.com/44941601/78568519-2f5ae880-785d-11ea-9645-e99d245d36c9.png">

speech Key を設定し、trans Text Key を設定することを第一にする。
---------------------------------

<img width="800" src="https://user-images.githubusercontent.com/44941601/78568860-b019e480-785d-11ea-81d2-b6b7671af85b.png">
<img width="800" src="https://user-images.githubusercontent.com/44941601/78568866-b314d500-785d-11ea-858a-5bb9853d2e5e.png">

その後、テキストを入力してもらい、入力してもらったテキストがどんな言語なのか、そしてどんな言語に変えるのかを決めるコード。
"こんにちは"(korean)を入力して韓国語であることを知らせて英語に翻訳した。
-------------------------------------
<img width="800" src="https://user-images.githubusercontent.com/44941601/78569146-1ef73d80-785e-11ea-9450-ed227a9fa28c.png">
text to speech コードを通じて翻訳を行う。 その前に翻訳された変数をmy Textに連結してあげる。
-----------------------------------
<img width="800" src="https://user-images.githubusercontent.com/44941601/78569276-54039000-785e-11ea-9133-719ee0bd5a59.png">
そして、再びspeech to text コードを通して認識させる。この部分では上に音声をダウンロードしてフォルダーに音声を入れてくれる。
-------------------------------
<img width="800" src="https://user-images.githubusercontent.com/44941601/78569414-9200b400-785e-11ea-8ec8-793be89b0c07.png">
その後、翻訳してくれるコードを書き直して翻訳してくれる。
--------------------------
この時、toはfromLandCodeで受け取り、fromはtoLangCodeする。
--------------------------
<img width="800" src="https://user-images.githubusercontent.com/44941601/78569595-cffdd800-785e-11ea-93fa-5f473569dff2.png">
"こんにちは"(korean)と入力したのは、英語に翻訳され、音声に変換されて再び逆翻訳されたとき、同じではないという結果が出た。

