# EJU 理科课程讲义

本仓库收录本次课程中整理完成的 LaTeX 讲义与作业。各项目均以 `main.tex` 为入口，并附有编译后的 PDF。

| 目录 | 内容 | PDF |
| --- | --- | --- |
| `00-math-foundations` | 微分与向量基础 | `main.pdf` |
| `01-physics1` | 位移、速度、运动的合成与分解 | `main.pdf` |
| `02-chem1` | 物质分类、分离精制、元素与同素体、三态、原子与同位素 | `main.pdf` |
| `03-chem1-homework` | 化学第一课作业（学生版、无答案） | `main.pdf` |
| `04-physics2` | 匀变速直线运动、图像、竖直抛体与拓展结论 | `main.pdf` |

## 本地编译

项目使用 XeLaTeX，以正确显示中文和日文：

```powershell
xelatex main.tex
xelatex main.tex
```

VS Code 已配置 LaTeX Workshop：打开任意 `main.tex` 后执行“Build LaTeX project”即可。
