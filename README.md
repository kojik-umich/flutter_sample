# flutter_sample

これは NSK 117期・同期一同で作成する flutter の最初のプロジェクトです．

## 開発環境の作り方

ここではWindowsの導入方法を説明します．Macはまた今度．なかしーすまん．

基本的には以下のサイトを参考にしてるので，不明点はここを見てください．
公式：https://docs.flutter.dev/get-started/install/windows
初心者向け：https://qiita.com/apricotcomic/items/7ff53950e10fcff212d2

### Git の入手

絶対的に必要です．入れてください．これとかを参考に頑張って．
https://miya-system-works.com/blog/detail/128
### flutter の導入

Git の clone で入手しましょう．練習にもなるし．
`Win+R` で `cmd` と打ってください．おすすめのコマンドは以下の通りです．

```console clone
cd {クローンしたい場所} （楠崎はC:\Git）
git clone https://github.com/flutter/flutter.git -b stable
```

フォルダに flutter が入っていることを確認の後，次のコマンドを打ってください．

```console install
cd {クローンした場所}\flutter\bin
flutter
flutter.bat
dart
dart.bat
```

### VSCode の設定
まずは公式から VSCode をインストールしてください．
https://code.visualstudio.com/

次に，ここからプラグインを入手してください．
https://marketplace.visualstudio.com/items?itemName=Dart-Code.flutter

### このプロジェクトの取得

```console this_project
cd {クローンしたい場所}　（楠崎は[...]\Desktop）
git clone https://github.com/kojik-umich/flutter_sample.git
```

## このプロジェクトの動かし方
VScodeで `Ctrl+Shift+@` でターミナルを起動．

```console this_project_run
{flutter入れた場所}\bin\flutter run
```

これで 1 を選択すれば Chrome でプログラムが立ち上がるはずです．

おしまい
