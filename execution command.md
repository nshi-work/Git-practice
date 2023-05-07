# Initial setting

* git config --global user.name "user"
* git config --global user.email "email"
* git config --global core.editor 'vim -c "set fenc=utf-8"'



# create project

* mkdir folder name

* git init

### Create file or Fix file

* git add 'File name(Specify multiple files using single-byte spaces)'

* git commit -m "commit message"



```
add : ファイルの追加
fix : バグ修正
hotfix : クリティカル(致命的)なバグの修正
update : 機能修正（バグではない）
change : 仕様変更
clean : 整理（リファクタリングなど）
remove : ファイルの削除
upgrade : バージョンアップ
```



### Add Repositories

* git remote add origin https://github.com/xxxxx/xxxxx.git
*  git push -u origin master

