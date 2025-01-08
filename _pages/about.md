---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently an Associate Researcher with the <a href="http://cic.tju.edu.cn">College of Intelligence and Computing</a>, <a href="https://www.tju.edu.cn">Tianjin University</a>, Tianjin, China. And I am a member of TANK Lab, led by <a href="https://cic.tju.edu.cn/faculty/likeqiu/index.html">Prof.Keqiu Li</a>. From 2022 to 2024, I was a Postdoctoral Researcher in the <a href="https://storage.cs.tsinghua.edu.cn">Storage Research Group</a> (advised by <a href="https://storage.cs.tsinghua.edu.cn/~jiwu-shu/">Prof.Jiwu Shu</a> and <a href="https://storage.cs.tsinghua.edu.cn/~lu/">Youyou Lu)</a>, Department of Computer Science and Technology, Tsinghua University, Beijing, China. I received the PhD degree from the School of Computer Science and Technology, Shandong University, Qingdao, China, in June 2022. My research interest includes storage system and AI system.


# 🔥 News
- 🎉*2024.07*: &nbsp; Our paper entitled “Achieving Wire-Latency Storage Systems by Exploiting Hardware ACKs" has been accepted by NSDI'25. 
- 🎉*2024.07*: &nbsp; Our paper entitled “Deft: A Scalable Tree Index for Disaggregated Memory" has been accepted by Eurosys'25.
- 🎉*2024.07*: &nbsp; Our paper entitled “Ares-Flash: Efficient Parallel Integer Arithmetic Operations Using NAND Flash Memory" has been accepted by MICRO'24.
- 🎉*2024.05*: &nbsp; Our paper entitled “Full Lifecycle Data Analysis on a Large-scale and Leadership Supercomputer: What Can We Learn from It?" has been accepted by USENIX ATC'24.



# 💬 Research Topics

<p>Storage system:</p>
-  Distributed Storage System with Fast/Smart CXL/Network Devices (e.g., RDMA/Smart NIC). <br>
-  Near Data Processing (i.e., Processing-in-memory and Computing-in-Storage) with Emerging Devices (e.g., DIMM PIM Modules and Smart SSD).


<p>AI system:</p>
- Task Scheduling and Memory/Storage Management for Large Scale AI Models.<br>
- High Performance Networking for Large Scale AI Models.


# 📝 Publications 

<!-- <ul>
</ul> -->

<p>Check my full publication list on <a href="https://scholar.google.com/citations?user=KEvXHFIAAAAJ&hl=zh-CN">google scholar</a>.</p>


- Achieving Wire-Latency Storage Systems by Exploiting Hardware ACKs.[<a href="">PDF</a>] <br>
Qing Wang, Jiwu Shu, Jing Wang, <b>Yuhao Zhang</b>. <br>
The 22nd USENIX Symposium on Networked Systems Design and Implementation (NSDI'25), 2025, <b>CCF-A</b>.
<br>

- Deft: A Scalable Tree Index for Disaggregated Memory.[<a href="">PDF</a>] <br>
Jing Wang, Qing Wang, <b>Yuhao Zhang</b>, Jiwu Shu. <br>
The 20th European Conference on Computer Systems (Eurosys'25), 2025, <b>CCF-A</b>.
<br>

- Ares-Flash: Efficient Parallel Integer Arithmetic Operations Using NAND Flash Memory.[<a href="">PDF</a>]<br>
Jian Chen, Congming Gao, Youyou Lu, <b>Yuhao Zhang</b>, Jiwu Shu.<br>
57th Annual IEEE/ACM International Symposium on Microarchitecture (MICRO'24), 2024, <b>CCF-A</b>.
<br>

- Full Lifecycle Data Analysis on a Large-scale and Leadership Supercomputer: What Can We Learn from It?[<a href="">PDF</a>]<br>
Bin Yang, Hao Wei, Wenhao Zhu, <b>Yuhao Zhang</b>, Weiguo Liu, Wei Xue.<br>
USENIX Annual Technical Conference (USENIX ATC'24), 2024, <b>CCF-A</b>.
<br>

- A Semantic-integrated LSM-tree based Key-Value Storage Engine for Blockchain Systems.[<a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10376454">PDF</a>]<br>
Qian Wei, Zehao Chen, <b>Yuhao Zhang</b>, Xiaojun Cai, Zhiping Jia, Zhaoyan Shen, Yi Wang, Zili Shao, Bingzhe Li.<br>
IEEE Transactions on Computer-Aided Design of Integrated Circuits And System (TCAD), 2024, <b>CCF-A</b>.
<br>

- Towards High-throughput Neural Network Inference with Computational BRAM on Nonvolatile FPGAs.[<a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10546738">PDF</a>]<br>
Hao Zhang, Mengying Zhao, Huichuan Zheng, Yuqing Xiong, <b>Yuhao Zhang</b>, Zhaoyan Shen.<br>
Design, Automation & Test in Europe (DATE'24), 2024, <b>CCF-B</b>.
<br>

- Perseid: A Secondary Indexing Mechanism for LSM-based Storage Systems.[<a href="https://dl.acm.org/doi/pdf/10.1145/3633285">PDF</a>]<br>
Jing Wang, Youyou Lu, Qing Wang, <b>Yuhao Zhang</b>, Jiwu Shu.<br>
ACM Transactions on Storage (TOS), 2024, <b>CCF-A</b>.
<br>

- ASHL: An Adaptive Multi-stage Distributed Deep Learning Training Scheme for Heterogeneous Environments.[<a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10256683">PDF</a>]<br>
Zhaoyan Shen, Qingxiang Tang, Tianren Zhou, <b>Yuhao Zhang</b>, Zhiping Jia, Dongxiao Yu, Zhiyong Zhang, Bingzhe Li.<br>
IEEE Transactions on Computers (TC), 2024, <b>CCF-A</b>.
<br>

- Static Scheduling of Weight Programming for DNN Acceleration with Resource Constrained PIM.[<a href="https://dl.acm.org/doi/pdf/10.1145/3615657">PDF</a>]<br>
Xin Gao, Hongyue Wang, Yiyan Chen, <b>Yuhao Zhang</b>, Zhaoyan Shen, Lei Ju.<br>
Transactions on Embedded Computing Systems (TECS), 2023, <b>CCF-B</b>.
<br>


- Revisiting Secondary Indexing in LSM-based Storage Systems with Persistent Memory.[<a href="https://www.usenix.org/system/files/atc23-wang-jing.pdf">PDF</a>]<br>
Jing Wang, Youyou Lu, Qing Wang, <b>Yuhao Zhang</b>, Jiwu Shu.<br>
USENIX Annual Technical Conference (USENIX ATC'23), 2023, <b>CCF-A</b>.
<br>

- PQ-PIM: A Pruning-Quantization Joint Optimization Framework for ReRAM-Based Processing-in-Memory DNN Accelerator.[<a href="https://www.sciencedirect.com/science/article/pii/S1383762122000911?via%3Dihub">PDF</a>]<br>
<b>Yuhao Zhang</b>, Xinyu Wang, Xikun Jiang, YuhanYang, Zhaoyan Shen, Zhiping Jia.<br>
Journal of Systems Architecture (JSA), 2022, <b>CCF-B</b>.
<br>


- An Efficient Highly Parallelized ReRAM-based Architecture for Motion Estimation of HEVC.[<a href="https://www.sciencedirect.com/science/article/pii/S1383762121000928?via%3Dihub">PDF</a>]<br> 
<b>Yuhao Zhang</b>, Bing Liu, Zhiping Jia, Renhai Chen, Zhaoyan Shen.<br>
Journal of Systems Architecture (JSA), 2021, <b>CCF-B</b>.
<br>

- A Practical Highly Paralleled ReRAM-based DNN Accelerator by Reusing Weight Pattern Repetitions.[<a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9395497">PDF</a>]<br>
<b>Yuhao Zhang</b>, Zhiping Jia, Hongchao Du, Runzhen Xue, Zhaoyan Shen, Zili Shao.<br>
IEEE Transactionson Computer-Aided Design of Integrated Circuits And System (TCAD), 2021, <b>CCF-A</b>.
<br>

- PattPIM: A Practical ReRAM-Based DNN Accelerator by Reusing Weight Pattern Repetitions.[<a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9218638">PDF</a>]<br>
<b>Yuhao Zhang</b>, Zhiping Jia, Yungang Pan, Hongchao Du, Zhaoyan Shen, Mengying Zhao, Zili Shao.<br>
Design Automation Conference (DAC'20), 2020, <b>CCF-A</b>.
<br>


# 🎖 Honors and Awards

- Outstanding Graduate, Shandong University, 2022.
<br>

- Outstanding Academic Achievement Award for Graduate Students, Shandong University, 2022.(1 PhD students from the the the school of computer science and technology were selected).
<br>

- National Scholarship for Ph.D. Graduate Students, Shandong University, 2021. (2 PhD students from the the the school of computer science and technology were selected)
<br>


