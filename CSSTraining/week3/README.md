### 眼鏡形象網站
PC + RWD 已完成：layout、store、faq
https://elaineliu7598.github.io/hexschool/CSSTraining/week3/store.html

### 依助教回饋調整內容
* 門市據點
    1. 以「格線系統概念」取代「用 class(card-2, card-3, card-4)處理間距問題」
    2. .store-detail 從 `<p>` 改成 `<a>`
    3. 寫死 .photo 高度並用 `object-fit: cover` 讓圖片自適應呈現，以解決圖片原檔大小不一的問題。另一方法是將圖片裁成同樣大小。
    4. icon 建議使用 fontawesome 而非 `img`（不易處理對齊），若用 `img` 可優先使用 `margin-top` 處理間距，使 icon 對齊。--> 此份作業暫維持原先做法，不調整

* 程式碼建議
    1. css reset.css 檔名改成 reset.css，避免出現錯誤而讀取不到檔案
    2. 原「.m-inline」調整名稱，並加入斷點設計，放在 layout.css 作為通用樣式使用

* 表頭表尾
    1. 刪除「.divider」區塊，將 border-bottom 設定在 .footer-top
