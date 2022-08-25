<style>			
	/*黑幕CSS*/
	span.heimu a.external,span.heimu a.external:visited,span.heimu a.extiw,span.heimu a.extiw:visited {
		color: #252525
	}
	.heimu,.heimu a,a .heimu,.heimu a.new {
		background-color: #252525;
		color: #252525;
		text-shadow: none
	}
	body:not(.heimu_toggle_on) .heimu:hover,body:not(.heimu_toggle_on) .heimu:active,body:not(.heimu_toggle_on) .heimu.off {
		transition: color .13s linear;
		color: #ffffff
	}
	body:not(.heimu_toggle_on) .heimu:hover a,body:not(.heimu_toggle_on) a:hover .heimu,body:not(.heimu_toggle_on) .heimu.off a,body:not(.heimu_toggle_on) a:hover .heimu.off {
		transition: color .13s linear;
		color: #add8e6
	}
	body:not(.heimu_toggle_on) .heimu.off .new,body:not(.heimu_toggle_on) .heimu.off .new:hover,body:not(.heimu_toggle_on) .new:hover .heimu.off,body:not(.heimu_toggle_on) .heimu.off .new,body:not(.heimu_toggle_on) .heimu.off .new:hover,body:not(.heimu_toggle_on) .new:hover .heimu.off {
		transition: color .13s linear;
		color: #293e50
	}

	/*萌绿CSS*/	
	#nice {
		line-height: 1.6;
		letter-spacing: .034em;
		color: rgb(63, 63, 63);
		font-size: 16px;
		word-break:all;
	}
	#nice p {
		padding-top: 1em;
		color: rgb(74,74,74);
		line-height: 1.75em;
	}
	/* 一级标题 */
	#nice h1 {
		text-align:center;
		background-image:	url(http://img.xiaogangzai.cn/title_h1.png); 
		background-position: center top;
		background-repeat: no-repeat;
		background-size: 75px;
		line-height:95px;
		margin-top: 38px;
		margin-bottom: 10px;
	}
	/* 一级标题内容 */
	#nice h1 .content {
		font-size: 20px;
		color: #48b378;;
		border-bottom:2px solid #2e7950;
	}
	/* 一级标题修饰 请参考有实例的主题 */
	#nice h1:after {
	}
		 
	/* 二级标题 */
	#nice h2 {
		display:block;
		text-align:center;
		background-image:	url(http://img.xiaogangzai.cn/title.png); 
		background-position: center center;
		background-repeat: no-repeat;
		background-attachment: initial;
		background-origin: initial;
		background-clip: initial;
		background-size: 50px;
		margin-top: 1em;
		margin-bottom: 5px;
	}
	/*二级标题伪元素*/
	#nice h2:before {
	}
	/* 二级标题内容 */
	#nice h2 .content {
		text-align:center;
		display: inline-block;
		height: 38px;
		line-height: 42px;
		color: #48b378;
		background-position: left center;
		background-repeat: no-repeat;
		background-attachment: initial;
		background-origin: initial;
		background-clip: initial;
		background-size: 63px;
		margin-top: 38px;
		font-size:18px;
		margin-bottom: 10px;
	}
	/* 三级标题 */
	#nice h3:before {
		content: "";
		background-image:url(http://img.xiaogangzai.cn/title_h2.png);
		background-size:100% 100%;
		background-repeat:no-repeat;
		display: inline-block;
		width: 16px;
		height: 15px;
		line-height:15px;
		margin-bottom:-1px;
	}
	#nice h3 {
		margin-top:1.2em;
	}
	#nice h4 {
		margin-top: 30px;
	}
	/* 三级标题内容 */
	#nice h3 .content {
		font-size:17px;
		font-weight:bold;
		display:inline-block;
		margin-left:8px;
		color:#48b378;
	}
	/* 三级标题修饰 请参考有实例的主题 */
	#nice h3:after {
	}
	/* 列表内容 */
	#nice li {
	}
	/* 引用
	 * 左边缘颜色 border-left-color:black;
	 * 背景色 background:gray;
	 */
	#nice blockquote {
		padding: 15px 20px;
		line-height: 27px;
		background-color:#FBF9FD;
		border-left:3px solid #35b378;
		display:block;
	}
	/* 引用文字 */
	#nice blockquote p {
		padding: 0px;
		font-size:15px;
		color:rgb(89,89,89);
	}
	/* 链接 */
	#nice a {
		color: #48b378;
		text-decoration:none;
		border-bottom: 1px solid #48b378;
	}
	/* 加粗 */
	#nice strong {
		line-height: 1.75em;
		color: rgb(74,74,74);
	}
	/* 斜体 */
	#nice em {
	}
	/* 加粗斜体 */
	#nice em strong {
		color:rgb(248,57,41);
		letter-spacing:0.3em;
	}
	/* 删除线 */
	#nice del {
	}
	 
	/* 分割线 */
	#nice hr {
		height:1px;
		padding:0;
		border:none;
		text-align:center;
		background-image:linear-gradient(to right,rgba(93, 186, 133,0),rgba(93, 186, 133,0.75),rgba(93, 186, 133,0));
	}
	/* 图片 */
	#nice img {
	    border-radius:4px;
	    margin-bottom:25px;
	}
	/* 图片描述文字 */
	#nice figcaption {
		display:block;
		font-size:12px;
		font-family:PingFangSC-Light;
	}
	/* 行内代码 */
	#nice p code, #nice li code {
		color: #28ca71;
	}
	/* 非微信代码块
	 * 代码块不换行 display:-webkit-box !important;
	 * 代码块换行 display:block;
	 */
	#nice pre code {
	}
	/* 表格内的单元格
	 * 字体大小 font-size: 16px;
	 * 边框 border: 1px solid #ccc;
	 * 内边距 padding: 5px 10px;
	 */
	#nice table tr th,
	#nice table tr td {
		font-size: 14px;
	}
	#nice .footnotes{
		padding-top: 8px;
	}
	/* 脚注文字 */
	#nice .footnote-word {
		color: rgb(90, 185, 131);
	}
	/* 脚注上标 */
	#nice .footnote-ref {
		color: rgb(90, 185, 131);
	}
	/* 脚注超链接样式 */
	#nice .footnote-item em {
		color: rgb(90, 185, 131);
		font-size:13px;
		font-style:normal;
		border-bottom-color:1px dashed rgb(90, 185, 131); 
	}
	/* "参考资料"四个字 
	 * 内容 content: "参考资料";
	 */
	#nice .footnotes-sep:before {
		background-image: none;
		background-size: none;
		display: block;
		width: auto;
		height: auto;
	}
	/* 参考资料编号 */
	#nice .footnote-num {
		color: rgb(90, 185, 131);
	}
	/* 参考资料文字 */
	#nice .footnote-item p {
		color: rgb(90, 185, 131);
		font-weight:bold;
	}
	/* 参考资料超链接 */
	#nice .footnote-item a {
		color:rgb(93, 186, 133);
	}
	/* 参考资料解释 */
	#nice .footnote-item p em {
		font-size:14px;
		font-weight:normal;
		border-bottom:1px dashed rgb(93, 186, 133);
	}
	/* 行间公式
	 * 最大宽度 max-width: 300% !important;
	 */
	#nice .block-equation svg {
	}
	/* 行内公式*/
	#nice .inline-equation svg {  
	}
	
	#center {
		text-align:center;
		color:rgb(33,201,187);
	} 
	
</style>

<!--记得HTML和MD隔行-->

# 福州八中信息部宣传页

## 关于信息部

**福州八中信息部**是属于<a href="https://www.fzbz.com.cn" title="福州第八中学官网">福州第八中学</a>初中部学生会的一个**学生组织**\(´ｰ∀ｰ`\)，<!--暂空--><br>

## 信息部纳新计划

<span style=color:rgb(33,201,187)>**信息部的纳新计划常年开放**</span>

希望加入我们？>﹏<**必须满足**的条件如下（拍摄后期二选一\~\~或者全选）<br>
<span class="heimu" title="被你发现咯~">抱着一颗想学习的心也可以来欧(￣▽￣)"</span>
* 拍摄
	* 拥有至少一台拍摄设备，能够完全**自行熟练使用**
	* 对计算机软硬件知识有一定的认知
* 后期制作
	* 熟练**图片处理**、**视频剪辑**或**动画制作**类后期软件至少一种
	* 对计算机软硬件知识有一定的认知

**拒绝胶片相机**<span class="heimu" title="你钱多~">，除非你自备冲洗工具和大几千的胶片扫描仪(￣▽￣)"</span><br><br>
建议所有无人机起飞重量大于249克者在<a href="https://www.caac.gov.cn" title="中国民用航空总局官网">中国民用航空总局</a>进行无人机实名登记<span class="heimu" title="你知道的太多了">实际上部里基本都是黑飞</span>，否则请低于120公尺高度飞行以避免违规。<br><br>
请按以下格式发送电子邮件到<1843887033@qq.com>：<br><br>
**标题：信息部纳新报名**<br>
**正文：**
* 班级-姓名-能力（拍摄或后期制作）<br>
* 设备**详细**型号（请务必提供尽可能详细的设备型号）<br>
* 电子联系方式（QQ、微信或电邮）

<br><br><br><br><br><br><br><br><br><br><br>
试试能不能上视频~

<div style="position: relative; padding: 30% 45%;">
<iframe style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;" src="https://player.bilibili.com/player.html?aid=2053100&bvid=BV1Cx411A7ro&cid=3178910&page=1" frameborder="no" scrolling="no"></iframe>
</div>

## 相关链接
* <a href="https://www.fzbz.com.cn" title="什么年代了还在用传统网站样式~">福州第八中学官网</a>
* <a href="https://space.bilibili.com/30765769/?spm_id_from=333.999.0.0">福州八中三江口电视台</a>

<br>——此网页使用CSS3、HTML5标准<br>——使用MarkDown制作
