# LUCC-Code-convent-to-Chinese-name
这个代码用于在Arcmap中将来源于中国科学院资源环境科学数据中心( http://www.resdc.cn ) 的中国土地利用/土地覆被遥感监测数据遥感监测数据的地类编码转换为地类中文名称，便于可视化输出。
# Running environmental: Arcmap
# 操作步骤

1、在属性表中选择需要重新赋值的字段，右键打开字段计算器（Field Calculator），注意该字段类型必须是string类型。

![image](https://user-images.githubusercontent.com/44941550/167173563-3413706a-9d35-43a7-aee8-f74ae6a0a95b.png)


2、勾选Show Codeblock后填入本程序的源代码（代码当中CODE字段代表地类代码，如果在实际操作中，地类代码字段名称不是CODE，需要把本程序源代码中的CODE改为实际的地类代码字段名称），然后在“class2010=”下面填入u

![image](https://user-images.githubusercontent.com/44941550/167173591-4087ca1e-07a7-4af9-bbbb-36d6c56be2a8.png)


3、这里填入的u是跟代码里面的Dim u对应的，如果代码第一条的u变成其它字符，相应的下面填入的字符也要跟着变，而class2010用来演示的字段名称，也就是刚才点击右键打开字段计算器的字段的名称。
然后点击ok就开始计算了

![image](https://user-images.githubusercontent.com/44941550/167173612-e865220d-a983-4b43-b858-b1e46ff7dda9.png)


下图是重新赋值的结果

![image](https://user-images.githubusercontent.com/44941550/167173636-1df03613-c936-4444-9579-462886609a0e.png)
