Bug-Project-Framework
======================
[+]Введение:
---------
	*Язык использования платформы BPF
	*Позвольте себе расширить опыт
	*Быстро определяет, существует ли уязвимость в системе безопасности
	*Позволяет провести аудит безопасности работы в соответствующей сетевой среде


[+]Тестовый объект:
---------------
	*Интернет уязвимая цель


[+]Инструкция по применению:
---------------
	*Пожалуйста, попробуйте закрыть программу soft kill или приостановить службу защиты файлов перед запуском фреймворка. Антивирусная программа убьет компонент фреймворка и вызовет сбой фреймворка.
	*Перед первым использованием извлеките все файлы в папку , затем откройте параметры шеллкода, чтобы изменить путь шеллкода;
	*Затем поместите эксплойт в соответствующую папку, класс эксплойта помещается в папку исследования, класс poc помещается в папку poc, класс буфера помещается в папку буфера, запускается инфраструктура и может использоваться соответствующая функция;

	*Класс exploit в основном предназначен для веб-уязвимостей, а класс POC - для обнаружения веб-уязвимостей, а буферный класс вызывает внешние исполняемые модули.

[+]Как использовать:
------------------

    在BPF根命令行下：

          help                查询帮助

          reload              重新加载框架，此时会刷新全部模块

          search              搜索模块关键词并显示
                              （ e.g.  search ms17-010 ）
          searchall           显示所有模块

          use                 使用模块
                              （ e.g.  use \buffer\ms17-010 Scan.bpf ）
          set shellcodes      配置默认Shellcode路径

          exit                退出BPF


    在BPF模块命令行下：

          help                查询帮助

          show options        查看当前模块参数以及配置情况

          set options         设置当前模块参数以及配置

          set shellcodes      配置默认Shellcode路径

          run                 运行模块

          exit                退出当前模块

    当你输入除上述指定规定参数以外的命令时，BPF框架会将命令识别为系统命令，提交Windows操作系统进行处理

          HAPPY HACK ！GOOD LUCK ！
          2018.5.7 BY Fplyth0ner

[+]使用截图
-------------
![One](https://github.com/Fplyth0ner-Combie/Bug-Project-Framework/blob/master/images/1.jpg)
![Two](https://github.com/Fplyth0ner-Combie/Bug-Project-Framework/blob/master/images/2.jpg)

[+]exploit编写：
----------------
	*框架自带编写记事本，可参考BPF语法快速编写exploit，详情请参考BPF IDE提示的语法。


[+]感谢：
---------------
	Metasploit - Rapid7
	NetCat - Hobbit

[+]铭恩：
-----------
	Computer - John von Neumann
	Internet - Tim Berners-Lee
	Linux - Linus Benedict Torvalds
	Windows - Bill Gates
	C - D.M.Ritchie
	JavaScript - Brendan Eich
	Tomcat - James Duncan Davidson
	Apache - Apache Software Foundation
	Java - James Gosling
	VMware - Diane Greene
	Baidu - 李彦宏
	Google - Larry Page


[+]特别感谢：
-------------
	Tencent - 马化腾
	E - 吴涛

---------------------------------
2017年4月12日工程  -- Fplyth0ner

欢迎大家积极参与模块编写计划！

---------------------------------
