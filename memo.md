# 手順
## Docker
- `docker network create wtgnet`
- `docker-compose up -d --build`
    - ./wtg/docker配下で実行。

# frontend
## 初期セットアップ
- wtg-frontend配下のファイルを全て削除。
- `rm -rf *`
- `git init`
- `git remote add origin https://github.com/chokunari/wtg-frontend.git`
- `git pull origin master`
- `yarn`

# backend
## 初期セットアップ
- `express -e wtg-backend`
    - これやらずにgit pullすれば良いかも。
- `cd wtg-backend`
- `mkdir src`
- `touch index.js`
- `git init`
- `git remote add origin https://github.com/chokunari/wtg-backend.git`
- `git pull origin master`
- `node src`

# geocoding api
- json結果の緯度経度の場所
    - 緯度
        - results.geometry.location.lat
    - 経度
        - results.geometry.location.lng