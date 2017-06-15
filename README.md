# speech
用jQuery写的扩展插件，主要是用来语音播报。

接口调用百度翻译的接口，所以存在url参数长度问题。百度接口本身也不允许长文本调用，只能短文本调用。

初始参数详解：
"speech": true, //通过点击链接播报，还是直接播报
"lang": "zh", //语言			
"speed": 3, //语速	
"http":false,//默认true 启用https		
"sWidth": 16, //链接按钮的宽度			
"sHeight": 13, //链接按钮的高度			
"bg": "./image/speech.png", //链接按钮的背景图片			
"content": "这是一段测试内容" //直接播报内容

调用示例：
<pre>
	$('#Result').speech({
		"speech": true,
		"speed": 1,
		"bg": "./images/speech.png"
	});
</pre>


<a href="http://www.tuterm.com/jquery-speech/" target="_blank">演示</a>


