https://elaineliu7598.github.io/hexschool/CSSTraining/week1/task/index.html

### jasonlu 助教給予回饋

1. 建議在 body 加上 line-height:1.5，讓元素能夠依字體大小自動計算行高，文字的行高就會是 文字大小 * body 設定的行高。例如 字體 24px ，行高就會是 24*1.5 = 36px。在 body 設定行高後文字都不需要設定行高。
    * (v)原本散落在各個需要的標籤上，改成統一放在 body

2. 建議把 學歷區塊移出 profile，獨立成一個區塊
    * (v)

3. 個人資料、學歷區塊的列表 建議使用 ul li 結構
    * (v)

4. 工作經驗區塊 li 內的文字 " 六角學院 視覺設計實習生 | 2019/07－2020/06 " 可以使用 h3 標籤，助教這邊提供 [範例圖](https://i.imgur.com/EqaKy2j.png)
    * (v)
  
  -------新增---------
1. .skills h2, .contact h2, .contact a 重複設定的文字顏色可以思考共用一個 class
    * (v)
2. .red 建議加上前綴 text-*，這樣在比較容易透過語意判斷是文字相關的設定
    * (v)
3. .profile h2, .education h2, .work h2 可以思考一個共用的名稱，例如: .title
    * (v)
