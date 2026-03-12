Python 虚拟环境（Virtual Environment）Python 3.3+ 自带<br>
**venv**创建一个虚拟环境，实际上它只是一个带有几个shell脚本和一个指向Python解释器的链接的文件夹`.venv`激活环境后，所有安装的库都存储在这个文件夹中。<br>

虚拟环境可以保持项目的隔离。每个程序都需要一定的环境设置才能干净地运行。而且在大多数情况下，操作系统的环境（主要是 Linux）会干扰应用程序的环境依赖。<br>

再者，使用虚拟环境可以为项目安装特定的库、选择特定版本的Python。通过在当前环境中运行“`pip freeze > requirements.txt`”来创建一个`requirements.txt`文件，文件将包含运行项目所需的所有库。

---

1. 不移动虚拟环境。只移动代码和资源/配置文件。

2. 创建requirements.txt文件，这样会很容易重建虚拟环境。

3. 使用git作为代码管理工具移动代码。使用GitHub和GitLab作仓库。

---

>创建虚拟环境：在**项目根目录**运行 `python -m venv .venv`。

>激活环境：<br>
>    Windows: `.venv\Scripts\activate`<br> 
>    macOS/Linux: `source .venv/bin/activate`

>退出环境：运行 `deactivate` 命令。
---