# 忘記密碼

![畫面示意](asset/forget-password.png)

## 頁面元件

| 項目 | 類型 | 操作 | 系統回應與處理邏輯 |
| --- | --- | --- | --- |
| 輸入 e-mail | Input | type | - |
| 送出 | Button | Click | 判斷是否有相符合 e-mail：<br>相符：Input下方顯示已送出重設密碼信件，在信箱點選連結開啟[重設密碼](Pages/Account/reset-password.md)頁面；不相符：回報錯誤訊息 |
| 返回登入畫面 | Link | Click | 跳轉至[登入](Pages/Account/login.md) |

<br>

## 操作流程與系統判斷

![一般管理員忘記密碼](asset/forget-pw-flow.jpg)

![高級管理員忘記密碼](asset/forget-hp-pw-flow.jpg)

