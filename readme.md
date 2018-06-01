# hidemaru_sbfolder
秀丸エディタで「今開いているファイルのフォルダ」をポップアップメニューで一覧表示して一発アクセスする。

![hidemaru_sbfolder_demo](https://user-images.githubusercontent.com/23325839/40838711-6556489a-65da-11e8-8b1b-7d580ab4df7c.jpg)

## システム要件
- [秀丸エディタ](https://hide.maruo.co.jp/software/hidemaru.html)
  - 動作確認は V8.58 で行ってます
- [SbFolder](http://home.att.ne.jp/delta/hrymkt/)

## インストール
- (1) SbFolder をダウンロードし、適当なフォルダに展開します
- (2) SbFolder.exe のフルパスをメモしておきます
- (3) hidemaru_sbfolder.mac.sample をコピーして hidemaru_sbfolder.mac をつくります
- (4) hidemaru_sbfolder.mac をテキストエディタで開き **$sbfolder_bin_path の部分に (2) でメモしたフルパスを記入** します
- (5) 秀丸エディタから hidemaru_sbfolder.mac をマクロ登録します
  - [マクロ] メニュー > [マクロ登録] を選択します
  - 空いているマクロ番号に登録してください
- (6) (5) で登録したマクロにショートカットキーを割り当てる
  - [その他] メニュー > [キー割り当て] を選択します
  - 左ペインにて割り当てたいショートカットキーを選び、右ペインにて (5) で登録した番号のマクロを選びます

## 使い方
登録したショートカットキーを押すと **カーソル（キャレット）位置** に、**今開いているファイルのあるフォルダ** を基点としてポップアップメニューが表示されるはずです。

## カスタマイズ
SbFolder 自体の使い方については SbFolder のドキュメントを参照ください。

SbFolder に与えるコマンドライン引数を変えたい場合、hidemaru_sbfolder.mac を適当に編集してください。

## ライセンス
[MIT License](LICENSE)

## 作者
[stakiran](https://github.com/stakiran)
