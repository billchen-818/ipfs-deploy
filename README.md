# ipfs-deploy

## 前置条件

 编译ipfs docker images

```
git clone git@github.com:ipfs/go-ipfs.git
cd go-ipfs
git checkout v0.9.0
docker build -t ipfs:v0.9.0 -f Dockerfile .
```

## 运行

```
git clone git@github.com:billchen-818/ipfs-deploy.git
cd ipfs-deploy
docker-compose up -d
```
