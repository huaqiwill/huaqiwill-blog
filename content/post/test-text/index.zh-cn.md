---
title: PHP编程基础
description: 这里简单介绍PHP的编程基础，并且实战开发一个隔个人博客网站
date: 2024-09-03T22:16:31+08:00
slug: test-text
image: helena-hertz-wWZzXlDpMog-unsplash.jpg
categories:
    - Hugo
---

# PHP简介

PHP官网：https://www.php.net/

目前最新版：8.3



# PHP安装和配置

## Windows

修改文章内容


## Linux

参考：https://blog.csdn.net/belen_xue/article/details/79418744

 yum安装检查：

```
yum list installed | grep php
```



## 运行时配置



```php
<!DOCTYPE html>
<html>
<body>

<?php
echo "Hello World!";
?>

</body>
</html>
```





# PHP语法基础







## PHP变量和常量







## PHP数据类型







## PHP运算符







## PHP字符串







## PHP数组







## PHP超全局变量

这些超全局变量是：    

- [$GLOBALS](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/reserved.variables.globals.html)
- [$_SERVER](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/reserved.variables.server.html)
- [$_GET](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/reserved.variables.get.html)
- [$_POST](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/reserved.variables.post.html)
- [$_FILES](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/reserved.variables.files.html)
- [$_COOKIE](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/reserved.variables.cookies.html)
- [$_SESSION](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/reserved.variables.session.html)
- [$_REQUEST](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/reserved.variables.request.html)
- [$_ENV](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/reserved.variables.environment.html)

## PHP魔术常量





## PHP函数







## PHP命名空间







## PHP面向对象





## PHP生成器









## PHP测验







## PHP表单







## PHP Cookie和Session







## PHP错误处理







## PHP异常处理





## PHP正则表达式









## PHP文件和目录

### 文件系统



### 目录



### Direct IO











## PHP文件系统安全











# PHP图像处理





# PHP线程





# PHP进程控制

## 系统进程执行



## Eio





# PHP加密

## Crack





## Hash





## CSPRNG





## OpenSSL





## 密码散列算法













# PHP日期和时间

## 日历



## HRTime









# PHP测试







# PHP XML

## DOM



## LibXML



## SDO









# PHP邮件

## Mail

[mail()](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.mail.html) 函数可以让你发送邮件。 



配置







Table of Contents

- [ezmlm_hash](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.ezmlm-hash.html) — 计算 EZMLM 所需的散列值
- [mail](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.mail.html) — 发送邮件





## Mailparse



Mailparse是解析和处理电子邮件的扩展。它可以处理»RFC 822和»RFC 2045（MIME）兼容的消息。

Mailparse是基于流的，这意味着它不在内存中保存处理的文件的副本，因此在处理大型消息时非常节省资源。

>注：
>
>Mailparse需要mbstring扩展，并且必须在Mailparse之前加载mbstring



Table of Contents

- [mailparse_determine_best_xfer_encoding](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.mailparse-determine-best-xfer-encoding.html) — Gets the best way of encoding
- [mailparse_msg_create](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.mailparse-msg-create.html) — Create a mime mail resource
- [mailparse_msg_extract_part_file](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.mailparse-msg-extract-part-file.html) — Extracts/decodes a message section
- [mailparse_msg_extract_part](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.mailparse-msg-extract-part.html) — Extracts/decodes a message section
- [mailparse_msg_extract_whole_part_file](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.mailparse-msg-extract-whole-part-file.html) — Extracts a message section including headers without decoding the transfer encoding
- [mailparse_msg_free](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.mailparse-msg-free.html) — Frees a MIME resource
- [mailparse_msg_get_part_data](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.mailparse-msg-get-part-data.html) — Returns an associative array of info about the message
- [mailparse_msg_get_part](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.mailparse-msg-get-part.html) — Returns a handle on a given section in a mimemessage
- [mailparse_msg_get_structure](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.mailparse-msg-get-structure.html) — Returns an array of mime section names in the supplied message
- [mailparse_msg_parse_file](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.mailparse-msg-parse-file.html) — Parses a file
- [mailparse_msg_parse](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.mailparse-msg-parse.html) — Incrementally parse data into buffer
- [mailparse_rfc822_parse_addresses](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.mailparse-rfc822-parse-addresses.html) — Parse RFC 822 compliant addresses
- [mailparse_stream_encode](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.mailparse-stream-encode.html) — Streams data from source file pointer, apply encoding and write to destfp
- [mailparse_uudecode_all](mk:@MSITStore:D:\编程\编程语言\PHP\php7.3.8.chm::/res/function.mailparse-uudecode-all.html) — Scans the data from fp and extract each embedded uuencoded file







# PHP数据库

## DBA



## DBX





## ODBC





## PDO





## MySQL





## SQLite3





## MongoDB







# PHP数据库安全





# PHP文件上传





# PHP安全模式







# PHP垃圾回收机制







# PHP内存管理





# PHP文本处理

## BBCode



## Common Mark



## Parle





## POSIX Regex





## SSdeep





## 字符串



# PHP Web服务



## 授权和认证QAuth





## SCA



## SOAP



## Yar





## XML-RPC







# PHP Windows

## COM







## 进程 Win32Ps







## 服务 Win32Service









# PHP服务器

PHP内置服务器运行

```
php -S localhost:8000
```





## Apache



## FastCGI



## IIS



## NSAPI










