# venv是什么&作用
Python 虚拟环境（Virtual Environment）Python 3.3+ 自带<br>
**venv**创建一个虚拟环境，实际上它只是一个带有shell脚本和指向Python解释器的链接的文件夹`.venv`激活环境后，所有安装的库都存储在这个文件夹中。<br>

**虚拟环境可以保持项目的隔离**。程序需要一定的环境设置才能干净地运行。在大多数情况下，操作系统的环境（主要是 Linux）会干扰程序的环境依赖。<br>

再者，使用虚拟环境可以为项目**安装特定的库**、选择**特定版本的Python**。
-- --
>1. 不移动虚拟环境。只移动代码和资源/配置文件。
>2. 创建requirements.txt文件，这样会很容易重建虚拟环境。创建requirements.txt文件命令：`pip freeze > requirements.txt`
>3. 使用git作为代码管理工具移动代码。使用仓库。
---

# venv创建&激活方法
1. 创建虚拟环境：在**项目根目录**运行 `python -m venv .venv(可以自定义)`。

2. 激活环境：
- CMD: `.venv\Scripts\activate.bat`
- PowerShell:`Set-ExecutionPolicy`以及`.venv\Scripts\Activate.ps1`
3. 退出环境：运行 `deactivate` 命令。
---

# venv配置检查

| 命令                                          | 检查内容         | 检查结果                          |
| ------------------------------------------- | ------------ | ----------------------------- |
| `where python`\|`findstr venv`              | 检查当前解释器路径    | `where python`命令输出的第一个是当前解释器。 |
| `python -c "import sys; print(sys.prefix)"` | 检查sys.prefix | 输出路径包含虚拟环境目录表示已经激活            |
| `echo %VIRTUAL_ENV%`(CMD)                   | 检查环境变量       | 变量应该指向虚拟环境路径                  |
| `where pip`                                 | 检查pip指向      | 命令输出的第一个是当前pip指向              |
| `python --version`                          | 检查pip版本      | 确保与创建环境时版本一致                  |


