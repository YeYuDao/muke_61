# muke_61
Android 应用程序构建实战+原理精讲
Android 应用程序构建实战+原理精讲
👇👇👇👇👇👇👇👇点击图片跳转下载地址👇👇👇👇👇👇👇
### 第1章 课程导学 

#### 本章将带你了解课程整体内容和最终的效果，之后会为你介绍本课程内容具体安排，最后给出如何学好这门课程的一些学习建议。希望你能通过这门课程，学有所成，学有所归。
1-1 课前必读

1-2 课程导学 (11:37)


### 第2章 Gradle基础 

#### 本章将从基本概念、语言基础、生命周期等方面，带你掌握构建基石Gradle的基础必备技能。
2-1 本章介绍 (02:13)

2-2 Gradle是什么 (05:15)

2-3 Gradle的安装 (06:08)

2-4 Gradle的执行 (03:31)

2-5 如何升级Gradle【升级降级Gradle两种方式】 (03:17)

2-6 Groovy快速上手 (02:46)

2-7 Groovy必备语法 (15:21)

2-8 Groovy进阶语法-1 (13:42)

2-9 Groovy进阶语法-2 (12:05)

2-10 Gradle构建脚本基础 (02:03)

2-11 Gradle构建的生命周期 (08:25)

2-12 Gradle几个重要的角色 (06:22)

2-13 Gradle任务 (04:59)


### 第3章 Gradle插件开发【页面路由项目】

#### 本章将通过页面路由框架开发实战，带你掌握Gradle插件的开发流程，建立页面路由框架的Gradle插件工程。
3-1 本章介绍 (01:00)

3-2 Gradle插件是什么 (02:11)

3-3 插件的分类与二进制插件的使用方法【如何使用插件】 (05:57)

3-4 脚本插件的使用方法【如何使用插件】 (03:08)

3-5 Gradle插件的开发流程 (01:53)

3-6 页面路由框架-Gradle插件功能梳理 (04:10)

3-7 实战：插件工程建立 (12:09)

3-8 实战：实现参数配置 (09:31)

3-9 实战：发布与使用插件-1 (09:11)

3-10 实战：发布与使用插件-2 (07:22)


### 第4章 APT采集页面路由信息【页面路由项目】 

#### 本章将带你剖析APT技术原理及APT开发流程，还会结合编译时注解处理技术，为页面路由组件添加页面信息采集的能力。
4-1 APT是什么 (06:28)

4-2 APT技术原理&开发流程 (03:37)

4-3 页面路由框架-功能梳理 (07:16)

4-4 实战：注解工程的建立&注解的定义&注解的使用 (16:40)

4-5 实战：注解处理器工程的建立 (07:04)

4-6 实战：采集注解【注解处理器实现】 (10:30)

4-7 实战：注册注解处理器【注解处理器实现】 (12:07)

4-8 实战：生成类-类信息拼接【注解处理器实现】 (14:29)

4-9 实战：生成类-类信息写入本地文件【注解处理器实现】 (09:51)

4-10 实战：发布与使用-1 (17:23)

4-11 实战：发布与使用-2 (08:05)

4-12 页面路由框架如何支持参数自动注入？

4-13 页面路由框架如何支持前置逻辑处理？

4-14 页面路由框架如何支持打开更多页面类型？


### 第5章 为Gradle插件添加文档生成功能【页面路由项目】

#### 本章将继续页面路由框架开发，完成Gradle插件最后开发，为页面路由框架实现文档生成能力。
5-1 本章介绍&功能梳理 (02:28)

5-2 实战：实现思路分析 (02:28)

5-3 实战：传递路径信息 (12:20)

5-4 实战：生成JSON文件 (16:30)

5-5 实战：自动传递路径参数到注解处理器中 (06:56)

5-6 实战：实现旧的构建产物自动清理 (03:05)

5-7 实战：汇总生成页面文档 (14:27)


### 第6章 字节码插桩实现路由组件自动注册【页面路由项目】

#### 本章继续实现页面路由项目，为了避免人工注册存在的问题，引入字节码插桩技术，实现路由映射表的自动注册功能。
6-1 本章介绍&字节码插桩基础 (02:14)

6-2 使用场景 (02:50)

6-3 技术原理 (02:25)

6-4 功能梳理【页面路由框架】 (02:17)

6-5 实战：创建类结构【实现Transform】 (07:43)

6-6 实战：实现类的拷贝逻辑【实现Transform】 (12:26)

6-7 实战：模拟添加一个子工程【收集目标类】 (09:54)

6-8 实战：完成映射表类名的收集与打印【收集目标类】 (16:53)

6-9 实战：规划目标类的结构【生成汇总映射表】 (07:54)

6-10 实战：引入插件【生成汇总映射表】 (04:16)

6-11 实战：编写生成字节码的逻辑【生成汇总映射表】 (15:31)

6-12 实战：字节码写入本地文件【生成汇总映射表】 (09:31)


### 第7章 运行时功能的实现【页面路由项目】

#### 本章将从建立工程开始到目标页面的查找，功能测试，最后发布为AAR，带你实现页面路由组件在运行期间的处理逻辑。
7-1 本章介绍&功能梳理 (02:06)

7-2 实战：建立工程 (02:13)

7-3 实战：实现初始化逻辑 (11:16)

7-4 实战：目标页面的查找 (08:45)

7-5 实战：参数解析与打开Activity (05:24)

7-6 实战：进行功能测试 (09:13)

7-7 实战：发布为AAR (03:27)


### 第8章 Android开发工作流-从工程建立到应用发布

#### 本章将从工程建立到应用发布带你掌握Android开发整体工作流程，包含依赖库引用、代码混淆等常用技能。
8-1 本章导学 (04:01)

8-2 企业级Android开发流程 (08:00)

8-3 Android开发三剑客【基础巩固】 (09:37)

8-4 建立工程【基础巩固】 (16:49)

8-5 工程的参数配置 (10:48)

8-6 代码编写运行调试 (07:48)

8-7 本地&远程引用第三方库 (10:16)

8-8 多项目构建运行 (09:25)

8-9 为什么会产生方法数65535的错误 (05:44)

8-10 使用MultiDex突破方法数65535的限制 (12:50)

8-11 代码混淆 (18:13)

8-12 APK签名 (12:17)

8-13 定制不同的APK (10:26)

8-14 多渠道打包 (22:22)


### 第9章 Android应用构建实用技能

#### 本章将带你掌握Android日常高频实用的构建技巧，包含依赖库的管理技巧、构建速度优化、安装包大小优化、APK逆向等。
9-1 本章介绍&构建脚本的管理技巧 (16:11)

9-2 依赖库的管理技巧 (12:17)

9-3 BuildConfig正确使用姿势 (09:28)

9-4 构建速度优化 (10:14)

9-5 APK逆向入门 (10:39)

9-6 安装包大小优化思路 (07:01)


### 第10章 Android应用构建原理

#### 本章将从安装包结构出发，带你掌握安装包构建的整个工作流程，并基于Android构建原理，自研Demo实现代码热修复，将构建技能落地到生产实践中。
10-1 本章介绍&安装包结构解析 (04:23)

10-2 了解构建流程 (06:36)

10-3 探究资源编译流程 (14:13)

10-4 探究代码编译流程 (07:11)

10-5 基于构建技术理解热修复原理 (07:12)

10-6 实战：基础代码准备【自研代码实现热修复】 (05:59)

10-7 实战：生成补丁包【自研代码实现热修复】 (06:25)

10-8 实战：添加反射工具类【自研代码实现热修复】 (09:39)

10-9 实战：实现注入逻辑【自研代码实现热修复】 (19:51)

10-10 实战：效果展示【自研代码实现热修复】 (06:57)

10-11 构建技术的应用场景

10-12 寻找最适合你们团队的热修复方案


### 第11章 课程总结

#### 本章将带你回顾总结课程重点难点，在课程问答区老师等着与你进一步交流，有问题欢迎大家到课程问答区提问。
11-1 课程总结 (09:45)

11-2 技能拓展


[下载地址](https://51xueit.vip "下载地址")
