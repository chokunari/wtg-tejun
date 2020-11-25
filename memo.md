# 手順
## Docker
- `docker network create wtgnet`
- `docker-compose up -d --build`
    - ./wtg/docker配下で実行。

# frontend
## 初期セットアップ
- wtg-frontend配下のファイルを全て削除。
- `git init`
- `git remote add origin https://github.com/chokunari/wtg-frontend.git`
- `git pull origin master`
- `yarn`

# backend
## 初期セットアップ
- `express -e wtg-backend`
- `mkdir src`
- `touch index.js`
- index.jsを他からコピー or git pull
- `node src`