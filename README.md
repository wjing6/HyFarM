# HyFarM
HyFarM is a novel task management strategy for hybrid far memory clusters.

# Abstract
Memory disaggregation possesses huge potential to save costs for data centers. It is still unclear how to efficiently place tasks on a disaggregated architecture. Recent advances in both storage-based vertical far memory (FM) and network-based horizontal FM have raised new questions about leveraging hybrid FM tiers to achieve the best performance per bit of memory. To date, very limited work has been done in this important area. 

In this work, we propose HyFarM, a novel task management strategy for hybrid FM clusters. We analyze FM-sensitivity and cooperatively co-locate tasks to enable high utilization and scalability. Further, by tapping into dynamic memory adaption within and across servers, our strategy allows one to consistently deliver high performance on memory-intensive tasks. We evaluate our design with a heavily instrumented environment.

# Environment
Python3

Numpy

Pandas

<code> apt-get install python3 </code>

<code> apt-get install python3-pip </code>

<code> pip install numpy </code>

<code> pip install pandas </code>

# How To Run
<code>python3 manager.py </code>

# How To Run in Container
We provide docker image in Baidu cloud[https://pan.baidu.com/s/1oLvpO3Mzu4Q2w3WBDkP8Ow?pwd=t6ra] with extracting code **t6ra**.

Start docker:

<code> docker run -it hyfarm:v1 bash </code>

Run application:

<code> python3 /root/FarMemSysSimv6/Manager.py</code>

# Parameter Configurations
Set sever number as  50, we use  <code> ServerNum = 50 </code>

Set Task number as 2000, we use  <code> Tasknum = 2000 </code>
