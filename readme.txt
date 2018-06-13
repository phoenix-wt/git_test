Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
第一次修改并add
创建一个新分支

记住 evosuite 设置(生成properties文件，并设置参数)
每次给evosuite提供projet classpath是很不方便的，尤其是项目比较复杂而且classpath数量很多的时候。同样，有人想设定参数让所有evosuite运行
我们可以将这些设置到properties文件中，evosuite会默认去 evosuite-files/evosuite.properties寻找
我们可以用-setup<arg>令自动生成该文件，arg指定为classes放置的文件路径
随后会生成 evosuite-files 文件夹内有evosuite.properties文件，对文件内参数修改即可使用
