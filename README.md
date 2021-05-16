# POC-Test
### 在学习代码审计过程中，复现了一些漏洞案例，并在其过程中使用Pocsuite3框架编写了对应POC。
### 声明：POC仅限于测试交流，严禁用于非法用途
### 命令注入案例
Java：CVE-2020-13925 Apache Kylin命令注入漏洞，http://code2sec.com/cve-2020-13925-apache-kylinming-ling-zhu-ru-lou-dong.html

Php: seacms 6.45 代码执行漏洞,https://github.com/jiangsir404/PHP-code-audit/blob/master/seacms/seacms%20%E5%A4%9A%E4%B8%AA%E7%89%88%E6%9C%AC%E7%9A%84%E4%BB%A3%E7%A0%81%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E%E6%80%BB%E7%BB%93(search.php).md

### SQL注入案例
Java：CVE-2019-9615 OFCMS SQL注入漏洞，https://lanvnal.com/2020/03/15/ofcms-cve-2019-9615-fu-xian/

Php：CVE-2018-14961 ZZCMS 8.3 前台SQL 注入漏洞，http://keac.club/2020/02/02/CVE-2018-14961/

### XXE漏洞案例
Java：CVE-2018-15531，JavaMelody 组件 XXE 漏洞，https://paper.seebug.org/705/

Php：phpshe v1.7 XXE 漏洞，https://www.sohu.com/a/307805554_354899

### XSS漏洞案例
Java：Jetty6.x test页面反射型XSS漏洞，https://www.exploit-db.com/exploits/33564

Php：BlueCMS V1.6 反射型XSS漏洞，http://wjlshare.com/archives/1473#XSS

### 文件上传漏洞案例
Java: Weblogic 任意文件上传漏洞（CVE-2018-2894）, https://paper.seebug.org/647/

Php：禅道 <= 12.4.2 后台文件上传漏洞， https://www.windylh.com/2020/10/28/CNVD-C-2020-121325%EF%BC%9A%E7%A6%85%E9%81%93%E5%90%8E%E5%8F%B0%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90%E4%B8%8E%E5%A4%8D%E7%8E%B0/

### 文件下载漏洞案例
Java：Apache Flink 任意文件下载漏洞(CVE-2020-17519),https://www.anquanke.com/post/id/228507#h3-8

Php：XYHCMS V3.5任意文件下载漏洞，http://itren.xiaolee.net/p/2335042.html