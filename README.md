# 家用記帳本

![rejected](https://github.com/Steavn-Chen/expense-track-n/blob/main/public/images/%E5%9C%96%E7%89%871.PNG)

### 本專案目的讓使用者記錄每個月的開銷記錄除了可以新增、修改、刪除，查詢上可以依照起始時間至最後時間查詢這段時間的消費記錄。

## HEROKU
- https://expenxe-tracker-t.herokuapp.com/users/login
- 可使用 root@example.com 登入，密碼 123456

## 啓動方式

- 將專案 clone 到本地端

-
https://github.com/Steavn-Chen/expense-track-n

- 進入到專案資料夾
```
- 安裝 npm
```
  npm install
```
- 啓動專案
```
  npm run dev
```
- 終端機出現  
  Expense-tracker web is running on http://localhost:3000
```
  出現 mongodb is connected. ，代表 mongodb 資料庫連接成功

- 在終端機輸入 npm run seed
```
  看到 insertMany categories ok. 和 insertMany records ok.  種子資料建立成功
```
## 開發環境
   
- Node.js -v14.15.1
- Express -4.17.3
- Express-Handlebars-5.3.4
- mongoose 5.12.15   

## 使用的套件

- handlebars-helpers: 0.10.0
- method-override: 3.0.0
- moment: 2.29.1
   
