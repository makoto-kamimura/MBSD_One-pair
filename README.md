# MBSD_one
脆弱性診断ツール"脆弱性科クリニック(仮)"
創造社デザイン専門学校
情報セキュリティ管理者資格コース二年
チーム"MBSD_one"

# DEMO
※DEMO映像追記予定

# Requirement
* フロントエンド
    * HTML / CSS / javascript(Ajax)
* バックエンド
    * python(Django)
* インフラ
    * CentOS(テスト環境) / virtualbox(vagrant)(テスト環境) / AWS EC2(本番環境)
    * Docker(Docker-compose)
        * nginx
        * mariaDB(仮)
※バージョン等追記予定

![test](/README_img/shitagaki.jpg) 
※インフラ構成図については清書を予定

# Installation
1. テスト環境接続方法
    1. クライアントのDNS設定を"172.16.3.88"に設定
        1. ブラウザにて"mbsd.local"に接続(demo環境)
        2. ブラウザにて"mbsd.local:8000"に接続(テスト環境(Django))
        3. ブラウザにて"172.16.3.88"に接続(テスト環境_ターゲット)

2. 本番環境接続方法
    1. ※組織アカウントにて起動中_正式版は後日追記予定

# Author
* designer
    * sayaka tanabe

* engineer
    * makoto kamimura

# License
"脆弱性科クリニック" is Confidential.