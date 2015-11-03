# html
<h4>IE10及以上版本已将条件注释特性移除</h4>
<pre>
如不想在非IE中看到某区域，可这样写：
<textarea>
<!--[if IE]>
<p>你在非IE中将看不到我的身影</p>
<![endif]-->
</textarea>

上述p代码块，将只在IE中可见。

————————————————————————————————————
大于或等于，示例代码：
<textarea>
<!--[if gte IE 6]>
<style>
.test{color:red;}
</style>
<![endif]-->
</textarea>
在上述代码中，只有IE6以上（含IE6），才能看到应用了test类的元素是红色文本。



小于，示例代码：
<textarea>
<!--[if lt IE 7]>
<style>
.test{color:red;}
</style>
<![endif]-->
</textarea>
在上述代码中，只有IE7以下，才能看到应用了test类的元素是红色文本。



小于或等于，示例代码：
<textarea>
<!--[if lte IE 7]>
<style>
.test{color:red;}
</style>
<![endif]-->
</textarea>
在上述代码中，只有IE7以下（含IE7），才能看到应用了test类的元素是红色文本。



非指定版本，示例代码：
<textarea>
<!--[if ! IE 7]>
<style>
.test{color:red;}
</style>
<![endif]-->
</textarea>
在上述代码中，除IE7以外的IE版本，都能看到应用了test类的元素是红色文本。

</pre>
