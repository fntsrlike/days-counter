## 簡介
這是我用CoffeeScript寫的ECMAScript小玩具。
主要用來計算特定日期至今日共經歷幾天，並輸出到網頁上。

## 緣由
主要是我和我戀人每天都會在噗浪上發私噗，並且使用[yddd]作為開頭，
但是要是偶爾有漏幾天沒發，通常就要需要重新算日期，
身為工程師男友的我，心靈一動，就了乾脆來寫一個JS書籤小工具，幫忙解決這個問題，
於是就有了這個程式碼片段的產生。

## 需求
目前是用 jQuery 協助輸出，且本人的噗浪已利用小工具自動戴入 jQuery，
若是沒有戴入 jQuery ，程式可是會沒反應的哦。

## 修改
### 日期
可以將 begin 和 target 的值修改成你要的兩個日期，
我是將 begin 設成交往第一天， target 設成今日，就成了我要的小工具，

當然你也可以將begin設成今天，target設成目標日，就變成倒數計時器囉。

### 輸出
將 Selector 改成你要輸出的表單對象，
並修改 .val() 裡面的值，改成你要的輸出格式。

當然，若是你的對象不是表單，而是一般標籤，記得將.val()修改成.html()，
這些jQuery的使用方法，就不在這裡多說了。

## 使用
### Chrome
新增一個書籤，然後在書籤的網址表單新增 `javascript: `，然後在後面貼上編譯成JavaScript的程式碼。
如此一來，往後按該書籤即可執行本程式的功能囉。