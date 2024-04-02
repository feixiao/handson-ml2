# OSX M1pro 环境配置

#### 使用 conda 配置

```shell
#conda env create -f environment_osx_m1pro.yml
#conda remove --name tf2 --all

conda create -n tf2 python=3.8
conda activate tf2

conda install scikit-learn matplotlib request
conda install numpy pandas

jupyter notebook

# Visual Studio Code 配置juptyer server
# 控制台日志里面找配置
# Visual Studio Code 也可以直接选择tf2
```

#### 从配置文件恢复环境
