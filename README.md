# fuction 說明文件

## fakeAjax()
### 用途：
* 製作出對應元素的 button 使多數 html元素或區塊 可進行**互相做切換**.

### 實際案例：
* 使用者需要在 **登入的區塊** 直接切換成 **註冊使用者的區塊**.

## fakeSelect()
### 用途：
* 將 **Select** 元素轉換為 **ul li** 的架構.

### 說明:
* 原先 **select** 元素裡的 **option** 元素 是無法直接吃到 CSS 許多的樣式屬性,如 **padding**,**margin** 等等,會使前台開發上多了許多的限制,透過此 function 轉換成一般的 **ul li** 好方便進行開發.

## scrollAddclass()
### 用途：
* 針對 **scroll事件**,來對物件加入對應的Class,來達到此'物件'在畫面滾動時鎖觸發動畫的過渡效果.

### 說明：
* 需要先定義 **過渡前** 與 **過渡後** 的Class,把 **過渡前**,**過渡後** 的前台製作完成後,直接對想要的物件加入 **過渡前** 的樣式,function會自動判斷,當此物件出現於畫片中時加入 **過渡後** 的 class ,來達到執行動畫的效果.

## imageCover()
### 用途：
* 定對應html物件裡所有的 **img元素** 轉為 **background-cover**.

### 說明：
* 將 **img元素** 轉成 **background** 的同時也可以同時擁有'img的高'
