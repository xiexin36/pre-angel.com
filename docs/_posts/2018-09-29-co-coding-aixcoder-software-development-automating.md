---
title: “人机结对”来编程，「aiXcoder」要使软件开发自动化
author: aixcoder
categories: news
tags:
  - 36kr
  - ai
image: assets/2018/09-aixcoder-software-development-automating/slide.png
---

> AI驱动，让编程工作智能化

需求多，交付紧，加班久，程序员工作压力大已是不争的事实。然而，尽管工作时间长，程序员的开发效率却并不理想，绝大多数时间为机械化编程规则、debug以及惯用模式调用等拖累。现今人力成本越来越高，有没有什么工具能够让写代码这件事儿更加智能化呢？

近期，36氪接触到一家公司「硅心科技」，**运用深度学习等技术研发了一款智能编程机器人产品aiXcoder，希望实现以人工智能驱动的自动化软件开发模式。**

aiXcoder当前版本包含两个功能：代码自动补全和相似代码智能推荐。程序员写代码时，AI引擎会进行预测并自动补全后续代码。同时，aiXcoder会基于程序员输入的代码，从后台规范代码库中调用相似的代码，在分屏中显示以供程序员参考。

![AIxCoder](/assets/2018/09-aixcoder-software-development-automating/aixcoder.gif)

“人机结对”来编程，「aiXcoder」要使软件开发自动化

区别于IDE中自带的基于编程语法进行提示，aiXcoder是基于语义进行代码生成补全。aiXcoder 采用专门应用程序分析和生成了特定的深度神经网络模型，再用海量数据集训练，以aiXcoder的tensorflow版本为例，后台就使用了22万份代码以及35万份tensor flow代码来训练引擎。这样一来，得aiXcoder能学习和掌握隐藏在海量代码中的编码模式，从而提升代码预测精度。

据悉，在最近一次标准化对比测试中，aiXcoder和2018年人工智能顶会IJCAI上发布的最新成果对比，在代码补全人物中的推荐准确率比该成果高出近10个百分点。

除了上述功能，开发者也可以用自有代码训练自己的专属aiXcoder。日常编程工作中，aiXcoder能自动记录程序员常用的程序模式、API调用序列等，从而对引擎进行训练。李戈提到：借由aiXcoder,程序员可以节约原本需要上网搜索相似代码和搜索API使用模式的时间，从而投入更多时间在编写特定系统所需要的特定代码上，提升创造性和个人价值。

明年，硅心科技将在代码测试方面落地，实现代码测试用例自动生成的新功能。

“人机结对”来编程，「aiXcoder」要使软件开发自动化

商业上，当前硅心科技主要基于企业内部云来提供专业领域的定制化服务：已经与华为展开合作，提供支持Android开发的IntelliJ、Eclipse、VS Codes客户端；为百度提供Paddle Paddle客户端；为软通动力提供Android外包项目专用客户端；为阿里巴巴提供专用开发客户端。

目前，项目仍属于早期阶段，与企业用户合作一方面可以在一定条件下调用企业代码库，有足量数据集来训练引擎，另一方面也更能切中企业开发中效率低、流程长等痛点。但是硅心科技却希望在未来将服务提供给C端用户。

李戈表示：硅心科技希望能够面向C端，从拥有企业级用户出发，进一步推广至程序员个人，从而构建程序员社区，将aiXcoder服务覆盖到软件行业更多从业者。最终，硅心科技希望能够实现支持普通人自然语言交互生成模式，实现人工智能帮助普通人构造软件的新生态。

在就如何获客这一问题，李戈告诉36氪：除与企业合作外，公司也在尝试利用程序员社区进行推广。开发者可以通过Github账号登陆aiXcoder客户端，aiXcoder可调用登录用户Github中所有Star过的代码（即该用户点赞过的代码），用来训练引擎。如果Star代码是引用自他人，aiXcoder会通知相应开发者，并提供给他们客户端链接，这样他们便可以查阅aiXcoder的训练成果并进行产品试用，以此形成传播效应。

硅心科技创始团队来自北京大学高可信软件技术教育部重点实验室，创始人李戈是北大信息科学技术学院软件所副教授，国家重点研发计划程序生成/补全课题组负责人，曾任斯坦福大学AI实验室吴恩达团队访问学者；COO刘洋为北大计算机硕士，曾就职于朗讯、黑莓；CTO郝逸洋为早稻田大学硕士，北大本科，曾就职于微软亚洲工程院。

硅心科技已获得伽利略资本天使轮融资，目前在进行pre-A轮融资，也在寻求商务方面人才，希望能够帮助产品进行获客推广等。

> 郑铟, [36Kr](https://36kr.com/p/5155140)