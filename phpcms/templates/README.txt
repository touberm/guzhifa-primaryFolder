commit 00000000
2017-5-24
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
		替换/guzhiba  ==> /guzhifa/guzhiba
	TODO	
		全部修改完毕时应该替换回来

	