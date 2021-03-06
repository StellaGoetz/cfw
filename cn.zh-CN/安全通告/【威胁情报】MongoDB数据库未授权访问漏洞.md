# 【威胁情报】MongoDB数据库未授权访问漏洞 {#concept_smb_sws_2hb .concept}

MongoDB数据库未授权访问漏洞危害严重，可以导致数据库数据泄露或被删除勒索，从而造成严重的生产事故。

如 2月14日，国家互联网应急中心（简称：CNCERT）[监测发现](http://www.cert.org.cn/publish/main/9/2019/20190222090901924149842/20190222090901924149842_.html)，我国境内部分MongoDB数据库暴露在互联网上导致重要信息泄露。

漏洞危害：

MongoDB服务启动时，如果不修改数据库认证访问权限相关的默认配置，登录的用户无需权限验证即可通过默认端口（无需密码）本地或远程访问该数据库，并对数据库进行任意操作（增、删、改、查等高危操作）。

为保证您的业务和应用的安全，请参考[MongoDB数据库未授权访问漏洞防御最佳实践](../../../../../cn.zh-CN/最佳实践/MongoDB数据库未授权访问漏洞防御最佳实践.md#)尽快修复该漏洞。

