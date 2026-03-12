venv 是 Python 内置的虚拟环境工具，用于创建一个独立的 Python 运行环境。每个虚拟环境都有自己的 Python 解释器、标准库和第三方库，与全局 Python 环境及其他虚拟环境隔离，从而避免不同项目间的依赖冲突。

venv 文件夹内外文件的关系

- 内部（venv 文件夹）：包含了运行项目所需的 Python 解释器和所有依赖包。激活虚拟环境后，python 和 pip 命令都会指向这个内部的解释器和包管理工具，安装的第三方包都会被放在 lib/pythonX.X/site-packages/ 中。
- 外部（项目代码）：通常指你的项目源代码、配置文件、测试文件等。这些文件位于虚拟环境文件夹之外，与 venv 同层或更深层目录。

使用示例

1. 创建虚拟环境：python -m venv myenv
2. 激活环境：source myenv/bin/activate（Linux/macOS）或 myenv\Scripts\activate（Windows）
3. 在激活的环境中安装依赖：pip install requests
4. 运行外部项目代码：python /path/to/project/main.py
5. 退出环境：deactivate
