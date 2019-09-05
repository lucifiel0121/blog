# deep-javascript-v3 : introduction
###### tags: `deep-javascript` `learning` 


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



大抵上聊 `JavaScript開發人員並不真正知道程式碼的工作原理，但是它可以運行 ( JavaScript developers, isn't it true that we don't really know why the code's working, it just seems to be working right now)`

 >If we wanna understand what the javascript is doing to predict it and avoid problems. 
>The only way to do that is to understand what it's gonna do.
>如果要避免問題，唯一的辦法就是了解 javascript 在做甚麼。

這個部分有點像 保哥很久以前寫過的文章 [我要成為前端工程師！給 JavaScript 新手的建議與學習資源整理](https://blog.miniasp.com/post/2016/02/02/JavaScript-novice-advice-and-learning-resources)

很多寫 js 的人都是「腦補」寫 code，從來沒有理解為什麼 code 可以執行，所以一堆奇怪的bug ( 註:對新手而言，因為 js 隨便寫都可以 run ，比較少會出現其他語言理解有錯，不能編譯死給你看的狀況，所以因此出現神奇 bug 也很常見 )

 - ++ 運算子 spec
![](https://i.imgur.com/Q5cC1lf.png)

依照 spec 寫成 code =>
![](https://i.imgur.com/kq8DvFD.png)


![](https://i.imgur.com/MV98oAK.png)
如果在你腦補和真實code裡面發現分歧(divergence)，代表有 bug 要發生了!


---
### course-overview

三個核心 (pillars)

![](https://i.imgur.com/wM2U2gH.png)

- Types

沒有人喜歡 Types，尤其是像JavaScript這樣的動態類型語言。

甚至有些人 (比如  Doug Crockford) 直接告訴你說不要管、不要用型別，但這樣是不負責的。

你當然可以總是用 嚴格相等 (===) 來避免型別問題，但對型別不了解就是 bug 不知不覺產生的原因之一。

- Scope
Lexical scopes(語彙範疇)、closure、modular pattern (模組).


- Objects
這邊的 Objects Oriented 不是物件導向(class oriented)的那個 OOP，是指 `how JavaScript's objects system works`


此章節總結 :
你一定要「學」，但很多東西或許學會之後可以「不要用」

You absolutely should learn this system.
But you might not need some of it.
