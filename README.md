# MBSD_one
脆弱性診断ツール"脆弱性科クリニック"  
創造社デザイン専門学校  
情報セキュリティ管理者資格コース二年  
チーム"One_pair"
http://One-pair.com

※ Attention ※
当ツールは診断対象とするWEBサイトに対して相当数のアクセスを試みるツールです。
"不正アクセス禁止法"等の法律に触れる恐れがございますので、診断対象のWEBサイト管理者に認可を得てご利用して頂きますようお願い申し上げます。
当ツール作成チームは記載ライセンスに準拠し、その旨に対しての責任は一切負わない旨、ご了承下さい。

# DEMO
※DEMO映像等追記予定
![脆弱性診断ツール利用手順書.pdf](/README_img/脆弱性診断ツール利用手順書.pdf)  
![flow_image.jpg](/README_img/flow_image.jpg)  

# Requirement
※バージョン等追記予定
* Frontend
    * HTML / CSS / javascript(Ajax)
* Backend
    * Python(Django)
* Infrastructure
    * Docker(Docker-compose)
        * Nginx
        * MySQL

* Tool
    * Design
        * Adobe XD(Web Export)
        * Adobe Illustrator
        * Adobe Photoshop
    * Coding
        * Visual Stdio Code

# Installation

Local deploy
1. Git clone -------------
2. "docker-compose.yml"の存在するディレクトリまで移動
3. "docker-compose down -v && docker-compose build && docker-compose up -d"をターミナルにて実行
4. "localhost:8080"をブラウザにて入力/実行

Server deploy
1. Git clone -------------
2. "docker-compose.yml"の存在するディレクトリまで移動
3. "docker-compose.yml"の内容を下記の通りに変更
    1. "vi docker-compose.yml"をターミナルにて実行
    2. "i"を押下、入力モードに変更
    3. 29行目の値を"80:80"に変更
    4. "esc"を押下、"wq"を入力し、上書き保存を実行
4. "docker-compose down -v && docker-compose build && docker-compose up -d"をターミナルにて実行
5. デプロイしたサーバーのIPアドレスをブラウザにて入力/実行

# Author
* Designer
    * Sayaka Tanabe
* Engineer
    * Makoto Kamimura

# License
Copyright &copy; 2021 ONE_pair
This program is a free software; you may redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 3 of the License, or any later version.
This program is a distributed in the hope that it will be useful,but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
You should have received a copy of the GNU General Public License along with this program. If not, see <a href="http://www.gnu.org/licenses/.">http://www.gnu.org/licenses/.</a>
