`env_sample`を`.env`にコピーして、AWSの認証情報を記入する

```sh
docker-compose run aws sts get-caller-identity --query Account --output text
```

```
64********60
```

IAMユーザのIDが出力されればOK
