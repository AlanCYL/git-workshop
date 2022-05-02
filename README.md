# git-workshop

### 上課心得分享

#### 上半堂課

* _與大家分享學習狀況及目標以及未來的上課方式_
<br>

老師先從自我介紹開始說明，可以了解老師經歷相當豐富，不管 **外商、傳產、新創** ，甚至擁有 **創業經驗**，相信在未來的這個月的課堂上一定能跟老師學習到非常多。
<br>
gity 
且小賴老師十分用心，在開始教學前亦花時間了解大家目前的學習狀況，以及與大家討論希望未來的教學方式為何。
<br>

不過老師一直說  `就算你們現在這樣表決，我還是會講我想講的啦`  ，感覺的出來老師是一位非常幽默的老師，而且很用心，讓我相當期待!
<br><br><br>

* _複習git以及github_
<br>

老師先向我們再次說明什麼是 **git** ，以及 **git** 的重要性，補充了很多當時華如學姊尚未詳述的地方，因此對 **git** 的使用又更加地了解。老師也再次的教關於[終端機(Terminal)](https://zh.wikipedia.org/zh-tw/%E7%BB%88%E7%AB%AF_(macOS))，以及[git](https://zh.wikipedia.org/zh-tw/Git)的使用方式。
<br>

ex:
<br>

| Windows  | MacOS/Linux | 說明                        |
| -------- | ----------- | -------------------------- |
| cd       | pwd         | 顯示目前所在路徑              |
| cd       | cd          | 切換目錄 change directory   |
| mkdir    | mkdir       | 建立新的檔案夾  make dir     |
| type null > | touch    | 建立新的檔案                |
| dir      | ls          | 列出目前檔案夾的檔案列表  list   |
| copy     | cp     | 複製檔案   copy  |
| move     | mv     | 移動檔案   move  |
| del     | rm     | 刪除檔案    remove |
| cls     | clear     | 清除畫面上的內容     |

<br>
ex:
<br>

```bash=
git config --global user.name "ashleylai"
git config --global user.email "ashleylai58@gmail.com"
# 確認設定的情況
git config --list
```
<br>

#### 下半堂課

* _git 進階使用方式-(main,branch)_

```bash=
# 檢視分支
$ git branch

# 新增分支
$ git branch {branch-name}

# 切換分支
$ git switch {branch-name}   
$ git checkout {branch-name} 

# 合併分支, 例如把 feature-login 合併進去 main
# 先切換到 main
$ git switch main
# 再把 feature-login 合併進來
$ git merge feature-login

# 刪除本地分支
$ git branch -d {branch-name}

```


* _了解git flow(業界工作必用)_
![](https://i.imgur.com/rV7GdFn.png)


