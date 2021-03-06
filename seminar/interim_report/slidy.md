% GitHubを利用したプログラミング練習サイトの構築
%
% 2012-10-31


GitHubとは
====================


> GitHub（ギットハブ）はソフトウェア開発プロジェクトのための共有ウェブサービスであり、
  Gitバージョン管理システムを使用する。

  > <small>Wikipediaより</small>

Ruby on RailsやjQueryなど、
多くのオープンソースプロジェクトがGitHubを利用して開発を行なっている。



GitHubとは(2)
====================

ソフトウェア開発者のためのSNSでもある。

多くの開発者がGitHubを使って
自分が作ったプログラムを公開したり、
気に入ったプロジェクトの開発に参加したりしている。



研究内容
====================

GitHubのなかの**Gist**というサービスに注目


Gist
====================

数行程度から数ファイル程度の小さなコード片を投稿して共有するサービス。



研究内容(2)
====================

Gistを使って気軽にプログラミングの問題やその解答を投稿できるサイトを作りたい。



実装
====================

Ruby on Railsを使用。



既に実装した機能
====================

- ユーザー認証
- 問題・解答の投稿機能



これから実装したい機能
====================

- 解答の評価・採点
- ユーザビリティの改善
- ...

ちゃんとしたWebサービスと呼べるようになるくらいまで完成度を上げたい。



その他
====================

#### テストの充実

自動テストの環境はすでに整えてあるので、
既存の機能のテストやこれから実装していく機能のテストなども充実させたい。

(できるかぎりTDD・BDDで)



終わりに
====================

このプロジェクト自体もGitHubで開発中。
<https://github.com/i09158knct/seminar-proto>


開発中のアプリはHeroku上で稼働中。
<http://seminar-i09158knct.herokuapp.com/>
