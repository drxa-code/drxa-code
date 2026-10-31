# “开源就在我身边”调查

调查日期：2026-10-31。以下实例均通过项目官方仓库或许可证原文核实，而不是仅凭“可能开源”判断。

| 开源软件 | 日常场景 | 确认依据 | 许可证信息 | 发现方式 |
| --- | --- | --- | --- | --- |
| Visual Studio Code（Code - OSS） | 电脑上的代码编辑、阅读与调试工具 | [microsoft/vscode](https://github.com/microsoft/vscode) 的 README 明确说明该仓库是 Visual Studio Code 的开源开发仓库 | 仓库为 [MIT](https://github.com/microsoft/vscode/blob/main/LICENSE.txt)；README 同时提醒，微软发布的 Visual Studio Code 产品发行版包含特定定制并采用单独产品许可证，二者不能混为一谈 | 课程项目池 |
| Python（CPython） | 运行本课程的资料整理工具及其他 Python 程序 | [python/cpython](https://github.com/python/cpython) 是 Python 编程语言的官方实现仓库 | [LICENSE](https://github.com/python/cpython/blob/main/LICENSE) 明确写有 Python Software Foundation License Version 2；部分内置软件另有各自许可证 | 自主发现 |
| Git | 版本管理、克隆仓库和提交代码 | [git/git](https://github.com/git/git) 是 Git 源代码镜像仓库 | [COPYING](https://github.com/git/git/blob/master/COPYING) 说明项目采用 GPL Version 2，除非文件另有明确说明，并非 GPL-3.0 | 自主发现 |

## 调查结论

开源软件并不只存在于“开源项目网站”中：编辑器、编程语言运行环境和版本管理工具共同构成了日常开发环境。确认是否开源时，应找到具体仓库或许可证原文，同时注意“开源仓库”和“基于它构建的商业发行版”可能采用不同许可安排。
