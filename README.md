# railsAPIバックエンド側リポジトリ

## 操作

`docker-compose up --build -d`

```
docker-compose exec app bash
bundle install　（Gemfileに基づいて更新）
rails db:migrate:reset　（データベースの更新）
rails db:seed　（seedファイル記載のデータを投入）
```

## やり残し

- APIのRspecテスト