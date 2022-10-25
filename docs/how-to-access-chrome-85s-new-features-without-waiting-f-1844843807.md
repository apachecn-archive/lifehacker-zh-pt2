# 如何在不等待推出的情况下访问 Chrome 85 的新功能

> 原文:[https://life hacker . com/how-to-access-chrome-85s-new-features-without-waiting-f-1844843807](https://lifehacker.com/how-to-access-chrome-85s-new-features-without-waiting-f-1844843807)

就像一个孩子在[你选择的假期]一样，Chrome 85 昨天来到了大众面前。或者至少理论上是这样。昨天下午，当我打开浏览器，像往常一样导航到“关于谷歌浏览器”来发布更新时，什么也没发生。

Watch

嗯。或许谷歌暗示 Chrome 85 将面向大众推出比我预期的要晚得多。我只能希望你今天能接触到 Chrome 85——如果不能，你可以通过谷歌的安装程序 下载并安装最新版本的 [。它不会影响你的浏览体验，如果你还没有 Chrome 85，它会让你继续使用它。](https://www.google.com/chrome)

一旦你做到了这一点，这里有所有值得了解的功能，以及如何解锁它们，这样你就不用等着它们正式发布了。

### 签出(并可能禁用)选项卡缩略图

将鼠标悬停在 Chrome 85 中的任何标签上，你会看到一个快速弹出的缩略图，向你展示网站的样子。因为，你知道，那就是缩略图——一个微小的预览。

如果你讨厌他们，只要在地址栏拉起`chrome://flags`，禁用 ***#tab-hover-cards*** 标志，就会让你的悬停变成更无聊的:

### 加载网页的速度更快，使用的系统资源更少

好消息是:Chrome 85 的页面加载速度已经比以前的版本快了 10 %,你不需要做任何事情就能从这些改进中受益。这都要归功于 Profile Guided Optimization，一种编译器优化技术，你可以在这里 阅读更多关于 [。是的，这个“百分之十”的数字直接来自谷歌；我自己没有测试过，但是我当然很好奇。](https://blog.chromium.org/2020/08/chrome-just-got-faster-with-profile.html)

Chrome 的*也是*推出的 Tab 节流，但目前只在 [的 Beta 频道](https://blog.chromium.org/2020/08/chrome-just-got-faster-with-profile.html) 进行。这种节省电池和资源的行为，我们已经在上个月[Chrome Canary](https://lifehacker.com/how-to-try-out-chrome-86s-big-battery-saving-fix-today-1844283047)中预演过，最终将成为 Chrome 的默认行为。在那之前，你必须在`chrome://flags`中启用***#密集唤醒节流*** 标志，才能在 [Chrome 的测试版](https://www.google.com/chrome/beta) 中解锁

### 展开和折叠选项卡组

标签组在 Chrome 中出现已经有一段时间了，但是现在你可以通过点击标签组的名称(或者颜色，如果你不喜欢这个词)来扩展和收缩你的标签组。拉起`chrome://flags`并启用此标志，开启功能: ***#tab-groups-collapse。*** 我真的很喜欢这个。

### 多注意你已经打开的标签页

这不是一个你需要在浏览器中启用的功能，但它是一个你需要在头脑中作为地址栏程序的一部分来启用的功能。我的意思是。现在，当你去输入一个网站时，Chrome 会让你知道你是否已经*在你现有标签页的某个地方打开了那个网站。如果你保持你的浏览器干净整洁的话，这不是很有帮助，但是对于那些处理大量标签蔓延的人——包括我自己——这个功能很棒。随着 Chrome 85 的发布，它现在也可以在 Android 上使用。*

我有一个超宽的显示器，所以这个小选项很容易在浏览器的右边被忽略。每当您键入网址时，请查找以下内容:

点击它，你会跳转到已经有你试图打开的网站的标签。这个选项在 Android 上应该更明显，因为你知道，你的屏幕要窄得多。

### 保存。您在 Chrome 中填写的 PDF 表单

现在，如果你在 Chrome 中将数据输入到一个. PDF 文件中，并试图保存你所做的事情，保存到你电脑中的文件将不会包含你输入的任何内容。这在 Chrome 85 中有所改变，但该功能一如既往地是一个首次展示。

你很快就能长胖了。PDF 格式，并在 Chrome 中保存原始的*或*填写的 PDF，但如果你不耐烦，你可以今天就使用这个功能。加载`chrome://flags`并启用 ***#pdf-form-save*** 标志。同时，启用***# export-tagged-pdf***标志，这将添加关于。您保存的文件的 PDF 结构(对于辅助功能更好)。

### 创建二维码以共享网站

如果你进入`chrome://flags`并启用***# sharing-qr code-generator***，你现在可以在任何网站的正文中点击右键并生成一个 QR 码，然后你可以与他人分享，打印在你的店面上，挂在你的墙上，等等。

### 匿名化浏览器的用户代理字符串

如果你希望网站对你使用的浏览器和操作系统一无所知——试图限制你向任何人分享的数据量——你可以启用`chrome://flags/`中的***#冻结用户代理*** ，让你的浏览器对它分享的内容有更多的控制，而不是向它访问的任何网站发送各种信息(对于 [轻松指纹](https://httptoolkit.tech/blog/user-agent-client-hints) )。