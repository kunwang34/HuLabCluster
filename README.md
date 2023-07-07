# HuLabCluster

## 目录 Content
- [服务器概况 Cluster Overview](./docs/1.%20%E6%9C%8D%E5%8A%A1%E5%99%A8%E6%A6%82%E5%86%B5.md)
- [文件上传 File Upload](./docs/2.%20%E6%96%87%E4%BB%B6%E4%B8%8A%E4%BC%A0.md)
- [任务提交 Job Submission](./docs/3.%20%E4%BB%BB%E5%8A%A1%E6%8F%90%E4%BA%A4.md)
- [Slurm使用指南 Slurm User Guide](./docs/4.%20slurm%E7%94%A8%E6%88%B7%E6%8C%87%E5%8D%97.rst)

## 测试 Tests
- [服务器使用基础及slurm使用基础 Server Usage and Slurm Usage Basics](./test/1.%20%E6%9C%8D%E5%8A%A1%E5%99%A8%E5%8F%8Aslurm%E4%BD%BF%E7%94%A8%E5%9F%BA%E7%A1%80.md)，完成此测试方可创建服务器账号，但只能单核运行程序。
  
    [Server Usage and Slurm Usage Basics](./test/1.%20%E6%9C%8D%E5%8A%A1%E5%99%A8%E5%8F%8Aslurm%E4%BD%BF%E7%94%A8%E5%9F%BA%E7%A1%80.md)，After completing this test, you can create a server account, but you can only run the program on a single core.
- [多线程和并行基础 Multithreading and Parallel Basics](./test/2.%20%E5%A4%9A%E7%BA%BF%E7%A8%8B%E5%92%8C%E5%B9%B6%E8%A1%8C%E5%9F%BA%E7%A1%80.md)，完成此测试可以多核运行程序。
  
    [Multithreading and Parallel Basics](./test/2.%20%E5%A4%9A%E7%BA%BF%E7%A8%8B%E5%92%8C%E5%B9%B6%E8%A1%8C%E5%9F%BA%E7%A1%80.md)，After completing this test, the program can be run on multiple cores.

- 以上测试完成后发送到邮箱kunwang034@gmail.com. 
    
    After the above test is completed, send it to the mailbox kunwang034@gmail.com.
## Warning
- 严禁在服务器运行非科研需求程序，包括但不限于各种挖矿软件、PCDN软件; 
  
    It is strictly prohibited to run non-scientific programs on the server, including but not limited to various mining software and PCDN software.
- 严禁私自搭建内网穿透服务; 

    It is strictly prohibited to privately set up intranet penetration services.

- 运行时长>1分钟或需要多线程运行的作业提交必须通过slurm系统

    Jobs that require a runtime longer than 1 minute or multi-threaded execution must be submitted through the Slurm system.

- 大型数据下载/上传到服务器，需要经过管理员许可

    Large-scale data downloads/uploads to the server require permission from the administrator.