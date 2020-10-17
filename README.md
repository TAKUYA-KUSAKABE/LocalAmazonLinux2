# Setting
すぐに実験できるように秘密鍵を登録していますが、LocalのDockerにしか使えません。

## Dockerの起動

```bash
$ docker-compose up
```

## SSH

```bash
$ ssh ec2-user@localhost -p 2222 -i ./.ssh/id_rsa
```
