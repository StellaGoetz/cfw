# 【虚拟补丁】ThinkPHP 5.x 远程命令执行（getshell） {#concept_skw_dmx_cgb .concept}

云防火墙已可防御ThinkPHP 5.x 远程命令执行（getshell）攻击。

ThinkPHP是一个简便快速、兼容性强的轻量级国产PHP开发框架，在国内使用较多，特别是电子商务行业、金融服务行业、互联网游戏行业等行业网站。

2018年12月10日，ThinkPHP v5系列发布安全更新，修复了一处可导致远程代码执行的严重漏洞。该漏洞覆盖面广，可直接远程执行任何代码和命令。由于ThinkPHP v5框架对控制器名未进行足够的安全检测，此漏洞可导致在没有开启强制路由的情况下，黑客构造特定的请求，直接进行远程的代码执行，进而获得服务器权限。

影响范围： ThinkPHP v5.0系列 < 5.0.23 、ThinkPHP v5.1系列 < 5.1.31

规则类型：Web攻击

危险等级：高危

规则防护：云防火墙已可防御此类攻击，建议用户开启云防火墙的[入侵防御能力](../../../../cn.zh-CN/用户指南/安全策略/入侵防御策略.md#ol_ez3_mzd_dfb)。

