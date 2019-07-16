# vscode
VSCodeの設定ファイル



## シンボリックリンクを作成

### Mac

```bash
read -p "Please input the filepath of your settings.json: " __path; echo
sudo ln -fnsv ${__path} ~/Library/'Application Support'/Code/User
```



