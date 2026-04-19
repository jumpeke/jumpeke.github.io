# jumpeke.github.io

このリポジトリは、Jekyllを使ったGitHub Pagesの個人サイトです。

## ローカルでの実行方法（使い方）

ローカル環境でこのサイトをビルドして確認するには、以下の手順を実行してください。

1. **RubyとBundlerのインストール**
   Rubyがインストールされていることを確認し、Bundlerをインストールします。
   ```bash
   gem install bundler
   ```

2. **依存関係のインストール**
   Gemfileに記載されている必要なGem（Jekyllなど）をインストールします。
   ```bash
   bundle install
   ```

3. **ローカルサーバーの起動**
   以下のコマンドを実行すると、Jekyllのローカルサーバーが立ち上がります。
   ```bash
   bundle exec jekyll serve
   ```

4. **ブラウザで確認**
   ブラウザで `http://localhost:4000` にアクセスするとサイトが表示されます。ファイルの変更を検知して自動的にリロードされます。