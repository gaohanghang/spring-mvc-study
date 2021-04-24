## 视频学习 | Spring MVC起步

> 视频地址：[https://www.imooc.com/learn/47](https://www.imooc.com/learn/47)
> 代码地址：[https://github.com/gaohanghang/spring-mvc-study](https://github.com/gaohanghang/spring-mvc-study)



简介：Spring MVC为我们提供了一个基于组件和松耦合的MVC实现框架。在使用Java中其它MVC框架多年之后，面对Spring MVC有一种相见恨晚的感觉。Spring MVC是如此的优雅，轻盈与简洁， 让人从其它框架的桎梏解脱出来。本课程将带你步入Spring MVC。
## 第1章 MVC简介
MVC的演进，概念及优点
### [ 1-1 Spring MVC起步课程简介 (01:29)](https://www.imooc.com/video/7237)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248220181-acd71ad7-85e8-4d8c-a49f-492332082cf7.png#align=left&display=inline&height=605&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1210&originWidth=2186&size=641765&status=done&style=none&width=1093)
### [ 1-2 前端控制器 (03:50)](https://www.imooc.com/video/7126)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248254367-37decf30-ff3a-447a-a561-928bf5856529.png#align=left&display=inline&height=612&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1224&originWidth=2190&size=1196274&status=done&style=none&width=1095)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248403896-5a0caf4d-344d-49f9-b570-b0f716297052.png#align=left&display=inline&height=607&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1214&originWidth=2202&size=715416&status=done&style=none&width=1101)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248361598-33366731-59ef-474d-ae0a-e2e5bccd970f.png#align=left&display=inline&height=606&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1212&originWidth=2190&size=1639799&status=done&style=none&width=1095)




![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248422442-a6a27660-95db-42f2-8805-c1071b78d457.png#align=left&display=inline&height=617&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1234&originWidth=2192&size=881775&status=done&style=none&width=1096)


MVC本质

- MVC 的核心思想是业务数据抽取同业务数据呈现相分离
### [ 1-3 MVC概念 (05:05)](https://www.imooc.com/video/7165)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248496034-79447b44-e1c3-4cc3-8e9e-f89ee837aee3.png#align=left&display=inline&height=611&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1222&originWidth=2168&size=360660&status=done&style=none&width=1084)




![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248525235-554245ff-6e77-4b98-9108-0cc172001875.png#align=left&display=inline&height=610&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1220&originWidth=2196&size=1219939&status=done&style=none&width=1098)


#### View
视图层
为用户提供UI，重点关注数据的呈现


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248532283-43f7a9c1-c7cf-4f63-aaf5-f416bab22c59.png#align=left&display=inline&height=610&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1220&originWidth=2190&size=841611&status=done&style=none&width=1095)


#### Model


模型层
业务数据的信息表示，关注支撑业务的信息构成，通常是多个业务实体的组合。


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248585276-65cb9a8d-26ee-433f-b8af-7c635c7f347c.png#align=left&display=inline&height=616&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1232&originWidth=2210&size=1869892&status=done&style=none&width=1105)


#### Controller


控制层


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248614719-e85b0ad3-2ae4-4fe5-84c3-78bd1fc733a1.png#align=left&display=inline&height=606&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1212&originWidth=2148&size=654933&status=done&style=none&width=1074)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248630712-b78981a9-42d9-456a-910c-82d3abc57f61.png#align=left&display=inline&height=609&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1218&originWidth=2178&size=1065970&status=done&style=none&width=1089)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248645598-3f74773d-0a0a-4ea5-b976-a1e75266f320.png#align=left&display=inline&height=601&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1202&originWidth=2188&size=1930623&status=done&style=none&width=1094)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248653060-c9479c90-9efd-4137-a3db-715141847872.png#align=left&display=inline&height=588&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1176&originWidth=2196&size=842946&status=done&style=none&width=1098)






## 第2章 Spring MVC中的基本概念
抽茧剥丝，将Spring MVC中重要类及作用做概要说明
### [ 2-1 Spring MVC的静态概念 (06:59)](https://www.imooc.com/video/7501)




![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248766352-20dd3534-7bc5-47bf-b078-c1d9059ddc53.png#align=left&display=inline&height=609&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1218&originWidth=2182&size=643474&status=done&style=none&width=1091)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248791660-20c1f633-02c0-45b8-846e-6e391f3d5f9d.png#align=left&display=inline&height=605&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1210&originWidth=2174&size=424809&status=done&style=none&width=1087)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248860538-06cbae17-01e4-42e4-b8bd-198db334b343.png#align=left&display=inline&height=616&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1232&originWidth=2204&size=775077&status=done&style=none&width=1102)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248876056-57bf9d7d-bd1b-4fa6-bb4e-c74fcd27ba6e.png#align=left&display=inline&height=600&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1200&originWidth=2190&size=936588&status=done&style=none&width=1095)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248942910-ac780a49-8127-4754-93dc-400dd5aca767.png#align=left&display=inline&height=605&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1210&originWidth=2172&size=686451&status=done&style=none&width=1086)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248964788-26509361-244a-47aa-bf11-de806cb1f2d2.png#align=left&display=inline&height=611&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1222&originWidth=2196&size=693723&status=done&style=none&width=1098)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619248985355-ee1f7557-390e-4716-828e-daa4f25fdb63.png#align=left&display=inline&height=607&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1214&originWidth=2172&size=607355&status=done&style=none&width=1086)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619249024894-5d2e3b9a-2a2d-489d-9447-abd3e3216be8.png#align=left&display=inline&height=603&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1206&originWidth=2186&size=335862&status=done&style=none&width=1093)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619249034616-8d7f37c5-0a2f-4445-8805-aabd8e518325.png#align=left&display=inline&height=606&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1212&originWidth=2178&size=561473&status=done&style=none&width=1089)


### [ 2-2 Spring MVC的动态概念 (07:11)](https://www.imooc.com/video/7530)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619249137076-49cfbed9-92c3-4157-922a-9295751e837b.png#align=left&display=inline&height=612&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1224&originWidth=2184&size=979242&status=done&style=none&width=1092)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619249149991-c64d8538-a317-45c7-9ae4-20c987cb860b.png#align=left&display=inline&height=607&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1214&originWidth=2214&size=875812&status=done&style=none&width=1107)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619249230388-5fce0b96-6d03-4f5b-b2d2-1827cd360fe1.png#align=left&display=inline&height=626&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1252&originWidth=2186&size=897981&status=done&style=none&width=1093)




## 第3章 配置Maven环境
针对初学者，step by step安装配置Maven， 搭建Spring MVC开发环境
### [ 3-1 Maven介绍 (07:12)](https://www.imooc.com/video/7417)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619249330522-57693093-def7-4d23-b838-ca6bd98f25b1.png#align=left&display=inline&height=596&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1192&originWidth=2140&size=401350&status=done&style=none&width=1070)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619249353073-114a0220-d2c1-4148-98c9-e1a467ea548f.png#align=left&display=inline&height=599&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1198&originWidth=2200&size=418099&status=done&style=none&width=1100)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619249360557-fb58dc76-d59f-417b-a7b5-e852261cca0b.png#align=left&display=inline&height=610&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1220&originWidth=2196&size=1169447&status=done&style=none&width=1098)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619249367628-3405f890-ab3e-4f89-bf34-bca8a01e971e.png#align=left&display=inline&height=606&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1212&originWidth=2180&size=1047652&status=done&style=none&width=1090)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619249376271-52c714a1-0c8d-4d26-865e-fe9a159d4fd7.png#align=left&display=inline&height=612&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1224&originWidth=2194&size=636175&status=done&style=none&width=1097)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619249392900-d489a062-935e-43e7-bf83-dae43099894c.png#align=left&display=inline&height=604&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1208&originWidth=2190&size=682838&status=done&style=none&width=1095)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619249445494-0afaaa64-ce22-4ba7-81d8-bf8379f34166.png#align=left&display=inline&height=597&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1194&originWidth=2192&size=870507&status=done&style=none&width=1096)


管理传递依赖关系


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619249485550-fd9b07cd-2f3d-4a9e-8f45-b011e73f7baa.png#align=left&display=inline&height=613&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1226&originWidth=2212&size=1085828&status=done&style=none&width=1106)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619249503916-af825708-8fec-4e46-8a8e-67ac7bebe5c8.png#align=left&display=inline&height=602&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1204&originWidth=2190&size=1336966&status=done&style=none&width=1095)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619249526200-fd3d408e-5245-4aaf-b571-d027e0e17739.png#align=left&display=inline&height=606&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1212&originWidth=2174&size=952380&status=done&style=none&width=1087)




### [ 3-2 Maven的安装 (03:24)](https://www.imooc.com/video/7418)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619249573266-01d18773-37b6-4896-a0fd-cee9c638d37e.png#align=left&display=inline&height=596&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1192&originWidth=2116&size=969972&status=done&style=none&width=1058)


### [ 3-3 Maven的配置 (03:57)](https://www.imooc.com/video/7419)
略
### [ 3-4 用Maven创建项目 (05:10)](https://www.imooc.com/video/7531)
略
### [ 3-5 Hello Spring MVC (12:51)](https://www.imooc.com/video/7533)
略
## 第4章 Spring MVC实操
基于课程管理的业务需求，用Spring MVC开发一个模块
### [ 4-1 从配置文件开始 (07:53)](https://www.imooc.com/video/7681)




![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619250046526-2d1539a5-20e9-46d7-9efb-2c183602ddcc.png#align=left&display=inline&height=609&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1218&originWidth=2164&size=1027549&status=done&style=none&width=1082)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619250102195-ebeebfdf-bfb9-4f0e-8d24-04d9bac482f7.png#align=left&display=inline&height=592&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1184&originWidth=2128&size=699061&status=done&style=none&width=1064)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619250111852-2a0cf5fe-9f62-4898-ae32-1ff4c3bbecef.png#align=left&display=inline&height=608&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1216&originWidth=2194&size=1435109&status=done&style=none&width=1097)
![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619250388325-f5ad70b4-06dc-4662-9eaa-fd0e37cba5a9.png#align=left&display=inline&height=618&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1236&originWidth=2200&size=1344073&status=done&style=none&width=1100)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619250400592-ac8748ba-8283-4db5-afd2-6b031ad04fa5.png#align=left&display=inline&height=617&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1234&originWidth=2204&size=2050807&status=done&style=none&width=1102)




### [ 4-2 Controller-基础代码 (06:00)](https://www.imooc.com/video/7682)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619250630053-539b4358-fddc-4d34-8ad7-1c8eff027ed8.png#align=left&display=inline&height=601&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1202&originWidth=2208&size=862788&status=done&style=none&width=1104)






### [ 4-3 Controller-现代方式 (08:41)](https://www.imooc.com/video/7683)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619250719905-d3978471-fc23-4b24-a508-6d75fa1258b7.png#align=left&display=inline&height=617&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1234&originWidth=2184&size=1312789&status=done&style=none&width=1092)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619250749976-1fcbc9a4-eed7-4ac3-9051-615cbc4b2d4d.png#align=left&display=inline&height=608&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1216&originWidth=2204&size=1305621&status=done&style=none&width=1102)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619250931585-51eb588a-278f-4131-be92-1e57135ea44f.png#align=left&display=inline&height=944&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1888&originWidth=3360&size=472325&status=done&style=none&width=1680)
```bash
 mvn jetty:run
```
[http://localhost:8080/courses/view?courseId=123](http://localhost:8080/courses/view?courseId=123)
![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619251081557-d2cb40c1-73ed-462e-b021-160313d50913.png#align=left&display=inline&height=899&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1798&originWidth=3258&size=2175672&status=done&style=none&width=1629)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619251755028-9c3f9dd5-52ac-4e0e-9caa-fcbda6c20098.png#align=left&display=inline&height=621&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1242&originWidth=2166&size=1794728&status=done&style=none&width=1083)


### [ 4-4 Controller-传统方式 (04:24)](https://www.imooc.com/video/7684)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619251842941-293bd842-74f8-45ba-a17f-47f2e5981b25.png#align=left&display=inline&height=619&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1238&originWidth=2188&size=1525518&status=done&style=none&width=1094)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619251856173-1aaeaf61-c029-4691-b341-fc26a9d75a86.png#align=left&display=inline&height=616&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1232&originWidth=2158&size=465222&status=done&style=none&width=1079)


### [ 4-5 Binding (11:51)](https://www.imooc.com/video/8358)




![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619251975845-fd90142d-2151-4a38-b5e9-d50edda8ecbf.png#align=left&display=inline&height=593&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1186&originWidth=2134&size=767375&status=done&style=none&width=1067)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619251948457-9f970893-a28f-4cbe-80f2-e56e1e0c2222.png#align=left&display=inline&height=622&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1244&originWidth=2208&size=1216002&status=done&style=none&width=1104)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252056647-c5070b72-7569-4f6c-80d8-6ef61b9e3cea.png#align=left&display=inline&height=615&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1230&originWidth=2178&size=1143842&status=done&style=none&width=1089)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252075075-ffbd89e2-3785-48ff-a6ee-8b82d178a37a.png#align=left&display=inline&height=620&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1240&originWidth=2216&size=404259&status=done&style=none&width=1108)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252146119-18648616-0b9e-4188-b37d-0f906938aead.png#align=left&display=inline&height=615&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1230&originWidth=2186&size=1211199&status=done&style=none&width=1093)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252155915-b10112df-268d-489c-824e-d9ae347583b1.png#align=left&display=inline&height=608&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1216&originWidth=2208&size=263896&status=done&style=none&width=1104)






### [ 4-6 FileUpload--单文件上传 (12:54)](https://www.imooc.com/video/8413)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252245273-42c6a00d-1fd6-43d9-847d-92102ba4c5c4.png#align=left&display=inline&height=610&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1220&originWidth=2180&size=1600786&status=done&style=none&width=1090)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252260296-8e6b2822-75a3-42cd-b24d-e0d468748785.png#align=left&display=inline&height=604&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1208&originWidth=2206&size=1219831&status=done&style=none&width=1103)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252274528-7f6b27d1-3be1-473d-97de-d25d52a5856e.png#align=left&display=inline&height=620&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1240&originWidth=2208&size=1230033&status=done&style=none&width=1104)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252286739-9bf179ef-b337-422a-b06f-6d2d5dabe2cf.png#align=left&display=inline&height=602&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1204&originWidth=2188&size=1453141&status=done&style=none&width=1094)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252442398-d41c81ea-21df-444a-a01a-db675efd1ca4.png#align=left&display=inline&height=601&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1202&originWidth=2220&size=1299542&status=done&style=none&width=1110)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252452856-2911ada2-fdb0-4d04-b386-5e841e29d89b.png#align=left&display=inline&height=617&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1234&originWidth=2208&size=715934&status=done&style=none&width=1104)




### [ 4-7 JSON（上） (03:41)](https://www.imooc.com/video/8602)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252508560-c9050f5d-4546-442e-89d1-2b0882a51379.png#align=left&display=inline&height=609&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1218&originWidth=2192&size=702081&status=done&style=none&width=1096)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252549271-b18fe20a-9a97-466f-9a88-3afb48311d55.png#align=left&display=inline&height=619&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1238&originWidth=2216&size=1015662&status=done&style=none&width=1108)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252583784-0d8f0570-ab4d-4445-9eb5-c5e1a56ffb13.png#align=left&display=inline&height=613&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1226&originWidth=2232&size=561747&status=done&style=none&width=1116)
### [ 4-8 JSON（中） (05:23)](https://www.imooc.com/video/8595)






![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252616822-106cb015-0104-444e-82c8-62f43d0fb569.png#align=left&display=inline&height=616&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1232&originWidth=2204&size=1552923&status=done&style=none&width=1102)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252631872-7783a553-08d2-4d4f-9323-4a23a294bc73.png#align=left&display=inline&height=620&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1240&originWidth=2216&size=1351764&status=done&style=none&width=1108)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252661557-5015b220-4baa-46ff-9ba9-fb514016804a.png#align=left&display=inline&height=605&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1210&originWidth=2220&size=1436142&status=done&style=none&width=1110)
[http://localhost:8080/courses/123](http://localhost:8080/courses/123)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252712395-6f7ee6d1-2da8-468c-8bd0-7b3d7a4645a1.png#align=left&display=inline&height=902&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1804&originWidth=2938&size=406585&status=done&style=none&width=1469)




![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252762127-aca136db-cd7e-4a47-b443-914ad03fccba.png#align=left&display=inline&height=594&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1188&originWidth=2212&size=1226860&status=done&style=none&width=1106)
[http://localhost:8080/courses/jsontype/123](http://localhost:8080/courses/jsontype/123)
![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252824955-fffab06f-084c-484c-bb4e-242b01eaf9b4.png#align=left&display=inline&height=641&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1282&originWidth=3346&size=306211&status=done&style=none&width=1673)




### [ 4-9 JSON（下） (04:46)](https://www.imooc.com/video/8655)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619252919993-c18c5951-4971-4967-9d79-c32df754f9e1.png#align=left&display=inline&height=613&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1226&originWidth=2218&size=1799304&status=done&style=none&width=1109)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619253001148-d0c2a84e-5b5c-4880-837f-531cec8cb4ef.png#align=left&display=inline&height=613&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1226&originWidth=2166&size=646769&status=done&style=none&width=1083)




## 第5章 总结
### [ 5-1 总结 (02:44)](https://www.imooc.com/video/8656)




![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619253089450-ab976195-d83a-438f-bf8a-6413ee9beb61.png#align=left&display=inline&height=619&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1238&originWidth=2212&size=1217424&status=done&style=none&width=1106)![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619253123151-6fa260ba-9496-4aa0-93a5-557869bac23e.png#align=left&display=inline&height=620&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1240&originWidth=2212&size=662115&status=done&style=none&width=1106)




![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619253139311-e763b4c9-f15d-4b0c-adb8-2c388e59b24f.png#align=left&display=inline&height=616&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1232&originWidth=2216&size=320569&status=done&style=none&width=1108)


![image.png](https://cdn.nlark.com/yuque/0/2021/png/576791/1619253149341-1fdabbf2-0dec-447c-9bc9-8ff822eea397.png#align=left&display=inline&height=608&margin=%5Bobject%20Object%5D&name=image.png&originHeight=1216&originWidth=2184&size=500450&status=done&style=none&width=1092)
