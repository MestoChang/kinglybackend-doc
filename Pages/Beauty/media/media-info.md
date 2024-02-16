# 媒體內容
> - 置換上傳圖片
> - 編輯關鍵字
> - 編輯媒體描述
> - 變更媒體狀態

![畫面示意](asset/media-info.png)

## 頁面元件

| 項目 | 類型 | 操作 | 系統回應與處理邏輯 |
| --- | --- | --- | --- |
| 更新 | Button | Click | 檢查上傳圖片／各欄位是否符合規範，不符回傳錯誤提示 |
| 取消 | Button | Click | - |
| 媒體名稱 | Input | - | 不可更改 |
| 媒體狀態 | Select | choose | 正常 or 停用 <br>設定為停用前端網站會顯示死圖 |
| 選擇檔案 | file | upload | - |
| 媒體描述 | Textarea | Type | - |
| 關鍵字 | Input | Type | 至少需選擇一個關鍵字 |


## 操作流程

### 編輯媒體
![編輯媒體資訊](asset/edit-media-info-flow.png)

### 變更狀態
參考 [媒體狀態變更](Pages/Beauty/media/media-list.md#媒體狀態變更)


