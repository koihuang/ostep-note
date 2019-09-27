操作系统相关 Operating Systems: Three Easy Pieces 学习笔记
===

Operating Systems: Three Easy Pieces这本书从 虚拟化(virtualization), 并发(concurrency), 持久化(persistent) 三方面对操作系统在抽象层面上做了很好的分析介绍.
此书能让读者对操作系统有一个综合的感性认识,特别是在抽象层面上,关键还免费,免费,免费!!!. 
感兴趣的读者可以读一下 http://pages.cs.wisc.edu/~remzi/OSTEP/

作为学习巩固,分享一下自己的学习笔记,有兴趣的也可以看一下.(蓝色有链接的为已经写好的笔记,后面逐步更新中,有些不重要的选择性跳过)

| intro           | virtualization          |                                  | concurrency                | persistence                         | appendices       |
| --------------- | ----------------------- | -------------------------------- | -------------------------- | ----------------------------------- | ---------------- |
| Preface| 3 Dialogue | 12 Dialogue | 25 Dialogue | 35 Dialogue| Dialogue | 
| TOC | 4 [Processes](https://github.com/koihuang/ostep-note/blob/master/1%20virtualization/4%20Processes.md) | 13 [Address Spaces](https://github.com/koihuang/ostep-note/blob/master/1%20virtualization/13%20Address%20Spaces.md) | 26 Concurrency and Threads | 36 I/O Devices | Virtual Machines | 
| 1 Dialogue | 5 [Process API](https://github.com/koihuang/ostep-note/blob/master/1%20virtualization/5%20Process%20API.md) | 14 Memory API | 27 Thread API| 37 Hard Disk Drives | Dialogue | 
| 2 Introduction | 6 [Direct Execution](https://github.com/koihuang/ostep-note/blob/master/1%20virtualization/6%20Direct%20Execution.md) | 15 Address Translation | 28 Locks | 38 Redundant Disk Arrays (RAID) | Monitors | 
|  | 7 [CPU Scheduling](https://github.com/koihuang/ostep-note/blob/master/1%20virtualization/7%20CPU%20Scheduling.md) | 16 Segmentation | 29 Locked Data Structures | 39 Files and Directories | Dialogue | 
|  | 8 [Multi-level Feedback](https://github.com/koihuang/ostep-note/blob/master/1%20virtualization/8%20Multi-level%20Feedback.md) | 17 Free Space Management | 30 Condition Variables| 40 File System Implementation | Lab Tutorial | 
|  | 9 Lottery Scheduling | 18 Introduction to Paging| 31 Semaphores| 41 Fast File System (FFS) | Systems Labs | 
|  | 10 [Multi-CPU Scheduling](https://github.com/koihuang/ostep-note/blob/master/1%20virtualization/10%20Multi-CPU%20Scheduling.md) | 19 Translation Lookaside Buffers | 32 Concurrency Bugs | 42 FSCK and Journaling | xv6 Labs | 
|  | 11 Summary | 20 Advanced Page Tables| 33 Event-based Concurrency| 43 Log-Structured File System (LFS) |  | 
|  |  | 21 Swapping: Mechanisms | 34 Summary | 44 Data Integrity and Protection|  | 
|  |  | 22 Swapping: Policies |  | 45 Summary|  | 
|  |  | 23 Complete VM Systems |  | 46 Dialogue |  | 
|  |  | 24 Summary |  | 47 Distributed Systems|  | 
|  |  |  |  | 48 Network File System (NFS)|  | 
|  |  |  |  | 49 Andrew File System (AFS)|  | 
|  |  |  |  | 50 Summary |  | 