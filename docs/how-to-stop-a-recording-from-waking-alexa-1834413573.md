# 如何阻止录音唤醒 Alexa

> 原文:[https://life hacker . com/how-to-stop-a-recording-from-awake-Alexa-1834413573](https://lifehacker.com/how-to-stop-a-recording-from-waking-alexa-1834413573)

Lifehacker 最近 [发布了一个视频](https://lifehacker.com/is-it-faster-to-ask-a-digital-assistant-or-just-do-it-y-1834390220) ，其中两个受试者测试了一个亚马逊 Echo 的功能。不久之后，我们的 [高级技术编辑大卫·墨菲](https://kinja.com/thedavidmurphy) 提醒视频团队，任何通过扬声器在家观看视频的人都会发现，每当视频中有人说出唤醒单词“Alexa”时，他们的回声就会反复激活

Watch

现在，这不一定是坏的，因为播放我们的视频会自动让 Alexa 告诉你时间、天气或最新的头条新闻。但当然这可能会很麻烦，所以我们找到了一种方法，某人制作视频、音频记录或播客可以阻止 Alexa 响应。

亚马逊自己使用这种方法来阻止电视广告触发 Alexa，方法是当说出唤醒词时， [将 3,000hz 到 6000hz](https://www.theverge.com/2018/2/2/16965484/amazon-alexa-super-bowl-ad-activate-frequency-commercial-echo)范围内的频率静音。人耳仍然可以听到这些频率，所以*你*仍然可以听到录音中有人说“Alexa”，但你的亚马逊 Echo 不会。

以下是如何在一些流行的音频编辑软件中将这些频率静音。

### **试镜和首映**

两种 Adobe 产品都具有相同的静音功能。选择您的音频剪辑，并导航到名为“FFT 滤波器”的效果你会看到一个频率范围的图表。单击 3k 标记，然后再次单击 6k 标记，将这些点向下拖到零。然后点按“应用”(在“试听”中)，或者直接关闭窗口(在 Premiere 中)。

您也可以从同一个效果菜单中选择图形均衡器(30 个波段)，并将 3000 和 6000 附近的所有频率尽可能向下拖移。

### **专业工具**

转到插件菜单，导航到 EQ，并选择 EQ 3 7-Band。这也将显示一个跨频谱的线形图，所以选择最接近 3k 和 6k 的点，并将它们拖到图形的底部以静音。

虽然这些方法会阻止回声对单词“Alexa”的响应，但它们也会改变音频，使其听起来有点像是通过电话传来的。因此，我将只对单词“Alexa”的发音使用这个效果*来防止频率变化被察觉。否则你的音频听起来会让其他人*或*感到不舒服...只是不是阿利克夏。*