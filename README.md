# phpSvn
first version<br>
本系统用php管理svn代码审核及代码发布，目前只适用linux：<br>

1、先配置include/config.db.php<br>
2、运行install<br>
3、在计划任务里加上1小时一次执行的任务：php 根目录/crontab/get_revision_list.php (notice:get_revision_list.php里要改require路径)<br>
4、默认用户名和密码是admin admin<br>
