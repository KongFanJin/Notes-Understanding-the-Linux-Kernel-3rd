使用jupyter记录C++笔记
- https://notebooks.gesis.org/binder/
- https://github.com/jupyter-xeus/xeus-cling
- https://github.com/conda-forge/miniforge
- https://zhuanlan.zhihu.com/p/623557144

配置环境变量
```
# miniforge
export MINIFORGE_HOME=$HOME/mambaforge
export PATH=$PATH:$MINIFORGE_HOME/bin
```
```shell
$ source ~/.profile
$ mamba install -c conda-forge xeus-cling
```
```shell
$ jupyter kernelspec install PREFIX/share/jupyter/xcpp11 --sys-prefix
$ jupyter kernelspec install PREFIX/share/jupyter/xcpp14 --sys-prefix
$ jupyter kernelspec install PREFIX/share/jupyter/xcpp17 --sys-prefix
```
使用

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/KongFanJin/Notes-Understanding-the-Linux-Kernel-3rd/HEAD)

Linux kernel Source Codes
- [kernel - Linux source code (v2.6.11) - Bootlin](https://elixir.bootlin.com/linux/v2.6.11/source/kernel)

Free PDF
- [gauss.ececs.uc.edu/Courses/e4022/code/memory/understanding.pdf](http://gauss.ececs.uc.edu/Courses/e4022/code/memory/understanding.pdf)
