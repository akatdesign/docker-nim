## docker-nim


**環境構築**
``` bash
$ cd docker-nim/
$ docker compose up -d --build
$ docker compose exec nim bash
``` 
**環境から抜ける**
```bash
$ exit
$ docker compose down
$ docker image rm imageid
```
**確認**
```bash
$ docker image ls
$ docker container ls
```
