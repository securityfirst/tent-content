[Title]: # ()
[Order]: # (0)

＃TRUECRYPT TOOL GUIDE 

## TrueCrypt工具指南
安全文件存储

**课程阅读：[保护文件](伞：//课程/保护文件)** 
**下载位置：** [https://truecrypt.ch/downloads/](https://truecrypt.ch/downloads/)
**电脑要求：** 
-互联网连接，Windows 2000 / XP / 2003 / Vista / 7，Mac OS X或GNU Linux（本指南通过Windows运行)
-安装或创建卷所需的管理员权限，但不能访问现有卷
**本指南中使用的版本：** 7.1a 
_（开发人员网页提供了TrueCrypt的新版本7.2，删除了一些功能。尽管这个新版本，我们建议您继续使用旧版本7.1a。)_ 
**许可证：**免费和开源软件
**等级：**高级
**其他阅读：** [http://andryou.com/truecrypt/docs/index.php](http://andryou.com/truecrypt/docs/index.php)
**所需时间：** 30-60分钟

**使用TrueCrypt会给你：**  - 能力t o有效保护您的文件免受入侵者或未经授权的访问
能够轻松安全地存储重要文件的副本

**注意：TrueCrypt目前无人维护，可能会有安全隐患。**![image](tool_truecrypt1.png)

### 1.0开始之前

通过防止没有正确密码的人打开文件，加密可以保证文件的安全。它像电子保险柜一样工作，在您的计算机或硬盘驱动器上创建一个加密容器（称为音量)，您可以随意放置多个文件。如果您忘记了密码，您将无法访问您的数据！ 

请注意，在某些国家使用加密是非法的。 

TrueCrypt提供了创建标准加密卷或隐藏卷的功能。任何一个都将保留您的文件的机密性，但是隐藏卷允许您将重要信息隐藏在较不敏感的数据后面，以便保护它，即使您不得不泄露您的TrueCrypt卷。本指南详细介绍了这两个卷。

- 	如何安装TrueCrypt和创建标准卷
-	如何安装标准卷
- 	如何备份卷
- 	隐藏卷
-  	Portable TrueCrypt 

**_注意：TrueCrypt目前未被维护，可能会有安全隐患。如何安装TrueCrypt并创建标准卷_**

### 2.0如何安装TrueCryrpt 

**第1步。**双击 _TrueCrypt安装程序7.1a.exe_; 可能会出现 _Open File  -  Security Warning_ 对话框。如果确实如此，请点击“下一步”以激活TrueCrypt _License_ 屏幕。


**步骤2.** 检查我接受并同意接受_license terms_选项以启用接受按钮;点击 "Accept" 激活以下屏幕：
！[image](tool_truecrypt2.png)

-安装模式：此选项适用于不想隐藏使用TrueCrypt的用户他们的电脑。 
-解压缩模式：此选项适用于希望在USB记忆棒上携带TrueCrypt的便携版本，并且不希望在其计算机上安装TrueCrypt的用户。

**注意：**当只提取TrueCrypt时，选项（例如整个分区和磁盘加密)将不起作用。

**注意：**尽管此处推荐使用默认的_Install_模式，但您以后仍然可以在便携模式下使用TrueCrypt。 

**第3步。点击** "下一步”激活以下屏幕：
！[image](tool_truecrypt3.png)

**第4步。** “以激活_Installing_屏幕开始在您的系统上安装TrueCrypt。

步骤5. 
单击”确定“，然后单击”完成“以激活以下屏幕：
！[image](tool_truecrypt4。 png)

**第6步。**点击“是”完成TrueCrypt安装。注意：**强烈建议所有用户参考[TrueCrypt帮助文档](http：//andryou.com/truecrypt/docs/index.php)。**

### 2.1关于TrueCrypt 

TrueCrypt是一个通过防止没有正确密码的人访问文件来保护文件的程序。它的功能就像一个电子保险箱，让你锁定你的文件，只有拥有正确密码的人才能打开它们。 TrueCrypt通过让您在计算机上设置_volumes_或部分来安全地存储文件。当您在这些卷中创建数据或将数据移动到这些卷时，TrueCrypt将自动加密该信息。打开或取出文件时，会自动解密以供使用。这个过程称为_on-the-fly_加密。

### 2.2如何创建标准卷

使用TrueCrypt可以创建两种卷：_Hidden_​​和_Standard_。在本节中，您将学习如何创建用于存储文件的 _Standard Volume_ 。

要开始使用TrueCrypt创建 _Standard Volume_ ，请执行以下步骤：

**第1步。点击TrueCrypt图标或选择**开始>程序> TrueCrypt > TrueCrypt 打开TrueCrypt。

**第2步。**从TrueCrypt窗格的列表中选择一个驱动器，如下所示： n！[image](tool_truecrypt5.png)

**第3步。**点击“Create Volume”激活_TrueCrypt卷创建向导_，如下所示：
！[image](tool_truecrypt6.png)

加密_Standard Volume 
有三个选项。在本指南中，我们将使用“创建加密文件容器”选项。请参阅**[TrueCrypt 文档](www.truecrypt.org/docs/)**以获得其他两个选项的说明。

**第4步。**点击“下一步”以激活以下屏幕：
！[image](tool_truecrypt7.png)

使用
TrueCrypt卷创建向导Volume Type_窗口可以指定是否希望创建_Standard_或_Hidden ** TrueCrypt **_卷。_**

有关如何创建隐藏卷的更多信息，请参阅隐藏卷部分。

**步骤5.** 检查_Standard TrueCrypt卷_选项。

**第6步。** 点击"下一步"激活以下屏幕：
！[image](tool_truecrypt8.png)

您可以在_Volume Creation Wizard  -  Volume Location_屏幕中指定要存储 _Standard Volume_ 的位置。此文件可以像任何其他文件一样存储。

**第7步。** 将文件的名称输入到文本字段中，或者单击“选择文件”以激活以下屏幕：
！[image](tool_truecrypt9.png)

**注：** TrueCrypt卷包含在普通文件中。这意味着它可以被移动，复制甚至删除！您需要记住文件的位置和名称。但是，您必须为您创建的卷选择新的文件名。在本教程中，我们将在**我的文档文件夹**中创建我们的标准卷，并将文件命名为_My Volume_，如上面的图8所示。

**提示：**您可以使用任何文件名和文件扩展名。例如，您可以命名标准卷_recipes.doc_，使其看起来像_Word_文档或_holidays.mpg_，因此它看起来像电影文件。 

**第八步。**点击“Save”关闭_Specify Path_和_File Name_窗口并返回到_Volume Creation Wizard_窗口如下图所示：
！[image](tool_truecrypt10.png)

**第9步。**点击“下一步”。

### 2.3如何在USB记忆棒上创建标准音量

要在USB记忆棒上创建TrueCrypt  _Standard Volume_ ，请执行第2.2节“如何创建标准卷”中的第1步到第7步，在该步骤中激活_选择TrueCrypt卷_屏幕。选择 _My Documents_ 作为您的文件位置，而不是选择 **您的** USB记忆棒。然后**输入**一个文件名，并在那里创建 _Standard Volume_ 。

### 2.4如何创建一个标准卷（续)

在这个阶段，您已经准备好选择一个特定的加密方法（或 _algorithm_，因为它在屏幕上被引用)来编码将被存储在_Standard Volume _中的数据_。
[image](tool_truecrypt11.png)

**注意：**您可以离开默认选项，因为它们出现。所有在这两个选项中出现的算法都被认为是安全的。

**第10步。**点击“下一步”激活_TrueCrypt卷创建向导_屏幕如下：
！[image](tool_truecrypt12.png )

_Volume Size_ 窗格可让您指定  _Standard Volume_  的大小。在这个例子中，它被设置为10兆字节。但是，您可以指定不同的大小。考虑您想存储的文档和文件类型的大小，然后为它们设置适当的卷大小。

**提示：**如果您稍后想要将标准卷备份到CD，那么你应该把大小设置为700MB或更少。

**第11步。**在文本字段中输入特定的卷大小，然后点击“下一步”激活以下屏幕：
！[image](tool_truecrypt13.png)

**重要提示：**选择一个安全和强壮的密码是创建  _Standard Volume_  时要执行的最重要的任务之一。一个好的密码可以保护你的加密音量，而且你选择的密码越好越好。如果您使用像KeePass这样的密码生成程序，您不必创建自己的密码，甚至不需要记住它们。请参阅 **[KeePass课程](umbrella：//lesson/keepassx)**以了解更多关于密码创建和存储的信息。

**步骤12：**输入您的密码，请将密码输入到_Confirm_文本字段中。

**重要提示：**在两个文本字段中的密码匹配之前，_Next_ 按钮将保持禁用状态。如果您的密码不是特别安全或不安全，您会看到一条警告提示您。考虑改变它！虽然 **TrueCrypt**仍然可以使用您选择的任何密码，您的数据可能不是很安全。

**第13步。**点击“下一步”激活以下屏幕：
！[image](tool_truecrypt14.png)

TrueCrypt现在可以创建一个  _Standard Volume_ 。在_TrueCrypt卷创建向导_窗口中随机移动鼠标几秒钟。您移动鼠标的时间越长，加密密钥的质量越好。

**第14步。**点击“Format”开始创建标准卷。

TrueCrypt现在将创建一个名为_My在_My Documents_文件夹中的Volume_如前所述。该文件将包含TrueCrypt  _Standard Volume_ ，大小为10 MB，可用于安全地存储文件。

成功创建  _Standard Volume_  后，将出现以下对话框：
！[image]( 

**第15步。**点击“OK”完成创建您的  _Standard Volume_  并返回到TrueCrypt控制台。

**第16步。**点击"退出\ “关闭_TrueCrypt卷创建向导_。

### 3如何安装标准卷

### 3.0如何装入标准卷

在TrueCrypt中，装载 _Standard卷_ 是指制作标准卷可供使用。在本节中，您将学习如何安装新创建的标准卷。

要开始安装标准卷，请执行以下步骤：

**第1步。**双击TrueCrypt图标或** 选择开始\程序> TrueCrypt > TrueCrypt **打开TrueCrypt。**

**第2步。**从列表中选择任何驱动器如下：
！[image](tool_truecrypt16.png)\在此示例中，标准卷将作为M：驱动器安装。注意： **在上图中_M**：_驱动器已被选择用于安装_标准卷_。然后，您可以选择另一个列出的驱动器。

**第3步。**单击"选择文件... "

选择一个TrueCrypt音量屏幕将显示如下：_ 
！[image](tool_truecrypt17.png)

**第4步。**选择您创建的标准卷文件，然后单击“打开”关闭_图2_并返回到TrueCrypt控制台。

**第5步。**点击“Mount”激活提示屏幕的_Enter密码，如下所示：
！[image](tool_truecrypt18.png)

**步骤6.** 在密码中输入密码：_文本字段_。

**第7步。** 单击“OK”开始安装_Standard卷_。

**注意：**如果您输入的密码不正确，TrueCrypt会提示你要重新输入你的密码，然后点击“确定”。如果密码正确，_Standard Volume_ 将被挂载如下：
！[image](tool_truecrypt19.png)

**第8步。**双击TrueCrypt中突出显示的项目，或者双击相应的驱动器在_My Computer_屏幕上的字母以访问 _Standard Volume_（现在安装在您的计算机上的_M：_上_)。
！[image](tool_truecrypt20.png)

**注意：**我们刚成功安装虚拟磁盘上的 _My Volume 标准卷_M：_。这个虚拟磁盘的行为就像一个真正的磁盘，除了它是完全加密的。任何文件在复制，移动或保存到虚拟磁盘时都将被自动加密（一种称为即时加密的过程)。

您可以像复制文件一样将文件复制到 _Standard Volume_ 和 _Standard Volume_ 中到任何正常的磁盘（例如，通过拖放它们)。将文件移出 _Standard Volume_ 时，会自动解密。相反，如果将文件移动到 _Standard Volume_ 上，则TrueCrypt将自动对其进行加密。如果您的计算机崩溃或突然关闭，TrueCrypt将立即关闭_Standard卷_。

**重要提示：**将文件传输到TrueCrypt卷后，请确保没有任何文件的痕迹留在计算机上或USB记忆棒，他们来自。 

### 3.1如何卸载标准卷

在TrueCrypt中，为_dismount_ a  _Standard Volume_ 只是意味着无法使用卷。

要关闭或卸除 _Standard Volume_ 并使其文件只能由具有密码的用户访问，请执行以下步骤：

**第1步。**如下图所示：
！[image](tool_truecrypt21.png)

**第二步。**点击“卸载”卸载或关闭您的TrueCrypt标准音量。

**重要提示：**在将计算机置于_Standby_或_Hibernate_模式之前，请务必卸除TrueCrypt音量。更好的是，如果您打算无人看管，请务必关闭计算机或笔记本电脑。这样可以防止任何人获得密码。

要关闭或卸除存储在标准卷中的文件，您必须重新挂载。
### 4.0备份您的卷

定期备份文档，文件和文件夹至关重要。备份你的TrueCrypt卷是至关重要的，（幸运的是)容易做到。 

**第1步。**导航到您的 _Standard Volume_ 文件（在下图中，它位于_My Documents_文件夹中)。
！[image](tool_truecrypt22.png)

**第2步。**将文件保存到外部存储设备，如CD，DVD或USB记忆棒。

**提示：**如果您有大量要重复加密和存档的数据，为什么不创建一个与CD或DVD大小相同的新 _Standard Volume_ ？这可以用作安全存储技术。

在将标准卷备份到可移动设备之前，请确保设备大小与卷的大小相对应。

### 5.0关于隐藏卷

在TrueCrypt中， _Hidden Volume_ 存储在加密的 _Standard Volume_ 中，但其存在是隐藏的。即使您“挂载”或打开标准音量，也无法找到或证明隐藏音量的存在。如果您不得不泄露您的密码和标准卷的位置，则可能会显示其内容，但是**不是**中隐藏卷的存在。

使用秘密隔间设计一个公文包。你保留的文件，你不介意没收或丢失在你的公文包的正常部分，你把重要的和私人的文件保密的秘密。隐秘隔间（特别是精心设计的隔离隔间)的要点在于隐藏自己的存在，因此隐藏其中的文档。

### 5.1如何创建隐藏卷

创建TrueCrypt  _Hidden Volume_ 类似于创建TrueCrypt  _Standard Volume_ ：某些窗格，窗口和窗口甚至是相同的。

**第1步。**打开TrueCrypt。

**第2步**点击“创建卷”激活_TrueCrypt卷创建向导_。

**第3步。**点击“下一步”接受默认_创建一个加密文件container_选项。

**第四步**检查_Hidden TrueCrypt_卷选项如下：
！[image](tool_truecrypt23.png)

**第五步。**点击“下一步”激活以下屏幕：
！[image](tool_truecrypt24.png)

- _Direct mode_：使用此选项可以在现有的 _Standard Volume_ 中创建 _Hidden Volume_ 。 
-正常模式：这个选项可以让你创建一个全新的 _Standard Volume_ ，用于存储 _Hidden Volume_。

在这个例子中，我们将使用_Direct模式_。

**注意：**如果你宁愿开始一个新的 _Standard Volume_ ，请重复从2.2节如何创建一个标准卷的过程。

**第6步。**检查_Direct Mode_选项，然后点击“下一步”激活_TrueCrypt卷创建 - 卷位置_窗口。

**注意：**确保 _Standard Volume_ 在卸载之前已被卸载。

**第7步。**点击“选择文件”以激活以下屏幕：
！[image](tool_truecrypt25.png)

**步骤8.**使用 _Select TrueCrypt Volume_ 窗口找到卷文件，如上所示。

**第9步。** 点击"打开"返回到 _TrueCrypt卷创建向导_ 。

**步骤10.** 点击“下一步”激活密码输入屏幕

**步骤11。** 输入在_Password_文本字段中创建 _Standard Volume_ 时使用的密码打开以下屏幕：
！[image](tool_truecrypt26.png)

**第12步。**阅读完信息以激活_Hidden Volume Encryptions Options_屏幕后，点击“Next” 
**注意：**同时保留隐藏卷的默认_加密算法_和_散列算法_设置。

**第13步。**单击“下一步”激活以下屏幕： 
！[image](tool_truecrypt27.png)

您将被提示指定_Hidden Volume的大小_。

**注意：**请考虑文档的种类，数量和大小存储。为 _Standard Volume_ 留出一些空间。如果您选择 _Hidden Volume_ 可用的最大大小，则无法将更多新文件放入原始_Standard Volume _中。如果 _Standard Volume_ 的大小为10 MB，并且指定了 _Hidden Volume_ 大小为5MB（如上面的图6所示)，您将拥有两个大小各为5MB的卷（一个隐藏卷和一个标准卷)。

确保您存储在 _Standard Volume_ 中的信息不超过您拥有的5MB组。这是因为TrueCrypt程序本身不会自动检测 _Hidden Volume_ 的存在，并且可能会意外覆盖它。如果您超出了以前建立的大小，您可能会丢失存储在隐藏卷中的所有文件。

**第14步。**将所需的隐藏卷大小输入到相应的文本框中，如下图所示。 n 
**第15步。**点击“下一步”激活_隐藏音量密码_窗口。

现在您必须为用于保护标准音量的隐藏音量创建一个_different_密码。再一次，请记住选择一个强大的密码。请参阅
**[KeePass工具指南](umbrella：//lesson/keepassx)**以了解更多关于创建强密码的信息。

**提示：**如果您预计被迫泄露内容您的TrueCrypt卷，然后将标准卷的密码存储在KeePass中，并创建一个强密码，您只需要记住隐藏的音量。这将帮助您隐藏隐藏的音量，因为您不会留下任何痕迹。

**第16步。**创建一个密码并输入两次，然后单击“下一步”以激活以下屏幕：
！[image](tool_truecrypt28.png)
保留默认的_File System_和_Cluster_选项。


**第17步。**将鼠标指针移到屏幕上增加加密的加密强度，然后单击"Format "格式化隐藏卷。

_隐藏的音量格式化后，出现以下屏幕：_ 
！[image](tool_truecrypt29.png)

**注意：** _图8_ 两者都证实您已成功创建了一个隐藏卷，并警告您在将文件存储到标准卷时覆盖隐藏卷中的文件的危险。

**第18步。**点击“确定”以激活 _Hidden Volume Created_ 窗口，然后点击"退出"并返回到TrueCrypt控制台。

隐藏的音量现在已经被创建你的标准音量。您现在可以将文档存储在隐藏的卷中，即使对于已经获得该特定标准卷的密码的用户，这些文档仍然是不可见的。

### 5.2如何安装隐藏卷

安装或制作方法可以使用的 _Hidden Volume_ 与 _Standard Volume_ 完全相同;唯一的区别是您将使用您为 _Hidden Volume_ 创建的密码。

要_mount_或打开 _Hidden Volume_ ，执行以下步骤：

**第1步。** （在这个例子中，驱动器 _K_)：
！[image](tool_truecrypt30.png)

**第二步。**点击“选择文件...”激活选择一个TrueCrypt卷_窗口。

**第3步。**导航到，然后选择您的_TrueCrypt_卷文件（与标准卷相同的文件)。

**步骤4.** 点击“打开”返回到TrueCrypt控制台。

**第五步。** 点击“Mount”激活提示屏幕的_Enter Password_，如下所示：
！[image](tool_truecrypt31.png)

**步骤6。** 输入用于创建隐藏卷的密码，然后单击"确定"。

您的隐藏卷现在按以下方式安装（或打开)：
！[image](tool_truecrypt32.png)

**第7步。**双击上述条目或通过_My Computer_窗口访问它。

### 5.3如何使用隐藏磁盘的提示Fe ature安全

隐藏磁盘功能的目的是为了逃避一个潜在的危险情况_appearing_移交你的加密文件，当有人在权力要求看到他们，而不必被迫泄露你最敏感的信息。除了保护您的数据，这可能会使您避免进一步危及自己的安全或暴露您的同事和合作伙伴。为了使这种技术有效，您必须创建一个情况，要求查看您的文件的人将通过您向他们展示的内容满足您的要求并让您离开。

要执行此操作，您可能需要执行以下某些建议：

-将一些您不介意的机密文件放在标准卷中。这些信息必须足够敏感，以便将其保存在加密卷中。 
-请注意，有人要求查看您的文件可能知道隐藏卷。但是，如果您正确使用TrueCrypt，则此人将无法证明您的隐藏卷存在，这将使您的拒绝更可信。 
-每周更新标准卷中的文件。这会造成您确实在使用这些文件的印象。

无论您何时挂载TrueCrypt卷，都可以选择启用_Protect隐藏卷，以防止因写入外部卷volume_功能而造成的损坏。一个非常重要的功能，它可以让您添加新的“诱饵”文件到您的标准卷，而没有意外删除或覆盖隐藏卷的加密内容的风险。

如前所述，超过标准卷的存储限制否则可能会破坏您的隐藏文件。当强制安装TrueCrypt卷时，请勿启用_Protect hidden volume_功能，因为这样做需要您将密码输入到隐藏卷中，并清楚地显示该卷的存在。但是，如果要私密更新诱饵文件，则应该_always_启用此选项。

要使用_Protect hidden volume_功能，请执行以下步骤：

**第1步。** 选项...“在上图中显示的_Enter Password_提示符下。这将激活_Mount选项_窗口，如下所示：
！[image](tool_truecrypt33.png)

**第2步。**检查_Protect隐藏卷防止写入外部卷volume_选项造成的损坏。

**第3步。**输入隐藏卷密码，然后点击“确定”。

**第4步。**点击“Mount”安装标准卷。成功安装后，您将能够添加诱饵文件，而不会损坏您的隐藏卷。

**第5步。**单击“卸除”卸载，或使您的标准卷不可用，当你完成修改它的内容。

**记住：**您只需要在更新标准卷中的文件时执行此操作。如果被迫向其他人显示标准音量，则不应使用_Protect隐藏音量_功能。

### 6.便携式TrueCrypt 
！[image](tool_truecrypt34.png)

加密保留您的文件通过防止没有正确密码的人打开隐藏的文档和文件来确保安全。它可以像电子保险柜一样工作，您可以使用它来安全地锁定您的文件。

### 6.1安装的和便携式的TrueCrypt版本之间的区别

鉴于便携式工具未安装在本地计算机上，它们的存在和使用可能仍未被发现。但请记住，您的外部设备或USB记忆棒以及便携式工具只与您使用的计算机一样安全，并可能冒着暴露于广告软件，恶意软件，间谍软件和病毒的风险。

与许多便携式软件工具在这里记录，便携式TrueCrypt允许您使用一个功能强大而简单的文件加密工具，而不被检测到。将便携式TrueCrypt放在可移动设备或USB记忆棒上，可以让您在不同的工作站上使用它。

便携式TrueCrypt的安装和便携版本之间几乎没有什么区别，主要的一点是便携式TrueCrypt不允许加密整个磁盘或系统磁盘。

### 6.2下载，提取和使用便携式TrueCrypt 

**注意：**必须在可移动设备上手动创建要将Portable TrueCrypt提取到的文件夹，USB记忆棒或电脑磁盘。\​​ n 
**第1步。**导航到要将便携式TrueCrypt程序提取到的所选目标位置，然后右键单击以激活其相关菜单。 

**第2步。**选择_New item_激活其子文件夹，然后选择_Folder_子菜单项，如下所示：
！[image](tool_truecrypt35.png)

**第3步。**输入文件夹的名称。

**注意：**您可以给这个文件夹一个不太明显的名称来隐藏便携式TrueCrypt程序的存在。

便携式TrueCrypt可以从与安装版本相同的存档中提取：

**步骤1.**导航到计算机上的TrueCrypt安装文件。

**第2步。**双击_TrueCryptSetup7.1.a.exe_;可能会出现_Open File  -  Security Warning_对话框;如果是，请点击“是”激活TrueCrypt安装向导。

**步骤5.** 检查Extract选项以将TrueCrypt移植到可移动驱动器或USB设备，如下所示：
！[image](tool_truecrypt36.png)

**第6步。**点击“下一步”激活以下两个屏幕：
！[image](tool_truecrypt37.png)！[image](tool_truecrypt38.png )

**分别点击** "确定"和"是"，激活**提取选项**窗口，如下所示：
！[image](tool_truecrypt39.png)

**第7步。**点击“浏览”按钮激活文件夹浏览窗口：
！[image](tool_truecrypt40.png)

**步骤8.** 导航到目标文件夹在外部驱动器或USB记忆棒上，然后点击“OK”，返回_Extraction Options_窗口如下：
！[image](tool_truecrypt41.png)

**第9步。** 点击“Extract”开始提取TrueCrypt到您的可移动驱动器或USB记忆棒;几秒钟后，将会出现以下窗口：
！[image](tool_truecrypt42.png)

**第10步。**点击“确定”，然后点击“完成”安装过程。

_如果启用了“打开目标位置，当fininshed”选项被启用（因为它通常是默认情况下)，将出现以下屏幕：_ 

**第11步。**导航到然后双击_TrueCrypt.exe_运行便携式TrueCrypt。

从这一点开始，请参阅上述常规TrueCrypt的说明，了解更多有关如何使用TrueCrypt的信息。

### 6.3如何消除所有痕迹提取便携式TrueCrypt 

**重要提示：**成功提取便携式TrueCrypt到您的外部/可移动设备后，您必须从您的计算机上删除安装文件，以进一步消除您已下载和安装的任何痕迹TrueCrypt。

**第1步。**导航至下载了Portable TrueCrypt的文件夹，然后右键单击_TrueCryptSetup 7.1.a.exe_安装文件激活Windows弹出式菜单;然后选择“删除”命令将其移动到您的回收站中。

**第二步。**双击回收站打开关联的窗口，然后选择并删除文件。

**注意：**如果您安装了CCleaner或橡皮擦，您可以使用它们中的任何一个来消除您曾经下载并安装过的Portable TrueCrypt的所有痕迹。请参阅** [安全删除课程](伞：//课程/安全删除)**了解更多关于如何执行此操作的信息。