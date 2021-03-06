# 【虚拟补丁】WebLogic T3协议反序列化漏洞 {#concept_v3r_pdc_dfb .concept}

Oracle官方发布了4月份的关键补丁更新CPU（Critical Patch Update），其中包含一个高危的Weblogic反序列化漏洞\(CVE-2018-2628\)。通过该漏洞，攻击者可以在未授权的情况下远程执行代码。该漏洞安全风险高。Oracle官方及时发布了最新补丁修复了该漏洞，阿里云安全团队建议您尽快自查并升级。

Oracle WebLogic Server 10.3.6.0，12.1.3.0，12.2.1.2，和12.2.1.13版本WebLogic T3协议反序列化漏洞可导致远程代码执行。恶意攻击者可以通过构造恶意请求报文远程执行命令获取系统权限，带来严重的安全风险。

CVE编号：CVE-2018-2628

规则防护：防护漏洞导致的远程命令执行

影响范围：WebLogic 10.3.6.0、WebLogic 12.1.3.0、WebLogic 12.2.1.2、WebLogic 12.2.1.3

规则类型：命令执行

危险等级：高危

