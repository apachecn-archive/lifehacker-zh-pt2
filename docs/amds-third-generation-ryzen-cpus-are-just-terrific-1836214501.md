# AMD 的第三代锐龙处理器非常棒

> 原文:[https://gizmodo . com/amds-third-generation-ryzen-CPU-is-just-terrible-1836214501](https://gizmodo.com/amds-third-generation-ryzen-cpus-are-just-terrific-1836214501)

AMD 做到了。它生产了一系列速度快得离谱的 CPU，比竞争对手和前辈的功耗低得多，同时也更便宜，并增加了一些额外的功能，如 PCIe 4.0 支持，只有铁杆 PC 用户才需要。新的 500 美元的锐龙 9 3900X 和 330 美元的锐龙 7 3700X 兑现了 AMD 在过去几年中关于功率和价格的许多承诺。

Watch

(我应该从一开始就注意到，有一个非常恼人的缺陷，可能会破坏首次构建者的安装。这是次要的，如果潜在的破坏性，所以我不会详细的投诉，直到本审查结束。)

新的 Ryzens 是第一个基于 7 纳米工艺 广泛发布的 x86 CPU[。那汤是什么意思？“x86”是当今几乎所有笔记本电脑和台式机所采用的处理器架构。“7 纳米”是指工艺节点。在历史上，这个数字是用来对应处理器本身的晶体管门之间的距离。更短的距离意味着处理器本身的信息传输距离更短，需要的能量更少，理论上，这意味着速度和能效的提高。](https://gizmodo.com/amds-new-gpus-and-cpus-keep-the-pressure-on-the-intel-a-1835381601)

因此，AMD 基于 Zen 2 微架构的新 7 纳米处理器应该比上一代 Zen+12 纳米处理器和英特尔基于 14 纳米工艺的第九代处理器更快、更节能。

在我的测试中，理论似乎反映了现实。竞争对手包括:

*   500 美元的锐龙 9 3900X，基于 Zen 2 微架构。它拥有 12 核 24 线程和 105 瓦 TDP。
*   330 美元锐龙 7 3700X 基于 Zen 2 微架构。它有 8 个内核、16 个线程和 65W TDP。
*   [锐龙 Threadripper 2950X](https://gizmodo.com/amds-16-core-beast-quickly-creams-intels-but-you-might-1828292147) 基于 Zen+微架构。这款 [售价低至 600 美元](https://www.amd.com/en/products/cpu/amd-ryzen-threadripper-2950x) ，但通常售价在 800 至 900 美元左右。它拥有 16 个内核、32 个线程和 180 瓦 TDP
*   500 美元 [基于英特尔 14 纳米第九代微架构的英特尔 i9-9900K](https://gizmodo.com/intels-5ghz-i9-processor-is-incredible-for-hype-and-pre-1829850360) 。它有 8 个内核、16 个线程和 95W TDP。

我们使用类似的 256GB 固态硬盘、16GB 内存和相同的英伟达 GTX 1080 GPU 测试了所有四款产品。下面公布的基准描绘了一幅有趣的画面。

英特尔的 i9-9900K 在使用单核的任务中表现明显更好。所以在 Geekbench 4 单核基准测试和 WebXPRT 2015(一个用于测试浏览器完成任务速度的合成基准测试)中，英特尔部分击败了所有三个 AMD CPUs。多年来，AMD 一直在努力在核心到核心的性能上赶上英特尔，从这些基准测试来看，它显然仍有工作要做。很多应用程序，如网络浏览器和一些游戏功能，通常依赖于单个内核来实现性能，因此即使高级用户欣赏内核的数量，更多普通用户也会感觉到 AMD 的滞后。

AMD 的神奇之处在于它能够在一个处理器上塞进更多的内核，而收费却比英特尔低得多。它的处理器在耗电量大的应用中表现最佳。想想视频渲染或大量的数字运算。结果也证实了这一点。在我们的 Blender 基准测试中，我们对 3D 程序渲染一幅图像所需的时间进行了计时，在 Handbrake 中，我们对将 4K 视频转换为 1080p 所需的时间进行了计时，新的 AMD CPUs 表现非常好。事实上，锐龙 9 在手刹基准测试中击败了 Threadripper，在 Blender 中仅落后 8 秒。尽管少了四个内核。

令人惊讶的是，锐龙 7 与更贵的 i9 竞争很好。它在手刹上打败了它，只是在搅拌机基准测试上勉强输给了它。锐龙 7 不仅更便宜，而且比 i9 耗电更少，这似乎是预算有限的人的明确选择。与 i9-9900K 相比，锐龙 7 的性能如此令人钦佩，甚至试图与其他更便宜的处理器进行比较似乎都不公平，因为它们都要慢得多。

现在，我在这篇评论的顶部提到了一个问题:我恳求你，不要使用 AMD 最新一代锐龙处理器中包含的散热器和风扇组合冷却器。冷却器是必要的，但有很多比 AMD 免费提供的更好的替代品。它表面上是一个质量冷却器。它有 led 灯，可以与 Razer Chroma 软件同步，但它也非常吵，而且预先涂了太多异常粘稠的热化合物。它太粘了，以至于它会把冷却器粘到 CPU 上。这还不是最糟糕的事情；两者之间的良好密封有利于最佳冷却。

这就是为什么这是一个灾难的配方。AMD 的 CPU 通过一系列超级精致的针脚连接到主板上。弯曲它们中的任何一个，你就有一个不在 AMD 保修范围内的坏 CPU。同时，冷却器通过两个挂钩连接到主板上。你把冷却器的一边钩在板上，把它倾斜到 CPU 上，然后用一个小金属臂把另一边钩上。金属臂由廉价金属制成，可能会被卡住。您可能会觉得需要晃动它才能正常工作和连接。但是，一个错误的摆动和冷却器可以离开 CPU 和弯曲引脚。

如果你是第一次建造，你会想要投资一个单独的冷却器——一个可以拧进去而不是依靠钩子的冷却器(大约 50 美元)。但是你仍然想投资 AMD 处理器，而不是英特尔的竞争对手。这种最新一代的锐龙处理器速度快，价格实惠，而且这一次，它们不会占用电源输出的所有能量。

### 自述文件

*   AMD 的最新处理器在逐个核心的基础上无法与英特尔的竞争。
*   它们仍然更快，更便宜。