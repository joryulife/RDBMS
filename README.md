# RDBMS
webアプリケーションにおいて欠かせないRelational Database Management SystemをRustで実装しようという企画がWEB+DBという雑誌に掲載されていたためそれにならって実装したもの＋多少のオリジナリティ(実験要素)を含んだ簡易的なRDBMSです。実践したい方は本家様をご参考にしていただければと思います。
## 機能
### テーブル作成機能
テーブルの削除やテーブルの定義変更の機能はなしです
作成できるテーブルも一つのみです。
### 行の挿入
行の挿入は可能ですが、削除、更新は未実装です。
### 行のクエリ
クエリプランななど便利な機能はありません
### セカンダリインデックス
一応実装予定
### マルチスレット動作
シングルスレット実行のみを実装します。そのためトランザクション処理も考えません。
### JOIN機能
実装されていません。テーブル一つしかありませんし、、、
# DEMO
実装段階なのでなし

# Requirement
必要ライブラリ

# Installation
``` bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
# Usage

# Note

# Author

*joryulife
*龍谷大学
*joryulife@gmail.com

# License
