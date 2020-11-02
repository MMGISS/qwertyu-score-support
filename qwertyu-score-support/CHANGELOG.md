# QWERTY:U Score Support

Unity2020で製作中の音ゲー「QWERTY:U」の譜面シンタックスハイライト拡張機能です
拡張子.qwertuscore及び.qwertyuscore.txtを認識します
チェンジログの書き方はよく分かっていないのでお粗末

文法についてはここを参照されたし → https://hackmd.io/YJ8Fh3zfRaebYHNJWjPONg

## ご使用方法

1. このフォルダをコピーし"C:/Users/ユーザー名/.vscode/extentions/"に貼り付ける(Windows)
2. VSCodeの設定(Ctrl+,)に移動しthemeと検索
3. 出てきたテーマの項目を"Monokai (QWERTY:U Score Support Arrange)"に設定する
4. 使える

## チェンジログ

### v0.1.0 2020/10/21

- 最初期
- ノーツ、レーン移動、scroll、bpm、jumpに対応
- いい感じのフォルダ共有プラットフォームとかよくわからないのでとりあえずGoogle Driveにて共有

### v0.1.1 2020/10/22

- 微修正
- レーン移動のタイプ宣言の実装(x,y,z,dx,dy,dz,a)
- 移動軸に応じたハイライトカラーの変更

### v0.1.2 2020/10/22

- 単行コメントアウト機能の修正
- レーン回転(ラジアン)の追加

### v0.1.3 2020/10/22

- Githubにてリポジトリを作成
- https://github.com/MMGISS/qwertyu-score-support
- Download ZIPをおすすめします

### v0.1.4 2020/10/29

- positionfrom命令の実装
- 命令の簡略化の実装
  path → p
  positionfrom → pf など

### v0.1.5 2020/11/02

- beatdefault命令の実装