# git & github 整合
###### tags: `git` `github`
**要上傳檔案到 GitHub，需要先在上面開一個新的專案。請先在 GitHub 網站的右上角點選「+」號，並選擇「New repository」：**
1. Repository name 可填寫任意名稱，只要不重複即可。
**<font color="red">按下「Create repository」即可新增一新的 Repository。</font>**
**接下來，會看到的這個引導畫面：**
![](https://i.imgur.com/WpRuQya.jpg)
上面的指示僅教您做法而已。
<font color="red">*注意需使用https指令</font>
以下為首次處理(本機操作)
```bash
git init (建立.git隱藏檔)
git add *(自己需上傳的檔案)
git commit -m "first commit"
git remote add origin https://github.com/capeta0507/gitproj01.git (git & github 控管連結)
git push -u origin master (首次將 git 推播到 github 去 )
```
git push 成功之後 https://github.com/capeta0507/youtube_api_v3 就可以看見github專案了
#### 平常處理
```bash
git add .(上傳的檔案)
git commit -m "儲存命名"
git push (將檔案推至github)
```
