# メモ

## sshのチェックを無効にしておく
たまにkeyチェックで失敗するのでansible.cfgに設定追加する
```
[defaults]
host_key_checking = False
```

## コマンド実行
不安なら-D -Cつけると良い。差分確認とドライランできる
```
 ansible-playbook -i inventory/inventory.ini set_line_config.yml -D -C
```
