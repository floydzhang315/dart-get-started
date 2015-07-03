# 运行一个web应用程序

从 Dart 编辑器允许一个简单的应用程序

 - 选中 `index.html` 文件
 - 点击运行按钮
 
Dart 编辑器调用 Dartium 为简单应用程序的 HTML 文件提供的 URL 。 Dartium 加载简单应用程序的 HTML 文件和嵌入式应用程序,它在浏览器中输出的 `“Your Dart app is running”` 。

## 以 JavaScript 脚本方式运行

您可以通过将 Dart 的 Web 应用程序编译成 JavaScript 来让它运行在其他浏览器上。 Dart 编辑器提供了一个方便的菜单选项。右键单击 `index.html` 并从菜单中选择 `run as JavaScript` 。

Dart 编辑器会编译应用程序为 JavaScript 脚本并调用您的默认浏览器来运行该应用程序。