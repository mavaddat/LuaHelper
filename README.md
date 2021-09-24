# LuaHelper

LuaHelper is a free lua plugin. Intellisense, Linting, Debugging, Code formatting, High-performance, and more.

## Introduction

Lua is very popular in game development because of its simple syntax and flexible use. But its ecology is not perfect, IDE development tools and supporting support are few, which affects the development efficiency and quality of Lua to a certain extent. LuaHelper complies with the Microsoft Language Server Protocol and is a cross-platform Lua code editing and detection tool developed using the go language.

Compared with other Lua plugins currently on the market, it has the following **improvements**:

-[X] 1. Coroutine development, real-time detection, output detection results in milliseconds
-[X] 2. Support large-scale Lua projects, perfect support for editing and testing of projects with 1000+ files
-[X] 3. Comprehensive error type detection, including: syntax detection, semantic detection
-[X] 4. Various types of reference search, including: multi-file reference search, multi-layer reference search
-[X] 5. Abundant configurable items, including: multiple alarm information configuration, ignorable file settings
-[X] 6. Low memory consumption, low-performance machines can still run smoothly

## Documentation

* [Background [Project Background]](./docs/manual/introduction.md "Project Background Introduction")
* [Configuration [Check Configuration]](./docs/manual/config.md "Check Configuration")
* [Manual [source introduction]](./docs/manual/mainsource.md "source introduction")

## Features

### Editing assistance

* [Defintion Find [Definition Jump]](./docs/manual/Feature.md/#DefintionFind)
* [Find All References [reference search]](./docs/manual/Feature.md/#FindAllReferences)
* [Document Symbols [Document Symbol Table Query]](./docs/manual/Feature.md/#DocumentSymbols)
* [Workspace Symbols [Engineering symbol table query]](./docs/manual/Feature.md/#WorkspaceSymbols)
* [Auto Code Completion [Auto Code Completion]](./docs/manual/Feature.md/#AutoCodeCompletion)
* [Format Code [code format]](./docs/manual/Feature.md/#FormatCode)
* [Hover [Code hover]](./docs/manual/Feature.md#Hover)
* [Hightlight Global Var [Global Variable Coloring]](./docs/manual/Feature.md/#HightlightGlobalVar)

### Code detection

* [Syntax Check [Syntax Check]](./docs/manual/Feature.md/#SyntaxCheck)
* [Semantic Check [Semantic Check]](./docs/manual/Feature.md/#SemanticCheck)
* [Quick Analysis [Quick Incremental Analysis]](./docs/manual/Feature.md/#QuickAnalysis)

### Code debugging

The debugging function integrates the debugging components of Tencent open source [LuaPanda](https://github.com/Tencent/LuaPanda), and uses the [Debug Adapter Protocol](https://microsoft.github.io/debug-adapter-protocol/ ) Debugging protocol. The main body of the debugger is developed in lua language, and the debugger only needs to import the LuaPanda.lua file to enable the debugging function.

* [Debug Principle [Debug Principle]](./docs/manual/debugPrinciple.md)
* [Debug Use [Access debugging method]](./docs/manual/usedebug.md)
* [Debug and Run Sigle Lua File [Single File Debug and Run]](./docs/manual/debugsinglefile.md)

## Installation

**App market installation**

* Click the Vs Code application market icon
* Search luahelper in the input box
* Click to install Lua Helper

![avatar](https://raw.githubusercontent.com/yinfei8/LuaHelper/master/images/Install.gif)

**App Market Abnormal**

Click [app link](https://marketplace.visualstudio.com/items?itemName=yinfei.luahelper&ssr=false#overview) and try to install again

## Acknowledgements

* [luago-books](https://github.com/zxh0/luago-book), Go language generates lua AST, modified the source code (adding column attributes for each node of the AST, and also optimizing performance ).
* [LuaFormatter](https://github.com/Koihik/LuaFormatter), a Lua code formatting library written in c++, with high performance.
* [LuaPanda](https://github.com/Tencent/LuaPanda), integrates the debugging components of LuaPanda, LuaPanda author stuartwang also provided us with a lot of help.
* [EmmyLua](https://github.com/EmmyLua), the author, Tang, provides a lot of help and suggestions for the implementation of our entire plugin.

## Support

If you have any questions about LuaHelper, please refer to [FAQ](#FAQ) first. If you have any questions, please use [issues](https://github.com/yinfei8/LuaHelper/issues). We will pay attention and reply.

Email: yvanfyin@tencent.com; handsomeli@tencent.com; richardzha@tencent.com</br>
QQ group: 747590892
