# プロ炎
# 開発環境
- Node.js v11.5.0
- MongoDB v4.0.5

# Windowsでの環境構築
```
> choco install nodejs mongodb
```
* 自動的にMonngoDBのパスは通らないのでC:\Program Files\MongoDB\Server\4.0\binをPathに追加する必要がある
* MongoDBの実行時に使用するフォルダを作成する
  * C:\mongodb\data
  * C:\mongodb\logs

# 実行
```
# MongoDBのサービスを動かす
> mongod --dbpath C:\mongodb\data --logpath C:\mongodb\logs\mongodb.log
# プロジェクトディレクトリに移動
cd cd .\c-9-e\data\mevn-stack\
# アプリケーション起動
> npm start
```

## VM
### VM動作環境
- Vagrant 2.2.2
- Virtual Box 5.2.22

### 本番環境VMのつかいかた
```
$ cd vagrant/
$ vagrant up
```