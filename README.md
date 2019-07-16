# fun-with-graphics
这里整理了图形学相关的高校课程、书籍、教程、文章、博客、资源、开源项目。

## Rendering

| Courses                                                      |                                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [TU Wien Rendering/Ray Tracing Course](https://www.cg.tuwien.ac.at/courses/Rendering/VU.SS2018.html)<br>([YouTube](https://www.youtube.com/watch?v=pjc1QAI6zS0&list=PLujxSBD-JXgnGmsn7gEyN28P1DnRZG7qi), [哔哩哔哩](https://www.bilibili.com/video/av39918593)) | 一门关于真实感渲染、光线追踪和全局光照技术的课程             |
| [Computer Graphics](http://15462.courses.cs.cmu.edu/spring2019/) | CMU 15-462/662                                               |
| [Image Synthesis Techniques](http://graphics.stanford.edu/courses/cs348b/) | Stanford CS348b<br>This course provides a broad overview of the theory and practice of making photo-realistic imagery. |
| [Introduction to Computer Graphics and Imaging](https://web.stanford.edu/class/cs148/lectures.html) | Stanford CS148                                               |
| [Real-Time High Quality Rendering](http://www.cs.ucsb.edu/~lingqi/teaching/cs291a.html) | UCSB CS291A<br>Topics will cover programmable shaders, real-time shadows, interactive global illumination, image-based rendering, precomputed rendering, adaptive sampling and reconstruction, and real-time ray tracing. |
| [Physically Based Rendering and Material Appearance Modelling](http://courses.compute.dtu.dk/02941/) | DTU 02941                                                    |
| [Pixar in a Box: Rendering](https://www.khanacademy.org/partner-content/pixar/rendering) | Pixar 出品，渲染的「科普向」教程                             |

| Books                                                        |                                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [milo 的豆列](https://book.douban.com/people/miloyip/doulists) |
| 《全局光照技术》<br>([豆瓣读书](https://book.douban.com/subject/30264315/)) | 同时包含了离线和实时渲染的内容<br>探讨了渲染中最常用的约十种全局光照技术<br>并以其为线索介绍了大量计算机图形学相关的基础知识 |
| 《计算机图形学：原理及实践》<br>([豆瓣读书](https://book.douban.com/subject/30402778/), [book website](http://dept.cs.williams.edu/~morgan/cgpp/about.xml)) | 本书属于第二代图形学教科书<br>作者并不将之前的所有工作全部认定为天然合理的<br>而是按今天的理解重新审视它们<br>进而更新其原有的陈述方式 |
| 《Real-Time Rendering, Fourth Edition》<br>([豆瓣读书](https://book.douban.com/subject/30296179/), [book website](http://www.realtimerendering.com/)) | Real-Time Rendering 实时渲染<br>绝世武功的**目录**<br>Chapter25&26可以在配套网站上免费下载 |
| 《Physically Based Rendering: From Theory To Implementation, Third Edition》<br>([豆瓣读书](https://book.douban.com/subject/26736280/), [Read for free](http://www.pbr-book.org/)) | Offline Rendering 离线渲染<br>代码完备，读练结合，何况免费   |
| 《Advanced Global Illumination》<br>([豆瓣读书](https://book.douban.com/subject/2751153/), [authors' site](http://graphics.cs.kuleuven.be/publications/AGI2E/index.html), [Google Books sample](https://books.google.com/books?id=TB1jDAAAQBAJ&printsec=frontcover)) | 概述了全局光照有关理论<br>介绍了几种全局光照技术（有些现已过时） |
| 《Ray Tracing in One Weekend》<br>([Amazon](https://smile.amazon.com/Ray-Tracing-Weekend-Minibooks-Book-ebook/dp/B01B5AODD8?tag=realtimerenderin), [code](https://github.com/petershirley/raytracinginoneweekend/releases), [download for free](http://www.realtimerendering.com/raytracing/Ray%20Tracing%20in%20a%20Weekend.pdf)) | [Peter Shirley](https://twitter.com/Peter_shirley)'s Ray Tracing 三部曲其一 |
| 《Ray Tracing: the Next Week》<br>([Amazon](https://smile.amazon.com/Ray-Tracing-Next-Week-Minibooks-ebook/dp/B01CO7PQ8C?tag=realtimerenderin), [code](https://github.com/petershirley/raytracingthenextweek/releases), [download for free](http://www.realtimerendering.com/raytracing/Ray%20Tracing_%20The%20Next%20Week.pdf)) | Peter Shirley's Ray Tracing 三部曲其二                       |
| 《Ray Tracing: the Rest of Your Life》<br/>([Amazon](https://smile.amazon.com/Ray-Tracing-Next-Week-Minibooks-ebook/dp/B01CO7PQ8C?tag=realtimerenderin), [code](https://github.com/petershirley/raytracingtherestofyourlife/releases), [download for free](http://www.realtimerendering.com/raytracing/Ray%20Tracing_%20the%20Rest%20of%20Your%20Life.pdf)) | Peter Shirley's Ray Tracing 三部曲其三                       |
| 《Fundamentals of Computer Graphics, Fourth Edition》<br>([豆瓣读书](https://book.douban.com/subject/26868819/)) | 概述了计算机图形学相关基础，用来了解图形学的大全景不错       |
| 《Ray Tracing Gems》<br>([Book website](http://raytracinggems.com/), [amazon](https://www.amazon.com/Ray-Tracing-Gems-High-Quality-Real-Time/dp/1484244265?tag=realtimerenderin)) | Nvidia 出品，电子版免费                                      |
| [《Real-Time Rendering 3rd》提炼总结](https://github.com/QianMo/Real-Time-Rendering-3rd-CN-Summary-Ebook) |                                                              |

| Tutorials                                                    |                                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Learn OpenGL<br>([英文原版](), [中文版](https://learnopengl-cn.github.io/)) | OpenGL                                                       |
| [Learn Vulkan](https://learnvulkan.com/book/)                | Vulkan                                                       |
| [Vulkan Tutorial](https://vulkan-tutorial.com/)              | Vulkan                                                       |
| [The Book of Shaders](https://thebookofshaders.com/)         | Shader                                                       |
| [3d-game-shaders-for-beginners](https://github.com/lettier/3d-game-shaders-for-beginners)         | Shader                  |
| [The Graphics Codex](http://graphicscodex.com/)              | by [Morgan McGuire](https://twitter.com/CasualEffects)，IOS 上可以找到同名 App |
| [用JavaScript玩转计算机图形学(一)光线追踪入门](https://www.cnblogs.com/miloyip/archive/2010/03/29/1698953.html)         | by [Milo Yip](https://www.cnblogs.com/miloyip) |
| 用 C 语言画光<br>([1](https://zhuanlan.zhihu.com/p/30745861), [2](https://zhuanlan.zhihu.com/p/30748318), [3](https://zhuanlan.zhihu.com/p/30816284), [4](https://zhuanlan.zhihu.com/p/30961545), [5](https://zhuanlan.zhihu.com/p/31127076), [6](https://zhuanlan.zhihu.com/p/31534769), [7](https://zhuanlan.zhihu.com/p/31901449)) | by [Milo Yip](https://www.zhihu.com/people/miloyip)          |
| [Scratchapixel 2.0](http://www.scratchapixel.com/index.php)  | 32 lessons, 166 chapters, 450,000 words, C++ source code     |
| [Daily Pathtracer](http://aras-p.info/blog/2018/03/28/Daily-Pathtracer-Part-0-Intro/) | by [Aras Pranckevičius](http://aras-p.info/)                 |
| [Tiny renderer or how OpenGL works](https://github.com/ssloy/tinyrenderer/wiki) | software rendering in 500 lines of code |
| [Rasterization in One Weekend](https://tayfunkayhan.wordpress.com/2018/11/24/rasterization-in-one-weekend/) | by [Tayfun Kayhan](https://tayfunkayhan.wordpress.com/)      |

| Articles                                                     |                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------- |
| [什么是计算机图形学？](http://staff.ustc.edu.cn/~lgliu/Resources/CG/What_is_CG.htm), [什么是深度学习？](http://staff.ustc.edu.cn/~lgliu/Resources/DL/What_is_DeepLearning.html) | by [刘利刚](http://staff.ustc.edu.cn/~lgliu)            |
| [系统的学习计算机图形学，有哪些不同阶段的书籍的推荐？](https://www.zhihu.com/question/26720808)  | Q&A |
| [现阶段应该怎么学习计算机图形学呢？](https://www.zhihu.com/question/26341836)  | Q&A |
| [一篇光线追踪的入门](https://zhuanlan.zhihu.com/p/41269520)  | by [洛城](https://www.zhihu.com/people/luo-cheng-11-75) |
| [光线追踪与实时渲染的未来](https://zhuanlan.zhihu.com/p/34851503) | by [文刀秋二](https://www.zhihu.com/people/edliu)       |
| [基于摄影参数渲染](https://zhuanlan.zhihu.com/p/23827065)    | by [文刀秋二](https://www.zhihu.com/people/edliu)       |
| 基于物理着色([1](https://zhuanlan.zhihu.com/p/20091064), [2](https://zhuanlan.zhihu.com/p/20119162), [3](https://zhuanlan.zhihu.com/p/20122884), [4](https://zhuanlan.zhihu.com/p/21247702)) | by [文刀秋二](https://www.zhihu.com/people/edliu)       |
| [How to start learning graphics programming?](https://interplayoflight.wordpress.com/2018/07/08/how-to-start-learn-graphics-programming/amp/) | by Kostas Anagnostou                                    |
| [基于物理着色：BRDF](https://zhuanlan.zhihu.com/p/21376124)  | by [Maple](https://www.zhihu.com/people/maple)          |
| [金属，塑料，傻傻分不清楚](https://zhuanlan.zhihu.com/p/21961722?refer=highwaytographics) | by [叛逆者](https://www.zhihu.com/people/minmin.gong)   |

| Blogs                                                        |                                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [casual-effects](http://casual-effects.com/)                 | Computer graphics projects by [**Morgan McGuire**](http://casual-effects.com/morgan/index.html) and friends<br>NVIDIA 大牛, The Graphics Codex 作者 |
| [INTERPLAY OF LIGHT](https://interplayoflight.wordpress.com/) | "This blog is my scratchpad for graphics techniques I try and experiment with."<br>by [Kostas Anagnostou](https://twitter.com/KostasAAA) |
| [Self Shadow](https://blog.selfshadow.com/)                  | [@self_shadow](https://twitter.com/self_shadow) has been collecting [Siggraph courses/papers links](https://blog.selfshadow.com/categories/conference/) for many years:  Especially interesting are the Physically Based Shading in Theory and Practice course presentations. |
| [Jendrik Illner](https://jendrikillner.bitbucket.io/)        | **每周更新 Graphics Programming weekly**<br>Ubisoft *FarCry 5* 项目组图程 |
| [Alan Zucconi](https://www.alanzucconi.com/)                 | 《Unity 2018 Shaders and Effects Cookbook》作者              |
| [Linden Reid](https://lindenreid.wordpress.com/)             | Procedural geometry & graphics tutorials<br>A game developer at Blizzard |
| [Harold Serrano](https://www.haroldserrano.com/home/)        | Creator of the [Untold Engine](https://www.untoldengine.com/) |
| [Prof. Dr. Ligang Liu （刘利刚）](http://staff.ustc.edu.cn/~lgliu/) | 主要研究领域：计算机图形学和图像处理                         |
| [Lingqi Yan (闫令琪)](http://www.cs.ucsb.edu/~lingqi/?tdsourcetag=s_pctim_aiomsg#bio) | An Assistant Professor at UC Santa Barbara                   |
| [Behind the Pixels](http://behindthepixels.io/)              | Edward(Shiqiu) Liu, a Senior Real Time Rendering Engineer at NVIDIA<br>[知乎专栏版](https://zhuanlan.zhihu.com/behindthepixels) |
| [iquilezles](http://www.iquilezles.org/index.html)           | Inigo Quilez 的 Blog                                         |
| [JOEY DE VRIES](https://joeydevries.com/#home)               | Joey (author of [learnopengl.com](https://learnopengl.com/)) |
| [線代啟示錄](https://ccjou.wordpress.com/)                   | 周志成の线性代数                                             |
| [Ke-Sen Huang's Home Page](http://kesen.realtimerendering.com/) | 收集了 CG 各大会议的 paper                                   |
| [浅墨的游戏编程Blog](https://blog.csdn.net/poem_qianmo)      | 整理了《RTR3》《GPU 精粹》等读书笔记                         |
| [Coding Labs](http://www.codinglabs.net/default.aspx)        |                                                              |
| [TYLER HOBBS](https://tylerxhobbs.com/)                      |                                                              |
| [HUMUS](http://humus.name/)                                  |                                                              |
| [Icare3D Blog](https://blog.icare3d.org/)                    |                                                              |

| Resources pages                                              |                                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Real-Time Rendering Resources](http://www.realtimerendering.com/) | 《Real-Time Rendering》配套网站，相关资源丰富                |
| [PBRT](https://www.pbrt.org/)                                | 《Physically Based Rendering: From Theory To Implementation》配套网站，相关资源丰富 |
| [McGuire Computer Graphics Archive](https://casual-effects.com/data/) | 提供了一些常用的测试场景|
| [mattdesl/graphics-resources](mattdesl/graphics-resources)   | A list of graphic programming resources                      |
| [Readings on The State of The Art in Rendering](https://interplayoflight.wordpress.com/2018/09/30/readings-on-the-state-of-the-art-in-rendering/) | by [Kostas Anagnostou](https://twitter.com/KostasAAA)        |
| [Readings on Physically Based Rendering](https://interplayoflight.wordpress.com/2013/12/30/readings-on-physically-based-rendering/) | by [Kostas Anagnostou](https://twitter.com/KostasAAA)        |
| [Advances in Real-Time Rendering in 3D Graphics and Games](http://advances.realtimerendering.com/) | the well-established series of SIGGRAPH courses<br>covering late-breaking work and advances in real-time computer graphics |
| [Rendering Resources](https://benedikt-bitterli.me/resources/) | This page offers 32 different 3D scenes that you can use for free in your rendering research, publications and classes. |
| [terkelg/awesome-creative-coding](https://github.com/terkelg) | Creative Coding: Generative Art, Data visualization, Interaction Design, Resources |
| [eug/awesome-opengl](https://github.com/eug)                 | A curated list of awesome OpenGL libraries, debuggers and resources |

| Projects                                                     |                                                              |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [Mitsuba](http://www.mitsuba-renderer.org/)                  | Mitsuba is a research-oriented rendering system in the style of [PBRT](http://www.pbrt.org/), from which it derives much inspiration. |
| [Filament](https://google.github.io/filament/)               | Filament is a real-time physically-based renderer written in C++. It is mobile-first, but also multi-platform. |
| [The Mesa 3D Graphics Library](https://www.mesa3d.org/intro.html) | The Mesa project began as an open-source implementation of the [OpenGL](https://www.opengl.org/) specification - a system for rendering interactive 3D graphics. |
| [The Advanced Rendering Toolkit](https://cgg.mff.cuni.cz/ART/) | ART is a command-line system for physically based image synthesis. |
| [TAICHI](http://taichi.graphics/)                            | TAICHI: Open-source computer graphics library                |
| [Intel® Embree](https://embree.github.io/)                   | Intel® Embree is a collection of high-performance ray tracing kernels, developed at Intel |
| [MERL BRDF Database](http://www.merl.com/brdf/)              | The MERL BRDF database contains reflectance functions of 100 different materials |
| [minpt](https://github.com/hi2p-perim/minpt)                 | A path tracer in 300 lines of C++ |
| [yocto-gl](https://github.com/xelatihy/yocto-gl)             | Tiny C++ Libraries for Data-Driven Physically-based Graphics |

## Game Engines

| Tutorials                                                    |                               |
| ------------------------------------------------------------ | ----------------------------- |
| Massive UE4 Tutorial Playlist<br/>[Youtube](https://www.youtube.com/watch?v=QMsFxzYzFJ8&list=PLZlv_N0_O1gaCL2XjKluO7N2Pmmw9pvhE) | UnrealEngine 4<br/>官方入门教程，很全面 |
| [C# and Shader Tutorials for the Unity Engine](https://catlikecoding.com/unity/tutorials/) | Unity3D, Shader |
|  |                               |

| Books                                                        |                 |
| ------------------------------------------------------------ | --------------- |
| 《游戏引擎架构》<br>([豆瓣读书](https://book.douban.com/subject/25815142/), [book website](https://www.gameenginebook.com/)) | 《游戏引擎架构》同时涵盖游戏引擎软件开发的理论及实践，并对多方面的题目进行探讨|
| 《Unity Shader 入门精要》<br/>[豆瓣读书](https://book.douban.com/subject/26821639/) | Unity3D, Shader |
|                                                              |                 |
|                                                              |                 |

| Websites                                                     |                |
| ------------------------------------------------------------ | -------------- |
| UnrealEngine的官方视频主页<br>[Youtube](https://www.youtube.com/channel/UCBobmJyzsJ6Ll7UbfhI4iwQ)<br>[优酷](http://i.youku.com/i/UMzE2NDk2OTIw) | UnrealEngine 4 |
| [Unity 官方中文论坛](http://forum.china.unity3d.com/forum.php) | Unity3D        |
|                                                              |                |

