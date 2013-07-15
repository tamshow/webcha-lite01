 webっちゃlite JavaScript研究会 第1回
===========


### 「JavaScriptのタスクランナーGruntでsassをwatchする」

####Gruntとは？
JavaScriptのタスクランナー
http://gruntjs.com/

####手順
1. Node.jsをインストールしておきます。
1. Gruntのコマンドを使えるようにnpmのグローバルにインストールします。
`npm install -g grunt-cli`
1. npmをプロジェクトディレクトリにインストールします。
 - プロジェクトディレクトリにpackage.jsonを作成します。
 ````
{
  "name": "name",
  "version": "1.0",
  "devDependencies": {
    "grunt": "~0.4.0"
  }
}
````
`npm install`
1. Gruntを設定します。
 - Gruntfile.jsを作成します。
