
<html>
<head>
<style type="text/css">
	div#div1{ 
	position:fixed; 
	top:0; 
	left:0; 
	bottom:0; 
	right:0; 
	z-index:-1; 
	} 
	
	div#div1 > img { 
	height:100%; 
	width:100%; 
	border:0; 
	}
	 
	div#box {
	height: 280px;
	width: 200px;
	margin-top: -200px;
	margin-left: -200px;
	position: absolute;
	left: 50%;
	top: 50%;
	background-color:#ccc;
	}
	.buttons {
	TEXT-ALIGN: center; PADDING-BOTTOM: 20px; PADDING-LEFT: 0px; PADDING-RIGHT: 0px; PADDING-TOP: 20px
	}
	
</style>


 
    <meta charset="UTF-8">
    <title>Basic PasswordBox - jQuery EasyUI Demo</title>
    <link rel="stylesheet" type="text/css" href="jeasyui/themes/default/easyui.css">
    <link rel="stylesheet" type="text/css" href="jeasyui/themes/icon.css">
    <link rel="stylesheet" type="text/css" href="jeasyui/demo.css">
    <script type="text/javascript" src="jeasyui/jquery.min.js"></script>
    <script type="text/javascript" src="jeasyui/jquery.easyui.min.js"></script>
</head>
<body>

	<div>
	<form method="post" action="login">
    <div id="div1"><img src="2786001_152906119000_2.jpg" /></div> 
    
    <div id="box" class="easyui-panel" style="width: 419px;height: 384px;padding:60px 70px;opacity:0.8;">
    	<h2 style="color:green">用户登录-SMS信息管理系统</h2>
        <div style="margin-bottom:20px">
            <input class="easyui-textbox" prompt="用戶名" name="users.userName" iconWidth="28" style="width:80%;height:34px;padding:10px;"><a href="getDept">注册账号</a>
        </div>
        
        <div style="margin-bottom:20px">
            <input class="easyui-passwordbox" prompt="登录密码" name="users.userPwd" iconWidth="28" style="width:80%;height:34px;padding:10px"><a href="wangjiPwd.jsp">找回密码</a>
        </div>
        
       	<div class="buttons"> 
       		<input type="submit" value="登录" style="height: 33px; width: 78px" > 
       		<input type="reset" value="重置" style="height: 33px; width: 78px" > 
       	</div>
	</div>
	
    
</form>
    

