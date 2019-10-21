# 服务端软件技术树

自20世纪30年代现代计算机诞生至今，服务端软件技术（本文简称服务端技术）已经发展成为IT领域一大重要分支。大到操作系统，小到仅一行代码的工具，数以亿计的服务端软件运行在无数服务器和各类硬件设备上，支撑着现代人类文明的运转。

为使一个服务端软件从开发到最终交付运行，技术人员除了要实现业务相关的功能外，还要解决一些业务无关的问题，比如性能、效率、质量等。进一步说，所有业务无关问题又都能归类到少数几个问题上，本文称之为“业务无关元问题”，简称`元问题`。举个例子，我们经常遇到的一个业务无关问题是开发成本过高，而成本过高的原因往往是开发效率低下，因此成本并非元问题，而是结果或指标，开发效率才是元问题。事实上，业内对元问题的划分和定义由来已久，参与者众多，包括权威机构（比如ISO/IEC 9126、25010软件质量模型标准）、各企业以及个人，但目前并未形成统一的事实标准。

## 服务端技术元问题模型

本文通过对业内主流思路的借鉴，提出一个独特的元问题模型，将现代服务端技术描述成是一棵由9大元问题领域组成的技术树。经过多年发展，每个元问题领域都已沉淀大量成熟软件或技术理论，在日常研发和技术选型前，技术人员应该先弄清楚自己要解决的元问题是什么，再利用或借鉴该元问题领域下的已有软件或技术理论去做研发。

<div align="center">
    <a href="https://github.com/star2478/server-tech-tree/blob/master/img/server-tech-tree-model.png"> <img src="https://github.com/star2478/server-tech-tree/blob/master/img/server-tech-tree-model.png"></a>
</div>
<br>

## 元问题定义与指标
* [定义和指标](https://github.com/star2478/server-tech-tree/blob/master/元问题定义和指标.md)

## 元问题主要技术
* [开发效率](https://github.com/star2478/server-tech-tree/blob/master/开发效率.md)
    * [开发框架与微服务](https://github.com/star2478/server-tech-tree/blob/master/元问题主要技术/开发效率/开发框架与微服务.md)
    * [ServiceMesh服务网格技术](https://github.com/star2478/server-tech-tree/blob/master/元问题主要技术/开发效率/ServiceMesh服务网格技术.md)
    * [Serverless无服务技术](https://github.com/star2478/server-tech-tree/blob/master/元问题主要技术/开发效率/Serverless无服务技术.md)
    * [共享技术](https://github.com/star2478/server-tech-tree/blob/master/元问题主要技术/开发效率/共享技术.md)
    * [扩展性技术](https://github.com/star2478/server-tech-tree/blob/master/元问题主要技术/开发效率/扩展性技术.md)
    * [无代码开发](https://github.com/star2478/server-tech-tree/blob/master/元问题主要技术/开发效率/无代码开发.md)
* [资源管理能力](https://github.com/star2478/server-tech-tree/blob/master/资源管理能力.md)
* [可用性](https://github.com/star2478/server-tech-tree/blob/master/可用性.md)
* [伸缩性](https://github.com/star2478/server-tech-tree/blob/master/伸缩性.md)
* [性能](https://github.com/star2478/server-tech-tree/blob/master/性能.md)
* [安全](https://github.com/star2478/server-tech-tree/blob/master/安全.md)
* [质量](https://github.com/star2478/server-tech-tree/blob/master/质量.md)
* [数据](https://github.com/star2478/server-tech-tree/blob/master/数据.md)
* [智能](https://github.com/star2478/server-tech-tree/blob/master/智能.md)
