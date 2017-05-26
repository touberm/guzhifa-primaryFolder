commit 00000000
2017-5-24
		原始账户 phpcms
		原始密码 hao123a
		
		caches/configs/system.php需修改如下
		'web_path' => '/guzhifa/',
		
		phpcms后台设置:
		1.设置-站点管理-站点域名  ==> http://localhost/guzhifa/
		2.内容-批量更新URL
		3.批量跟新栏目页


		原head中:
		<link rel="stylesheet" type="text/css" href="/guzhiba/css/style.css"/>
		<link rel="stylesheet" type="text/css" href="/guzhiba/css/zhuanti.css"/>
		<script type="text/javascript" src="/guzhiba/js/lrtk.js?v=1"></script>
		<script src="/guzhiba/js/uaredirect.js" type="text/JavaScript"></script>
		……
		等等

	/未进行操作
		替换/guzhiba  ==> /guzhifa/guzhiba
	Todo
		全部修改完毕时应该替换回来
	END TODO
	/END 未进行操作

		Edit in guzhifa/a/jiamengyewu/hsi/index.html line in 294
		Css in guzhiba/css/style.css  line in 571
commit 1-2
2017-5-26
	phpcms自动生成html
	
	生成HTML 路径设置: caches/configs/system.php
		'html_root' => '/html',//生成静态文件路径

	代理分部 (频道页)phpcms/template/default/content/category_picture.html
		修改文件后 批量更新栏目页 生效

	地方页（列表页）phpcms/template/default/content/list_picture.html
		修改文件 进入管理内容  选择对应的项目的内容列表 批量更新_项目名_列表  生效
	将dist文件夹放在和guzhifa同级目录下 否则没有lightbox.js插件效果

	<script language='javascript' src='{APP_PATH}index.php?m=formguide&c=index&a=show&formid=14&action=js&siteid=1'></script>
	表单向导功能 相关文章http://blog.csdn.net/luyaran/article/details/53374896
	