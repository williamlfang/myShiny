# Installation

```r
install.packages("shiny")
```

## 搭建　App

1. 建立一个目录，并为其命名，这个是以后具体的　`App` 调用的名称．比如，`myApp`
2. 在目录下面建立两个　`.R` 文件，用于存放代码，分别命令为　
    
    - `ui.R`：这个用于控制可视化界面
    - `server.R`：这个用于服务器处理
    
３. 通过　`shiny` 函数　`runApp('./myApp')` 来运行应用


