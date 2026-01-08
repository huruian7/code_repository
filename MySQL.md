# 第一章 SQL语句
DDL，DML，DQL，DCL
alt table student    add （column）添加字段，位置补充控制，first，after	    
				modify    修改字段
				 change   重命名字段且可以修改字段约束（修改列定义）
				 drop       删除字段
	 。modify,change,dro
	![[ddl语句总结.png]]
注意：
1. 均可以多行，比如add s_age int,add s_name varchar(50);(modify,change,drop同理)
2. FIRST  和AFTER 字段名可以用来控制字段位置


