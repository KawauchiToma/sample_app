#Ruby on Rails チュートリアルのサンプルアプリケーション

これは、次の教材で作られたサンプルアプリケーションです。
[*Ruby on Rails チュートリアル*](https://raisltutorial.jp/)
[Michael Hartl](http://michaelhartl.com/)著

##ライセンス

[Ruby on Rails チュートリアル](https://railstutorial.jp/)内にあるソースコードがMITライセンスとBeerwareライセンスのもとで公開されています。詳細は[LICENSE.md](LICENSE.md)をご覧ください。

##使い方

このアプリケーションを動かす場合は、まずはリポジトリを手元にクローンしてください。その後、次のコマンドで必要となるRubyGemsをインストールします。

$bundle install --without production

その後、データベースへのマイグレーションを実行します。

$rails db:migrate

最後に、テストを実行してうまく動いているかどうかを確認してください。

$rails test

テストが無事に通ったら、Railsサーバーを立ち上がる準備が整ってるはずです。

$rails server

詳しくは、[*Ruby on Rails チュートリアル*](https://railstutorial.jp/)を参考にしてください。
