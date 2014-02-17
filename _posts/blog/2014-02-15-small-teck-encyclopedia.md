---
layout: post
title: 技术小百科（更新2014-02-15）
category: tech
tags: 技术
---

**1. Linux中的kill -2, kill -9, kill -15有什么区别？**
{: .sub-title}
>1. kill -2 与 Ctrl+C的效果是相等的。
>2. kill -9 pid，是不顾后果的强制终止。
>3. kill -15 pid，是先关闭和其有关的程序，再将其关闭
>
>		信号介绍：
> 		SIGINT  2  A   键盘中断（如break键被按下) 
> 		SIGKILL 9  AEF Kill信号
> 		SIGTERM 15 A   终止信号 

