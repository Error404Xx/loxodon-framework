![](docs/images/icon.png)

# Loxodon Framework

[![license](https://img.shields.io/badge/license-MIT-blue.png)](https://github.com/cocowolf/loxodon-framework/blob/master/LICENSE)
[![release](https://img.shields.io/badge/release-v1.7.6-blue.png)](https://github.com/cocowolf/loxodon-framework/releases)

[(中文版)](README_CN.md)

**MVVM Framework for Unity3D(C# & XLua)**

*Developed by Clark*

Requires Unity 5.6.0 or higher.

LoxodonFramework is a lightweight MVVM(Model-View-ViewModel) framework built specifically to target Unity3D.
Databinding and localization are supported.It has a very flexible extensibility.It makes your game development faster and easier.

For tutorials,examples and support,please see the project.You can also discuss the project in the Unity Forums.

The plugin is compatible with MacOSX,Windows,Linux,UWP,IOS and Android,and provides all the source code of the project.

**Tested in Unity 3D on the following platforms:**  
PC/Mac/Linux  
IOS  
Android  
UWP(window10)

## Downloads  
- [AssetStore](https://www.assetstore.unity3d.com/#!/content/77446)
- [Releases](https://github.com/cocowolf/loxodon-framework/releases)

## Key Features:
- MVVM Framework;
- Multiple platforms;
- Higher Extensibility;
- XLua support(You can make your game in lua.);
- Asynchronous result and asynchronous task are supported;
- Scheduled Executor and Multi-threading;<br>
- Messaging system support;
- Preferences can be encrypted;
- Localization support;
- Databinding support:
    - Field binding;
    - Property binding;
    - Dictionary,list and array binding;
    - Event binding;
    - Unity3d's EventBase binding;
    - Static property and field binding;
    - Method binding;
    - Command binding;
    - ObservableProperty,ObservableDictionary and ObservableList binding;
    - Expression binding;
    
## Notes  
- LoxodonFramework supports .Net2.0 and .Net2.0 Subset  
- LoxodonFramework supports .Net4.x and .Net Standard2.0  
- LoxodonFramework supports Mono2x and IL2CPP  
- AOT Compilation Options: "nrgctx-trampolines=8192,nimt-trampolines=8192,ntrampolines=8192" for IOS  

## Tutorials and Examples

- [Tutorials](https://github.com/cocowolf/loxodon-framework/tree/master/Assets/LoxodonFramework/Tutorials)
- [Examples](https://github.com/cocowolf/loxodon-framework/tree/master/Assets/LoxodonFramework/Examples)

## Chinese manual

- [HTML](https://github.com/cocowolf/loxodon-framework/blob/master/docs/LoxodonFramework.md)
- [PDF](https://github.com/cocowolf/loxodon-framework/blob/master/Assets/LoxodonFramework/Docs/LoxodonFramework.pdf)

## Quick start of Loxodon.Framework.XLua
- You can download the latest version of xlua from Xlua's Github repository,the file name is usually xlua_v2.x.xx.zip, unzip and copy it to your project.([XLua Download](https://github.com/Tencent/xLua/releases))
- Configure a macro definition called "XLUA" in PlayerSetting/Scripting Defin Symbols.It is recommended to configure all platforms.
- Find Loxodon.Framework.XLua.unitypackage in the LoxodonFramework/Docs/XLua directory and import it into the project.
- Please see the example in the LoxodonFramework/Lua/Examples directory to enjoy your lua tour.

## Introduction
- Window View 
  ![](docs/images/Window.png) 
- Localization 
  ![](docs/images/Localization.png) 
- Databinding 
  ![](docs/images/Databinding.png) 
- Variable Example 
  ![](docs/images/Variable.png) 
- ListView Binding 
  ![](docs/images/ListView.png) 

## Contact Us
Email: [yangpc.china@gmail.com](mailto:yangpc.china@gmail.com)   
Website: [https://cocowolf.github.io/loxodon-framework/](https://cocowolf.github.io/loxodon-framework/)  
QQ Group: 622321589 [![](https://pub.idqqimg.com/wpa/images/group.png)](https:////shang.qq.com/wpa/qunwpa?idkey=71c1e43c24900ee84aeffc76fb67c0bacddc3f62a516fe80eae6b9521f872c59)




