# [首页查询更多项目](https://github.com/GraduationProject-ssm) 包安装运行


# 11086ssm疫情之下社区管理系统

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1Kp48e9EtU?p=128)


﻿



**　　　　


毕业设计



|**题    目：**|**疫情之下社区管理系统**|
| - | :-: |
|||
|**作    者：**||
|**学   号：**||
|**所属学院：**||
|**专业年级：**||
|**学校导师：**||**职  称：**||
|**班级导师：**||**职  称：**||
|**完成时间：**||

**目    录**

[摘  要	I](#_Toc55328682)

[**Abstract**	II](#_Toc55328683)

[第1章  前  言	3](#_Toc55328684)

[1.1  研究背景	3](#_Toc55328685)

[1.2  研究现状	3](#_Toc55328686)

[1.3研究内容	3](#_Toc55328687)

[第2章  系统开发环境	5](#_Toc55328688)

[2.1 java技术	5](#_Toc55328689)

[2.2 Mysql数据库	6](#_Toc55328690)

[2.3 B/S结构	7](#_Toc55328691)

[2.4 SSM框架	7](#_Toc55328691)

[第3章  需求分析	9](#_Toc55328693)

[3.1  需求分析	9](#_Toc55328694)

[3.2  系统可行性分析	9](#_Toc55328695)

[3.3  项目设计目标与原则	9](#_Toc55328696)

[3.4  系统流程分析	10](#_Toc55328697)

[第4章  架构设计	12](#_Toc55328698)

[4.1  系统体系结构	12](#_Toc55328699)

[4.2  数据库实体设计	13](#_Toc55328700)

[4.3  数据库表设计	15](#_Toc55328701)

[第5章  系统实现	17](#_Toc55328702)

[5.1  登录	17](#_Toc55328703)

[5.2  管理员功能模块	19](#_Toc55328704)

[5.3  用户后台功能模块	19](#_Toc55328704)

[5.4  社区人员后台功能模块	19](#_Toc55328704)

[第6章  系统测试	23](#_Toc55328705)

[6.1  测试目的	23](#_Toc55328706)

[6.2  测试方法	23](#_Toc55328707)

[6.3  功能测试	24](#_Toc55328708)

[6.4  测试结论	25](#_Toc55328709)

[第7章 结  论	26](#_Toc55328710)

[参考文献	27](#_Toc55328711)

[致  谢	28](#_Toc55328712)




**摘  要**

2020年是非常特殊的一年 受新型冠状病毒肺炎的影响 我们的生活、工作 学习等等都发生了很大的改变 ，疫情防控需要大家共同努力、团结对社区管理进行了新型冠状病毒肺炎防控知识普及和宣传教育，通过社区公告栏、楼道张贴宣传单、社区每日循环广播、社区微信群等多种形式，从个人防护知识、居家防护知识、外出公共场所防护知识、新型冠状病毒肺炎医学知识、就医流程五个方面，有针对性地向用户普及了防疫知识。充分做到疫情防控人人知晓、人人参与认识病毒的可怕，最好方式就是建立疫情之下社区管理系统信息，并对其进行管理。 

系统采用了Java技术，将所有业务模块采用以浏览器交互的模式，选择MySQL作为系统的数据库，开发工具选择My eclipse来进行系统的设计。基本实现了疫情之下社区管理系统应有的主要功能模块，本系统有管理员、用户、社区人员。主要权限管理员：首页、个人中心、用户管理、社区人员管理、健康打卡管理、日常需求管理、意见栏管理。用户权限；首页、个人中心、健康打卡管理、日常需求管理、意见栏管理等。社区人员：首页、个人中心、用户管理、健康打卡管理、日常需求管理、意见栏管理等操作。

对系统进行测试后，改善了程序逻辑和代码。同时确保系统中所有的程序都能正常运行，所有的功能都能操作，并且该系统有很好的操作体验，实现了对于管理员和用户管理政府部门双赢。

关键词：疫情之下社区管理系统；SSM框架 ;Mysql数据库；Java语言 





**Abstract**

2020 is a very special year. Our lives and work are affected by New Coronavirus pneumonia. Great changes have taken place in learning and so on. We need to work together to prevent and control the epidemic. We have carried out the popularization and education of New Coronavirus pneumonia prevention and control through community bulletin boards, billboards in the corridor, community daily circular broadcast, community WeChat group and so on. The knowledge of epidemic prevention was popularized from five aspects, namely, knowledge, knowledge of New Coronavirus pneumonia, and process of seeking medical advice. The best way to fully realize that everyone knows and participates in the prevention and control of the epidemic is to establish and manage the information of the community management system under the epidemic situation.

The system uses Java technology, uses browser interaction mode for all business modules, selects MySQL as the database of the system, and selects my eclipse as the development tool to design the system. The main functional modules of the community management system under the epidemic situation are basically realized. The system includes administrators, users and community personnel. Main authority administrator: home page, personal center, user management, community personnel management, health punch management, daily demand management, opinion bar management. User rights; home page, personal center, health punch management, daily demand management, opinion bar management, etc. Community staff: home page, personal center, user management, health punch management, daily demand management, opinion bar management and other operations.

After testing the system, the program logic and code are improved. At the same time to ensure that all the programs in the system can run normally, all the functions can be operated, and the system has a good operating experience, to achieve a win-win situation for administrators and user management government departments.

Key words: community management system under epidemic situation; SSM framework; MySQL database; Java language

**第1章  前  言**

1.1  研究背景

由于新冠病毒突然其来给社区带来压力增大，社区用户的防疫知识还没有得到普及，用户也不知如何应对，在政府在大力支持下，让有需要的用户得到政府部门和小区社区部门的悉心照顾。

近年来，随着我国经济的不断发展，网络平台的管理制度越来越多。每个社区也都将通过计算机进行整体智能化操作，对于社区管理功能所牵扯的数据都是通过用户进行管理相关的数据信息内容、并且管理员可以进行在线处理社区发生的问题，可以通过系统进行分配，传统的防疫方式信息已经无法满足用户的需求。为此开发了本疫情之下社区管理系统 ，为用户提供一个基于疫情之下社区管理系统管理 ，同时方便管理员在线了解情况，管理员通过系统查看用户管理、社区人员、健康打卡、日常需求、意见栏等详细情况进行操作。该系统满足了用户对疫情之下社区管理系统信息获取的需求，并且信息可以及时、准确、有效地进行查看并且系统化、标准化和有效的工作。
## 1.2研究现状
随着社会的发展和科学技术的进步，互联网技术越来越受欢迎。网络传播的生活方式逐渐受到广大人民群众的喜爱。越来越多的互联网爱好者开始在互联网上满足他们的基本需求，同时逐渐进入各个用户的生活起居。互联网具有许多优点，例如便利性，速度，高效率和低成本。因此，类似于疫情之下社区管理系统 ，满足用户工作繁忙的需求，不仅是方便用户随时查看信息的途径，而且还能提高管理效率。

本文首先以社区管理过程的基本问题作为研究对象。在开发系统之前，我们对现有状况进行了详细的调查和分析。最后，我们利用计算机技术开发了一套完整合适的疫情之下社区管理系统，该系统的实现主要优势是：该系统主要采用计算机技术开发，它方便快捷；系统可以通过管理员界面查看用户的所有信息管理。

疫情之下社区管理系统管理系统软件是一款方便、快捷、实用的信息服务查询软件。随着智能网络在全球市场的不断普及以及各种智能平台的使用，系统的开发与人们的日常需求相关，作为中国主流智能的技术开发系统，自然需要这样的软件来满足更多用户的需求和体验。

1.3研究内容

疫情之下社区管理系统的开发及实现，所需要的工作内容：

（1）首先是确定选题，确定好所要做的系统，并对系统的背景及现在面临的一些问题等进行系统的初步确认。

（2）系统确认完成后，结合系统开发的需求进行确认系统开发所使用的技术，本疫情之下社区管理系统的开发使用JAVA技术，数据库进行平台的搭建开发，确认好使用的技术进行技术分析，所使用的技术是否可以完成疫情之下社区管理系统的实现。

（3）确定好系统使用的技术，进行在线确认系统所划分的用户角色，并且根据用户角色划分确定所要设计的功能模块，对于小程序疫情之下社区管理系统的设计主要划分别为管理员和用户、社区人员三个角色，并所使用的功能模块也相应不同，但是系统的数据库实现的内容是交互的，用户可以随时根据自己的需求进行查看疫情信息，对于系统工作人员可以根据自己的分管内容进行在线信息的处理及操作，管理员获取到所有用户的详细数据信息，并根据需求进行第一时间处理解决。

（4）系统的功能模块确认完成后进行程序及界面的设计，设计完成后，并且通过测试来判断程序是否完善，对于系统测试，需要不同的用户进行不同的内容编辑及提交，及使用不同的测试方式找出程序中存在的漏洞，并对程序出现的漏洞问题进行在线解决处理，如果测试系统没有任何问题时，可以将系统上传进行正式操作使用。

**第2章  系统开发环境**
## 2.1 JAVA简介
Java主要采用CORBA技术和安全模型，可以在互联网应用的数据保护。它还提供了对EJB（Enterprise JavaBeans）的全面支持，java servlet API，java（java server pages），和XML技术。JAVA语言是一种面向对象的语言，它通过提供最基本的方法来完成指定的任务，开发者只需要知道一些概念就能够编写出一些应用程序。Java程序相对较小，其代码能够在小机器上运行。Java是一种计算机编程语言，具有封装、继承和多态性三个主要特性，广泛应用于企业Web应用程序开发和移动应用程序开发。

Java语言和一般编译器以及直译的区别在于，Java首先将源代码转换为字节码，然后将其转换为JVM的可执行文件，JVM可以在各种不同的JVM上运行。因此，实现了它的跨平台特性。虽然这使得Java在早期非常缓慢，但是随着Java的开发，它已经得到了改进。
## 2.2 MySql数据库
Mysql的语言是非结构化的，用户可以在数据上进行工作。MySQL因为其速度、可靠性和适应性而备受关注。大多数人都认为在不需要[事务](https://baike.baidu.com/item/%E4%BA%8B%E5%8A%A1)化处理的情况下，MySQL是管理内容最好的选择。并且因为Mysql的语言和结构比较简单，但是功能和存储信息量很强大，所以得到了普遍的应用。

Mysql数据库在编程过程中的作用是很广泛的，为用户进行数据查询带来了的方便。Mysql数据库的应用因其灵活性强，功能强大，所以在实现某功能时只需要一小段代码，而不像其他程序需要编写大段代码。总体来说，Mysql数据库的语言相对要简洁很多。 

数据流程分析主要就是数据存储的储藏室，它是在计算机上进行的，而不是现实中的储藏室。数据的存放是按固定格式，而不是无序的，其定义就是：长期有固定格式，可以共享的存储在计算机存储器上。数据库管理主要是数据存储、修改和增加以及数据表的建立。为了保证系统数据的正常运行，一些有能力的处理者可以进行管理而不需要专业的人来处理。数据表的建立，可以对数据表中的数据进行调整，数据的重新组合及重新构造，保证数据的安全性。介于数据库的功能强大等特点，本系统的开发主要应用了Mysql进行对数据的管理。
#########
### 2.3  B/S架构 
B/S结构的特点也非常多，例如在很多浏览器中都可以做出信号请求。并且可以适当的减轻用户的工作量，通过对客户端安装或者是配置少量的运行软件就能够逐步减少用户的工作量，这些功能的操作主要是由服务器来进行控制的，由于该软件的技术不断成熟，最主要的特点就是与浏览器相互配合为软件开发带来了极大的便利，不仅能够减少开发成本，还能够不断加强系统的软件功能，层层相互独立和展现层是该B/S结构完成相互连接的主要特性。

## 2.4 SSM三大框架
1.Spring的优势:
通过Spring的IOC特性，将对象之间的依赖关系交给了Spring控制，方便解耦，简化了开发。

2.Spring MVC的优势:
SpringMVC是使用了MVC设计思想的轻量级web框架，对web层进行解耦，使我们的开发更简洁。

3.Mybatis的优势:

数据库的操作(sql)采用xml文件配置，解除了sql和代码的耦合，提供映射标签，支持对象和和数据库orm字段关系的映射，支持对象关系映射标签，支持对象关系的组建提供了xml标签，支持动态的sql。

**第3章  需求分析**

3.1  需求分析

开发系统的过程中，去调查用户的功能诉求，对需要存在的功能进行需求分析是特别重要的，且对于系统的开发有着实际的意义，设计疫情之下社区管理系统通过对用户的需求进行分析，结合实际情况进行开发研究，对用户的所有需求做出一个完整的基本的框架，然后一步一步的完成、实现。需求分析可以为系统的开发提供一个目标，只有按照这个目标进行开发设计，才能进行完整的开发，这样设计出的系统才有使用的意义，才能在竞争激烈的软件市场中生存，才能真正的帮助人们解决问题，提高实际的效率。

3.2  系统可行性分析

3.2.1 技术可行性

本系统采取的是目前应用最广泛的程序进行技术的支持，主要的技术支持是java语言，他作为一个相当成熟的语言程序，在众多的软件开发中起着很大作用。而且用java语言编辑出来程序可以直接运行，不需要借助其他的翻译器进行翻译。所以在技术方面是完全可以行的。

3.2.2 经济可行性

本项目开发的初衷就是为了节约，因为系统开发的所有过程都是我自己开发的，而且在开发过程使用到的技术也都是市面上常见的容易操作的，所以不需要请专业的人士花资金来进行系统的开发，而且在项目开发的过程中我也学到了更多的知识。开发的这个软件可以在网络中进行免费的下载，对计算机的软硬件没有很高的要求，因此这个项目是非常实惠的，在经济方面是完全可性的。

3.2.3 操作可行性

操作可行性也就是系统的可用性，一个系统的操作是否容易决定着这个系统的使用度，在系统的操作方面的设计我都是采取简洁易懂的方式，操作的整个菜单界面整齐有序，所有的功能都有序的排列，不会出现重叠或者需要转换的现象，用户想要哪方面的操作都可以直接进行操作，所以该系统任何人都可以进行操作，不需要有相关专业的技术这样用户在操作起来就容易很多。

3.3  项目设计目标与原则

1、关于疫情之下社区管理系统的基本要求

（1）功能要求：管理员：首页、个人中心、用户管理、社区人员管理、健康打卡管理、日常需求管理、意见栏管理。

社区人员：首页、个人中心、用户管理、健康打卡管理、日常需求管理、意见栏管理  

用户权限；首页、个人中心、健康打卡管理、日常需求管理、意见栏管理等功能模块。

（2）性能：因为疫情之下社区管理系统管理中有很多的信息需要存储，因此对于系统的存储量有很大的要求，需要有一个强大的数据库的支持才能确保所有的信息都能安全稳定的进行存储。

（3）安全与保密要求：用户都必须注册、登录才能进入系统。

（4）环境要求：支持Windows系列、Vista系统等多种操作系统使用。

2、设计原则

本疫情之下社区管理系统采用java技术，Mysql数据库开发，充分保证了系统稳定性、完整性。 

（1）系统响应效率：由于是疫情之下社区管理系统，因此就需要系统的响应效率是非常高的，并且可以支持很多人同时进行系统的使用。

（2）界面简洁清晰：系统界面要简单有序，所有的功能一目了然。

（3）储存性高：因为是疫情之下社区管理系统，所以就会在数据库要求上比较严格，信息录入的比较多，而且丰富复杂， 这就需要一个强大的数据库来存放更多的数据和保证数据的时时性。

（4）易学性：系统的设计一定要简单，使得用户使用起来非常好的顺手。

（5）稳定性需求：该系统在使用过程中必须保持稳定，不要出现卡顿、模糊等情况。

（6）稳定性：由于是疫情之下社区管理系统，因此系统运行必须要十分的稳定。

3.4  系统流程分析

用户需要拥有属于自己的账号和密码，且必须正确，这样才能顺利登录到系统中。进入网站后，用户可以自行填写个人信息、健康打卡、、日常需求、、意见栏等等。，在自己需要的信息的进行填写，可以直接在系统中进行操作。具体流程如下图3-2所示：

![](/md/blog.001.png)

图3-2 用户操作流程图

为了保证系统的安全性，要使用本系统对系统信息进行管理，必须先登陆到系统中。其具体登录流程图如图3-3所示：

![](/md/blog.002.png)

图3-3 系统操作流程图

**第4章  架构设计**

4.1  系统体系结构

疫情之下社区管理系统的结构图4-1所示：

网

络

管理员

服务器和程序

用户管理

用户管理

![](/md/blog.003.png)![](/md/blog.004.png)

图4-1 系统结构

登录系统结构图，如图4-2所示：

疫情之下社区管理系统

用户登录

密码正确

管理员界面

用户界面

管理员界面
![](/md/blog.005.png)

图4-2 登录结构图

系统结构图，如图4-3所示：

![](/md/blog.006.png)

图4-3 系统结构图

**4.2  数据库实体设计**

数据库的功能就是对系统中所有的数据进行存储和管理。所有的数据可以在数据库中产时间的进行存储，方便用户的使用。而且所有的数据库中的数据也应该具有一定的共享性，任何的系统可以对一些数据进行使用，同时还应该保持一定的独立性，每一个数据库中的数据都有很强的安全性，可以被很好的存放到数据库，没有进行身份的验证是不能对这些数据进行查看和使用的。数据库的设计需要明确每一个实体之间的联系，系统的E-R图如下图所示：：

管理员实体主要存储管理信息包括用户名、密码、角色。管理员信息属性图如图4-5所示。

![](/md/blog.007.png)

图4-5 管理员信息实体属性图

用户管理：用户账号、用户姓名、密码、籍贯、性别、年龄、联系电话、电子邮箱、家庭住址实体图如图4-6所示：

![](/md/blog.008.png)

图4-6用户管理实体图
#########
社区人员：社区账号、姓名、密码、性别、年龄、职务、联系电话、身份证、家庭地址体图如图4-7所示：

![](/md/blog.009.png)

图4-7社区人员实体图

**4.3  数据库表设计**

当疫情之下社区管理系统在运行的时候，数据库要能确保自己的独立性，想要哪部分的数据就选择相应的设置选项，对应的数据就会以表格的形式展现出来。当对这一个功能进行设置，他就会与数据库进行连接，会在对话框中弹出相应的数据源。


` `allusers表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|username||150||255||
|3|pwd||150||255||
|4|cx||150||255||
|5|addtime|DateTime|8||19||

jiankangdaka表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|addtime||150||255||
|3|yonghuzhanghao||150||255||
|4|yonghuxingming|DateTime|8||255||
|5|tiwen||150||255||
|6|shentishifoubushi|DateTime|8||255||
|7|tiwenshifouzhengchang||150||255||
|8|jiarenzhongshifouyourenquezhenxinguanfeiyan|DateTime|8||255||
|9|beizhu||150||255||
|10|dengjishijian|DateTime|8||255||

richangxuqiu表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|addtime||150||255||
|3|yonghuzhanghao||150||255||
|4|yonghuxingming|DateTime|8||255||
|5|jiatingzhuzhi||150||255||
|6|jialichengyuanrenshu|DateTime|8||255||
|7|xuqiuxiangxi||150||255||
|8|tijiaoshijian|DateTime|8||255||
|9|sfsh||150||255||
|18|shhf||150||||

shequrenyuan表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|addtime||150||255||
|4|shequzhanghao||150||255||
|5|xingming||150||255||
|6|mima|DateTime|8||||
|7|xingbie|||8|||
|8|nianling|DateTime|8||255||
|9|zhiwu||||||
|10|lianxidianhua|DateTime|8||255||
|11|`	`shenfenzheng||||||
|12|jiatingdizhi|DateTime|8||255||

yijianlan表:

|序号|字段名称|字段类型|大小|允许为空|最大长度|备注|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|1|id|Int|4||10||
|2|addtime||150||255||
|4|bianhao||150||255||
|5|yonghuzhanghao||150||255||
|6|yonghuxingming|DateTime|8||||
|7|jianyifankui|DateTime|||||
|8|tijiaoshijian||||||
|9|sfsh||DateTime|8|||
|10|shhf||DateTime|8|||












第5章  系统实现
## **5.1 登录**
管理员输入个人的账号、密码、角色登录系统，这时候系统的数据库就会在进行查找相关的信息，如果我们输入的账号、密码不正确，数据库就会提示出错误的信息提示，同时会提示管理员重新输入自己的账号、密码，直到账号密码输入成功后，会提登录成功的信息。网站管理员登录效果图如图5-1所示：

![](/md/blog.010.png)     
图5-1登录界面
## **5.2  管理员功能模块**
### **5.2.1 个人信息**
管理员对个人中心进行操作填写原密码、新密码、确认密码并进行添加、删除、修改以及查看，程序成效图如下图5-2所示:

![](/md/blog.011.png)

图5-2管理员个人信息界面图
###
### **5.2.2用户管理**
管理员对用户管理进行用户账号、用户姓名、密码、籍贯、性别、年龄、联系电话、电子邮箱、家庭住址等等添加、删除、修改以及查看等操作。程序成效图如下图5-3所示:

![](/md/blog.012.png)

图5-3用户管理界面图
### **5.2.3社区人员**
管理员对社区人员编辑社区账号、姓名、密码、性别、年龄、职务、联系电话、身份证、家庭地址进行添加、删除、修改以及查看等操作。程序效果图如下图5-4所示：

![](/md/blog.013.png)

图5-4社区人员界面
### **5.2.4健康打卡管理**
管理员对健康打卡管理进行添加用户账号、用户姓名、体温、身体是否不适、体温是否正常、家人中是否有人确诊新冠肺炎、备注、登记时间查看、修改以及删除等操作。程序效果图如下图5-5所示：

![](/md/blog.014.png)

图5-5健康打卡管理界面
### **5.2.5日常需求管理**
管理员可以对日常需求管理进行查看编辑用户账号、用户姓名、家庭住址、家里成员人数、需求详细、提交时间、审核回复、审核状态、审核等查看、修改以及删除操作。程序效果图如下图5-6所示：

![](/md/blog.015.png)

图5-6车日常需求管理界面

### **5.2.6意见栏管理**
管理员可以对意见栏管理进行查看编辑编号、用户账号、用户姓名、建议反馈、提交时间、审核回复、审核状态、审核等操作。程序效果图如下图5-7所示：

![](/md/blog.016.png)

图5-7意见栏管理界面
#########
## **5.3 用户后台功能模块**
### **5.3.1 用户注册/登陆**
`   `用户注册/登陆，在用户注册页面通过填写用户账号、用户姓名、密码、籍贯、性别、年龄、联系电话、电子邮箱、家庭住址等信息完成用户注册/登陆。程序成效图如下图5-8所示:

![](/md/blog.017.png)

![](/md/blog.018.png)

图5-8用户注册/登陆界面图
### **5.3.2 用户后台个信息查看**
用户可以对个人信息进行查看编辑用户账号、用户姓名、密码、籍贯、性别、年龄、联系电话、电子邮箱、家庭住址等查看、修改以及删除操作。程序效果图如下图5-9所示：

![](/md/blog.019.png)

图5-9用户信息管理界面

## **5.3.3 健康打卡管理**
用户进入健康打卡管理可以编辑用户账号、用户姓名、体温、身体是否不适、体温是否正常、家人中是否有人确诊新冠肺炎、备注、登记时间，查看添加、删除、上传等操作。程序成效图如下图5-10所示:

![](/md/blog.020.png)

图5-10健康打卡管理界面图

## **5.3.4 日常需求管理**
用户进入日常需求管理可以编辑用户账号、用户姓名、家庭住址、家里成员人数、需求详细、提交时间、详细需求查看添加、删除、上传等操作。程序成效图如下图5-11所示:

![](/md/blog.021.png)

图5-11日常需求管理界面图

## **5.3.5 意见栏管理**
用户进入意见栏管理可以进行编辑编号、用户账号、用户姓名、建议反馈、提交时间操作进行添加/删除、修改等操作。程序成效图如下图5-12所示:

![](/md/blog.022.png)


图5-12意见栏管理界面图

## **5.4 社区人员后台功能模块**
### **5.4.1 社区人员注册/登陆**
`   `社区人员注册/登陆，在社区人员注册页面通过填写社区账号、姓名、密码、性别、年龄、职务、联系电话、身份证、家庭地址等信息完成用户注册/登陆。程序成效图如下图5-13所示:

![](/md/blog.023.png)

![](/md/blog.024.png)

图5-13前台用户注册/登陆界面图
### **5.4.2 社区人员后台个信息查看**
社区人员可以对个人信息进行查看编辑社区账号、姓名、密码、性别、年龄、职务、联系电话、身份证、家庭地址等查看、修改以及删除操作。程序效果图如下图5-14所示：

![](/md/blog.025.png)

图5-14社区人员信息管理界面

## **5.4.3 健康打卡管理**
社区人员进入健康打卡管理可以编辑用户账号、用户姓名、体温、身体是否不适、体温是否正常、家人中是否有人确诊新冠肺炎、备注、登记时间，查看添加、删除、上传等操作。程序成效图如下图5-14所示:

![](/md/blog.026.png)

![](/md/blog.027.png)

图5-14健康打卡管理界面图

## **5.4.4 日常需求管理**
社区人员进入日常需求管理可以编辑用户账号、用户姓名、家庭住址、家里成员人数、需求详细、提交时间、详细需求查看审核回复等添加、删除、上传等操作。程序成效图如下图5-15所示:

![](/md/blog.028.png)

![](/md/blog.029.png)

图5-15日常需求管理界面图

## **5.4.5 意见栏管理**
社区人员进入意见栏管理可以进行编辑编号、用户账号、用户姓名、建议反馈、提交时间、审核回复、审核状态、审核操作进行添加/删除、修改等操作。程序成效图如下图5-16所示:

![](/md/blog.030.png)


图5-16意见栏管理界面图





第6章  系统测试

6.1  测试目的

随着互联网不断的发展，目前各大领域都利用互联网进行了信息的管理，质量问题是很重要的标准，也决定着是否有更多的人使用。所以软件的质量我们必须要把关，必须要把软件做好，做到位，少出不必要的问题，这样才能有更多的用户使用，并且得到更多的推广。所以，我们在开发完系统后，需要进行大量的测试，以确保系统的稳定性和可使用性，并要确定系统的质量能否做到满足不同人的需求。这是系统在开发设计中非常重要的环节，测试的结果直接关系到系统的好坏。

集成测试：在系统测试当中会出现很多的问题，我们要及时的进行标注并且在进行测试的时候要采取自动化的测试，这样即准确又快速，而且不会出现疲劳，手动的测试很容易出现疲劳期，而且测试的结果也有时候会出错，所以在测试的时候才去自动测试时最好的测试方法。

在测试的过程中及时的发现问题，并且进行问题的解决，这样设计出的系统可以正常稳定的运行，不会出现重大的问题。我所进行的软件测试参照以下三个步骤进行测试：

(1)模块测试：对系统中的每一项都进行针对的测试，发现并找到问题。

(2)系统测试：让系统长时间进行各种情况下的运行，反馈运行期间的稳定性问题并解决。

(3)验收测试：其他测试完成后，最后检测阶段，确保软件准备就绪。

6.2  测试方法

在对系统进行测试的时候我们主要应用到两种测试的方法，通过测试我们就能找出可能存在的问题保证系统成功运行。

从软件的内部构造和具体实施是否有关系的观点来看：黑盒测试和白盒测试。

1）黑盒测试：测试系统功能，当用户进行相应的操作时，系统是否能够及时且准确的反馈数据，并执行相应功能。需要对功能以及使用方法进行详细的测试，保证所有的操作信息都能够完整的输出输入。

2）白盒测试：主要是对系统的结构进行测试，了解系统在运行过程中是否可以正常的工作。

疫情之下社区管理系统的测试也会从下面几方面进行：

(1)窗体测试：例如用户登录界面，在用户名和密码输入时，需要界面窗口弹出，给予用户反馈，我对窗口的设计进行了测试，确保每一个窗口在用户进行相应操作后，能够及时的弹出。

(2)数据跟踪：进行数据跟踪，我们就能知道系统功能是否在顺利的执行当中。将数据库中的相关的信息进行调动，弹出我们需要的相对应的数据信息。同时，在追踪过程中，我们也更容易的发现系统的问题所在，便于解决问题和维护系统。

(3)综合测试：完成上述测试后，需要对系统进行由内而外的重新检测，来宏观的发现系统中存在的问题，并且及时的进行解决，系统的设计要结合实际的使用情况有针对性的进行开发，可以满足不同人的需求。

6.3  功能测试

本疫情之下社区管理系统设计基本达到我理想的开发状态，在各个功能的运行方面，表现较为良好，基本满足用户的使用需求，及时矫正了较多的错误信息。总体说来，软件通过了相应的测试。

表6-1：用户登录测试表

|模块名称|测试用例|预期结果|实际结果|是否通过|
| :-: | :- | :- | :- | :- |
|登录模块|用户名：122   密码：123  |弹出错误提示，提示密码错误|弹出错误提示，提示密码错误|通过|
|登录模块|<p>用户名：123   </p><p>密码：122   </p>|弹出错误提示，提示用户名错误|弹出错误提示，提示用户名错误|通过|
|登录模块|<p>用户名：001   </p><p>密码：001   </p>|管理员登录成功|管理员登录成功|通过|

表6-2：删除健康登记测试表

|模块名称|测试用例|预期结果|实际结果|是否通过|
| :-: | :- | :- | :- | :- |
|删除疫情上报模块|疫情上报名：最新通知  |删除成功、页面自动跳转|删除成功、页面自动跳转|通过|

表6-3：修改密码测试表

|模块名称|测试用例|预期结果|实际结果|是否通过|
| :- | :- | :- | :- | :- |
|修改密码模块|<p>原密码：666</p><p>新密码：123</p><p>确认密码：123  </p>|弹出错误提示，提示原密码错误|弹出错误提示，提示原密码错误|通过|
|修改密码模块|<p>原密码：122   新密码：123</p><p>确认密码：333  </p>|弹出错误提示，提示确认密码不一致|弹出错误提示，提示确认密码不一致|通过|
|修改密码模块|<p>原密码：123  新密码：123</p><p>确认密码：123  </p>|密码修改成功|密码修改成功|通过|

6.4  测试结论

测试的过程要按照指定好的计划一步一步的实行，测试时候一定不要着急，并且将测试的结果进行详细的记录，我们在进行测试的时候做好选择自动化的测试，这样更加的准确也更快捷，如果采用人工测试的方法就不会这么的方便，很可能会出现一些问题，而且极其测试不会疲劳也不会出现问题。在测试的时候一定要非常专注，时刻关注着测试的结果，一旦发现异常及时进行修改，；最后，测试完之后的文档应该保存下来，方便以后测试时用到。

通过测试，我们也可以直观的感受到，在我们最开始进行系统设计的时候，先把思路理清楚，才能有机会把代码写好。有好的逻辑性的代码在后期的测试中才能避免出现问题，也可以给我们节省很多的时间和不必要的操作。

第7章 结  论

` `疫情之下社区管理系统为用户提供了公平的、相互包容的、操作方便的使用系统，基本满足了用户的使用需要，以及我最初的开发目标和方向。Java语言、MySQL数据库等技术时是我开发的基础，这些技术都有各自的优点，学好这些技术，至关重要。通过这些优点设计出来的系统能够正常稳定的运行，并且可以满足人们的所有需求，在对系统的需求以及各个模块进行了详细的分析后，有针对性的进行设计，最后通过测试，系统能够正常的运行，该疫情之下社区管理系统设计完成。

本次开发过程中使用的是Java技术，该技术具有代码编写简单方便，对平台没有要求对技术方面也没有要求，并且有很好的面像对象性，所以在技术方面是相当成熟的。利用java技术作为系统主要的技术支持可以使得系统能够正常的运行并且实现相应的功能。在这次的系统的设计过程中遇到了很多的困难，幸好有老师同学们的帮助，在他们的帮助下完成了这次系统的设计。

通过这次疫情之下社区管理系统的开发，我参考了很多相关系统的例子，取长补短，吸取了其他系统的长处，逐步对该系统进行了完善，但是该系统还是有很多的不足之处，有待以后进一步学习。

实践证明，疫情之下社区管理系统有着非常好的发展前景，经过测试运行，系统各项功能都十分完善，界面漂亮，使用方便，操作容易，在技术理论上已经成熟。
#########
参考文献

[1] 贝伊利 (Lynn Beighley),莫里森 (Michael Morrison),苏金国, 徐阳. Head First Java & MySQL(中文版)[M]. 中国电力出版社,2018,03.

[2] 潘凯华,刘中华, 等. Java开发实战1200例(第1卷)(附DVD-ROM光盘1张)[M].  清华大学出版社,2019,01.

[3] 帕蒂拉(Armando Padilla),霍金斯(Tim Hawkins),盛海艳,刘霞. 高性能Java应用开发[M]. 人们邮电出版社,2019,11.

[4] 陈益材,等. Java+MySQL+Dreamweaver动态网站建设从入门到精通(附多媒体语音教学光盘)[M]. 机械工业出版社,2019,06.

[5] 高洛峰,LAMP兄弟连. 细说Java(精要版)(附DVD光盘1张)[M]. 电子工业出版社,2018,06.

[6] Lorna Mitchell,等. Java精粹:编写高效Java代码[M]. 机械工业出版社,2018,10.

[7] 列旭松,陈文. Java核心技术与最佳实践[M]. 机械工业出版社,2018,07.

[8] Symfon,CakeJava,Zend Bartosz Porebski,Karol Przystalski,Leszek Nowak, 付勇. Java框架高级编程:应用[M]. 清华大学出版社,2017,02.

[9] 波诺赛克 (Boroncxyk.T.),Elizabeth Naramore,薛焱. Web开发入门经典:使用Java6、Apache和MySQL[M]. 清华大学出版社 ,2017,07.

[10] 辛洪郁,张鑫. Java项目开发全程实录(第3版)[M]. 清华大学出版社,2018,11.

[11] 杨宇,等. Java典型模块与项目实战大全(附DVD-ROM光盘1张)[M]. 清华大学出版社,2018,01.

[12] 贾素来．常见动态网页技术比较[J]．大众科技，2018,9.

[13] 西尔伯沙茨(Silberschatz.A.) . 计算机科学丛书：数据库系统概念(原书第6版)[M]. 机械工业出版社,2019,03．.                                                      

[14]萨师煊，王珊．数据库系统概论[M]．北京:高等教育出版社，2018：10-180．

[15]陈刚．Eclipse从入门到精通[M]．(第2版)．北京:清华大学出版社，2018：17-380． 

[16]孙卫琴．精通Struts:基于MVC的Java Web设计与开发[M]．北京:电子工业出版社，2017：19-421



致  谢

光阴似箭，一晃大学生活即将过去了。一直以严谨的态度和积极的热情投身于学习和工作中，虽然有竞争，也有泪水，但是通过我不断学习和奋斗不断的完善自己，不仅很好的完成了我的学业而且也让我的各方面得到了发展，取得了很大的进步。

大学的生活也即将结束，虽然也有许多的不舍，但是终究是要告别的。回想大学的学习生活，有泪水也有汗水。在此期间我严格要求自己，凭着对知识的强烈追求，刻苦钻研，勤奋好学，态度端正，目标明确，牢固的掌握了一些专业知识和技能，做到了理论联系实际。除了专业知识的学习外，我还不断的扩展我的知识面，从不同的领域以不同的方式来获得新的知识。争取成为一名各方面都很合格的大学生。

这次的毕业设计，是我独自完成周期最长，也是耗力最大的一个项目。值得庆幸的是，在我毕业设计完成的过程当中，有许多帮助我的同学和老师。在几个月的开发过程中，我遇到了大大小小无数个问题。是我的舍友和老师，不断地帮助鼓励。

我的指导老师，在自身工作十分繁忙的情况下，依然能做到及时恢复我们发去的问题邮件，并抽时间对我们进行线下的辅导。指出我们设计上的失误，逻辑错误以及学习规划问题，可以说没有导师的帮助，我的毕设会陷入死胡同，是导师为我指点了迷津，像迷雾中的路灯，为我指明方向！


48
![](/md/blog.031.png)











