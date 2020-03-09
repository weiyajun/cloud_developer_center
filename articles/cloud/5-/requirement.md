**江湖传言，产品经理和开发同学的矛盾由来已久。**

![](/articles/cloud/5-/media/f299bd4afbd776b417c31c3842d2226a.png)

**现在疫情蔓延，这些江湖传言是否是真实存在的呢？**

**矛盾不存在，在技术中台中，产品经理和开发同学的小伙伴是相亲相爱的一家人。**

**我们是怎么做到的呢？**

**小黑板、小板凳支起来，开始划重点了。**

**在技术中台中我们的开发者可以在创建流水线的时候，将产品经理在jira上提交的信息关联起来，这样每次提交新的流水线，所提交的应用就和功能需求对接起来了，查阅起来非常方便。**

**首先，在技术中台的持续集成中点击应用的流水线，在点击“需求管理”菜单**

![](/articles/cloud/5-/media/dc4d29addc6b8a489a6a93aac82210f0.png)

**点击“需求配置”将jira的链接地址和用户认证添加上去。**

![](/articles/cloud/5-/media/55e845a5327744a98ad9fdd16cf8af02.png)

**然后在你每次提交代码的时候，commt操作带上jira的需求版本号。**

**比如现在疫情严重，提个jira需求来十只口罩，让我们的产品经理和开发同学冰释前嫌。**

![](/articles/cloud/5-/media/c76df2de95ad815cef6d7ebc62b7c823.png)

**重要的事情说三遍，“一定要在commit操作时带上jira的版本号”**

**这里我们的jira版本号是“BGTEST-73”，我们在git提交代码的时候，在commit操作加上对应的jira版本号，多个条码以空格或，分隔。**

![](/articles/cloud/5-/media/c222c1babcf70a7369dd665636080c01.png)

**这样我们在执行流水线我们就看到了在jira上提交的信息，技术中台会自动抓取jira上的信息并关联起来。**

![](/articles/cloud/5-/media/bcf0608819079c23e3887052f3d933bf.png)

**这么做的意义有哪些呢？**

**通过技术中台的“需求管理”这个功能，我们在项目上用的代码、产品经理提出的需求、测试部门的测试验证和部署上线等过程就被串连起来了。**

**对于开发经理的来说，每个新开发的代码版本都和产品需求关联起来了，可以非常方便看到整个流水线构建的应用对应了哪些需求任务。**

**而对于产品经理来说，可以直观的看到现在的应用版本都完成了哪些需求更新，能更好的管理和推进整个产品迭代。**

![](/articles/cloud/5-/media/0a338b9c63fe6147283ede508bc656db.jpg)

**技术中台通过对“需求管理”这个功能的创新，将“应用研发”、“产品经理”等角色紧密结合起来，同时以技术中台驱动业务和产品的迭代，快速响应业务需求，将越来越多的共享信息沉淀在平台上，打造面向“数字化”的技术平台。**
