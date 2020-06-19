### Open3D: 一个现代化的3D数据处理库
> Open3D是一个开放源代码库，支持快速开发处理3D数据的软件。前端在C ++和Python中公开了一组精心选择的数据结构和算法，后端经过高度优化，并设置为并行化。
---
1. Open3D的核心功能包括：
   - 3D数据结构
   - 3D数据处理的算法
   - 场景重建
   - 表面对齐
   - 3D可视化
   - 基于物理的渲染
   - C++接口和Python接口
2. Open3D viewer app
    Open3D现在带有在Ubuntu和macOS上可用的独立3D查看器应用程序。[github下载](https://github.com/intel-isl/Open3D/releases)
3. Python quick start
    在系统Ubuntu18.04以上、macOS10.14以上和Windows 10（64位）支持使用pip和conda进行安装，Python版本支持3.5、3.6、3.7和3.8。如果是其它系统或者是其它Python版本，请通过源码进行安装：
    - To install Open3D with pip:

      ```pip install open3d```
    - To install Open3d with conda:

      ```conda install -c open3d-admin open3d```
    - To compile Open3D from source
       - see [compiling from source](http://www.open3d.org/docs/release/compilation.html)

    Test your installation with:

      ```python -c import open3d as o3d```

      and follow the [basic tutorials](http://www.open3d.org/docs/release/tutorial/Basic/index.html) or [Python examples](https://github.com/intel-isl/Open3D/tree/master/examples/Python) to get started
4. C++ quick start
    Please refer to [compiling from source](http://www.open3d.org/docs/release/compilation.html) and [Open3D C++ interface.](http://www.open3d.org/docs/release/tutorial/C++/cplusplus_interface.html)
5. Communication channels
   - [GitHub Issue](https://github.com/intel-isl/Open3D/issues/): bug reports, features requests, etc.
   - [Forum](https://forum.open3d.org/): discussion on the usage of Open3D.
   - [Discord Chat](https://discord.gg/D35BGvn): online chats, discussions, and collaboration with other users and developers.
