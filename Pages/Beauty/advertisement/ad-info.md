# 廣告專案內容
> - 調整顯示的日期區間
> - 設定圖片關鍵字
> - 上傳/更換/刪除圖片不同尺寸
> - 設定/連結
>


<br>

![畫面示意](asset/advert-case.png)


## 頁面元件

### 欄位限制
| 項目 | 類型 | 操作 | 系統回應與處理邏輯 |
| --- | --- | --- | --- |
| 圖片標題 | Input | Type | alt/title 屬性使用 |
| 網址連結 | Input | Type | --- |
| 關鍵字 | Input | Type |至少需要選擇一個類別。<br>僅能選擇資料庫已有的關鍵字。<br>不得重複選擇關鍵字。<br>在input auto complete 設定關聯資料庫。|
| 開始日期 | Input | Type | 不可早於當前時間(暫定) |
| 結束日期 | Input | Type | 不可早於開始日期 |
| 優先顯示 | Checkbox | Choose | 輪播時優先顯示 |
| 上團圖片 | File | upload | 須符合欄位限制的尺寸規範 |


