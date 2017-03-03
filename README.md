## 2017-03-02 Thur
* `DONE`: 页面自适应调整
* `Get`: 
  1. 怎么查看本机电脑ip地址？
  ```bash
  "cmd" 中输入 "ipconfig"
  ```

  2. 怎么在手机中查看制作的网页效果？
  ```bash
  首先，在 "package.json" 中配置 "dev:"，加上 "--host 0.0.0.0"

  然后在手机浏览器中输入网址 "ip地址:8080"，即可查看网页效果。
  ```
* `TO DO`: 判断是iphone还是android，来显示相应的下载按钮。


## 2017-03-03 Fri
* `DONE`:
	1. 判断是iphone还是android，来显示相应的下载按钮。
	2. 添加二维码。
* `Get`: 

  [代码参考](http://www.cnblogs.com/sese/p/5629404.html)

  #### 运用
  ```javascript
	var ios=document.getElementById('ios')
	var and=document.getElementById('and')
	if (/(iPhone|iPad|iPod|iOS)/i.test(navigator.userAgent)) {  //判断iPhone|iPad|iPod|iOS
		//alert(navigator.userAgent);  
		ios.style.display ='block';
	} else if (/(Android)/i.test(navigator.userAgent)) {  //判断Android
		//alert(navigator.userAgent); 
		and.style.display ='block';
	} else {  //pc
		ios.style.display ='block';
		and.style.display ='block';
	};
  ```

  `navigator.userAgent`[定义和用法](http://www.w3school.com.cn/jsref/prop_nav_useragent.asp)<br>
  userAgent 属性是一个只读的字符串，声明了浏览器用于 HTTP 请求的用户代理头的值。一般来讲，它是在 navigator.appCodeName 的值之后加上斜线和 navigator.appVersion 的值构成的。
* `TO DO`: 深入学习javascript。[学习资源1_W3Cschool](http://www.w3cschool.cn/javascript/)[学习资源2_W3School](http://www.w3school.com.cn/b.asp)

