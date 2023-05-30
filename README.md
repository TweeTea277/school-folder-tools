
- [ツールの機能の説明](#ツールの機能の説明)
  - [時間割から学校の授業用フォルダを作成するツール](#時間割から学校の授業用フォルダを作成するツール)
  - [指定した範囲の数で連番フォルダ作るだけのツール](#指定した範囲の数で連番フォルダ作るだけのツール)
- [ツールを使用する方法](#ツールを使用する方法)
  - [ウェブサイトにアクセスする](#ウェブサイトにアクセスする)
  - [コードをDLしてローカルで動かす](#コードをdlしてローカルで動かす)
- [使用しているJSのライブラリ](#使用しているjsのライブラリ)
  - [JSZip.js：ZIPファイルの作成](#jszipjszipファイルの作成)
  - [FileSaver.js：ファイルの保存とDL](#filesaverjsファイルの保存とdl)
- [ライセンス](#ライセンス)


<br>  

# ツールの機能の説明 
## 時間割から学校の授業用フォルダを作成するツール
・「各曜日＞各授業＞各回」というフォルダを生成します。  
・エクセルに貼り付ける用のTSVも一緒に生成します。  
・日本の学校全般を想定して作成しました。  
![screenshot](screenshots/screenshot1.PNG)  

<hr>

<br>  

## 指定した範囲の数で連番フォルダ作るだけのツール

![screenshot2](screenshots/screenshot2.PNG)  

<br>

# ツールを使用する方法

## ウェブサイトにアクセスする
**・GitHub Pages↓にデプロイしているのでウェブ上で使えます**  
**・このURLにアクセスするだけで使用することが可能です。**  
・参考にしたブログの記事等も書いてあります。  
***https://tweetea277.github.io/school-folder-tools/***

<br>

## コードをDLしてローカルで動かす
・ファイルを右上の「Code＞Download ZIP」でDLし解凍、  
　中にある「index.html」をブラウザで開くだけで使用可能です。  
・同一生成元ポリシーの制限に引っ掛かる機能は使用してないです。  
・ライブラリを同梱しているので、オフラインでも使用可能です。  
~~・ライブラリはCDNから読み込んでいるので、オフラインでは使用不可です。~~    
***・このリンク↓からダウンロードできます。(踏むとDL開始されます)***  
***https://github.com/TweeTea277/school-folder-tools/archive/refs/heads/master.zip***

<br>

# 使用しているJSのライブラリ
これらのライブラリを使用しています。  <br><br>

## JSZip.js：ZIPファイルの作成
https://github.com/Stuk/jszip  
Copyright (c) 2009-2016 Stuart Knightley, David Duponchel, Franz Buchinger, António Afonso.
<br>
  
## FileSaver.js：ファイルの保存とDL  
https://github.com/eligrey/FileSaver.js  
Copyright © 2016 Eli Grey.
<br>
  
# ライセンス
・[MIT license](https://en.wikipedia.org/wiki/MIT_License)です。自由に改造とかしてくださいな。
