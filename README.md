# public-style-pc
pc版本的公共样式

@charset "utf-8";
/* 
 * CSS Document
 * Author
 * Tips id使用小驼峰，样式类使用“ - ”
 * Url
*/
*{
	margin: 0;
	padding: 0;
}
body{
	font-size: 14px;
	line-height: 1;
	font-family: "微软雅黑", "microsoft yahei", "PingFang SC", Arial , sans-serif;
	background: #f3f3f3;
	text-align: left;
}
a{
	text-decoration: none;
}
a:link{
	color: #0099ff;
	text-decoration: none;
}
a:visited{
	color: #0099ff;
	text-decoration: none;
}
a:hover{
	color: #0099ff;
	text-decoration: none;
	transition: .3s all ease;
	-webkit-transition: .3s all ease;
	-moz-transition: .3s all ease;
	-ms-transition: .3s all ease;
	-o-transition: .3s all ease;
}
a:active{
	color: #0099ff;
	text-decoration: none;
}
ul,li,dl,dt,dd{
	list-style-type: none;
}
h1,h2,h3,h4,h5,h6{
	font-weight: normal;
}
table{
	border-collapse: collapse;
}
input{
	outline: none;
	border: 1px solid #ccc;
}
.clearfix:after{
	content: " ";
	display: block;
	clear: both;
	height: 0;
}
.clearfix{
	zoom: 1;
}
.fl{
	float: left;
}
.fr{
	float: right;
}