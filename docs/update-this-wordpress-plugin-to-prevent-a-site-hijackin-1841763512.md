# 更新这个 WordPress 插件来防止站点劫持攻击

> 原文:[https://life hacker . com/update-this-WordPress-plugin-to-prevent-a-site-hijackin-1841763512](https://lifehacker.com/update-this-wordpress-plugin-to-prevent-a-site-hijackin-1841763512)

我用 WordPress 给我在互联网上强大的小角落提供动力，我承认，我很懒，没有及时更新我的各种插件和主题。y 站点是非常基础的，所以,这个想法从来没有出现过。然而，我强烈建议你现在就访问*你的* WordPress 网站，更新所有需要的东西，尤其是如果你使用的是 ThemeGrill 的某个插件，如果不打补丁的话，这个插件会有很大的漏洞。

Watch

根据最近来自 [WebARX](https://www.webarxsecurity.com/critical-issue-in-themegrill-demo-importer/) 的一份报告，Wordpress 的 ThemeGrill 演示导入器插件——在他们发表文章时已有超过 200，000 次安装，但这个数字正在迅速下降——在 1.3.4 到 1.6.1 之间的任何版本中都存在漏洞。如果一个 WordPress 用户为他们的博客安装并激活了一个 ThemeGrill 主题，并且在他们的 WordPress 安装中有一个默认的“admin”用户帐户，攻击者可以利用这个漏洞“将整个数据库清除到默认状态，之后他们会自动以管理员身份登录。”

正如 WebARX 所写的:

> “这是一个严重的漏洞，会造成巨大的损失。因为它不需要像我们之前在 InfiniteWP 中发现的那样可疑的有效载荷，所以不希望任何防火墙默认阻止这一点，需要创建一个特殊的规则来阻止这一漏洞。”

你需要尽快更新你的 ThemeGrill Demo Importer 插件到 1.6.2 版本，这应该很容易从你的 WordPress 安装的“插件”页面完成。你不可能错过你的更新，因为你的网站的后端看起来像这样:

### 是时候开始使用自动更新程序了

如果你和我一样，对你的未决更新数量感到惊讶——或者你真的想确保你的插件一弹出就抓取所有更新，这是一个很好的安全实践——我建议抓取一个二级插件来管理你的插件更新。在你的 WordPress 系统中安装一个插件，比如 [**伴侣自动更新**](https://wordpress.org/plugins/companion-auto-update/) ，它会自动确保你的 WordPress 的所有东西(甚至是它的核心文件)总是运行最新版本。

默认情况下，伴侣自动更新会自动更新你的插件，主题，翻译文件，以及 WordPress 的小更新；如果你不担心任何兼容性问题，你也可以让它安装主要更新。为了仔细检查这个插件是否正常工作，你甚至可以让它在你的网站上更新内容时给你发一封电子邮件。

虽然您在自己的网站上运行上述 ThemeGrill 演示导入程序的可能性很低，但我认为这个漏洞是一个很好的借口，可以花几分钟时间确保您已经设置了网站自动更新。这样的话，如果在你实际使用的插件中发现了漏洞，你可以在补丁出现的时候得到你需要的补丁。

当你这么做的时候， [停止使用](https://www.enginethemes.com/change-wordpress-admin-username/) 一个 WordPress 的默认“管理员”帐号。