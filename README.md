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

$ composer create-project --prefer-dist "laravel/laravel=8.*" .

$ php artisan -V 
Laravel Framework X.X.X
```
### frontend
```
# install dependencies
$ yarn install

# serve with hot reload at localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```

