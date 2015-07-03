# 创建一个命令行程序

在 Dart 编辑器中,在菜单中选择 `File > New Project` 或点击 `New Project button` 按钮。会出现一个对话框,要求您填写一个简单的表单。

1. 在 `Application Name` 的文本框中输入 **helloworld** 作为应用名称。按照惯例,应用程序名是小写的。这个名字是用于应用程序的目录。
2. 输入或者浏览到你想要保存的文件的目录。默认情况下, Dart 编辑器在您的主目录中会创建一个新的目录，命名为 `dart`。
3. 从列表中选择 `Console Application` 。
4. 单击 `Finish` 。

Dart 编辑器为应用程序创建一个目录，为小型命令行应用程序创建样板文件。 `Files view` 为这些应用程序呈现文件的层次结构。

在 **helloworld** 应用程序中的文件和目录包括以下几个:

##  Helloworld

包含一个简单的命令行应用程序的样板文件和目录。
 
## Pubspec.yaml

声明应用程序的需要哪些库。packages目录包含了这些库。pubspec.lock文件指定了应用程序所依赖的库的版本号。
 
## Bin

包含应用程序的源文件。这个示例的主要源文件是main.dart。
 
## Main.dart

包含了这个dart程序的源代码。

在 `Editor pane` 中显示 **main.dart** 的内容。程序使用 `print()` 函数输出 `“Hello,World !“` 到标准输出流,这是由 **dart:core** 库提供的。 core 库中定义的函数和对象会自动对所有 Dart 程序可用。