# 学习git.md 怎么书写  

## 目录
* [大标题](#大标题)
* [中标题](#中标题)
* [换行]（#换行）





大标题  
======
大标题的用法就是在一行文本下面打上等号（=）

中标题
----------
标题就是在标题下面加上（-） 个数不限对于0个   

换行  
----------

		 注意换行，因为它不支持换行，所以呢需要直接打<br/> 或者两个空格 加上回车！！    
 
 单行文本和多行文本 
 ----------
 		 就是输入两个tab键就可以，但是我输入的时候就是不行（输进去的字都没了），必须在输入两个tab键的时候在加上一个空格才行。
		 多行文本，其实单行文本直接换行就在多行文本上，直接就能用。退出多行文本，我是 空格+回车单后 shift+tab两下 
		 然后呢就回到了正常编辑的环境  
 
 高亮代码
 ---------
 		 高亮代码可以在你想高亮的代码前面加上``   这个东西就行 但是这个不是冒号 而是tab键上面的那个键  
 使用 `高亮` 就可以完成
 
 		 但是在文本框里我没有高亮成功，后面可以继续试试
 
 添加链接
 ---------------
 		 就是给[百度](http://www.baidu.com "百度的网站")就可以（） 后面还可以加这鼠标悬停文字 但是我也没有成功！！
[baidu的链接](http://www.baidu.com)
 
 列表原点图
 --------------
 		 列表原点图 就是把原点换成*好就行 原点要空一个 要不然他不认识列表
		 如果想加入多层次的列表 只需要在列表前面多加一个tab 就可以
 
		 
* 列表一   
	* 列表二  
		* 列表三
* 列表四
 
 ---------------------
 
 缩进
 -----------
 有时候列表不能完全表达想要的意思 可以使用>
 
 >hello
 >>my 
 >>>name
 >>>>is
 >>>>>marain
 >>>>>>hehe
 ----------------
 
 添加图片
 --------
 		 只需要在[]()前面加上！ 这样就可以解析成图片 [里面可以写一些标示] 和链接 一样 只需要在后面加上悬停需要加的文字就好
		 https://github.com/ 你的用户名 / 你的项目名 / raw / 分支名 / 存放图片的文件夹 / 该文件夹下的图片  如果需要加git上的图片 可以这样（没有测试）
		 
 ![百度图片](http://www.baidu.com/img/bdlogo.gif "百度logo") 

 图片上添加外链
 -----------
		  保持上下两行的标示是一行的 就可以 做到图片的链接    （暂时没有验证）
[![baidu]](http://baidu.com)  
[baidu]:http://www.baidu.com/img/bdlogo.gif "百度Logo"  


代码怎么添加
-------------  
这个比较重要一点   
```javascript
function(){
	console.log('这里面就会展示代码片段');
}
```  

这里的代码 只需要在代码的上方和下方输出三个（\`）
还是在tab上面的那个键 然后在上面的三个点后面写上你书写的代码是什么语言就可以。
 
 
 
 
 
 
 
