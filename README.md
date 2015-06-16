# s14119120 筆記

至sites新增資料夾 (ex:bst) 拉到sublime      
在bst裡新增檔案index.html → 內容打html按Tab鍵      
改`<html lang="utf-8">`      
在`<body>`裡新增`<h1>`文字`</h1>`.`<p>`.`<h2>`.`<p>`.`<button>`.`<button>`.`<h3>`.`<p>`      
在`<head>`裡打link按Tab鍵 → 至bootstrap下載 → 把三個檔案(css.fonts.js)拉到bst裡 → 再至link這行後面改href="css/bootstrap.css"      
在`<body>`行上面,去bootstrap網站 → Getting strat → 右邊Basic template → 複製這兩行,貼上      
`<!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->`      
`<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>`      
下一行打`<script src="js/bootstrap.js"></script>`      

在`<body>`行下面,打`<div>`,`</div>`拉到中間打的下面        
．改為`<div class="container">` → 置中      
．改為`<div class="container-fluid">` → 佔滿頁面      
(皆要有`</div>`結尾      

`<div class="col-md-12">` 分欄位    
．xs>768px以下, sm>768~992px, md>992~1200px, lg>1200px以上 (size)      
`<img src="圖片網址" style="width:100%">`      
`<div class="row">` → 增加可讀性(可加可不加)      
加間隔 → 在分欄位後打col-md-offset-1 (左右各縮1)      
．(ex: class="cd-md-10 col-md-offset-1"      
後面再加class="cd-md-0 , 拉大就可正常      

`<div class="col-md-6 hidden-sm hidden-xs">` → 當...時隱藏      
．visible → 可見的      

`<div class="row text-center">` → 文字置中      
◎font-family 選字體之網頁      
改字體 → 先另開一個css(new file) 名字main.css 存檔      
打body{ 　 font-family: "字體"; }      
在index.html 的分欄位後打 features (接關聯      
`<div class="lead">` → 凸顯字      

◎Components Bootstrap 選擇圖示網頁      
圖示 → `<i class="glyphicon...."></i>`      
在`<head>`裡加入`<link...."css/main.css">`
