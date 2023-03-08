# Laravel プロジェクトのテンプレート

---

- PHP 8.0
- Nginx 1.23.3
- MySQL 8.0

```
docker compose -f "docker-compose.yml" up -d --build
```

※ 権限がないため、ログが記録できず、エラーになる場合は、以下コマンドを実行

```
docker exec -it app sh
cd laravel
chmod -R 777 storag
```
