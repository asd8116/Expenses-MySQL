# 記帳本

運用 Express & MySQL 打造的網頁，將平常的花費與開銷進行紀錄。

## Picture

![畫面截圖](https://i.imgur.com/6OF1u7H.jpg)

## Environment SetUp

- [MySQL](https://downloads.mysql.com/archives/) - Database

* [Node.js](https://nodejs.org/en/) - JavaScript runtime built

- [Express](https://expressjs.com/zh-tw/starter/installing.html) - Node.js web framework

## Installing

###### 如何下載並啟動專案

啟動 MySQL 資料庫，開啟終端機並下載專案，完成後會顯示 Done 訊息

```
git clone https://github.com/asd8116/Expenses-MySQL.git
```

從終端機導入目標檔案，並下載工具包

```
npm install
```

在 [facebook for developers](https://developers.facebook.com/) 創建一個新的應用程式，取得編號 (App ID)和密鑰 (App Secret)

開啟程式碼編輯器，在根目錄底下創建一個 `.env` 檔，輸入 ID 與 Secret

```
FACEBOOK_ID=******
FACEBOOK_SECRET=******
FACEBOOK_CALLBACK=http://localhost:3000/auth/facebook/callback
```

開啟本地伺服器。

```
node app.js
```

成功連結後，瀏覽器輸入 http://localhost:3000
網頁即可運行並執行動作。

## Register & Login

###### 有帳號後方可使用網頁功能

- 使用者可以進行一般帳密註冊
- 使用者可以透過 Facebook 進行第三方登入
- 使用者登入、註冊時會依據狀況出現提示訊息

## Features

###### 功能特點

- 可瀏覽全部的開支紀錄，並顯示總花費
- 用月份欄進行開支查找
- 用類別欄進行開支查找
- 點擊 `新增支出` 可填入新的開支紀錄
- 點擊 `修改` 可修改開支紀錄的資料
- 點擊 `刪除` 可移除開支紀錄的內容

## Contributor

[馬振壹 Wanaka](https://github.com/asd8116)
