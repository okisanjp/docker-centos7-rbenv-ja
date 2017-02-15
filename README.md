# docker-centos7-rbenv-ja

centos7を日本語環境用に構成し、rbenvを導入したコンテナです

## usage

```
docker pull okisanjp/docker-centos7-rbenv-ja
```

```
docker run -itd --name rbenv-test okisanjp/docker-centos7-rbenv-ja
```

```
docker exec -it rbenv-test /bin/bash --login
```

```
# rbenv -v
rbenv 1.1.0-2-g4f8925a

# ruby -v
ruby 2.3.0p0 (2015-12-25 revision 53290) [x86_64-linux]

# type -a ruby
ruby is /root/.rbenv/shims/ruby
```
