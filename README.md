# Ball


一、工程文件
1.C#工程文件
●Assembly-CSharp-vs.csproj：VS
●.Assembly-CSharp.csproj：MonoDevelop
2.JS工程文件
●.Assembly-UnityScript-vs.unityproj：VS
●.Assembly-UnityScript.unityproj：MonoDevelop
二、IDE的解决方案文件
1.testproject.sln ：包含C#、JS、Boo全部脚本的工程
2.testproject-csharp.sln ：只包含C#的工程，只能在VS中打开，因为VS无法处理JS和Boo脚本。
三、用户配置
.userprefs 文件：保存用户文件打开，断点和监视等配置。
四、注意
每次在U3d中同步MonoDevelop,所有文件除了.userprefs 文件都会重新生成。
五、提示
1.MonoDevelop同步完成后，会打开project.sln，但是如果只有c#脚本可以选择project-csharp.sln，此时能够减少至少2倍的文件数量而且不会有关于JS的报错。
六、文件夹的
1.Assets：所有的资源：脚本、纹理、声音等等。毫无争议，最重要的文件夹
2.ProjectSettings ：记录我们在Edit->ProjectSetting菜单下的配置。如Physics、Tag、Player等的设置。
3.Libray：本地对重要资源的缓存，当我们使用自己的版本控制器的时候可以忽略它。
4.obj和Temp：在创建期间生成的临时文件，obj是MonoDevelop生成的，Temp是Unity生成的。
七、关键
项目文件只需要同步和版本控制：Assets 和 ProjectSettings 文件夹。
