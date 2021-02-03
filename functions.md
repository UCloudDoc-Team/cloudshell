
### 功能特性



* 自动创建免费虚拟机

    当Cloud Shell启动时，会自动创建一台虚拟机，供您独享使用，同一个账户的不同会话会共享一台虚拟机。不同账户的虚拟机相互隔离，保障安全。
    
* 文件永久存储

    Cloud Shell可以挂载UFile存储桶到/data目录，用于永久存储文件，避免文件随着虚拟机销毁而丢失。挂载时可选已有存储空间挂载，也可以授权Cloud Shell
    帮你新建存储空间并挂载，根据计费规则，当存储数据小于20GB时免费，详细计费规则请[参考文档](https://docs.ucloud.cn/ufile/bill/new) 。
    
* 预装命令
  - UCloud工具链产品：[UCloud-CLI](https://docs.ucloud.cn/cli/intro) , [Terraform](https://docs.ucloud.cn/terraform/README) 
    (即开即用，无须配置账户信息)。
  - 编程语言：golang, python, java, nodejs
  - 常用Linux命令：git, vim, curl, ssh等
  
* 使用限制
  
  - 每个账户同时能打开的会话不超过5个。 
  - 这些会话公用同一台虚拟机。
    

     