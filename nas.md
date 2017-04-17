---
layout: page
title: 研究室での共有フォルダ・個人フォルダ利用
description: 中村研究室での共有フォルダ・個人フォルダの利用方法
section_id: tips
---

# 中村研究室における共有フォルダ・個人フォルダの利用について

## 目次
* [概要](#概要)
* 初期設定
    * [利用者登録・ID・初期PW](#利用者登録・ID・初期PW)
    * [接続・パスワード変更](#接続・パスワード変更)
    * [ドライブの割り当て（Windows）](#ドライブの割り当て)
    * [ドライブの認識（Mac）](#ドライブの認識)
* [インターネット経由での共有フォルダ・個人フォルダの利用](#インターネット経由での共有フォルダ・個人フォルダの利用)

<a name="概要"></a>
## 概要
* 中村研究室内LAN及びインターネット経由でアクセスできるフォルダを提供します
* 共有フォルダは登録全員が読み書き可能。共通文書置き場やファイル交換に便利。文献データベースもここに置いておきます。
* 個人フォルダは自分だけが読み書き可能。16GBの容量割り当て

<a name="初期設定"></a>
## 初期設定

<a name="利用者登録・ID・初期PW"></a>
### 利用者登録・ID・初期PW
* 利用者の登録は中村が行う。
* ログインIDはNUメールの@の前の部分、初期パスワードは12345678

<a name="接続・パスワード変更"></a>
### 接続・パスワード変更
* ブラウザから [https://QuickConnect.to/nakamura-nas01/](https://QuickConnect.to/nakamura-nas01/) にアクセス
* ログインID、初期パスワードを入れてサインイン
![LANからのサインイン画面]({{site.baseurl}}/images/fy2016/20170120nas-signin.png)
* 右上の人の上半身のアイコンをクリックし、「個人」メニューを選択
![ログイン後のトップページ]({{site.baseurl}}/images/fy2016/20170120option-menu.png)
* 新しいパスワードを設定する
![個人設定画面]({{site.baseurl}}/images/fy2016/20171020personal-settings.png)
* 一旦ログアウトして下さい
![ログイン後のトップページ]({{site.baseurl}}/images/fy2016/20170120option-menu.png)
* 新しいパスワードを設定する（右上の人の上半身のアイコンをクリックし、「ログアウト」メニューを選択）
![ログイン後のトップページ]({{site.baseurl}}/images/fy2016/20170120option-menu.png)

<a name="ドライブの割り当て"></a>
### ドライブの割り当て（Windows）
* [Synologyのサイト](https://www.synology.com/ja-jp/knowledgebase/DSM/help/DSM/Tutorial/store_with_windows)を参考に設定します。Windows10の場合は、次のようになります。
* エクスプローラーを起動し、ネットワークドライブの割り当てをクリック
![ネットワークドライブメニュー]({{site.baseurl}}/images/fy2016/network-drive-menu.png)
* フォルダー欄に「\\\\92.168.11.28\public」と入力し、再接続するにチェックを入れて、次に進む。「\」は、Windowsでは半角の円マークを入力する。
![ネットワークパスの入力]({{site.baseurl}}/images/fy2016/assign-network-drive.png)
* 共有フォルダのIDとパスワードを入力し、資格情報を記憶にチェックを入れて、次に進む
![認証]({{site.baseurl}}/images/fy2016/nas-authentication.png)
* ドライブが追加された
![エクスプローラー（ドライブ追加）]({{site.baseurl}}/images/fy2016/public-drive-added.png)
* 同様に個人フォルダ（パスは、\\\\192.168.11.28\home）もネットワークドライブの割り当てを行う

<a name="ドライブの認識"></a>
### ドライブの認識（Mac）
* [Synologyのサイト](https://www.synology.com/ja-jp/knowledgebase/DSM/help/DSM/Tutorial/store_with_mac)を参考に設定して下さい。
* IPアドレスは、192.168.11.28です。

<a name="インターネット経由での共有フォルダ・個人フォルダの利用"></a>
## インターネット経由での共有フォルダ・個人フォルダの利用
* 自宅などからのインターネット経由でもフォルダにアクセスできます。
* ブラウザから [https://QuickConnect.to/nakamura-nas01/](https://QuickConnect.to/nakamura-nas01/) にアクセス
* ログインID、初期パスワードを入れてサインイン
* File Stationのアイコンをクリックすると下のダイアログが出る。「home」が個人フォルダ（あなただけアクセス可能）、「public」が共有フォルダ（登録利用者全員がアクセス可能）
![共有・個人フォルダ]({{site.baseurl}}/images/fy2016/20170120file-station.png)
* ファイルをドラッグアンドドロップで移動できます
![ドラッグアンドドロップ]({{site.baseurl}}/images/fy2016/20170120drag-and-drop.png)
