# **FGUI**

FairyGUI Editor is a Professional and intuitive UI editor  .

簡単に言えば、UIを作るための神ツールです。

## インストール

https://www.fairygui.com/download　からインストール

![image-20221109163332150](FGUI紹介.assets/image-20221109163332150.png)

開きます。

![image-20221109163629572](FGUI紹介.assets/image-20221109163629572.png)

## 導入

新規プロジェクト

![image-20221109163955047](FGUI紹介.assets/image-20221109163955047.png)

設定します。

![image-20221109164200908](FGUI紹介.assets/image-20221109164200908.png)

## 紹介

<img src="FGUI紹介.assets/image-20221109165351886.png" alt="image-20221109165351886" style="zoom:200%;" />

1.ショートカットボタンリストです。Component、Buttopnとかの作成、画面解像度の調整、テスト、とかの処理。

2.**Library**はPackageとPackageのComponent管理です。

**Favorites**は…Favoritesです、よく使うものは便利に確認。

Searchは**Library**のもの探す用です。

3.**Hierarchy**はこのcomponent中のエレメントリスト。

4.**Preview**、プレビュー用。

5.photoshopみたいな感じ、エレメント追加、変更とかの操作。

6.Tabです。他のTabに切り替えます。

7.具体的な機能調整。

## 先ずはFGUIで画面を作りましょう！

タイトルを作りたいの場合

1.まずは名前変更

![image-20221109173136345](FGUI紹介.assets/image-20221109173136345.png)

2.Textを作り出す

![image-20221109173752487](FGUI紹介.assets/image-20221109173752487.png)

3.名前変更、サイズ調整、内容入力とか

![image-20221109174103013](FGUI紹介.assets/image-20221109174103013.png)

4.画像付き

素材はファイルに追加します。

![image-20221109180424044](FGUI紹介.assets/image-20221109180424044.png)

![image-20221109180340435](FGUI紹介.assets/image-20221109180340435.png)

Refreshすればこんか感じ

![image-20221109180524778](FGUI紹介.assets/image-20221109180524778.png)

ドラッグして、サイズ調整

![image-20221109180625959](FGUI紹介.assets/image-20221109180625959.png)



もう一匹追加

![image-20221109180957880](FGUI紹介.assets/image-20221109180957880.png)

**Set Exported**、これ大事

![image-20221109181021033](FGUI紹介.assets/image-20221109181021033.png)



## FGUIから(Publish)導出する

![image-20221109181313051](FGUI紹介.assets/image-20221109181313051.png)

Package SettingのGenerate Code をチェック忘れず！ソースコード生成用。

Global Setting→PackingのTarget PathとGenerate CodeのTargetPathを設定して、Publishする。

![image-20221109183635046](FGUI紹介.assets/image-20221109183635046.png)

![image-20221109182912746](FGUI紹介.assets/image-20221109182912746.png)

これでファイルに反映

![image-20221109183832361](FGUI紹介.assets/image-20221109183832361.png)

自動的にSprite Atlas化

![image-20221109183948593](FGUI紹介.assets/image-20221109183948593.png)

自動的に生成されたソースコード、Unity中に使える。

![image-20221109184124758](FGUI紹介.assets/image-20221109184124758.png)

## Unityで反映

### 1.UnityでSDK入れる

https://github.com/fairygui/FairyGUI-unityからインストール

Asset内丸コピ

![image-20221110110720230](FGUI紹介.assets/image-20221110110720230.png)

### 2.FGUIで生成ファイルはAseets内にコーピ

実際開発の時にはFGUIから生成パスはここに指定すればこの手順いらないです。

![image-20221110114201816](FGUI紹介.assets/image-20221110114201816.png)	

### 3.Unity中に表示

右クリックしてUICameraを選択、FGUI用のカメラを作りだす。

![image-20221110120726991](FGUI紹介.assets/image-20221110120726991.png)

Tag調整

![image-20221110184740335](FGUI紹介.assets/image-20221110184740335.png)



Todo

ソースコード部分