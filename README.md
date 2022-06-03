# template-code-example

這邊主要放跟網頁相關的範例程式碼，省去跑官網查文件的時間，未來工作可能會用上!

- 若是使用 cdn 記得加上 cdn-xxx.html
- npm 版本記得用資料夾包起來
- 可以的話結尾加上大的版本號碼
- 有新增的話記得在 README 更新

---

## bootstrap

cdn-bootstrap5 | 5.0

## express

- express4
  - basic | 基本啟用 server 方式

## pixijs

## react

- cdn-react-basic | 18
- cdn-react-function-component | 18
  <!-- - react-react-i18next -->
  <!-- - react-router -->
  <!-- - react-bootstrap -->

## vue

- cdn-vue2-basic | 2.6 | vue 框架 cdn
- cdn-vuetify-table | 2.6 | vue+CSS 框架

## web-function

right-click-menu | 自定義滑鼠右鍵選單

---

## 講解遠端協作的公司是如何合併程式碼

1. 拉群組成員，ex:我們創一個叫做`todomonster`的群組
2. 組長用公司帳號創建一個`repo`
3. 組員使用`fork`將該專案拉回到私人專案
4. 組員更新程式碼後`commit`+`push`到私人專案，之後使用`pull request`推到公司的`repo`
5. 組長會看到 PR 提交的通知，`code review`後執行`merge`，Github 檢查是否有衝突`conflict`，沒有的話完成合併

其實正式上線的專案會分成不同分支`branch`，有開發新功能和穩定版...等

`fork`和`clone`剛開始會以為都是複製，但其實差很大!
