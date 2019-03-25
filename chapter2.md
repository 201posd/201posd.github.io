# Chapter 2

## Principle 1 ：quality is \#1
> A customer will not tolerate a product with poor quality, regardless of the definition of quality. Quality must be quantified and mechanisms put into place to motivate and reward its achievement. It may seem politically correct to deliver a product on time, even though its quality is poor, but it is politically correct in the short term only；it is political suicide in the  middle and long term. There is no trade-off to be made. The first requirement must be quality. Edward Yourdom suggests that you "Just say no" when you're asked to speed up testing, ignore a few bugs, or code before agreeing on a design or a set of requirements.
### 原则1：质量第一  
无论对于质量的定义如何，用户都不会容忍质量差的产品。我们必须量化质量并建立机制以激励和奖励高质量的成果。有时候看起来即使软件质量很差，但是能按时交付似乎是正确的。虽然在短期内它似乎是正确的，但是中长期来说这就是自杀。质量是不应该被权衡取舍的。第一个要求必须是质量。 Edward Yourdon 建议你面对以下情况时 "当你被要求加速测试而忽略一些错误代码，或者在你还没有同意设计或一系列需求之前就开始写代码" 时，说” 不！“。

## Principle 2：quality is in the eyes of the beholder
> There is no one definition of software quality. To developers, it might be an elegant design or elegant code. To users who work in stress environments, it might be response time or high capacity. For cost-sensitive projects, it might be low development cost. For some customers, it might be satisfying all their perceived and not-yet-perceived needs. The dilemma is that these may not be all compatible. Optimizing one person'quality might be detrimental to another's. (This is Weinberg's Political Dilemma principle) A project must decide on its priorities and articulate them to all parties.
### 原则2：质量是旁观者的眼睛  
软件质量没有一个明确定义。对于开发人员来说，高的质量可能是优雅的设计或优雅的代码。但是对于在一些压力环境中工作的用户，他们可能希望高质量是快速的响应时间或高的容量。而对于成本敏感的项目，高质量可能是低开发成本。对于用户来说，高质量的软件可能满足所有他们感知到的和尚未感知到的需求。但是有个困境就是，不可能完全满足所有用户的需求。当我们优化一个人的关注的质量问题时，可能会影响其他人的。（这是温伯格的 “政治困境” 原则。）所以，一个项目必须决定其质量标准的优先级，并向所有各方表达这一事项。

## Principle 3：productivity and quality are inseparable
> There is a clear relationship between productivity(measured by numbers of widgits--whether they be lines of code or function points--per person-month) and quality. The higher the demand for quality, the lower your productivity becomes. The lower the demand for quality, the higher your productivity becomes. The more you emphasize increased productivity, the lower your resulting quality. Bell Labs has found that, to achieve one to two bugs per thousand lines of code, productivities of 150 to 300 lines of code per person-month are common . As attempts are made to drive productivity up, the density of bugs increases.
### 原则3：生产力和质量是不可分割的  
生产力之间存在明显的关系（通过 widgits 的数量来衡量 - 每个人每月提交的代码行或者功能点 ）和质量。对质量的要求越高，生产力就越低。对质量的要求越低，生产力就越高。您越是强调提高生产力，您的质量就越低。贝尔实验室发现，为了达到每千行代码一到两个漏洞，每人每月 150 到 300 行代码的生产率是常见的 [参见 Fleckenstein，W，“软件开发中的挑战”，IEEE 计算机，16， 3（1983 年 3 月），Pp 60-64]。当试图提高生产率时，千行代码的 Bug 数增加。


## Principle 4: high-quality software is possible
> Although our industry is saturated with examples of software systems that perform poorly, that are full of bugs, or that otherwise fail to satisfy users’ needs, there are counter examples.large-scale software systems can be built with very high quality, but for a steep price tag: on the order of $1000 per line of code. One such example is IBMS on-board flight software for NASAS space shuttle. Totaling approximately three million lines of code,the rigorous software development process resulted in less than one error found per ten thousand lines of code after product release.
As a developer, be aware of the techniques that have been demon-strated to increase quality considerably. These include involving the customer(Principle 8), prototyping(to verify requirements prior to full-scale development; Principles 11 through 13), keeping the design simple (Principle 67), inspections(Principle 98), and hiring the best people ( Principles 130 and 131). As a customer, demand excellence but be aware of the high costs involved

### 原则4：高质量的软件是可能的  
尽管我们的行业充斥着性能差，漏洞多更甚者无法满足用户需求的软件例子，但也有反例。大型软件系统可以以非常高的质量构建，但价格昂贵：每行代码 1000 美元。一个这样的例子是用于 NASAS 航天飞机的 IBMS 机载飞行软件。总共约 300 万行代码，严格的软件开发过程导致产品发布后每万行代码中发现的错误少于一个。
作为开发人员，需要注意极大提高软件质量被证明是可能的。这些包括涉及客户（原则 8），原型设计（在全面开发之前验证要求；原则 11 至 13），保持设计简单（原则 67），校验检查（原则 98）和雇用最优秀的人员（原则） 130 和 131）。作为客户，需求卓越，但要注意所涉及的高成本。

## Principle 5: don’t try to retrofit quality
> Quality cannot be retrofit into software .This applies to any definition of quality: maintainability, reliability, adaptability, testability, safety, and so on. We have a very difficult time building quality into software during development when we try to. How can we possibly expect to achieve quality when we don’ t try? This is primarily why you must not try to convert a throwaway prototype into a product(Principle 11).
### 原则5：不要试图改进质量  
质量是不能通过翻新改进软件来保证的，这适用于所以对于质量的定义：可维护性、可靠性、适应性、可测试性、安全性等等。在开发过程中，我们很艰难的在软件中建立起了质量。所以，当我们不去尝试在构建软件时建立质量，又怎么可能期望达到高质量呢？这就是为什么你不能尝试将一个一次性的原型转换成一个真实产品的原因。(原则 11)。


## Principle 6: poor reliability is worse than poor efficiency
> When software is not efficient, it is generally possible to isolate the sections of the program that consume most of the execution time and redesign or recode them for increased efficiency(Principle 194).Poor reliability is not only more difficult to detect, it is also more difficult to fix.A system’s poor reliability may not become apparent until years after the system is deployed–and it kills somebody.Once the poor reliability manifests itself, it is often difficult to isolate its cause.

### 原则6：低可靠性比低效率更糟糕  
当软件效率不高时，通常可以将耗费大部分执行时间的程序部分分离出来，重新设计或重新编码以提高效率 (原则 194)。但是，可靠性差不仅难检测，而且更难修复。尤其，系统的低可靠性可能要到系统部署多年后才会显现出来 —— 而且可能会导致人员死亡。一旦糟糕的可靠性表现出来，通常很难排查它的原因。


## Principle 7: give products to customers early
> No matter how hard you try to learn users’needs during the requirements phase, the most effective means to ascertain their real needs is to give them a product and let them play with it.If you follow a conventional interpretation of the waterfall model, the first delivery of a product to the customer occurs after 99 percent of the development resources are already expended.Thus, the majority of customer feedback on their needs occurs after the resources are expended.Contrast that with an approach, for example, of constructing a quick and dirty prototype early in the development process.Deliver this to the customer, gather feedback, and then write a requirements specification and proceed with a full-scale development.In this scenario, only 5 to 20 percent of the development resources are expended by the time customers experience their first product.f the appropriate features were built into the prototype, the highest-risk user needs will become better known and the final product is more likely to be user-satisfactory.This helps ensure that the remainder of the resources are spent building the right system.

### 原则7：尽早把产品给顾客  
无论您在需求阶段多么努力地了解用户的需求，确定他们真正需求的最有效方法就是给他们一个产品，让他们使用它。如果您遵循瀑布模型的常规解释，那么在 99% 的开发资源已经消耗完之后，才会第一次向客户交付产品。因此，客户对其需求的大多数反馈发生在资源消耗之后。与此形成对比的是一种方法，例如，在开发过程的早期构建一个快速且肮脏的原型。将此交付给客户，收集反馈，然后编写需求规范并进行全面开发。在这种情况下，当客户体验他们的第一个产品时，只有 5% 到 20% 的开发资源被消耗。如果在原型中构建了适当的特性，就会让最高风险的用户需求变得更加为人所知，最终的产品就更有可能让用户满意。这有助于确保将剩余的资源用于构建正确的系统。


## Principle 8: communicate with customers/users
> Never lose sight of why software is being developed:to satisfy real needs,to solve real problems.The only way to solve real needs is to communicate with those who have the needs.The customer or user is the most important person involved with your project.If you are a commercial developer, talk often with the clients.Keep them involved.Sure, it is easier to develop software in a vacuum, but will the customer like the result?If you’re a producer of shrinkwrap software,”customers”are harder to locate during development.So role-play.Designate three or four individuals in your organization as prospective customers and tap them for ideas that will keep them as customers or make them happy.If you’re a government contractor, talk often with the contracting officers, their technical representatives, and, if possible, the users.People and situations change often in the government.the only way to keep up with the change is communication.Ignoring the changes may make life seem easier in the short term, but the final system will not be useful.

### 原则8：与客户 / 用户沟通  
永远不要忽视软件开发的原因：满足真正的需求，解决真正的问题。解决真正需求的唯一方法是与有需求的人交流。客户或用户是参与项目的最重要的人。如果你是一个商业开发人员，经常和客户交流。让他们参与进来。当然，在真空中开发软件更容易，但是客户会喜欢这样的结果吗？如果你是软件外包的生产商，在开发过程中很难找到 “客户”。所以角色扮演。在你的组织中指定 3 到 4 个人作为潜在的客户，并征求他们的意见，让他们成为客户或让他们开心。如果你是政府的承建商，要经常与承建商、他们的技术代表，以及 (如果可能的话) 与使用者沟通。政府里的人和事经常变化。跟上变化的唯一方法是交流。忽视这些变化可能会让生活在短期内看起来更容易，但最终的系统将不会有用。


## Principle 9: align incentives for developer and customer
> Projects often fail because customers and developers have different(and perhaps incompatible) goals.For example, take the simple case in which the customer wants features 1, 2, and 3 by a specific date and the developer wants to maximize revenue or profit.To maximize revenue the develper may attempt to build all three features in their entirety even if late.To maximize revenue the develper may attempt to build all three features in their entirety even if late.To help align the two organizations’ goals:
(1)Prioritize requirements (Principle 50)so that developers understand their relative importance,
(2) reward the developer based on the relative priorities(for example, all highpriority requirements must be satisfied, each medium priority requirement earns the developer a small additional bonus of some kind and each low priority requirement satisfied earns a very small bonus),
(3)use strict penalties for late delivery

### 原则9：调整对开发者和客户的激励  
项目经常失败，因为客户和开发人员有不同的 (可能是不兼容的) 目标。例如，以一个简单的例子为例，在这种情况下，客户希望在特定日期前获得特性 1、2 和 3，而开发人员希望最大化收益或利润。为了获得最大的收益，开发人员可能会尝试完整地构建这三个特性，即使会导致延期。为了帮助这两方的目标保持一致:(1) 对需求进行优先级排序 (原则 50)，以便开发人员了解它们的相对重要性，(2) 根据相对优先级奖励开发人员 (例如，必须满足所有高优先级的要求，每个中等优先级的要求为开发人员带来一些额外的小奖励，每个低优先级的要求得到的奖励非常小)，(3) 对逾期实行严厉的处罚

## Principle 10: plan to throw one away
> One of the most important critical success factors for a project is whether it is entirely new.Programs that tread on brand new territory(whether it be with respect to application, architecture, interface, or algorithm) rarely work the first time.Fred Brooks, in his Mythical Man Month, makes this perfectly clear with his advice, “Plan to throw one away; you will anyway.”This advice was originally presented by Winston Royce in 1970, when he said one should plan for the first fully deployed system to be the second one created.The first should at least check out the critical design issues and the operational concept.Furthermore Royce recommended that such a prerelease version should be developed with approximately 25 percent of the total system development resources.As a developer of a new custom product, plan to build a series of throwaway prototypes(Principles 11, 12, and 13)before embarking on the full-scale product development.As a commercial high-volume developer expect that your first product version will be able to be modified for a certain period of years, after which it will need to be fully replaced(related Principles 185, 186, 188, and 201).As a maintainer of a product, be aware that you can fiddle with the program just so much before it becomes unstable and must be replaced (see related Principles 186, 191, 195, and 197).

### 原则10：计划扔掉一个  
一个项目最重要的关键成功因素之一是它是否全新。踏上全新领域的程序 (无论是在应用程序、体系结构、接口或算法方面) 很少在第一次运行。弗雷德・布鲁克斯 (Fred Brooks) 在他的《人月神话》一书中明确提出了这一点:“计划扔掉一个；反正你会 “。这条建议最初是由温斯顿・罗伊斯在 1970 年提出的，当时他说一个人应该计划将第一个完全部署的系统变成第二个系统。首先，至少应该检查关键的设计问题和操作概念。此外，Royce 建议这样的预发布版本应该使用大约 25% 的系统开发资源来开发。作为新定制产品的开发人员，在开始全面的产品开发之前，计划构建一系列一次性的原型 (原则 11、12 和 13)。作为一个商业的大容量开发人员，您的第一个产品版本将能够在一定的时间内被修改，之后它将需要被完全替换 (相关原则 185,186,188 和 201)。作为产品的维护者，请注意，在程序变得不稳定并必须被替换之前，您可以对它进行太多的修改 (请参阅相关原则 186、191、195 和 197)。

## Principle 11: Build The Right Kind of Prototype
> There are two types of prototypes: throwaway and evolutionary. Throwaway prototypes are built in a quick and dirty manner, are given to the customer for feedback, and are thrown away once the desired information is learned. The desired information is captured in a requirements specification for a full-scale product development.  Evolutionary prototypes are built in a quality manner, are given to the customer for feedback, and are modified once the desired information is learned to more closely approximate the needs of the users. This process is repeated until the product converges to the desired product. 
> Throwaway prototypes should be built when critical features are poorly understood. Evolutionary prototypes should be built when the critical functions are well understood but many other features are poorly understood. Build a throwaway prototype followed by a "from-scratch" evolutionary prototype if most functions are poorly understood.

### 原则11：构建正确的原型

## Principle 12: Build The Right Feature into a Prototype

## Principle 37: Take Responsibility

