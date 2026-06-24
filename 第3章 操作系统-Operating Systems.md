# 第3章 操作系统 — Operating Systems

---

## 📝 核心词汇

### 操作系统基础

| 单词 | 音标 | 释义 | 例句 | 备注 |
|:---|:---|:---|:---|:---|
| **operating system** | /ˈɒpəreɪtɪŋ ˈsɪstəm/ | 操作系统 | An operating system manages hardware and software resources for computer programs. | 常缩写为 OS，本单元最核心的词 |
| **kernel** | /ˈkɜːnl/ | 内核 | The kernel is the core part of the operating system that controls hardware and manages resources. | OS 的心脏，直接与硬件交互 |
| **user interface** | /ˈjuːzə ˈɪntəfeɪs/ | 用户界面 | The user interface is the space where interactions between humans and the computer occur. | 简称 UI |
| **supervisor** | /ˈsuːpəvaɪzə(r)/ | 管理者；监督者 | In supervisor mode, the CPU can access machine resources without restriction. | 也作 supervisor mode（管理者模式） |

### 任务调度

| 单词 | 音标 | 释义 | 例句 | 备注 |
|:---|:---|:---|:---|:---|
| **single-tasking** | /ˈsɪŋɡl tɑːskɪŋ/ | 单任务 | A single-tasking system can run only one program at a time. | 早期 DOS 系统即如此 |
| **multi-tasking** | /ˌmʌlti ˈtɑːskɪŋ/ | 多任务 | A multi-tasking operating system allows more than one program to run concurrently. | 现代操作系统的重要特征 |
| **time-sharing** | /taɪm ˈʃeərɪŋ/ | 分时 | Time-sharing divides processor time among multiple processes. | 和多任务处理一起理解 |
| **concurrency** | /kənˈkʌrənsi/ | 并发（性） | The operating system makes concurrency possible by scheduling processes. | 指多个任务看起来同时进行 |
| **preemptive** | /prɪˈemptɪv/ | 抢占式的 | In a preemptive multitasking system, the OS allocates CPU time slices to each program. | 操作系统主动分配 CPU 时间 |
| **interrupt** | /ɪntəˈrʌpt/ | 中断 | An interrupt can stop the current program and force the system to respond to an event. | 硬件可触发中断通知 CPU |
| **trigger** | /ˈtrɪɡə(r)/ | 触发 | A hardware device can trigger an interrupt. | 编程里很常见的动作 |
| **suspend** | /səˈspend/ | 挂起；暂停 | When an interrupt occurs, the hardware may suspend the currently running program. | 与 resume（恢复）常构成一组 |
| **priority** | /praɪˈɒrəti/ | 优先级 | The kernel may decide how to handle an event according to its priority. | 高优先级任务先执行 |
| **assign** | /əˈsaɪn/ | 分配 | The kernel can assign memory space and other resources to a process. | 常与 resource、memory、priority 连用 |
| **execution** | /ˌeksɪˈkjuːʃn/ | 执行 | The operating system starts the execution of an application after loading it. | execute 的名词形式 |
| **deterministic** | /dɪˌtɜːmɪˈnɪstɪk/ | 确定性的 | A real-time system needs deterministic behavior when it handles tasks. | 实时系统的关键要求 |

### 用户与系统类型

| 单词 | 音标 | 释义 | 例句 | 备注 |
|:---|:---|:---|:---|:---|
| **single-user** | /ˈsɪŋɡl ˈjuːzə(r)/ | 单用户 | A single-user operating system may allow several programs to run in tandem. | 重点不是程序多少，而是用户只有一个 |
| **multi-user** | /ˌmʌlti ˈjuːzə(r)/ | 多用户 | A multi-user operating system permits multiple users to interact with the system simultaneously. | 如 Linux 服务器 |
| **distributed** | /dɪˈstrɪbjuːtɪd/ | 分布式的 | A distributed operating system manages a group of distinct computers. | 管理独立计算机为统一系统 |
| **subsystem** | /ˈsʌbsɪstəm/ | 子系统 | Each process is repeatedly interrupted by the task scheduling subsystem. | 系统的组成部分 |

### 内存与存储

| 单词 | 音标 | 释义 | 例句 | 备注 |
|:---|:---|:---|:---|:---|
| **paging** | /ˈpeɪdʒɪŋ/ | 分页 | Virtual memory addressing can be achieved by paging. | 常和 segmentation 对照记忆 |
| **segmentation** | /ˌseɡmenˈteɪʃn/ | 分段 | Some systems use segmentation to manage virtual memory. | 另一种内存管理方式 |
| **disk** | /dɪsk/ | 磁盘 | Files are stored on disk so that the operating system can access data later. | 常见搭配：disk space / disk access |
| **hierarchy** | /ˈhaɪərɑːki/ | 层次结构 | A file system may store files in a hierarchy of directories. | 也作 directory hierarchy |
| **directory** | /dəˈrektəri/ | 目录 | A directory can contain files and other folders in a file system. | 文件系统的基本组织单位 |
| **algorithm** | /ˈælɡərɪðəm/ | 算法 | A real-time operating system uses special scheduling algorithms. | 调度算法是 OS 核心 |

---

## ✍️ 长句分析

### Sentence 1
> An operating system manages all hardware and software resources, assigning CPU time and memory space to different programs to ensure orderly execution of processes.

**操作系统管理所有的硬件和软件资源，为不同的程序分配 CPU 时间和内存空间，以确保进程的有序执行。**

- **主句：** An operating system manages all hardware and software resources.
- **现在分词：** assigning CPU time and memory space... 作伴随状语
- **目的状语：** to ensure orderly execution of processes
- **重点词汇：** operating system（操作系统）、assign（分配）、execution（执行）、process（进程）

---

### Sentence 2
> The kernel can assign memory space and other resources to a process, and may decide how to handle an event according to its priority.

**内核可以为一个进程分配内存空间和其他资源，并且可以根据事件的优先级来决定如何处理它。**

- **并列句：** The kernel can assign... and may decide...
- **介词短语：** according to its priority（根据优先级）
- **重点词汇：** kernel（内核）、assign（分配）、process（进程）、priority（优先级）

---

### Sentence 3
> A multi-tasking operating system allows more than one program to run concurrently, with the OS scheduling processes and switching between them to give the appearance of simultaneous execution.

**多任务操作系统允许多个程序并发运行，操作系统调度进程并在其间切换，以呈现同时执行的外观。**

- **with 复合结构：** the OS scheduling processes and switching between them
- **重点词汇：** multi-tasking（多任务）、concurrently（并发地）、schedule（调度）、switch（切换）

> 💡 Concurrency（并发）不等于 Parallelism（并行）。并发是"看起来同时"，实际是快速切换；并行是真正的"同时执行"。理解这个区别对掌握操作系统调度至关重要。

---

### Sentence 4
> In a preemptive multitasking environment, hardware devices can trigger interrupts, forcing the supervisor mode to suspend the current program and give control to a higher-priority process.

**在抢占式多任务环境中，硬件设备可以触发中断，迫使管理者模式挂起当前程序并将控制权交给更高优先级的进程。**

- **介词短语：** In a preemptive multitasking environment
- **现在分词：** forcing the supervisor mode to suspend...
- **重点词汇：** preemptive（抢占式的）、trigger（触发）、interrupt（中断）、supervisor mode（管理者模式）、suspend（挂起）

---

### Sentence 5
> A distributed operating system manages a group of networked computers as a single coherent system, maintaining a unified file directory structure and allowing users to access remote resources as if they were local.

**分布式操作系统将一组联网计算机管理为一个单一的连贯系统，维护统一的文件目录结构，并允许用户像访问本地资源一样访问远程资源。**

- **主句：** A distributed OS manages a group of networked computers.
- **现在分词1：** maintaining a unified file directory structure
- **现在分词2：** allowing users to access remote resources
- **as if 从句：** as if they were local（虚拟语气）
- **重点词汇：** distributed（分布式的）、coherent（连贯的）、unified（统一的）、remote（远程的）

---

## 📄 核心概念

### 操作系统四大核心功能

| 功能 | 英文 | 说明 |
|:---|:---|:---|
| 进程管理 | Process Management | 处理多个进程的运行、调度和切换 |
| 内存管理 | Memory Management | 控制和协调计算机内存，分配内存块给程序 |
| 文件管理 | File Management | 以层级结构组织文件和目录 |
| 设备管理 | Device Management | 管理输入/输出设备 |

### 操作系统类型对比

| 类型 | 特点 | 例子 |
|:---|:---|:---|
| 单任务 | 一次只运行一个程序 | 早期 DOS |
| 多任务 | 多个程序并发运行 | Windows, macOS, Linux |
| 分时 | 分时技术实现并发 | Unix 系统 |
| 实时 | 确定性的响应时间 | 工业控制、航空系统 |
| 分布式 | 管理联网的多台计算机 | 集群系统 |

---

## 🗣️ 口语练习

**练习形式：** 技术解释

**场景：** 向非技术人员解释操作系统的基本功能。

**示例对话：**
- Q: "What is an operating system in simple terms?"
- A: "Think of the OS as the manager of your computer. It controls the hardware, runs your programs, and makes sure everything works together smoothly."
- Q: "Why can I run multiple apps at the same time?"
- A: "That's because modern operating systems support multi-tasking — they rapidly switch between programs so fast you don't notice."

---
*信息工程学院 丁彤 | tongding@nxu.edu.cn*
