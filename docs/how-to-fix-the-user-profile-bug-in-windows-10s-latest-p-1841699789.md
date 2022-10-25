# 如何修复 Windows 10 最新补丁中的用户档案漏洞

> 原文:[https://life hacker . com/how-to-fix-the-user-profile-bug-in-windows-10s-latest-p-1841699789](https://lifehacker.com/how-to-fix-the-user-profile-bug-in-windows-10s-latest-p-1841699789)

又来了:最新的 Windows 10 补丁 [KB4532693](https://support.microsoft.com/en-us/help/4532693/windows-10-update-kb4532693) 可能会让你陷入一个恼人的 bug。一些安装了它的 Windows 用户报告说，当他们登录时，他们的 Windows 用户档案——以及其中的所有数据和应用程序——无法加载。

Watch

突然丢失数据并在没有任何警告的情况下将所有操作系统设置设为默认值令人担忧，但好消息是，错误是*而不是*删除您的个人资料或数据。

相反，Windows 重命名您的普通用户配置文件文件夹，然后在您的电脑启动时创建并加载一个临时用户配置文件。通过打开 **C: >用户**并查找以“.”结尾的重命名文件，原始的——但已重命名——配置文件应该仍然可见。ooo“还是”。bak”。您的个人资料无法通过这种方式访问，但有办法恢复。

Reddit 用户报告说，重新启动 Windows 几次就修复了这个错误，但对于需要重新启动多少次，以及为什么会这样(或者这是否真的是修复错误的原因)，人们没有达成一致。更一致的选择是卸载更新，直到微软修复一切。

1.  打开 Windows 10 开始菜单，点击齿轮形状的设置图标。
2.  在设置窗口，进入**更新&安全>查看更新历史>卸载更新**。
3.  使用搜索框，搜索**“Windows 10 自动驾驶更新 KB4532441。”**
4.  突出显示更新，然后单击列表顶部的**“卸载”**按钮。
5.  点击**“是”。**
6.  等待卸载完成，并根据需要重新启动电脑。

如果你需要更多的帮助，我们有更长的关于卸载 Windows 更新 的指南。当下一个 Windows update bug 不可避免地出现时，将该指南加入书签也是值得的。

[ [哔哔声电脑](https://www.bleepingcomputer.com/news/microsoft/windows-10-kb4532693-update-bug-hides-user-data-loads-wrong-profile/)