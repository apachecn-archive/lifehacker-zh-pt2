# 如何禁用火狐 75 的新地址栏

> 原文:[https://life hacker . com/how-to-disable-Firefox-75s-new-address-bar-1842728031](https://lifehacker.com/how-to-disable-firefox-75s-new-address-bar-1842728031)

对于那些今天已经更新了 Firefox 的人，以及那些还没有更新的人——通过**汉堡图标>帮助>关于 Firefox**——知道今天发布的 Firefox 75 给浏览器的地址栏带来了一些有趣的变化。火狐现在每当你点击地址栏时，它就会自动打开，你可能喜欢也可能不喜欢。

Watch

这是一个有益的调整。例如，您将获得一个您经常访问的网站列表，以便于访问。如果这些网站已经在你的浏览器中打开，网站的 URL 将被一个方便的“切换到标签”链接所取代，它将自动把你带到那个的*，而不是鼓励你用更多不必要的标签来增加你的浏览器。*

Mozilla 我承认，我真的没有注意到这个实现和你在 Firefox 的过去版本中会发现的有很大的区别——除了地址栏的列表除了搜索词之外什么也没有，而不是任何网站，只有我输入来测试的几个词。

也就是说，如果你不喜欢 Mozilla 的任何改变，你可以*禁用它们，让自己回到老派的地址栏体验。正如 Reddit 用户 **Time_Terminal** [指出的](https://www.reddit.com/r/firefox/comments/fwguqj/here_is_what_is_new_and_changed_in_firefox_750/fmomv1v/) ，在 Firefox 的首选项中有四个条目可以编辑，再次给自己一个斯巴达式的地址栏:*

*   browser . urlbar . open viewone fs
*   browser.urlbar.update1
*   浏览器. urlbar.update1 .干预
*   浏览器. urlbar.update1.searchTips

你需要在火狐的地址栏中输入 **about:config** ，然后搜索这四个。双击它们，将它们的值从“真”更改为“假”，然后重新启动浏览器。现在，当你点击地址栏时，你不会看到一个巨大的下拉菜单。当你开始输入时，你仍然会看到一些有用的建议——这是不可避免的——但至少你不必整天盯着你的热门网站或每次点击地址栏时都打开标签。

如果你经常访问某些你不想让其他人知道的网站，如果他们借用你的电脑一会儿，关闭这个功能几乎是强制性的。正确