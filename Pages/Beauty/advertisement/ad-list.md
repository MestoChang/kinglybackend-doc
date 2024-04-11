# 廣告專案列表
> - 停用廣告專案
> - 搜尋廣告名稱
> - 廣告專案列表(名稱、縮圖、狀態、日期區間)

<br>

![畫面示意](asset/advert-case-manage.png)



##　頁面元件

### 欄位說明
| 項目 | 類型 | 操作 | 系統回應與處理邏輯 |
| --- | --- | --- | --- |
| 狀態篩選 | Select | select | 篩選不同的廣告狀態 |
| 停用 | Button | Click | 按下後停用該廣告專案，不可回復 |
| 搜索 | Input | Type | 搜索廣告專案名稱 |
| 新增廣告 | Button | Click | 開啟 [新增廣告](Pages/Beauty/advertisement/add-ad.md) |


### 廣告狀態說明
| 狀態 | 說明 | 可編輯名稱 | 可修改日期 | 可修改連結 | 可置換圖片 |
| --- | --- | --- | --- | --- | --- |
| 正常 | 正在前端顯示中 | V | X | V | V |
| 失效 | 過期或者被停用，不可恢復為正常 | X | X | X | X |
| 排程 | 已上傳檔案但日期未到 | V | V | V | V |


<br>

## 操作流程與系統判斷

### 廣告專案管理

![廣告專案管理](asset/advert-manage-flow.jpg)


### 新增廣告專案

![新增廣告專案](asset/add-advert-flow.jpg)


### 停用廣告專案

![停用廣告專案流程](asset/suspend-advert-flow.jpg)

