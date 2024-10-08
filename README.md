﻿Light.vn
========
  
![My image0](https://raw.github.com/hsdk123/Light.vn/master/screenshots/light_ss_171004_00.png)    

## Note

- This is the legacy old repo, which is being kept as history.
- The latest repo is [here](https://github.com/SoulEngineProject/Light.vn)

## 紹介

[Light.vn（ライト・ヴィエン）](http://lightvn.net) はビジュアルノベル系作品の製作のために  
作られたエンジン、及びエディターです。  
    
  「全てのノベルが本来持っている "光" を引き出す事」を目標に、  

  Light .vn の「Light」はそのための製作の灯になれたら、と言う意味を込めて、  
 「vn」はVisual Novel（ヴィジュアルノベル）の略語として名付けました。

#### 参考リンク
* [公式サイト](http://lightvn.net)
* [導入事例の一覧](https://docs.google.com/document/d/136RDiACVN4JpYQpD6NCi824CJlblKLunuzmQFofIhXE/edit?usp=sharing)

## ダウンロード

「[リリースページ](https://github.com/hsdk123/Light.vn/releases)」 : Light.vnの最新バージョンページ。  
  
フィードバックはLight.vnの成長の原動力になります。   
どんな些細な事でもいいので、バグ発見や要望などありましたら、  
Light.vnの[Slack](lightvn-invite.herokuapp.com)や[Twitter](http://www.twitter.com/daegon137)などでお気軽にご連絡ください。
  
プロジェクト支援・参加等のより個人的なお問い合わせや  
上手く伝わらない内容や感想に関しては下のメールアドレスまでお願いします。  

製作者：hsdk(炯淳) (berserkd)  
mail: daegon.dhsk at outlook.com | [Twitter](http://www.twitter.com/daegon137)

## チュートリアル

「[ゼロから作品公開まで](http://lightvn.net/roadmap/)」
* Light.vnが提供する独自の機能で長くても30分で自分好みの作品を作ろう

「[Light.vnサポート](http://lightvn.net/support/)」
* Light.vnのマニュアル、動画チュートリアルなど幅広く収録


## 製作趣旨・目標

* 誰でも容易くノベルを作られる「環境」を提供する事
* 慣れることでは無く、直感的にスクリプト作業、及びプロジェクト管理が出来るようにする事  
* ノベル製作・管理を伴う無駄な時間と労力消費を最小限にし、作品制作・完成に集中できるようにする事  

## 主な特徴

##### リアルタイムプレビュー

* スクリプトを修正すると左の画面に即時表示
* どの行をクリックしてもその時点での結果を表示
* F5を押すとその場でプレイ開始
* 結果：製作時間を遥かに短縮し、濃厚な演出も楽に表現

##### 日本語基盤スクリプト

* パット見るだけですぐ読める
* 複雑な英単語を暗記する必要無し
* 自分の意図を楽に表現できる
* 結果：シナリオを書く感覚での自然な作品作り
  
## 対応OS・グラフィックドライバー  
  
##### Light.exe (ノベルアプリケーション）  

* WindowsXP, Windows7, Windows8, Windows10  
* Light.vnの成長に従い、以下の順でOS追加サポート予定：  Mac, モバイル（IOS, Android）

##### LightEditor.exe （エディター）
  
* エディターは現在 .Net 4.0 Fullを必要とするため以下のOSに限定されます：  
WindowsXP Service Pack 3 以上, Windows7, Windows8, Windows10

##### グラフィックドライバ
  
* OpenGL2.1以上を支援するグラフィックドライバの搭載を必要とします。         
* 現在使用中の環境が支援しているOpenGLバージョンはプログラムの起動後、  
フォルダー内に生成されるdebug.txtで確認できます。  
  
## 使用ライセンス    
  
Light  .vn の使用を含め製作作品の公開はすべて無料です。  
ただ、作品公開時はLight.vnの導入事例に追加し、宣伝協力などもしたい為、  
もしよろしければ、メール或いはSlackでご連絡ください。  
 
また、公開の際に作品パッケージやリンクも一緒に送って頂けますと開発者がもの凄く喜びますので、  
もし可能であればご検討ください（＿＿）
  
## スクリーンショット  
  
##### Light.exe (ノベルアプリケーション）
基本UI提供           |  複数テキストウインドウ
:-------------------------:|:-------------------------:
![My image1](https://raw.github.com/hsdk123/Light.vn/master/screenshots/light_ss_171004_05.png)   |   ![My image2](https://raw.github.com/hsdk123/Light.vn/master/screenshots/light_ss_171004_02.png)
バックログ |  柔軟な動画活用
![My image1](https://raw.github.com/hsdk123/Light.vn/master/screenshots/light_ss_171004_01.png)   |   ![My image2](https://raw.github.com/hsdk123/Light.vn/master/screenshots/light_ss_171004_06.png)

  
##### LightEditor.exe （エディター）  

基本           |  複雑な演出も楽に作ろう
:-------------------------:|:-------------------------:
![My image3](https://raw.github.com/hsdk123/Light.vn/master/screenshots/light_ss_171004_03.png) | ![My image4](https://raw.github.com/hsdk123/Light.vn/master/screenshots/light_ss_171004_04.png)

## 参考：翻訳に関して
  
Light . vn は未来の他言語対応（翻訳）に備えて以下二つのファイルに  
Light.vnのコマンドやエディター情報を全て収録しております。  
修正すると即時エディタとエンジンに反映されます。

もし他言語への翻訳などに興味のある方がいましたら、  
製作者にお気軽にご連絡ください（＿＿）
   

##### Commands.xml  
  
  Light.vn上で使用する日本語命令、及びエディター上のコマンド目録に表示される各コマンド情報が含まれております。  
  言い換えれば、このファイルを修正する事でLight.vnが使う命令語も、LightEditor.exe(エディター）上のコマンド情報目録に表示される各命令語の情報を変えることが出来ます。  
  
  例えば、`「背景」`という命令名がシンプル過ぎるため`「背景イメージ」`と言う命令名にしたい場合、Commands.xml を開いて、` <Command cmd="bg" name="背景" > `を` <Command cmd="bg" name="背景イメージ" > `に修正します。以降、Light.vnはスクリプト上で`「背景イメージ」`キーワードを読むたびに背景イメージファイルを表示します。  
  
  エディター上で表示される各コマンド情報も同じように修正できます。  
  例えば背景命令の情報が足りない、あるいはこう言い換えた方がもっと分かり易い、等と思う部分があったらCommands.xmlを開け   
  `<explanation lang="Jap" syntax="背景 [名前] [ファイル名]" 
                 details="//ex. 背景 bg1 scenery.png ...">`の`「details=」`部分を変えればエディター上で反映されます。

##### Strings(Editor).xml  
  
  エディターのテキスト目録。エディター上に表示されるあらゆるテキスト，  
例えばエディター下のFPS情報テキスト  
   `（FPS ( アップデート: {0} , render: {1} )）  `
等が入っています。  
  このファイルを修正すればエディター上で表示されるテキストが変わります。 
