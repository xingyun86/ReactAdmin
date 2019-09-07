```bush
git clone https://github.com/xingyun86/ReactAdminServer.git
```

## Install
```bush
yarn install
```
## Run
### Development
```bush
yarn run start
```
### Production(Build)
```bush
yarn run production
```


后台服务使用[koa2](https://github.com/koajs/koa)构建，并且使用[lowdb](https://github.com/typicode/lowdb)持久化数据到JSON文件。