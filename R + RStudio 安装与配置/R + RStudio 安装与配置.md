# R + RStudio 安装与配置

1. 安装[R](https://mirrors.sjtug.sjtu.edu.cn/cran/bin/windows/base/)，注意**路径不要有中文**（本例安装在`D:/R/R-4.3.0`）

2. **在R安装完成后**安装[RStudio](https://posit.co/download/rstudio-desktop/)

3. 修改`R`安装程序包的位置：

   打开`D:/R/R-4.3.0/etc/Rprofile.site`，添加以下代码：

   ```
   .libPaths(c('D:/R/R-4.3.0/library', .libPaths()))
   ```

4. 配置`RStudio`：

   1. Tools -> Global Options -> Code -> Saving -> Default text encoding 修改成 UTF-8
   2. Tools -> Global Options -> Packages -> Primary CRAM repository 设置成国内镜像源