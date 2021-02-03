# hex-JSLC-w5
2020 夏季．六角 JS 作品實戰班｜第五週．表單驗證  
[DEMO](https://yuu-chien.github.io/hex-JSLC-w5/cart.html)

<br>

## Info
本週重點：  
* 使用套件完成表單驗證功能
* 串接前台 API 完成購物車功能

提交等級：LV1.2，完成表單驗證功能與購物車列表  
<br>
### User Story
* 串接 API 並可以呈現產品列表、加入購物車、購物車列表功能
* 表單送出前進行表單驗證（必要完成），驗證內容包含：
    * 姓名：必填
    * Email：須符合格式
    * 電話：必填，超過 8 碼，input type 為 tel
    * 地址：必填
    * 付款方式：WebATM、ATM、Barcode、Credit、ApplePay、GooglePay
    * 留言：非必填

<br>

## Content 
* 使用 Vue.js 搭配 Bootstrap
* vee-validate

<br>

## 助教 Feedback
作業練習的不錯，購物車版型自行設計，很棒喔~
- VeeValidate 元件有正確註冊了，運作上沒有問題。
- 有看同學跟者老師的影片新增了 filter 功能，非常不錯呢。

助教這邊提醒一下:  
手機號碼 rules 有看同學嘗試使用 is:09 這個功能，  
不過 VeeValidate 官方文件有提到， is 使用的是嚴格判斷式  
必須值和設定的完全一致才會通過，is 的 TIP 框框，有相關說明  
如果是想要部分字串就能通行，可以參考 [Rules Object Expression](https://logaretm.github.io/vee-validate/advanced/rules-object-expression.html#defining-rules) 這部分的文件  

另外鄉鎮選單，一般來說我們會使用雙層的 select 去製作  
這邊附上相關範例:原生 [JS 雙層選單](https://codepen.io/Isshin/pen/VwvNREW)、[Vue 雙層選單](https://codepen.io/g901612002/pen/ZxpvLZ)  

恭喜你完成這個章節，也期待你後續的作業哩 :D  
