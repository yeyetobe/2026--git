# 一、学习资料来源及相关链接；

1. git官方文件：https://git-scm.com/install/mac（安装）；
           [https://git-scm.com/book/zh/v2/起步-初次运行-Git-前的配置](https://git-scm.com/book/zh/v2/%e8%b5%b7%e6%ad%a5-%e5%88%9d%e6%ac%a1%e8%bf%90%e8%a1%8c-Git-%e5%89%8d%e7%9a%84%e9%85%8d%e7%bd%ae)（配置）；
2. 关于git的原理和用法图解：https://marklodato.github.io/visual-git-guide/index-zh-cn.html

# 二、实践流程（如安装、配置、使用过程）；

1. 安装：（终端完成）
- 前置：安装homebrew：

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

- 然后：安装git
    
    `brew install git`
       （可以通过 `git --version`来确认安装）
    
    ![截屏2026-05-02 19.16.54.png](attachment:cffeb3a3-de75-4136-9b31-993ff4a8d486:截屏2026-05-02_19.16.54.png)
    
1. 配置：
    
    ```bash
    		git config --global user.name "你的名字"
        git config --global user.email "你的邮箱"
    ```
    
    确认配置：
    
    ```bash
    git config --list
    ```
    

（会显示用户名和邮箱）

1. 

# 三、对每次提交的主要内容进行简要说明；

# 四、遇到的问题及解决方法（不少于2个）；

# 五、 Git学习心得