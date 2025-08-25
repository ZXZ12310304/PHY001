# Python基础学习教程 (PHY001)

> **作者学习笔记** 
> 
> 这是我在学习Python编程时记录的完整学习笔记，包含从入门到进阶的7个核心章节，采用Jupyter Notebook形式进行记录。这些笔记记录了我在Python学习过程中的理解、实践和思考，希望能对其他学习者有所帮助。

## 关于作者

- **学习目的**: 系统学习Python编程基础
- **学习方式**: 理论结合实践，边学边记
- **笔记特点**: 包含大量代码示例、实践练习和个人理解
- **适用人群**: Python初学者、编程爱好者、需要复习Python基础的学习者

## 课程内容

### 第1章：Python简介
- **文件**: `Lecture1-简介.ipynb`
- **内容**: 
  - 编程语言概述（自然语言、人工语言、机器语言）
  - 计算机基础知识（CPU、内存、硬盘等）
  - Python语言特点和应用领域
  - 常用Python库介绍（numpy、pandas、scikit-learn等）

### 第2章：数据类型
- **文件**: `Lecture 2-类型.ipynb`
- **内容**:
  - Python基本数据类型（int、float、bool、str等）
  - 数据结构（list、tuple、dict、set）
  - 内存存储原理（Bit、Byte、KB、MB、GB）
  - turtle图形绘制基础
  - 对象和变量概念

### 第3章：循环结构
- **文件**: `Lecture 3-循环.ipynb`
- **内容**:
  - for循环和while循环
  - 循环控制语句（break、continue）
  - 嵌套循环
  - 循环优化技巧

### 第4章：函数
- **文件**: `Lecture 4-函数.ipynb`
- **内容**:
  - 函数定义和调用
  - 参数传递（形参、实参）
  - 默认参数和不定长参数（*args、**kwargs）
  - 全局变量和局部变量
  - 递归函数
  - 匿名函数（lambda）

### 第5章：面向对象编程
- **文件**: `Lecture 5-类.ipynb`
- **内容**:
  - 类和对象概念
  - 构造函数和析构函数
  - 继承和多态
  - 封装和访问控制
  - 特殊方法（魔术方法）

### 第6章：文件操作、迭代器和日志
- **文件**: `Lecture6-文件,迭代器,日志.ipynb`
- **内容**:
  - 文件读写操作
  - 迭代器和生成器
  - 日志记录和调试
  - 异常处理基础

### 第7章：错误和异常处理
- **文件**: `Lecture 7-错误异常.ipynb`
- **内容**:
  - 异常类型和分类
  - try-except语句
  - 自定义异常
  - 异常处理最佳实践

## 环境要求

### 必需软件
- **Python**: 3.8 或更高版本
- **Jupyter Notebook**: 用于运行和查看教程
- **conda** (推荐): 用于环境管理

### 安装步骤

1. **安装conda** (如果还没有安装)
   ```bash
   # 下载并安装Anaconda或Miniconda
   # 访问: https://docs.conda.io/en/latest/miniconda.html
   ```

2. **创建虚拟环境**
   ```bash
   conda create -n phy001 python=3.12
   conda activate phy001
   ```

3. **安装Jupyter**
   ```bash
   conda install jupyter notebook
   ```

4. **安装常用库**
   ```bash
   conda install numpy pandas matplotlib seaborn
   pip install jupyter_contrib_nbextensions
   ```

5. **启动Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

##  学习建议

### 学习顺序
1. 按照章节顺序学习，从第1章开始
2. 每章都要动手实践代码示例
3. 完成每章的练习和作业
4. 复习前面章节的内容

### 实践建议
- 每个代码单元格都要运行并理解
- 尝试修改代码参数，观察结果变化
- 自己编写类似的程序
- 记录学习笔记和疑问

## 贡献

欢迎提交Issue和Pull Request来改进这个项目！

⭐ 如果这个项目对您有帮助，请给它一个星标！感谢您！ 
