# 我的无线网络应该使用哪些 Wifi 频道？

> 原文:[https://life hacker . com/which-wifi-channels-should-I-use-for-my-wireless-networking-1832788063](https://lifehacker.com/which-wifi-channels-should-i-use-for-my-wireless-networ-1832788063)

[Lifehacker's Complete Guide to Wifi](https://wifiguide.kinja.com)) : title[![](../Images/be764d30b532adad70daeee8be76d9d7.png)](https://wifiguide.kinja.com)[Lifehacker's Complete Guide to Wifi](https://wifiguide.kinja.com)Wireless networking is complicated, but it doesn't have to be. Let us help you out.

显然，一群 Lifehacker 的读者在使用无线网络时遇到了问题——无论你是试图从很远的地方连接，还是你的设备速度很慢，或者你因为有 300 个不同的无线网络辐射着你的公寓而感到沮丧。

Watch

许多人在上周的 [**Tech 911**](https://lifehacker.com/c/tech-911) 帖子中提出了评论、担忧和后续问题: [我的设备应该使用哪个 Wifi 频段？我很高兴能解决无线网络这个潘多拉盒子里出现的一切问题。如果你想让你的设备有最好的范围和最快的速度，这是一个令人困惑的话题，我敢打赌，大多数人只是在设置过程中做他们的路由器告诉他们做的事情，连接到任何创建的网络，然后结束一天的工作(无论是好是坏)。](https://lifehacker.com/which-wifi-band-should-i-use-for-my-devices-1832635625?rev=1550771340870)

然而，本周我没有回答任何问题，而是想强调一下 Lifehacker 的读者 **Lee** 在阅读了上周的专栏后发来的电子邮件中提到的无线网络的一个具体方面:

> *“在下一篇文章中，你可能想谈谈 WiFi 渠道。许多业主从来没有改变他们的 WAP 从默认的渠道，并使用同一个作为他们的邻居。*
> 
> 对于您提出的由于信号范围的原因，房子的其他地方无法获得 5GHz 的信号的问题，您可以在第一个 WAP 上添加第二个 WAP。只需关闭第二台服务器上的 DHCP 和 DNS，这样您的主 WAP 就可以同时完成这两项工作。"

首先，是的！你是正确的。上周，我不想过多地讨论无线网络建议，但是你的观点是正确的。如果有机会，您应该尽一切努力避免竞争无线网络。

那是什么意思呢？让我们后退一点。您的(双频)无线路由器工作在一个无线频率范围内，大约为 2400MHz 到 2500MHz(对于 2.4GHz 网络)，以及 5200MHz 到 5800MHz(对于 5GHz 网络)。这些范围中的每一个都被分成无线信道:

*   **14 个 2.4GHz wifi 频道**(每个 20MHz，全部重叠)

*   【5GHz wifi 的 25 个频道(每个 20MHz，尽管在您的路由器设置中，您通常只会看到多达 12 个选项， [每个 40MHz 宽](http://www.revolutionwifi.net/revolutionwifi/2013/03/80211ac-channel-planning.html) )

还和我在一起吗？很好。这整个“信道”很重要，因为您希望您的无线网络生活在竞争网络尽可能少的信道上。来自竞争网络和设备的干扰越多，性能可能越慢。正如一位 Reddit 用户 [描述的](https://www.reddit.com/r/LifeProTips/comments/4jcp2o/lpt_download_wifi_analyzer_to_determine_what/) :

> “我最近搬进了一栋公寓，有一个 100mbps 的套餐，但我的 wifi 使用 Speedtest 只能获得 4Mbps。
> 
> 使用 Wifi 分析仪显示我和另外 6 个人在第 6 频道。
> 
> *11 频道只有一个有另一个，所以我换了 wifi 信号用 11 频道。在我运行 Speedtest 并获得 87Mbps 之后。"*

要弄清楚你的无线情况，你需要做的就是抓住一个免费的无线扫描应用程序。我以前分享过我对 [Wifi 分析器](https://lifehacker.com/see-how-bad-your-wifi-situation-really-is-with-wifi-ana-1826534324) (Windows)和 [Wifi 浏览器](https://lifehacker.com/get-the-fastest-wifi-on-your-wireless-network-with-wifi-1825489599) (Mac)的喜爱，尽管 Mac 用户也可以查看 [NetSpot](https://www.netspotapp.com/netspotpro.html) 如果你不想支付 20 美元的话。

扫描您的空间，您可能会看到类似这样的图表:

在这种情况下，我生活在无线地狱中，所以除了在房子周围安装更多的接入点(或网状网络)以在任何地方发射更强的信号，我没有什么可以改善我的情况。

如果您的图表看起来不那么混乱，并且您注意到您的邻居没有破坏 wifi 网络的频道，或者来自竞争网络的信号强度在特定频道上较低，那么这就是您的无线网络应该去的地方。理想情况下，您会希望在频道 1、6 或 11 上运行 2.4GHz wifi 网络。

您应该能够在路由器的设置 中将您的无线网络设置为一个新的频道 [。(别忘了对您的 5GHz 无线网络也进行同样的分析。)](https://lifehacker.com/how-to-make-your-wifi-router-as-secure-as-possible-1827695547)

作为 wifi 扫描的一部分，您可能还会注意到，与其他 wifi 网络相比，您的网络重叠了更多频道。用技术术语来说，你的路由器可能使用通道绑定，它将多个相邻通道结合在一起，给你 [甚至更快的速度](https://7signal.com/802-11ac-migration-part-2-whats-nobodys-telling-you-about-80mhz-and-160mhz-channel-bonding/) 。

如果没有任何其他网络干扰您的 40MHz(或更高)无线网络，那就太好了。但是，如果附近的其他网络使用相同的 wifi 信道， [它们也可能影响您的性能](https://www.snbforums.com/threads/ap-setting-40mhz-or-20mhz-channel-with.30283/) 。或者，更糟糕的是，你的无线网络可能会影响到所有人*其他人*，而通常情况下，如果你“呆在自己的车道上”，使用一个重叠频道更少的无线网络，这种情况是不会发生的。

这变得非常详细，但我想指出信道宽度，并让您知道这是一个您可以手动强制的设置，因为它会影响您的无线网络性能。不过，这是一种权衡。将您的 wifi 网络的信道宽度降低到一个较低的值，您可能会以整体性能为代价遇到较少的干扰。这也可能是*给*更好的无线性能的诀窍，取决于你周围竞争网络的设置。

当然，这些都是您想要测试的，但是现在您知道您可以(并且应该)分析您的周围位置，以找出配置您的无线网络的最佳方式。我知道这有点令人困惑，但希望这能让这个过程变得不那么神秘。如果你的个人设置仍然有问题，或者你不能完全弄清楚，请在评论中留言，我很乐意帮助你解决问题。