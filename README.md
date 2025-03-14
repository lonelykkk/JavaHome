## 前言

整理一份超级详细的Java面试题+后端基础+日常工作总结，做最暖心的男孩子，后面会慢慢完善，希望大家找到理想offer 

⭐ 点右上角给一个 Star，鼓励技术人输出更多干货，感谢感谢，爱了！ ！

作者捡田螺的小男孩，浪迹过几家大厂，**掘金优秀创作者**，CSDN博主，知乎博主。以下内容全部出自公众号：**捡田螺的小男孩**，欢迎关注。

- [田螺原创精品100篇](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&amp;mid=2247497536&amp;idx=1&amp;sn=3ac9934f607d79e51457fd01f4c8a4ef&amp;chksm=cf222869f855a17fc30c744e5b7ccdeca407f3b7ddcca46bae1c93b1436ffc6fe417ccb8aef4&token=1990771297&lang=zh_CN#rd)

## 工作总结

- [盘点数据库主从延迟的9个原因以及解决方案](https://mp.weixin.qq.com/s/aT7YjsTrM_dhDbddr8TSjg?token=528541177&lang=zh_CN)
- [实战项目，是如何保证缓存跟数据库数据一致性的？](https://mp.weixin.qq.com/s/UVHMeFDO4NYTnSwHZc9f1A?token=528541177&lang=zh_CN)
- [工作总结！日志打印的15个建议](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&mid=2247494838&idx=1&sn=cdb15fd346bddf3f8c1c99f0efbd67d8&chksm=cf22339ff855ba891616c79d4f4855e228e34a9fb45088d7acbe421ad511b8d090a90f5b019f&token=162724582&lang=zh_CN&scene=21#wechat_redirect)
- [25种代码坏味道总结+优化示例](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&mid=2247490148&idx=1&sn=00a181bf74313f751b3ea15ebc303545&chksm=cf21c54df8564c5bc5b4600fce46619f175f7ae557956f449629c470a08e20580feef4ea8d53&token=162724582&lang=zh_CN&scene=21#wechat_redirect)
- [聊聊日常开发中，如何减少bug呢？](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&mid=2247490662&idx=1&sn=d38a090611af7f64ee3c6a31331d5228&chksm=cf21c34ff8564a59e505e6edf3065a0fc506c6d2c96f492c8d8873cd46dedbe0704e43cb9c2e&token=1990771297&lang=zh_CN#rd)
- [工作四年，分享50个让你代码更好的小建议](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&mid=2247488708&idx=1&sn=6e2e0a740f5d42a59641487a0bf1e3bf&chksm=cf21cbedf85642fbb485fa1c7bf9af21923d8503f2542b6f8283ce79ddc683f7d9e45da83100&token=162724582&lang=zh_CN&scene=21#wechat_redirect)
- [写代码有这16个好习惯，可以减少80%非业务的bug](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&mid=2247488097&idx=1&sn=eaca1f92ca3ccd9de00dbc4ef3e4029a&chksm=cf21cd48f856445e4cc24c1f8bcf18d1479bad0a37a87a2fb70717d8a4e65dcf7b4d5f83d24f&token=162724582&lang=zh_CN&scene=21#wechat_redirect)
- [Java日常开发的21个坑，你踩过几个？](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&mid=2247488115&idx=1&sn=bdd4a4ca36bc7ea902106d058e8537fb&chksm=cf21cd5af856444cb36af600705615454b0aaa2b289b97ddb52d594556ac07a1915b73ecce19&token=162724582&lang=zh_CN&scene=21#wechat_redirect)
- [CAS乐观锁解决并发问题的一次实践](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&mid=2247487937&idx=1&sn=206a37bf6d6a7aa1d05674c479ed7a72&chksm=cf21cee8f85647fe7a082049a41c0f640f54976d2cdf4302b24c5517ca42b854eb84b13ece10&token=1990771297&lang=zh_CN#rd)
- [写代码有这些想法，同事才不会认为你是复制粘贴程序员](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&mid=2247487961&idx=1&sn=e646231067968d9f58e6665914293f9a&chksm=cf21cef0f85647e6f3ff2feece004ac3bd979e37fe45103c88d0f299dfe632a5cf6dd547c1d9&token=162724582&lang=zh_CN&scene=21#wechat_redirect)
- [程序员必备：Java日期处理的十个坑](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&mid=2247487973&idx=1&sn=0f713413098fb579e5f200b829f71e89&chksm=cf21ceccf85647da450765d79bf5943da551c3be950447063b9f8c77c21bf2a39b99387a949b&token=162724582&lang=zh_CN&scene=21#wechat_redirect)
- [内存泄漏问题的分析和解决方案](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&mid=2247487986&idx=1&sn=d681a585ac489703788e3baa48eb9aa3&chksm=cf21cedbf85647cd23bbab9dfec63e6877f83c34efb19bd16075d5d90fea91d3f4a20fc77921&token=162724582&lang=zh_CN&scene=21#wechat_redirect)
- [程序员必备基础：加签验签](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&mid=2247488022&idx=1&sn=70484a48173d36006c8db1dfb74ab64d&chksm=cf21cd3ff8564429a1205f6c1d78757faae543111c8461d16c71aaee092fe3e0fed870cc5e0e&token=162724582&lang=zh_CN&scene=21#wechat_redirect)
- [记一次接口性能优化实践总结：优化接口性能的八个建议](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&mid=2247488004&idx=1&sn=00840efd9c0bd0a7f172b59eb2ca130f&chksm=cf21cd2df856443bf21d8e09cfe5c8452ecaf82e3c2210fca3b28829ded04defddcf63c0a59b&token=162724582&lang=zh_CN&scene=21#wechat_redirect)
- [程序员必备基础：如何安全传输存储用户密码？](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&mid=2247488117&idx=1&sn=5d3d0eda0ed45f3f576e211de31ca3a9&chksm=cf21cd5cf856444af1407a94a2abf445265ca7c5f5855cfa1c223cb209e99040c7889621f231&token=162724582&lang=zh_CN&scene=21#wechat_redirect)
- [一次代码优化实践，用了模板方法+策略+工厂方法模式](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&mid=2247488061&idx=1&sn=1d9ab7954b03521ab81ecf033c0e5e50&chksm=cf21cd14f8564402b213f0ef908bbdb0e12fed4b281c5803b8e539cacb1551654194becfb7d6&token=162724582&lang=zh_CN&scene=21#wechat_redirect)
- [保证接口数据安全的10种方案](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&amp;mid=2247500285&amp;idx=1&amp;sn=7d0723f25d46e858859cfd79acb6fb9d&amp;chksm=cf221ed4f85597c2093f81baa5fdedc65817bf2d23a7951236836b0f54c2335695cbed61cd13&token=1990771297&lang=zh_CN#rd)
- [实战总结！18种接口优化方案的总结](https://mp.weixin.qq.com/s?__biz=MzkyMzU5Mzk1NQ==&amp;mid=2247506674&amp;idx=1&amp;sn=8b2914d9aafa334029495b029b69d0b6&amp;chksm=c1e0277ef697ae68e8c2bffe4bd7d9849be3165ef1a20286538f6a7569a6ba0879d517d55b87&token=337310304&lang=zh_CN#rd)
- [聊聊工作中常用的Lambda表达式](https://mp.weixin.qq.com/s?__biz=MzkyMzU5Mzk1NQ==&amp;mid=2247506654&amp;idx=1&amp;sn=4835e9f486e643765d4ad3b3fc93e079&amp;chksm=c1e02752f697ae442f62fc122d7604f4b01979f6d1665df414bb499fd8ba211335ebc503c368&token=337310304&lang=zh_CN#rd)
- [21个MySQL表设计的经验准则](https://mp.weixin.qq.com/s?__biz=MzkyMzU5Mzk1NQ==&amp;mid=2247506621&amp;idx=1&amp;sn=afca898cb461827054d706a92f9b9250&amp;chksm=c1e02731f697ae27a83e5637ee2184d1e26e5090caeaa58121d3cf5afab7d4d5832cac6d171a&token=337310304&lang=zh_CN#rd)
- [程序员必备基础：如何安全传输存储用户密码？](https://mp.weixin.qq.com/s?__biz=MzkyMzU5Mzk1NQ==&mid=2247506023&idx=1&sn=b96dde436c1c9fe4bda745ca5ca1b170&source=41#wechat_redirect)

## 福利 500+页原创面试题

- [田螺原创500+页面试题](https://mp.weixin.qq.com/s?__biz=Mzg3NzU5NTIwNg==&mid=2247499943&idx=1&sn=fe869c0a97a306e42830336fe74e17a6&chksm=cf221f8ef8559698781709bfbccbb85087286e48434905fb18bec3a3ec0af7329c2a1632c230&token=1990771297&lang=zh_CN#rd)


## 个人公众号

微信搜公众号：**捡田螺的小男孩**

- 小伙伴可以关注我的公众号（扫描下面二维码，还有**很多很多干货文章**），一起学习讨论哈~~

![扫一扫](https://user-images.githubusercontent.com/20244922/179399354-8a9fd2a8-42ba-4303-9ce5-04891e899e6d.png)
