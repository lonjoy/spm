## 课程大纲

* 支付宝前端工具 - Maven and spm
* 简介：康辉（花名陆辉，网名 小熊泡泡），支付宝高级前端开发工程师，2010年进入支付宝。主要从事前端基础工具和基础类库方面的工作

* 目录
	* Maven 介绍
	* Maven 在支付宝前端应用架构
	* Maven 基本使用 
	* spm 简单介绍
	* spm 使用
	* spm 架构
	* spm 配置
    * spm 源
    * spm 辅助
	* spm 扩展
	* spm 常见错误解析
* Maven 介绍
	* Maven 核心内容
		* 最核心的几个概念讲解
		* 和 Ant 相关工具对比
		* 提问： Maven 核心概念梳理
	* 本章小结
		* Maven 的核心思想(很关键，很多工具的思路都是从 Maven来的)
* Maven 在支付宝前端应用架构
    * maven-arale-plugin
        * 我们是如何对 Maven 进行插件扩展
        * 简单介绍下有那些插件
    * static-parent Maven 核心配置
        * 配置文件的继承模型
        * 相关配置说明
    * 本章小结
        * Maven 插件的扩展原理
        * 我们整个项目的配置模型
        * 相关插件功能了解
* Maven 基本使用
    * 工作中日常命令介绍
        * mvn clean install
        * mvn clean deploy
        * mvn dependency:tree
        * mvn release:prepare
        * mvn release:perform
    * 本章小结
        * 熟悉相关命令
* spm 简单介绍
    * spm 愿景和基本思想
    * spm 安装
    * spm API
    * 本章小结
       * 可以简单使用 spm
* spm 架构
    * spm 核心模块介绍
        * 核心类功能说明
        * 基本执行流程
    * spm action 和 plugin
        * action 介绍
        * plugin 介绍
    * 本章小结
        * spm 大概的运行原理
* spm 配置
    * spm 配置文件介绍
        * config.json
        * package.json
    * spm 配置文件加载流程
        
    * 本章小结
        * 配置文件种类
        * 配置加载过程
* spm 源
    * 源相关介绍
        * 源的作用
    * 源服务的使用
        * 源的搭建
        * 源服务相关参数简单说明
* spm 辅助功能介绍 
    * spm 几个扩展功能介绍
        * spm transport
        * spm search
        * spm init

* spm 扩展
    * spm 如何扩展自定义功能 

* 参考资料
