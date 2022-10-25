# 使用微软新的免费 Windows 应用程序恢复删除的文件

> 原文:[https://life hacker . com/recover-deleted-files-with-Microsoft-new-free-windows-1844203462](https://lifehacker.com/recover-deleted-files-with-microsofts-new-free-windows-1844203462)

如果你不小心删除了一个文件，所有的希望都不会落空。然而，假设你不能直接把它从 Windows 回收站中拖出来——尤其是如果你像我一样，倾向于默认使用更持久的 *Shift + Delete* 而不仅仅是“删除”——你将不得不卷起袖子，尝试稍微复杂一点的技术。

Watch

文件恢复应用程序 [已经存在很长时间了](https://lifehacker.com/how-to-recover-deleted-files-with-free-software-33293302) ，而且有很多很棒的免费选项可供你使用。微软又推出了一款，我建议把它添加到你的工具箱*中，以防*你需要它。它叫做 Windows 文件恢复，现在就可以从微软商店免费下载。

在你拉起它并开始恢复之前，让我们先了解一下基础知识。为了确保更成功的文件恢复，你可以做的最好的事情就是使用像这样的应用 t*他瞬间*你不小心删除了一些东西。不要关闭或重启计算机。不要说，“嗯，我明天再做。”在意外删除之后经过的时间越长——几天、几周、几个月——你就越不可能 [恢复数据](https://www.r-studio.com/file-recovery-basics.html) ，假设你在此期间一直在使用所述系统(及其硬盘或固态硬盘)。文件恢复工具可以扭转局面，但它们的威力不是无限的。

解决了这个问题后: L 启动 Windows 文件恢复并没有弹出你可能期待的漂亮 GUI 应用程序。取而代之的是，您会得到一个命令提示:

你可以为各种开关输入许多选项。但是，如果你只关心基本的东西，那么就像这样:

`winfr C: E: /n \Users\<username>\Documents\QuarterlyStatement.docx`

会将特定文件从 C:驱动器(QuarterlyStatement.docx)恢复到 E:驱动器。是的，要进行文件恢复，源驱动器和目标驱动器必须不同，因此如果您的系统没有两个独立的驱动器，您将需要插入一个 USB 驱动器来执行恢复。

同样，您也可以尝试恢复文件夹的全部内容:

`winfr C: E: /n \Users\<username>\Documents\`

使用该命令可以将 C:驱动器上的整个 Documents 文件夹恢复到 E:驱动器。

现在，你可能已经注意到，微软的工具中实际上内置了三种不同的文件恢复模式:默认、段和签名。根据您的文件恢复场景，您可能希望使用其中一个而不是另一个的原因有几个。例如，如果您使用非 NTFS 文件系统(如 FAT 或 exFAT)，您将只能使用签名模式。

正如微软 [拼出的](https://support.microsoft.com/en-us/help/4538642/windows-10-restore-lost-files) :

我还没有尝试过微软的工具来恢复任何东西——而且最近我也没有遭遇过任何可怕的意外删除——但是我会推荐使用微软推荐的顺序。签名模式，据我所知，可能需要相当长的时间来运行，取决于你的磁盘大小。从一个简单的模式开始，这样你就不会浪费时间，然后如果“未删除”没有找到你希望的东西，就转向更彻底的扫描。