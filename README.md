### 前提
フロント側にNuxt.js,バックエンドをAPIとしてlaravelで作成

### backend
install laravelX.X

```
# Install the latest Laravel project
$ make create-project

$ make install-recommend-packages 
```

or
```
$ docker-compose exec app bash

[app]

$ composer create-project --prefer-dist "laravel/laravel=8.*" .

$ php artisan -V 
Laravel Framework X.X.X
```
### frontend
