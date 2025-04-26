# 環境構築

以下ができる事

- ターゲットサーバに鍵を使って ssh ログイン
- ターゲットサーバ上でパスワードなしで sudo

# 実行

```bash
$ ansible-playbook -i inventory.txt install.yml -v
```
