1. 下载<u>mingw64.zip</u>、<u>cmake-3.13.5-win64-x64.zip</u>和<u>atom-x64-windows.zip</u>

2. 解压

3. 添加环境变量：

   ![](https://ae01.alicdn.com/kf/Hfa916ac8f1b648edb1dc65f5f4fa40e3c.png)

   ![](https://ae01.alicdn.com/kf/H22224547bb524470890836dc133df6d7b.png)

   在<u>path</u>的变量值**最后**添加 <font size=7>;mingw64解压后的文件夹\\**mingw64\bin**</font>和<font size=7>;cmake-3.13.5-win64-x64解压后的文件夹**\\bin**</font>

   （假如你的解压路径如下，就在变量值**最后**上添加 <font color=red>;D:\MinGW-w64\mingw64\bin</font> 注意第一个分号不能漏；cmake也是如此）

   ![](https://ae01.alicdn.com/kf/H2101b10d03e345b1845964079ad59698A.png)

   新建系统变量

   ![](https://ae01.alicdn.com/kf/H90ac6ea3dcfa4f3096dc3de458537a0ex.png)
   
   在变量名输入**ATOM_HOME**，变量值为<font size=7>atom-x64-windows解压后的目录\\**.atom**</font>
   
   ![](https://ae01.alicdn.com/kf/H773ed13875f14c57bff4e40558db43a4n.png)

   （假如你的解压路径如下，就在变量值上添加 <font color=red>D:\atom-x64-windows\\.atom</font> 注意“点”不能漏，且**没有**分号）

   ![](https://ae01.alicdn.com/kf/H038ed8614f0a4893b365bf95896c57ce3.png)

   win 10 的path环境变量设置结果图 如下
   
   ![](https://ae01.alicdn.com/kf/He707a73115064a9bb5abc7dc9a797a29i.png)


4. 设置atom：

   双击atom-x64-windows解压后的目录\\atom\atom.exe，进入atom（如果界面有中文，说明设置成功）

   ![](https://ae01.alicdn.com/kf/Hb7dd15cc5ef24e8788ae0c1aff2fbf19f.png)

   设置右键菜单：

   先进入偏好设置

   ![](https://ae01.alicdn.com/kf/H11f978d0654a40b1ad7e0e96344d114aw.png)

   再点击系统栏，将所有项目打勾

   ![](https://ae01.alicdn.com/kf/H16d2c00c4614445f8fa3b5f1035401f5X.png)
   
   **关闭atom**

5. 测试程序

   找一个空目录右键Open with Atom ，如果找到Open with Atom 说明上一步设置成功

   ![](https://ae01.alicdn.com/kf/H1482c92594b54ec6b8ba3f888d70f616P.png)

   ![](https://ae01.alicdn.com/kf/H8ee26280e82545bbb271b7399a183512G.png)

   如果没有找到Project栏，可以用键盘输入快捷键`ctrl`+`B`，点击Create files from template后，选择CMakeLists template（自动创建编译C语言设置文件）

   ![](https://ae01.alicdn.com/kf/H94fa7a2788984fe2ab04a9ff2ad109e7i.png)

   ![](https://ae01.alicdn.com/kf/H75b1793af5e24ce7aae809c85bcbc8057.png)

   在Project栏添加新文件

   ![](https://ae01.alicdn.com/kf/H0cf4254114204e479fac8ddd21799bc9x.png)

   文件名为main.c

   ![](https://ae01.alicdn.com/kf/H536720dbcbdf49ed94ce31a7eb9d0822L.png)

   ![](https://ae01.alicdn.com/kf/H73265a648946411cbc7d3ffac57802acv.png)

在键盘输入快捷键`ctrl`+`alt`+`T`（或者`shift`+`alt`+`T`）

![](https://ae01.alicdn.com/kf/H4ea6720a6f6c44428b8e0c679f78b7511.png)

（输入第一行代码的结果）

![](https://ae01.alicdn.com/kf/H35d154544f36492aaa95e14d7f1ace268.png)

（输入第二行代码的结果）

![](https://ae01.alicdn.com/kf/Hb5594c85ebe64d1fb8ea4e9c1f388b385.png)

（输入第三行代码的结果）

![](https://ae01.alicdn.com/kf/H41913c9810cc47c88b4c45f176cbde49o.png)


