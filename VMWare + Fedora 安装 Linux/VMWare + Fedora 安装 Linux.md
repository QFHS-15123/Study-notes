# VMWare + Fedora 安装 Linux

1. 下载 [VMware Workstation Pro](https://www.vmware.com/products/workstation-pro/workstation-pro-evaluation.html)

   页面下拉，下载试用版：<img src="VMWare + Fedora 安装 Linux_img/image-20230526095156887.png" alt="image-20230526095156887" style="zoom:50%;" />

2. 下载 [Fedora Workstation](https://fedoraproject.org/workstation/download/)

   <img src="VMWare + Fedora 安装 Linux_img/image-20230526105000482.png" alt="image-20230526105000482" style="zoom: 33%;" />

3. 打开 VMware Workstation Pro <img src="VMWare + Fedora 安装 Linux_img/image-20230526095527528.png" alt="image-20230526095527528" style="zoom:33%;" />，创建新的虚拟机（以下内容为用 CentOS 映像安装， Fedora 映像大同小异）

   1. 选择自定义配置：

      <img src="VMWare + Fedora 安装 Linux_img/1.png" alt="1" style="zoom:50%;" />

   2. 下一步：

      <img src="VMWare + Fedora 安装 Linux_img/image-20230526100856151.png" alt="image-20230526100856151" style="zoom:50%;" />

   3. 选择 .iso 映像文件：

      <img src="VMWare + Fedora 安装 Linux_img/image-20230526100930380.png" alt="image-20230526100930380" style="zoom: 50%;" />

   4. 输入用户名、密码：

      <img src="VMWare + Fedora 安装 Linux_img/image-20230526101155401.png" alt="image-20230526101155401" style="zoom: 50%;" />

   5. 输入虚拟机名称，设置位置：

      <img src="VMWare + Fedora 安装 Linux_img/image-20230526101310802.png" alt="image-20230526101310802" style="zoom:50%;" />

   6. 配置处理器：

      <img src="VMWare + Fedora 安装 Linux_img/image-20230526101345278.png" alt="image-20230526101345278" style="zoom:50%;" />

   7. 无脑下一步，选择 Start Fedora

   8. 根据引导安装 Fedora：

      <img src="VMWare + Fedora 安装 Linux_img/image-20230526104253437.png" alt="image-20230526104253437" style="zoom:50%;" />
      
      <img src="VMWare + Fedora 安装 Linux_img/image-20230526104638900.png" alt="image-20230526104638900" style="zoom:50%;" />
      
      <img src="VMWare + Fedora 安装 Linux_img/image-20230526104611868.png" alt="image-20230526104611868" style="zoom:50%;" />

4. 调出命令行：

   右上角![image-20230526110351813](VMWare + Fedora 安装 Linux_img/image-20230526110351813.png) -> ![image-20230526110415975](VMWare + Fedora 安装 Linux_img/image-20230526110415975.png) -> <img src="VMWare + Fedora 安装 Linux_img/image-20230526110433175.png" alt="image-20230526110433175" style="zoom:33%;" />

5. 设置共享文件夹：

   1. 虚拟机 -> 设置-> <img src="VMWare + Fedora 安装 Linux_img/image-20230526164235930.png" alt="image-20230526164235930" style="zoom: 50%;" />

   2. 挂载共享文件夹：

      `sudo mount -t vmhgfs .host:/共享文件夹名 /mnt`
