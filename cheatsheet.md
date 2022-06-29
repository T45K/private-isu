# Nginx
### `nginx -t`
- Nginxの設定ファイルを検証する

### `systemctl reload nginx`
- EC2でのnginx再起動コマンド
- Dockerコンテナ上でNginxを再起動するとコンテナが止まる

# Docker
### `docker logs webapp_nginx_1 2>/dev/null`
- コンテナ内で、stdoutに出力された結果のみを出力する

### `docker compose down --rmi all --volumes --remove-orphans`
- 滅びの呪文

# alp
### `alp json --file tmp --sort=avg -r`
- レスポンスタイム平均降順ソート

# tips
- `docker compose down`してから`up`するとDBの内容が消える