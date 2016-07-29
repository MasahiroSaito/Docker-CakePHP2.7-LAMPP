HakoEve の WEB 開発環境を「Immutable Infrastructure（不変のインフラ）」化させるために、hakoeve の debug ブランチを元に作成した。新規のリポジトリを作成した理由としてし、debug ブランチの app/webroot/img のファイルが一部おかしかったので、そこを修正した状態で新たにリポジトリを作成する必要があったから。

HakoEve Web 開発環境の構築
--------------------------

1. master ブランチをクローン
- `chmod -R 777 hakoeve/` を実行
- `docker-compose up --build -d` で起動
- [http://localhost/](http://localhost/) にアクセス
- _phpMyAdmin_ にアクセス
- _hakoeve_ という名前でデータベースを作成
- _hakoeve_ にデータをインポートする
- [http://localhost/hakoeve/events](http://localhost/hakoeve/events) にアクセス

<<<<<<< HEAD
CakePHP
=======

[![CakePHP](http://cakephp.org/img/cake-logo.png)](http://www.cakephp.org)

CakePHP is a rapid development framework for PHP which uses commonly known design patterns like Active Record, Association Data Mapping, Front Controller and MVC.
Our primary goal is to provide a structured framework that enables PHP users at all levels to rapidly develop robust web applications, without any loss to flexibility.

Some Handy Links
----------------

[CakePHP](http://www.cakephp.org) - The rapid development PHP framework

[Cookbook](http://book.cakephp.org) - THE Cake user documentation; start learning here!

[Plugins](http://plugins.cakephp.org/) - A repository of extensions to the framework

[The Bakery](http://bakery.cakephp.org) - Tips, tutorials and articles

[API](http://api.cakephp.org) - A reference to Cake's classes

[CakePHP TV](http://tv.cakephp.org) - Screen casts from events and video tutorials

[The Cake Software Foundation](http://cakefoundation.org/) - promoting development related to CakePHP

Get Support!
------------

[Our Google Group](https://groups.google.com/group/cake-php) - community mailing list and forum

[#cakephp](http://webchat.freenode.net/?channels=#cakephp) on irc.freenode.net - Come chat with us, we have cake.

[Q & A](http://ask.cakephp.org/) - Ask questions here, all questions welcome

[Lighthouse](https://cakephp.lighthouseapp.com/) - Got issues? Please tell us!

[![Bake Status](https://secure.travis-ci.org/cakephp/cakephp.png?branch=master)](http://travis-ci.org/cakephp/cakephp)

![Cake Power](https://raw.github.com/cakephp/cakephp/master/lib/Cake/Console/Templates/skel/webroot/img/cake.power.gif)
=======
hakoeve
=======
>>>>>>> 941a6573ded0404acd15e3067bbb6815fb8d4a84
