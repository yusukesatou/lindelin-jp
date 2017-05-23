---
layout: project
title: Laravel ELBサポート
description: "このパッケージを使用すると、Amazon ELBを使用している際、laravelプロジェクトがセキュア接続（HTTPS）を正しく認識することができます。"
related:
- Lindelin
- Lindalë
---

## Laravelパッケージ：AWS ロードバランササポート


このパッケージを使用すると、Amazon ELBを使用している際、laravelプロジェクトがセキュア接続（HTTPS）を正しく認識することができます。

### インストールと使用方法

パッケージをインストールするには、下記Composerコマンドを叩いてください:

~~~bash
composer require lindelea/laravel-aws-elb-support
~~~

インストール完了後、サービスプロバイダーを`config/app.php`の`providers` 配列に追加してくだいさい。 

~~~php
Lindelea\Support\Aws\Elb\ServiceProvider::class,
~~~

### ライセンス

このパッケージは[MIT license](https://github.com/lindelea/laravel-aws-elb-support/blob/master/LICENSE)の下で公開されているオーペンソースソフトウェアです。