## Blazor Hybrid Demo
在 Blazor Hybrid 应用中，Razor 组件在设备上本机运行。   
组件通过本地互操作通道呈现到嵌入式 Web View 控件。 组件不在浏览器中运行，并且不涉及 WebAssembly。   
Razor 组件可快速加载和执行代码，组件可通过 .NET 平台完全访问设备的本机功能。  

Blazor Hybrid 支持 .NET MAUI/WPF/WinForms  
对于 WPF/WinForms 仅支持 net6.0+  

在 Windows 上需要 WebView2，WinForms 应该是目前体积最小的方案
最终独立发布大小为 156MB 不包含 WebView2 Runtime，包含后应该有 300MB+  

不考虑体积的问题，相比于 Electron 是个不错的方案