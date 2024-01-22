# 忘記密碼
> 使用者點選忘記密碼後導向至此頁面。

## 操作流程
![忘記密碼流程](./asset/forgetpw-flow.png)

## 頁面功能
![忘記密碼畫面示意](./asset/forgetpw.png)

|頁面元件|類別|操作|系統回應與詳細處理邏輯|
|---|---|---|---|
|Email|Input|輸入|1. 預設狀態:Enable <br>2. 必填|
|送出|Button|Click|後端接收到重設密碼的 request，發送 email 驗證|



