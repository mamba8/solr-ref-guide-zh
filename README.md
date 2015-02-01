# Apache Solr 官方参考手册4.10（中文版） #
本文档是Apache Solr项目官方参考文档4.10（[Apache Solr Reference Guide 4.10](http://archive.apache.org/dist/lucene/solr/ref-guide/apache-solr-ref-guide-4.10.pdf)）的中文翻译版，旨在方便大家学习和使用Solr，Solr官方手册能够系统完整的介绍Solr的功能，模块介绍得详细可操作，可以了解设计思路和最佳实践，对Solr有更加准确完整的学习和掌握。

对原文档做翻译是为了方便快速入门和查阅，在尊重原文内容的基础上，适当进行了意译和词句调整，使得读起来更通顺易于理解，一些专业词组保留了英文，因为翻译过来反而更难理解，本文档难免有疏漏，欢迎大家提交issue一起完善，有兴趣的同学可以一起参与翻译，在学习和分享中获得进步:)

翻译Solr官方文档的想法，实际上缘于三年前刚学Solr的时候，中文资料少，官方提供的参考手册很详细，当时就有翻译的想法，只不过一直未行动，以为会有人来翻译的，结果两年多了还没有人来翻译，还是自己来完成当初的想法吧。2015，实践最初的想法。

本文档的英文原版可以在[这里](http://archive.apache.org/dist/lucene/solr/ref-guide/apache-solr-ref-guide-4.10.pdf)下载，官方cwiki地址是[这里](https://cwiki.apache.org/confluence/display/solr/Apache+Solr+Reference+Guide)。

当前翻译进度：(24/511)=4%


## 目录 ##

### 0 [说明](solr-ref-guide-zh/0-apache-solr-reference-guide.md) ###
### 1.1 [关于](solr-ref-guide-zh/1.1-about-this-guide.md) ###
### 1.2 [开始使用Solr](solr-ref-guide-zh/1.2.0-getting-started.md) ###
##### 1.2.1 [安装Solr](solr-ref-guide-zh/1.2.1-installing-solr.md) #####
##### 1.2.2 [运行Solr](solr-ref-guide-zh/1.2.2-running-solr.md) #####
##### 1.2.3 [快速总览](solr-ref-guide-zh/1.2.3-a-quick-overview.md) #####
##### 1.2.4 [更进一步](solr-ref-guide-zh/1.2.4-a-step-closer.md) #####
### 1.3 [升级Solr](solr-ref-guide-zh/1.3-upgrading-solr.md) ###
### 1.4 [Solr管理后台](solr-ref-guide-zh/1.4.0-using-the-solr-administration-user-interface.md) ####
#### 1.4.1[Solr管理后台概览](solr-ref-guide-zh/1.4.1-overview-of-the-solr-admin-ui.md) ####
#### 1.4.2[获得帮助](solr-ref-guide-zh/1.4.2-getting-assistance.md) ####
#### 1.4.3[日志](solr-ref-guide-zh/1.4.3-logging.md) ####
#### 1.4.4[Cloud界面](solr-ref-guide-zh/1.4.4-cloud-screens.md) ####
#### 1.4.5[Core Admin](solr-ref-guide-zh/1.4.5-core-admin.md) ####
#### 1.4.6[Java参数](solr-ref-guide-zh/1.4.6-java-properties.md) ####
#### 1.4.7[Thread Dump](solr-ref-guide-zh/1.4.7-thread-dump.md) ####

*1.4.8[Core管理工具](solr-ref-guide-zh/1.4.8.0-core-specific-tools.md)*

### LICENSE
Licensed to the Apache Software Foundation (ASF) under one or more contributor license agreements.  See the NOTICE file distributed with this work for additional information regarding copyright ownership.  The ASF licenses this file to you under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License.  You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the License for the specific language governing permissions and limitations under the License.

### Trademark
Apache and the Apache feather logo are trademarks of The Apache Software Foundation. Apache Lucene, Apache Solr and their respective logos are trademarks of the Apache Software Foundation. Please see the [Apache Trademark Policy](http://www.apache.org/foundation/marks/) for more information.
