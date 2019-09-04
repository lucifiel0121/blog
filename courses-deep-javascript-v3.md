# deep-javascript-v3


### introduction

 ![](https://i.imgur.com/QvH1mcU.png)

很多人寫 code 是從其他程式經驗來的，所以這邊很容易可以回答 ++ 運算規則

![](https://i.imgur.com/cCedULL.png)

然後發現 y 不如預期時，抱怨 js 是爛語言，但以前寫 java or c or c++ 都覺得是自己沒看好文件/了解不夠深入，只有寫 js 的時候會怪 js 設計很爛。


js 的 authority 不是 V8 是 specification
所以有問題先查 specification 看是否符合預期
1. do not match : bug :(
2. match : different sort of a bug
  -> bug inside of your brain which is `incorrect thinking`. (邏輯錯誤)

---
### understanding your code
 - ++ 運算子 spec
![](https://i.imgur.com/Q5cC1lf.png)


>If we wanna understand what the javascript is doing to predict it and avoid problems. 
>The only way to do that is to understand what it's gonna do.

大抵上聊 `JavaScript開發人員並不真正知道程式碼的工作原理，但是它可以運行 ( JavaScript developers, isn't it true that we don't really know why the code's working, it just seems to be working right now)`
 
這個部分有點像 保哥很久以前寫過的文章 [我要成為前端工程師！給 JavaScript 新手的建議與學習資源整理](https://blog.miniasp.com/post/2016/02/02/JavaScript-novice-advice-and-learning-resources)

很多寫 js 的人都是「腦補」寫 code，從來沒有理解為什麼 code 可以執行，所以一堆奇怪的bug ( 註:對新手而言，因為 js 隨便寫都可以 run ，比較少會出現其他語言理解有錯，不能編譯死給你看的狀況，所以因此出現神奇 bug 也很常見 )
