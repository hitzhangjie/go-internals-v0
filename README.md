Attention: This repo is archieved, please move to [go-internals-v2](https://github.com/hitzhangjie/go-internals-v2]

# 项目介绍

**go-internals** 包含了golang设计实现的一系列文章，内容覆盖范围包括编译器、链接器、调试器、运行时、垃圾回收器、内存分配器、goroutine、chan、panic/recover、defer、异步抢占、select-case等等的内部细节，并且会持续完善、更新，致力于将其沉淀成一个可供新老gophers查询的知识库。

文档的组织，重在成体系、风格一致，以形成可供长期协作、查询、学习的知识库。文档内容不一定要自己编写，也可以是转载高质量的文章，但是必须要有自己的阅读思考总结。

# 协作方式

为了保证协作可持续，需要考虑如何做到以下几方面：
- 协作编辑；
- 审核把关；
- 方便后续使用；

目前我们主张采用的协作方式是：

1、可以尝试通过提交单个markdown文档的形式，如：gc.md；  
2、每个文档包含一些liquid tag（对应表头字段），github流水线解析后可以自动合并到最终的表格或者目录树，  
   然后再将汇总后的内容发布到pages.oa.com。
    
    {%
	---
	author: "xyz"
	title: "gc"
	tags: ["gc"]
	---

	summary
    %}
	上面{% %}内部为markdown内容，其中的“---...---”部分即为liquid tags。

# 欢迎贡献

欢迎各位gophers一起来贡献！
