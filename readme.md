
# Blog

## C

### Lex与Yacc

Lex 是词分析器 Yacc 是语法分析器

1. 系统传递字符串给Lex,Lex通过定义的规则，把一大段字符串解析成为一个个Token，然后返回给Yacc。
2. Yacc定义语法之间的规则，规则一般可以理解为 "某Token 某Token 某Token"为一个语法，规则的后面会定义对应的动作，表示某语法下C语言的运行规则。
3. php解析器使用的是re2c和Yacc做解析工具，通过浏览PHP7  Zend/zend_language_parser.y 文件能够更加清晰的了解到php的语法，包括return type的指定.??的使用等等。

[Lex与Yacc书籍与练习用的源代码](http://git.oschina.net/wan3574489/Lex-and-Yacc)

##Git

###常用命令
1. git clone https:user:password@git_Url_Address.com 通过Http地址克隆git库
2. git checkout -t origin/branch  在本地新建一个跟远端branch一样的分支，并且自动进行关联

##YII2

###常用命令
    数据迁移与更新:
       新建迁移命令  yii migrate/create <name>
       运行迁移      yii migrate
       参考网站      http://www.yiichina.com/doc/guide/2.0/db-migrations

###PHPStorm
    1.代码注释能够让编辑器识别不容易识别的变量，提供较好的代码变量提示。
      /*
         * @var  $WxPay \common\components\NotificationService
         */
         @var 标签
         @WxPay 对应的变量名称
         @\common\components\NotificationService 变量对应的类
***
[Markdown使用手册](http://wowubuntu.com/markdown/)
[Markdown在线手册](http://mahua.jser.me/)
