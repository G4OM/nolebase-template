**PyPI**全称Python Package Index，而**pip**是一个命令行工具。
# 查看pip版本
>`pip --version`<br>
>或者`pip -V`
# 升级pip
- `python -m pip install --upgrade pip`
# 部分pip命令

| 命令                          | 用途            | 参数组合                     |
| --------------------------- | ------------- | ------------------------ |
| `pip install (目标Package)`   | 安装(目标Package) | -U升级，--user用户安装，临时换源     |
| `pip uninstall (目标Package)` | 卸载(目标Package) | -y免确认                    |
| `pip list`                  | 查看现有安装包       | --outdated查看可升级包         |
| `pip show package`          | 显示包详情         | -f显示文件列表                 |
| `pip freeze`                | 输出依赖          | `> requirements.txt`生成文件 |
| `pip check`                 | 检查依赖冲突        | 无                        |
| `pip cache`                 | 管理缓存          | purge清除所有缓存              |

# pip指定包版本安装
- `pip install numpy（目标Package）==1.21.0`

# pip参数自由组合
- `pip install -U -i https://mirrors.aliyun.com/pypi/simple/`

# pip临时换源
- 阿里源：`https://mirrors.aliyun.com/pypi/simple/`
- 清华源：`https://pypi.tuna.tsinghua.edu.cn/simple/`
