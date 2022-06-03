# djangotest

## 概要

Python + Djangoを使って何か作ってみる

## 開発環境の準備

### プロジェクト用のディレクトリを作成して移動

``` bash
$ mkdir djangotest
```

### プロジェクトの仮想環境を設定

``` bash
$ cd djangotest
$ python3 -m venv djangotest
$ source djangotest/bin/activate
```

## Djangoをインストール

``` bash
$ pip install Django
```

## Djangoプロジェクトの作成

``` bash
$ django-admin startproject test001
```

## サーバーを実行

``` bash
$ python manage.py runserver
```

## ブラウザで確認

サーバー実行時に表示されるURLを開くと初期画面が表示される