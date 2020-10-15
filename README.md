# メモ

## sshのチェックを無効にしておく
たまにkeyチェックで失敗するのでansible.cfgに設定追加する
```
[defaults]
host_key_checking = False
```
