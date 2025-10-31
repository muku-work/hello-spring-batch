## プロジェクトの概要
このプロジェクトは、Claude Codeを利用しながら Spring Batchの基礎を学ぶためのデモプロジェクトです。\
開発者はClaude Codeに一つずつ指示を与え、Claud Codeは指示の通りにファイルを作成します。\
これにより、開発者はSpring Batchの基本的なオブジェクト構成を短時間で習得することが出来ます。

## プロジェクトの情報
**General Info**
- Project: maven
- Language: Java
- Java Version: 21
- Spring Boot Version: 3.5.7

**Project Metadata**
- Group: com.udemy
- Artifact : hello
- Name : hello-spring-batch
- Description : Demo project for Spring Boot
- Package name: com.udemy.hello

## SpringBatchの設定
**Configクラス**
パッケージ: com.udemy.hello.config.SpringConfig.java

## Claude Codeの役割
- プロジェクトの初期状態は、プレーンなSpring Boot プロジェクトです。開発者の指示に従い、Claude Codeが適切なモジュールを作成します。
- Claude Codeは、claude.mdのプロジェクト構成に従ってプロジェクトを更新します。　
- Claude Codeは、モジュールの作成時にreadme.mdへフォルダの階層構造を追記します。
- Claude Codeは、アプリケーション完成時にアプリケーションの仕様をreadme.mdへ追記します。