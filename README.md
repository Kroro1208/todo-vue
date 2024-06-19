# 使用コマンド

`php artisan make:model YourModelName -m -f -r --controller --policy`

`php artisan install:api`

`php artisan make:resource TaskResource`

### 作成した api ルート確認

POSTMAN で api 叩いて json 取得できるかを確認する

`php artisan route:list --path=api`
