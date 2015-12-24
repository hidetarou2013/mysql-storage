# mysql-storage

mysql-storage コンテナの使用方法
mysqlサーバのデータ保持用コンテナになります。

## 3.git clone


```
mkdir work && cd $_
git clone git@github.com:hidetarou2013/mysql-storage.git
```


## 4.docker build

```
cd mysql-storage
docker build -t hidetarou2013/mysql-storage .
```

## 5.docker create

```
docker create --name mysql-storage hidetarou2013/mysql-storage
```

