# GFD — 地球物理流体动力学

清华大学地球系统科学系罗勇老师「地球物理流体动力学」课程的笔记与论文。

## 目录结构

```
note/     课程笔记
report/   课程论文
```

### 课程笔记 (`note/`)

| 章节 | 内容 |
|------|------|
| Ch 1 | 基本方程组 |
| Ch 2 | 无粘浅水系统 |
| Ch 3 | 摩擦与湍流 |
| Ch 4 | 风生洋流的匀质模式 |
| Ch 5 | 层结流体的准地转运动 |
| 附录 | 补充推导 |
| 作业 | 习题解答 |

### 课程论文 (`report/`)

**赤道波动力学的算子代数框架**（Operator Algebraic Framework for Equatorial Wave Dynamics）

从三维层结大气基本方程出发，建立描述赤道波动的统一数学框架，涵盖干波理论、湿过程修正及微扰分析。

## 编译

笔记与论文均使用 XeLaTeX 编译：

```bash
cd note && xelatex main.tex
cd report && xelatex main.tex && bibtex main && xelatex main.tex && xelatex main.tex
```

## 许可

本仓库内容仅供学习参考。
