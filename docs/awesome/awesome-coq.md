<div class="github-widget" data-repo="coq-community/awesome-coq"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
## Awesome Coq [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://raw.githubusercontent.com/coq-community/awesome-coq/master/coq-logo.svg?sanitize=true" align="right" width="100" title="Awesome Coq is a coq-community project">](https://github.com/coq-community/manifesto)

&gt; 精选的 Coq 库、插件、工具和资源的精选列表.

The [Coq proof assistant](https://coq.inria.fr) 提供了一种形式语言来编写数学定义、可执行算法和定理，以及用于机器检查证明的半交互式开发的环境.

欢迎投稿！ 阅读 [contribution guidelines](https://github.com/coq-community/awesome-coq/blob/master/CONTRIBUTING.md) 第一的.



---

## Projects

### Frameworks

- [CoqEAL](https://github.com/CoqEAL/CoqEAL) - 简化证明中数据表示更改的框架.
- [FCF](https://github.com/adampetcher/fcf) - 密码学证明框架.
- [Fiat](https://github.com/mit-plv/fiat) - 大部分是正确构建程序的自动合成.
- [FreeSpec](https://github.com/ANSSI-FR/FreeSpec) - 使用效果和效果处理程序模块化验证程序的框架.
- [Iris](https://iris-project.org) - 高阶并发分离逻辑框架.
- [Q\*cert](https://querycert.github.io) - 用于实现和验证查询编译器的平台.
- [Verdi](https://github.com/uwplse/verdi) - 正式验证分布式系统实现的框架.
- [VST](https://vst.cs.princeton.edu) - 用于在高阶并发、不可预测的分离逻辑中验证 Coq 中的 C 代码的工具链，该逻辑与 CompCert 编译器的 Clight 语言相符.

### User Interfaces

- [CoqIDE](https://coq.inria.fr/refman/practical-tools/coqide.html) - 用于与 Coq 交互的独立图形工具.
- [Coqtail](https://github.com/whonore/Coqtail) - 基于 Vim 文本编辑器的 Coq 接口.
- [Proof General](https://proofgeneral.github.io) - 基于可扩展、可定制的文本编辑器 Emacs 的校样助手通用界面.
- [Company-Coq](https://github.com/cpitclaudel/company-coq) - Proof General 的 Coq 模式的 IDE 扩展.
- [jsCoq](https://github.com/ejgallego/jscoq) - Coq 到 JavaScript 的端口，它允许在浏览器中运行 Coq 项目.
- [Jupyter kernel for Coq](https://github.com/EugeneLoy/coq_jupyter) - Coq 支持 Jupyter Notebook Web 环境.
- [VSCoq](https://github.com/coq-community/vscoq) - Visual Studio Code 编辑器的扩展.

### Libraries

- [ALEA](https://github.com/coq-community/alea) - 用于推理随机算法的库.
- [Bignums](https://github.com/coq/bignums) - 任意大数库.
- [CoLoR](http://color.inria.fr) - 关于重写理论、lambda 演算和终止的库，以及扩展 Coq 标准库的公共数据结构子库.
- [coq-haskell](https://github.com/jwiegley/coq-haskell) - 库为 Haskell 用户平滑过渡到 Coq.
- [Coq record update](https://github.com/tchajed/coq-record-update) - 提供更新 Coq 记录字段的通用方法的库.
- [Coq-std++](https://gitlab.mpi-sws.org/iris/stdpp) - Coq 的扩展替代标准库.
- [ExtLib](https://github.com/coq-community/coq-ext-lib) - 可能对其他 Coq 开发有用的理论和插件的集合.
- [FCSL-PCM](https://github.com/imdea-software/fcsl-pcm) - 用于验证指针操作程序的部分可交换幺半群的形式化.
- [Flocq](http://flocq.gforge.inria.fr) - 浮点计算的形式化.
- [Formalised Undecidable Problems](https://github.com/uds-psl/coq-library-undecidability) - 无法确定的问题和它们之间的减少库.
- [Hahn](https://github.com/vafeiadis/hahn) - 列表和二元关系推理库.
- [Metalib](https://github.com/plclub/metalib) - 使用局部无名变量绑定表示的编程语言元理论库.
- [Monae](https://github.com/affeldt-aist/monae) - 一元效应和等式推理.
- [Paco](http://plv.mpi-sws.org/paco/) - 参数化联合归纳库.
- [Regular Language Representations](https://github.com/coq-community/reglang) - 正则语言的不同定义之间的翻译，包括正则表达式和自动机.
- [Relation Algebra](https://github.com/damien-pous/relation-algebra) - 以异构二元关系为模型的代数的模块化形式化.
- [Simple IO](https://github.com/Lysxia/coq-simple-io) - 具有用户可定义原始操作的输入/输出 monad.
- [TLC](https://github.com/charguer/tlc) - Coq 标准库的非建设性替代方案.

### Package and Build Management

- [coq_makefile](https://coq.inria.fr/refman/practical-tools/utilities.html) - 与 Coq 一起分发并基于生成 makefile 的构建工具.
- [Coq Package Index](https://coq.inria.fr/packages.html) - 基于 OPAM 的 Coq 包集合.
- [Coq Platform](https://github.com/MSoegtropIMC/coq-platform) - 实验性策划的软件包集合，以支持 Coq 在工业、教育和研究中的使用.
- [Coq-community Templates](https://github.com/coq-community/templates) - 用于为 Coq 项目生成配置文件的模板.
- [Docker-Coq](https://github.com/coq-community/docker-coq) - 多版本 Coq 的 Docker 镜像.
- [Docker-MathComp](https://github.com/math-comp/docker-mathcomp) - 用于 Coq 和数学组件库版本的多种组合的 Docker 映像.
- [Docker-Coq-action](https://github.com/marketplace/actions/docker-coq-action) - 可与 Docker-Coq 或 Docker-MathComp 一起使用的 GitHub 容器操作.
- [Dune](https://dune.build) - Coq 和 OCaml（前 jbuilder）的可组合和自以为是的构建系统.
- [Nix](https://nixos.org/nix/) - Linux 和其他 Unix 系统的包管理器，支持原子升级和回滚.
- [Nix Coq packages](https://search.nixos.org/packages?channel=unstable&query=coqPackages) - Nix 的 Coq 相关包的集合.
- [OPAM](https://opam.ocaml.org) - 灵活且对 Git 友好的 OCaml 包管理器，具有多种编译器支持.

### Plugins

- [AAC Tactics](https://github.com/coq-community/aac-tactics) - 重写通用量化方程、模结合性和某些运算符的交换性的策略.
- [Coq-Elpi](https://github.com/LPCIC/coq-elpi) - 嵌入式 Lambda Prolog 解释器插件.
- [CoqHammer](https://github.com/lukaszcz/coqhammer) - 通用自动推理锤工具，它将从以前的证明中学习与将问题转换为自动证明者以及重建找到的证明相结合.
- [Equations](https://github.com/mattam82/Coq-Equations) - Coq 的函数定义包.
- [Gappa](https://gitlab.inria.fr/gappa/coq) - 实现有关浮点运算和舍入错误的目标的策略.
- [Hierarchy Builder](https://github.com/math-comp/hierarchy-builder) - 基于打包类声明 Coq 层次结构的命令集合.
- [Ltac2](https://coq.inria.fr/refman/proof-engine/ltac2.html) - 类似于 Coq 的经典 Ltac 语言的实验类型策略语言.
- [MetaCoq](https://github.com/MetaCoq/metacoq) - 在 Coq 中对 Coq 进行形式化的项目，并提供用于操作 Coq 术语和开发认证插件的工具.
- [Mtac2](https://github.com/Mtac2/Mtac2) - 为反向推理添加类型化策略的插件.
- [Paramcoq](https://github.com/coq-community/paramcoq) - 用于生成 Coq 术语的参数化翻译的插件.
- [QuickChick](https://github.com/QuickChick/QuickChick) - 用于随机属性测试的插件.
- [SMTCoq](https://github.com/smtcoq/smtcoq) - 检查来自外部 SAT 和 SMT 求解器的证明证人的工具.
- [Unicoq](https://github.com/unicoq/unicoq) - 用增强的算法替换现有的统一算法的插件.

### Tools

- [CFML](https://gitlab.inria.fr/charguer/cfml2) - 用于证明 OCaml 程序在分离逻辑中的属性的工具.
- [coq2html](https://github.com/xavierleroy/coq2html) - Coq 的替代 HTML 文档生成器.
- [CoqOfOCaml](https://github.com/clarus/coq-of-ocaml) - 从 OCaml 代码生成惯用 Coq 的工具.
- [coq-dpdgraph](https://github.com/Karmaki/coq-dpdgraph) - 在 Coq 对象之间构建依赖图的工具.
- [coq-tools](https://github.com/JasonGross/coq-tools) - 帮助构建错误的小型复制示例、删除不需要的导入等的脚本.
- [Cosette](https://github.com/uwdb/Cosette) - 用于推理 SQL 查询等价的自动求解器.
- [hs-to-coq](https://github.com/plclub/hs-to-coq) - 从 Haskell 代码转换为等效的 Coq 代码.
- [lngen](https://github.com/plclub/lngen) - 用于生成本地无名 Coq 定义和证明的工具.
- [Menhir](http://gallium.inria.fr/~fpottier/menhir/) - 可以为经过验证的解析器输出 Coq 代码的解析器生成器.
- [mCoq](https://github.com/EngineeringSoftware/mcoq) - Coq 项目的突变分析工具.
- [Ott](https://github.com/ott-lang/ott) - 用于编写可转换为 Coq 的编程语言和微积分定义的工具.
- [Roosterize](https://github.com/EngineeringSoftware/roosterize) - 在 Coq 项目中建议引理名称的工具.
- [SerAPI](https://github.com/ejgallego/coq-serapi) - 用于（反）序列化 Coq 代码到 JSON 和 S 表达式的库和工具.

### Type Theory and Mathematics

- [Analysis](https://github.com/math-comp/analysis) - 与数学组件兼容的经典实分析库.
- [Category Theory in Coq](https://github.com/jwiegley/category-theory) - 范畴论的无公理形式化.
- [Completeness and Decidability of Modal Logic Calculi](https://github.com/coq-community/comp-dec-modal) - 逻辑 K、K*、CTL 和 PDL 的稳健性、完整性和可判定性.
- [CoqPrime](https://github.com/thery/coqprime) - 使用 Pocklington 和 Elliptic Curve 证书来证明素性的库.
- [CoRN](https://github.com/coq-community/corn) - 建设性实分析和代数库.
- [Coqtail Math](https://github.com/coq-community/coqtail-math) - 从算术到实数和复数分析的数学结果库.
- [Coquelicot](https://gitlab.inria.fr/coquelicot/coquelicot) - 与标准库兼容并注重可用性的经典实分析的形式化.
- [Finmap](https://github.com/math-comp/finmap) - 使用有限映射、集合和多重集合扩展数学组件.
- [Four Color Theorem](https://github.com/math-comp/fourcolor) - 四色定理的正式证明，图论的一个里程碑式的结果.
- [Gaia](https://github.com/coq-community/gaia) - 实施布尔巴基的《数学原理》，包括集合论和数论.
- [GeoCoq](https://github.com/GeoCoq/GeoCoq) - 基于塔斯基公理系统的几何形式化.
- [Graph Theory](https://github.com/coq-community/graph-theory) - 形式化的图论结果.
- [Homotopy Type Theory](https://github.com/HoTT/HoTT) - 同伦理论思想的发展.
- [Infotheo](https://github.com/affeldt-aist/infotheo) - 信息论和线性纠错码的形式化.
- [Mathematical Components](http://math-comp.github.io) - 数学理论的形式化，特别关注群论.
- [Math Classes](https://github.com/coq-community/math-classes) - 基于类型类的数学结构的抽象接口.
- [Odd Order Theorem](https://github.com/math-comp/odd-order) - 奇数阶定理的形式证明，有限群论的一个里程碑式的结果.
- [Puiseuxth](https://github.com/roglo/puiseuxth) - Puiseux 定理的证明和 Puiseux 级数多项式根的计算.
- [UniMath](https://github.com/UniMath/UniMath) - 旨在使用单价观点形式化大量数学的图书馆.

### Verified Software

- [CompCert](http://compcert.inria.fr) - 几乎所有 C 语言 (ISO C99) 的高保证编译器，为 PowerPC、ARM、RISC-V 和 x86 处理器生成高效代码.
- [Fiat-Crypto](https://github.com/mit-plv/fiat-crypto) - 加密原始代码生成.
- [Incremental Cycles](https://gitlab.inria.fr/agueneau/incremental-cycles) - Verified OCaml implementation of an algorithm for incremental cycle detection in graphs.
- [JSCert](https://github.com/jscert/jscert) - 带有经过验证的参考解释器的 ECMAScript 5 (JavaScript) 的 Coq 规范.
- [lambda-rust](https://gitlab.mpi-sws.org/iris/lambda-rust) - Rust 核心语言和类型系统的正式模型、类型系统的逻辑关系以及一些 Rust 库的安全证明.
- [Vélus](http://velus.inria.fr/) - 经过验证的编译器，用于类似 Lustre/Scade 的数据流同步语言.
- [Verdi Raft](https://github.com/uwplse/verdi-raft) - Raft 分布式共识协议的实现，在 Coq 中使用 Verdi 框架进行验证.

## Resources

### Community

- [Official Coq website](https://coq.inria.fr)
- [Official Coq manual](https://coq.inria.fr/refman/)
- [Official Coq standard library](https://coq.inria.fr/stdlib/)
- [Official Coq Discourse forum](https://coq.discourse.group)
- [Official Coq Zulip chat](https://coq.zulipchat.com)
- [Official Coq-Club mailing list](https://sympa.inria.fr/sympa/arc/coq-club)
- [Official Coq wiki](https://github.com/coq/coq/wiki)
- [Official Coq Twitter](https://twitter.com/CoqLang)
- [coq-community package maintenance project](https://github.com/coq-community/manifesto)
- [Coq subreddit](https://www.reddit.com/r/coq/)
- [Coq tag on Stack Overflow](https://stackoverflow.com/questions/tagged/coq)
- [Coq tag on Theoretical Computer Science Stack Exchange](https://cstheory.stackexchange.com/questions/tagged/coq)
- [Mathematical Components wiki](https://github.com/math-comp/math-comp/wiki)
- [Planet Coq link aggregator](https://coq.pl-a.net)

### Blogs

- [Coq Exchange: ideas and experiment reports about Coq](https://project.inria.fr/coqexchange/news/)
- [Gagallium](http://gallium.inria.fr/blog)
- [Gregory Malecha's blog](https://gmalecha.github.io)
- [Guillaume Claret's Coq blog](http://coq-blog.clarus.me)
- [Joachim Breitner's blog posts on Coq](http://www.joachim-breitner.de/blog/tag/Coq)
- [MIT PLV blog posts on Coq](https://plv.csail.mit.edu/blog/category/coq.html)
- [PLClub Blog](https://www.seas.upenn.edu/~plclub/blog/)
- [Poleiro: a Coq blog by Arthur Azevedo de Amorim](http://poleiro.info)
- [Ralf Jung's blog posts on Coq](https://www.ralfj.de/blog/categories/coq.html)
- [Thomas Letan's blog posts on Coq](https://soap.coffee/~lthms/#coq)

### Books

- [Coq'Art](https://www.labri.fr/perso/casteran/CoqArt/) - 致力于 Coq 的第一本书.
- [Software Foundations](https://softwarefoundations.cis.upenn.edu) - 有关逻辑、函数式编程和编程语言基础的基于 Coq 的系列教科书，旨在让初学者易于使用.
- [Certified Programming with Dependent Types](http://adam.chlipala.net/cpdt/) - 关于使用 Coq 进行实用工程的教科书，它教授高级实用技巧和非常具体的证明风格.
- [Program Logics for Certified Compilers](https://www.cs.princeton.edu/~appel/papers/plcc.pdf) - 解释如何使用分离逻辑构建程序逻辑的书，附有 Coq 中的形式模型，该模型应用于 Clight 编程语言和其他示例.
- [Formal Reasoning About Programs](http://adam.chlipala.net/frap/) - 同时提供关于程序正确性的形式逻辑推理的一般介绍以及为此目的使用 Coq 的书.
- [Programs and Proofs](https://ilyasergey.net/pnp/) - 这本书对 Coq 中的交互式证明进行了简短且实用的介绍，强调了通过来自 SSReflect 证明语言的一小组原语对可判定命题进行归纳推理的计算性质.
- [Computer Arithmetic and Formal Proofs](http://iste.co.uk/book.php?id=1238) - 描述如何使用 Flocq 库在 Coq 中正式指定和验证浮点算法的书籍.
- [The Mathematical Components book](https://math-comp.github.io/mcb/) - 面向有数学倾向的用户的书籍，侧重于数学组件库和 SSReflect 证明语言.

### Course Material

- [Foundations of Separation Logic](https://chargueraud.org/teach/verif/) - 介绍使用分离逻辑来推理 Coq 中的顺序命令式程序.
- [Introduction to Computational Logic](https://courses.ps.uni-saarland.de/icl_20/2/Resources) - 介绍基本逻辑原理、构造类型理论和使用 Coq 证明的交互式定理.

### Tutorials and Hints

- [CodeWars' Coq kata](https://www.codewars.com/kata/search/coq) - 在线证明挑战.
- [Coq'Art Exercises and Tutorials](https://github.com/coq-community/coq-art) - Coq&#39;Art 书中的 Coq 代码和练习，包括附加教程.
- [Coq in a Hurry](http://cel.archives-ouvertes.fr/inria-00001173) - 介绍如何使用 Coq 来定义逻辑概念和函数以及对它们的推理.
- [Lemma Overloading](https://github.com/coq-community/lemma-overloading) - 使用规范结构进行编程和证明的设计模式演示.
- [Mike Nahas's Coq Tutorial](https://mdnahas.github.io/doc/nahas_tutorial.html) - 使用 Coq 编写形式证明的基础知识.
- [Tricks in Coq](https://github.com/tchajed/coq-tricks) - 难以发现的提示、技巧和功能.
