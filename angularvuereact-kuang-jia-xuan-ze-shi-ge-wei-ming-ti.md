# Angular、Vue、React 框架選擇是個偽命題

常會有剛投入前端的朋友問我：  
友人A：「洧杰，你覺得該不該學 XX 框架？」  
我：「你說最近剛出來的那個啊，那你知道他是做什麼的嗎？」  
友人A：「不知道欸...只是最近聽很多人推，感覺不學以後會找不到工作」  
我：「......」

也常被問到相同性質的框架來比較，尤其是 Angular、Vue、React 的提問率最高，但真的問他說你自己有研究他們的用途嗎？竟然都一問三不知，真的會讓我白眼翻到後腦杓去，這裡就講解一些身為前端框架正確的應對觀念。

## 學技術是要來解決問題的

學任何技術時，先想清楚學了以後要拿來幹嘛？這目標越具體越好，例如我說 HTML、CSS 就是要自己實作一個個人履歷網站，我學後端跟資料庫的目標是要用他來實作一個留言板、部落格、電子商務。學 jQuery 是為了能夠設計動畫效果，該如何載入別人寫好的第三方插件。學 Gulp 是為了讓自己的前端任務流能夠更加靈活。**要切記，不要為潮而學**，**要為解決實作上的目標而學。**你敢面試的時候跟面試官說因為他很潮所以才學嗎？當然是要講你學這個技術是為了要實踐某個功能，才不會讓人覺得你是來亂的。

在投入一個技術前，先找個具體的目標跟理由說服自己，再去花時間投入，心理才比較踏實。

## 先找成熟框架，站在前人的經驗上加速學習

例如你想瞭解 SPA \(Single Page Application\) 觀念，假使找一個很新的框架，你搜尋問題完全沒有人曾經踩過地雷，學一個觀念要卡非常久才有辦法進行到一步，學習成效絕對大打折扣。

那成熟框架有什麼特點呢？不是 GitHub 上星星比較多，更不是你周遭朋友都說他很夯。而是你在搜尋該框架的時候有很多資源可以參考。例如打個 XX.js 在 YouTube 上就有很多系列教學影片，書城也出了很多技術書籍，在你遇到各種奇怪地雷時，關鍵字搜尋 console 裡面的錯誤就有一把抓的苦主幫你寫好解決方式，StackOverflow、GitHub 上有各種範例讓你參考。

使用成熟框架的好處就是能夠站在前人的踩雷經驗上，快速熟悉在建置一個 SPA 網站所需要的觀念，以目前 2017 年來說，你學 Angular、Vue、React 都可以，因為都是業界挑選 SPA 框架的三大首選，每個都已經非常成熟。

## 如何評估框架的汰換

看到一個新框架時，我會思考以下問題：

1. 已經會一個類似功能的框架
2. 已經會了，它跟新框架優劣差在哪？
3. 它是否能解決目前開發上時常困擾自己的問題？

我們再以 SPA 為例，我自己是先從 NG1 開始，再來投入 Vue.js，我 NG1 用了很長一段時間，中間雖然也出了不少框架，但功能都是大同小異，沒有太突出的功能，而最後會讓我換新的 SPA 框架的主要原因是在於 Virtual DOM 能夠大幅提昇效能，實際的 DOM 操作很耗效能的，更別說當資料量一大時更是讓我非常頭痛，必須東刪西壓縮才有辦法滿足客戶的要求。以致於那時我才決定使用有支援 Virtual DOM 的框架，以滿足我當下開發時所遇到的困難。

## 在公司裡可以使用 SPA 框架嗎？

前端只有你一位嗎？如果是倒也沒關係，在工作時程沒那麼緊的狀況下嘗試用新框架很 ok，但如果是有一個前端團隊，甚至有技術主管呢？那你就必須要掌握到有一定程度的熟悉，或者是寫一些 Side Project 提升經驗。當同事或主管問你為什麼要汰換框架時，你如果有足夠的自信說服他們，不論是開發效率、程式碼維護、框架彈性上都能說出贏過你們目前用的框架才會有機會。假使你自己都不熟也沒把握，想推動新框架難如登天。

當你是新手在找工作時，要特別去看公司工作內容與他們有用到的框架，如果你到一間 JavaScript 只會用 jQuery 接一些動畫，後端也不是用 API 協作，工作內容反而比較常投入在 Web Layout 上，那你就根本沒有用 SPA 的機會。想要透過公司加強自己能力時，務必將公司所投入到的技術問清楚，不要不好意思，才能幫助你能否在公司有效提升前端能力。

## 先學深，再學精

我常遇到很多人在初期挑選框架就花了很多時間，彷彿是人生中最重大的決定，一直很擔心選了但之後框架不流行會後悔萬分。只能規勸你**醒醒吧，沒有任何框架可以讓你吃一輩子的**，你需要的是盡快投入一個新框架，並把它摸到很深，有實際做出幾個 Side Project，將這些開發經驗累積起來做為你未來的籌碼。最要不得的是每個都只摸皮毛就放棄，你勢必會遇到很多問題，但解決未知的問題不就是工程師所需要必備的技能之一嗎？就如同佛法上常會講的：「面對它、接受它、處理它、放下它」，重要的是不要逃避它。

雖然前端框架會因時代趨勢而式微，但我唯一能向你保證的是你所學的任何東西絕對不會是白費的，像是我學 jQuery 讓我在操控 DOM 元素上變得更加熟悉，學 NG1 讓我掌握到 two-way binding、MVC 的抽象觀念，學 D3 讓我對 SVG 底層更加透徹，學 WebVR 使我對 WebGL、three.js 有更深入的瞭解，在不停地學框架讓我更加瞭解底層，也幫助我掌握一個框架速度也越來越快了。

最後還是用個老話來結尾，唯有不停升級自己的腦袋思維才是王道。

