# speech
用jQuery写的扩展插件，主要是用来语音播报。

接口调用百度翻译的接口，所以存在url参数长度问题。百度接口本身也不允许长文本调用，只能短文本调用。

调用示例：
<pre>
	$('#Result').speech({
		"speech": true,
		"speed": 1,
		"bg": "./images/speech.png"
	});
</pre>


