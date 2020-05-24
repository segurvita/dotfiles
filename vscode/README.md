# vscode
VSCodeの設定ファイル



## シンボリックリンクを作成

### Windows

```bash
rem settings.json の設置フォルダをフルパスで入力
set /p __path="Please input the folder path of your settings.json: "

rem シンボリックリンクを作成
mklink /d %AppData%\Code\User %__path%
```

### Mac

```bash
# settings.json の設置フォルダをフルパスで入力
read -p "Please input the folder path of your settings.json: " __path; echo

# シンボリックリンクを作成
sudo ln -sf ${__path} ~/Library/'Application Support'/Code/User
```



