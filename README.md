# antig_next_postgres

Antigravity を使う前の準備。

```bash
# Next.jsアプリ作成
$ docker compose run --rm app sh -c 'npx create-next-app . --typescript'

# コンテナ起動
$ docker compose up

# 所有者と所有グループの変更
$ sudo chown -R $USER:$USER src/

```
