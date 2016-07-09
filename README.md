# haoEditor v1.0 轻量级富文本，配置方便，使用简单
===
## 1.说明
```
基于jQuery，兼容IE7+、Chrome、Firefox等主流浏览器
```
## 2.使用
```
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<title>haoEditor</title>
	<link rel="stylesheet" type="text/css" href="css/haoEditor.css">
	<script src="jquery.min.js" type="text/javascript"></script>
	<script src="haoEditor.js" type="text/javascript"></script>
</head>
<body>
	<textarea name="textarea" id="test-hao"></textarea>
	<!-- <div id="test-hao"></div> -->
</body>
<script type="text/javascript">
	$(function(){
		$("#test-hao").haoEditor();
	})
</script>
</html> 
```