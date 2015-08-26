*{
	margin: 0px;
	padding: 0px;
	text-decoration:none;
	list-style: none;
	font-size: 12px;
	font-family: Arial;
}
li{
	list-style: none;
}
a{
	color: inherit;
	text-decoration: none;
}
a:hover{
	color: red;
}
#top{
	width: 100%;
	height: 30px;
	background: #F7F7F7;
	border-bottom: 1px solid #EEE;
	position: relative;
}
#top_main{
	width:1210px;
	height: 30px;
	margin: 0 auto;
}
#top_main .topu{
	float: left;
}
#top_main .topu li{
	width: 82px;
	height: 30px;
	line-height: 30px;
	display: block;
	font-size: 12px;
	color: #666;
	float: left; 
}
#top_main .topu li a{
	padding-left: 20px;
}
a:hover{
	color: #e4393c;
	text-decoration: underline;
}
#top_main .topu li .xing{
	width: 13px;
	height: 13px;
	background: url(../images/xing.png) no-repeat;
	position: absolute;
	top: 8px;
}
#top #top_main .topu li .erwei{
	width: 13px;
	height: 13px;
	position: absolute;
	top: 9px;
	background: url(../images/erwei.png) no-repeat;
}

.didian{
	width: 20px;
	height: 20px;
	background: url(../images/didian.png) no-repeat 0 -40px;
	top: 4px;
	position: absolute;
}
#top #top_main .topu .erweitu{
	width: 116px;
	height: 120px;
	background: url(../images/erwei.png) no-repeat 0px -40px;
	border: 1px solid #CCC;
	position: absolute;
	top:30px;
	display: none;
	z-index: 22;
}
#top #top_main .topu.aa{
	display: block;
}

/*鼠标移入显示二维码*/
#top #top_main .topu .aa:hover .erweitu{
	display: block;
}
#top #top_main #hello{
	width: 230px;
	height: 30px;
	margin-left: 180px;
	float: left;
}
#top #top_main #hello span{
	height: 30px;
	line-height: 30px;
	font-size: 12px;
	color: #666;
}
#top #top_main #hello a{
	color: #666;
}
#top #top_main #hello a:hover{
	color: #E4393c;
	text-decoration: underline;
}







#top #top_main .topright{
	height: 30px;
	float: left;
	position: relative;
}
#top #top_main .topright ul li{
	float: left;
	padding-right:10px;
	height: 30px; 
}
#top #top_main .topright ul li>a{
	display: block;
	font-size: 12px;
	float: left;
	padding-left: 8px;
	line-height: 20px;
	color: #666;
	margin-top: 5px;
}
#top #top_main .topright ul li .cun{
	margin-top: 8px;
	float: left;
	border-left: 1px solid #CCC;
	height: 14px;
}
#top #top_main .topright ul li .cun a{
	font-size: 12px;
	line-height: 14px;
	color: #666;
	float: left;
	margin-left: 5px;
}
#top #top_main .topright ul li .cun a:hover{
	color: #E4393C;
	text-decoration: underline;
}
#top #top_main .topright ul li .vip{
	width: 24px;
	height: 11px;
	float: left;
	background:url(../images/vip.png) no-repeat 0px 0px;
	position: relative;
	top: 1px;
	margin-left: 5px;
}
#top #top_main .topright ul li .bjd{
	width: 21px;
	height: 11px;
	float: left;
	background: url(../images/bjd.jpg)no-repeat 0px 0px;
	position: relative;
	top: 1px;
	margin-left: 5px;
}
#top #top_main .topright ul li .phonetu{
	width: 13px;
	height: 22px;
	background: url(../images/all.png) no-repeat -128px -360px;
	position: absolute;
	top: 2px;
	line-height: 265px;
}
#top #top_main .topright ul li .downjian11{
	width: 10px;
	height: 8px;
	background: url(../images/all.png) no-repeat -94px -53px;
	position: absolute;
	top: 10px;
	left: 338px;
}

#top #top_main .topright ul li .downjian{
	width: 10px;
	height: 8px;
	background: url(../images/all.png)no-repeat -94px -53px;
	position: relative;
	top: -18px;
	left: 78px;
}
#top #top_main .topright ul li .cun a.dong{
	height: 11px;
	margin-left: 25px;
	padding-right: 10px;
}
#top #top_main .topright ul li .erwei{
	width: 250px;
	height: 294px;
	border: 1px solid #CCC;
	background: white;
	float: left;
	position: relative;
	top: 8px;
	z-index: 33;
	display: none;
}
#top #top_main .topright ul li.hidetu:hover .erwei{
	display: block;
}
#top #top_main .topright ul li .erwei .shoudan{
	width: 220px;
	height: 65px;
	background: url(../images/1.png)no-repeat;
	margin-top: 20px;
	margin-left: 10px;
}
#top #top_main .topright ul li .erwei .jd{
	width: 76px;
	height: 76px;
	background: url(../images/3.jpg)no-repeat;
	margin-left: 30px;
	margin-top: -20px;
}
#top #top_main .topright ul li .erwei .span1{
	width: 100px;
	font-size: 12px;
	font-weight: 700;
	color: #e4393c;
	display:block;
	float: left;
	margin-top: -85px;
	margin-left: 123px;
}
#top #top_main .topright ul li .erwei .apple{
	width: 95px;
	height: 28px;
	background: url(../images/all.png)no-repeat 0px -360px;
	margin-left: 123px;
	margin-top: -60px;
}
#top #top_main .topright ul li .erwei .andr{
	width: 96px;
	height: 28px;
	background: url(../images/all.png)no-repeat 0px -399px;
	margin-left: 123px;
	margin-top: 10px;
}
#top #top_main .topright ul li .erwei .ewtu{
	width: 76px;
	height: 76px;
	background: url(../images/2.png)no-repeat;
	margin-left: 30px;
	margin-top: 50px;
}
#top #top_main .topright ul li.kefu{
	width: 83px;
	height: 30px;
}

/*border: 1px solid orange;*/
#top #top_main .topright ul li.kefu span{
	padding-left: 10px;
	color: #666;
}
#top #top_main .topright ul li .downjian1{
	width: 10px;
	height: 8px;
	background: url(../images/all.png)no-repeat-94px -53px;
	position: relative;
	top: -10px;
	left: 65px;
}
#top #top_main .topright ul li .kefuhide{
	width: 78px;
	height: 135px;
	margin-left: 5px;
	margin-top: -2px;
	border: 1px solid #F7F7F7;
	position: relative;
	z-index: 999;
}
#top #top_main .topright ul li .kefuhide ul li{
	width: 73px;
	height: 22px;
}
#top #top_main .topright ul li .a1{
	width: 83px;
	height: 20px;
	overflow: hidden;
	position: relative;
	z-index: 999;
}
#top #top_main .topright ul li.kefu:hover .a1{
	overflow: visible;
}
#top #top_main .topright ul li.kefu:hover .kefuhide{
	border: 1px solid #CCC;
	background: white;
}
#top #top_main .topright ul li.wangzhan{
	width: 73px;
	height: 30px;
}
#top #top_main .topright ul li.wangzhan span{
	color: #666;
	padding-left: 10px;
}
#top #top_main .topright ul li.wangzhan .wangzhanhide{
	width: 250px;
	height: 206px;
	border: 1px solid #CCC;
	float: left;
	padding-left: inherit;
	top: 8px;
	left: -168px;
	display: none;
	z-index: 22;
}
#top #top_main .topright ul li.wangzhan:hover .wangzhanhide{
	display: block;
}
#top #top_main .topright ul li.wangzhan .tese{
	width: 250px;
	height: 28px;
}
#top #top_main .topright ul li.wangzhan .tese span{
	font-weight: 700;
	line-height: 28px;
}
#top #top_main .topright ul li.wangzhan .tesemain{
	width: 240px;
	height:66px;
	margin-left: 5px;
	border-bottom: 1px solid #EEE;
	margin-bottom: 5px; 
}

#top #top_main .topright ul li.wangzhan a{
	font-weight: 400;
	color: #666;
	padding-left: 6px;
	line-height: 1.7em;
}
#top #top_main .topright ul li.wangzhan a:hover{
	color: #E4393C;
	text-decoration: underline;
}
#top #top_main .topright ul li.wangzhan .tesemain1{
	width: 240px;
	height: 22px;
	margin-left: 5px;
	border-bottom: 1px solid #eee;
}
#top #top_main .topright ul li.wangzhan .tesemain2{
	width: 240px;
	height: 22px;
	margin-left: 5px;
}
