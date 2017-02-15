# docker-centos7-rbenv-ja

centos7を日本語環境用に構成し、rbenvを導入したコンテナです

## usage

```
docker pull okisanjp/centos7-rbenv-ja
```

```
docker run -itd --name rbenv-test rbenv
```

```
docker exec -it rbenv-test /bin/bash --login
```

```
# rbenv -v
rbenv 1.1.0-2-g4f8925a
```
