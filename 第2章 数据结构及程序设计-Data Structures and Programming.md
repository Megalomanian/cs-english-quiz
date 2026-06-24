# 第2章 数据结构及程序设计 — Data Structures and Programming

---

## 📝 核心词汇

### 开发工具与概念

| 单词 | 音标 | 释义 | 例句 | 备注 |
|:---|:---|:---|:---|:---|
| **storage** | /ˈstɔːrɪdʒ/ | 存储 | The program is usually placed in a storage area that the computer can read. | 常见搭配：storage area；是理解程序存放位置的基础词 |
| **interpreter** | /ɪnˈtɜːprɪtə/ | 解释器 | An interpreter can run a high-level program directly at runtime. | 解释器可以在运行时直接执行高级语言程序 |
| **statement** | /ˈsteɪtmənt/ | 语句 | A program is made up of many statements written in a programming language. | 写代码时非常常见，是最基础的程序单位之一 |
| **module** | /ˈmɒdjuːl/ | 模块 | Each module can be tested separately before it is integrated into the whole program. | 每个模块都可以在并入整个程序之前单独测试 |
| **editor** | /ˈedɪtə/ | 编辑器 | A programmer usually writes source statements in an editor. | 与代码最常见的软件工具之一 |
| **execute** | /ˈeksɪkjuːt/ | 执行 | The computer gets an instruction, executes it, and then gets the next one. | 常和 analyze 放在一起理解 |
| **compilation** | /ˌkɒmpɪˈleɪʃn/ | 编译 | Compilation turns source code into machine language or object code. | 编译把源代码转换成机器语言或目标代码 |
| **bytecode** | /ˈbaɪtkəʊd/ | 字节码 | Java programs can be compiled into bytecode first. | 常和 Java Virtual Machine 一起出现 |
| **translate** | /trænsˈleɪt/ | 翻译；转换 | A compiler translates high-level instructions into machine language. | 在计算机英语里常表示"把一种代码转成另一种代码" |
| **script** | /skrɪpt/ | 脚本 | A script can be used to add functionality to a Web page. | 脚本可以用来给网页增加功能 |
| **programming** | /ˈprəʊɡræmɪŋ/ | 程序设计 | Programming allows people to write instructions for computers. | 编程的统称 |
| **programmer** | /ˈprəʊɡræmə/ | 程序设计员 | A programmer writes programs in a programming language such as C or Python. | 和 programming 配套记忆 |
| **assembler** | /əˈsemblə/ | 汇编程序 | An assembler translates assembly language into machine language. | 汇编语言→机器码的翻译器 |
| **variable** | /ˈveəriəbl/ | 变量 | In Python, a simple assignment binds a name to a variable or object. | 编程入门最基础的概念之一 |

### 编程范式与代码质量

| 单词 | 音标 | 释义 | 例句 | 备注 |
|:---|:---|:---|:---|:---|
| **object-oriented** | /ˈɒbdʒekt ˈɔːrientɪd/ | 面向对象的 | Python mainly follows an object-oriented design. | 常缩写为 OOP |
| **readable** | /ˈriːdəbl/ | 可读的；易读的 | Python code is highly readable. | 常与 reusable、maintainable 一起出现 |
| **maintainable** | /meɪnˈteɪnəbl/ | 可维护的 | Good code should be readable and maintainable. | 软件工程核心质量指标 |
| **elegant** | /ˈelɪɡənt/ | 简洁的；优雅的 | Python is famous for its elegant coding style. | Python 以优雅简洁著称 |
| **library** | /ˈlaɪbrəri/ | 库 | Python provides many prebuilt libraries for developers. | 库是预构建的可复用代码集合 |
| **integration** | /ˌɪntɪˈɡreɪʃn/ | 集成；整合 | Python supports integration with components written in other languages. | 常指不同模块/语言的协作 |
| **intuitive** | /ɪnˈtjuːɪtɪv/ | 直观的 | OOP provides an intuitive way to build code. | 常用来形容"容易理解、容易上手"的设计 |
| **prototype** | /ˈprəʊtətaɪp/ | 原型 | Python is often used to build a software prototype quickly. | 在开发流程里很常见，尤其是快速开发场景 |

### 数据结构术语

| 术语 | 英文 | 说明 |
|:---|:---|:---|
| 数组 | Array | 连续存储的线性结构 |
| 链表 | Linked List | 节点+指针的线性结构 |
| 栈 | Stack | 后进先出 (LIFO) |
| 队列 | Queue | 先进先出 (FIFO) |
| 图 | Graph | 非线性结构，节点+边 |
| 哈希表 | Hash Table | 键值对快速查找 |
| 优先队列 | Priority Queue | 按优先级出队 |
| 抽象语法树 | Abstract Syntax Tree (AST) | 编译器解析后生成的树结构 |
| 抽象数据类型 | Abstract Data Type (ADT) | 数据和操作的抽象描述 |

---

## ✍️ 长句分析

### Sentence 1
> A variable in a programming language is a storage location paired with an associated symbolic name, which contains some known or unknown quantity of information referred to as a value.

**编程语言中的变量是一个与关联符号名配对的存储位置，它包含了一些已知或未知的、被称为"值"的信息量。**

- **主句：** A variable is a storage location... which contains some... value.
- **插入语：** paired with an associated symbolic name（与符号名配对），作后置定语
- **定语从句：** which contains...（包含…），修饰 storage location
- **重点词汇：** variable（变量）、programming language（编程语言）、storage location（存储位置）、symbolic name（符号名）、value（值）

> 💡 Variable 是程序设计中最基础的概念，提供了数据命名的 storage 空间。不同数据类型在 storage area 中占据不同字节数，直接影响算法的空间复杂度分析，也是理解后续 paging 和 segmentation 内存管理的前提。

---

### Sentence 2
> An interpreter directly executes statements written in a programming language, processing the source code line by line without previously compiling them into machine language.

**解释器直接执行用编程语言编写的语句，逐行处理源代码，而无需事先将其编译成机器语言。**

- **主句：** An interpreter directly executes statements.
- **分词短语：** written in a programming language，作后置定语修饰 statements
- **伴随状语：** processing the source code line by line，说明执行方式
- **介词短语：** without previously compiling them into machine language，表示条件
- **重点词汇：** interpreter（解释器）、execute（执行）、statement（语句）、compile（编译）

> 💡 Interpreter 与 Compiler 是两种不同的语言处理程序。解释器适合快速 prototype 开发，能立即执行 script 而无需等待完整的 compilation 过程。Python 和 JavaScript 通常采用解释执行，而 C/C++ 需要编译。

---

### Sentence 3
> In object-oriented design, a module represents a self-contained component that encapsulates data (variables) and procedures (methods) into a single unit, making the code more maintainable and reusable.

**在面向对象设计中，模块代表一个自包含的组件，它将数据（变量）和过程（方法）封装在一个单一单元中，从而使代码更具可维护性和可重用性。**

- **主句：** A module represents a self-contained component.
- **定语从句：** that encapsulates data and procedures into a single unit
- **现在分词：** making the code more maintainable and reusable，表示结果
- **重点词汇：** object-oriented（面向对象的）、module（模块）、component（组件）、maintainable（可维护的）、reusable（可复用的）

> 💡 Modular programming 是结构化程序设计的核心原则。每个 module 可以对应一个抽象数据类型（ADT），例如栈（Stack）、队列（Queue）或链表（Linked List）。通过将 implementation details 隐藏在模块内部，开发者可修改内部算法而不影响其他 component——这就是 Information Hiding 的核心思想。

---

### Sentence 4
> A compiler first parses the source statements according to syntax rules to check for grammatical errors, then translates the validated code into bytecode or assembly language before final execution.

**编译器首先根据语法规则对源语句进行解析以检查语法错误，然后将经过验证的代码翻译成字节码或汇编语言，最后才执行。**

- **主句：** A compiler first parses... then translates...
- **并列谓语：** parses 和 translates，表示编译的两个阶段
- **介词短语：** according to syntax rules，修饰解析方式
- **重点词汇：** compiler（编译器）、parse（解析）、translate（翻译）、bytecode（字节码）、syntax（语法）

> 💡 Compilation 过程的 parse 阶段构建 Abstract Syntax Tree（抽象语法树），是代码优化和生成的基础。Java 等语言先将代码编译为平台无关的 bytecode，再由 JVM 解释执行，实现"一次编译，到处运行"。

---

### Sentence 5
> Modern software development relies heavily on prebuilt library functions that provide intuitive APIs for complex operations, allowing programmers to focus on high-level algorithm design rather than low-level implementation details.

**现代软件开发严重依赖预构建的库函数，这些函数为复杂操作提供了直观的 API，使程序员能够专注于高层算法设计，而非底层实现细节。**

- **主句：** Modern software development relies heavily on prebuilt library functions.
- **定语从句：** that provide intuitive APIs for complex operations
- **对比结构：** rather than low-level implementation details，表示取舍关系
- **重点词汇：** library（库）、intuitive（直观的）、programmer（程序员）、implementation（实现）、API（应用程序接口）

> 💡 Software Reuse（软件复用）通过 library 机制大幅提高开发效率。标准模板库（STL）或 Python 的 built-in libraries 提供了已优化的 data structures。开发者只需调用 intuitive 的接口，无需了解底层 memory allocation，这就是 Abstraction 原则。

---

## 📄 段落精读

### Data Structures & Programming Paradigms

A **data structure** is a specialized format for organizing, processing, retrieving, and storing data in a computer. Common linear data structures include **arrays**, **linked lists**, **stacks**, and **queues**, while **graphs** and **trees** represent non-linear relationships between data elements.

Programming languages provide the tools to implement these structures. They include **rules**, **symbols**, and **keywords** used to write computer programs. High-level languages like **Python**, **Java**, **C++**, and **JavaScript** offer built-in support for common data structures, while low-level languages like **machine code** require manual memory management.

> 📌 **核心概念：**
> - **线性结构：** Array → Linked List → Stack → Queue（一对一关系）
> - **非线性结构：** Graph、Tree（多对多关系）
> - **高级语言 vs 低级语言：** 高级语言抽象程度高、易读易维护；机器码直接与硬件交互

### Software Quality Attributes

Good code should be:
- **Readable** — easy for humans to understand
- **Maintainable** — easy to modify and extend
- **Elegant** — concise, well-structured, and following best practices
- **Intuitive** — easy to grasp the design intent

Python exemplifies these qualities with its clean syntax and object-oriented design. The language's philosophy emphasizes code readability and programmer productivity.

---

## 💼 应用案例

### 编程语言选择场景

When starting a new software project, developers must choose the right programming language based on:

| 场景 | 推荐语言 | 理由 |
|:---|:---|:---|
| 快速原型开发 | Python | 语法简洁、库丰富、解释执行无需编译 |
| 高性能计算 | C / C++ | 编译型语言、底层内存控制 |
| 企业级 Web 应用 | Java | 跨平台（JVM）、强类型、生态成熟 |
| Web 前端交互 | JavaScript | 浏览器原生支持、事件驱动 |
| 数据分析 / AI | Python | NumPy、Pandas、TensorFlow 等库 |

**关键术语对照：**
- Integrated Development Environment (IDE) — 集成开发环境
- Version Control System (VCS) — 版本控制系统
- Debugging — 调试
- Deployment — 部署
- Refactoring — 重构

---

## 🗣️ 口语练习

**练习形式：** 技术讨论

**场景：** 团队成员讨论新项目的技术选型。

**示例对话：**
- Q: "Which programming language should we use for this project?"
- A: "I'd recommend Python because it's highly readable and has many prebuilt libraries for data processing."
- Q: "What about performance?"
- A: "We can implement the core algorithms in C++ and use Python for the high-level integration."
- Q: "How do you ensure the code is maintainable?"
- A: "We'll follow object-oriented design principles and write comprehensive documentation."

**讨论话题：**
1. Compare interpreted vs. compiled languages
2. Describe your favorite data structure and its use case
3. Explain the importance of code readability

---
*信息工程学院 丁彤 | tongding@nxu.edu.cn*
