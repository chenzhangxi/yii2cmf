# 动态模块（插件）

1.创建Plugins类,info属性表名`作者,插件名,插件说明,版本号等信息`

2.插件如果需要动态配置,则需要config.php,参考authclient插件

3.frontend方法扩展前台功能（监听视图事件添加内容,加控制器）,backend方法扩展后台功能（加菜单,加控制器）