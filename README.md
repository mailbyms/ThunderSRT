# ThunderSRT
迅雷字幕下载工具，使用迅雷api下载字幕文件。
参考[thunder-subtitle](https://github.com/weaming/thunder-subtitle)算法编写，用WPF编写了一个界面，方便使用。

**使用方法：**
 1. 将视频文件拖放到窗口，会自动获取可用字幕列表
 2. 选择要下载的字幕，点击下载按钮，会自动下载字幕文件

# 编译说明
1. 按 Visual Studio 提示，下载 [.Net Framework 4.7](https://dotnet.microsoft.com/download/visual-studio-sdks?utm_source=getdotnetsdk&utm_medium=referral)
2. 设置 NuGet 源件源：  
  工具>选择NuGet管理器>程序包管理器设置，选择NuGet包管理器>程序包源>添加获取包源位置`https://www.nuget.org/api/v2/`, 名称可随意