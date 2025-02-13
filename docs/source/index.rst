=======================
反应堆蒙卡程序RMC·文档
=======================

\ **反应堆蒙卡程序RMC(Reactor Monte Carlo code)**\ 是由清华大学工程物理系核能科
学与工程管理研究所反应堆工程计算分析实验室（`REAL`_）自主研发的、用于反应堆计算
分析的三维粒子输运蒙卡程序。

RMC针对反应堆计算分析中的基本需求，同时结合先进与新概念反应堆设计时几何结构灵活、
中子能谱复杂及材料组分多样、各向异性及泄漏强（某些特定情况）等特点进行研发，是多
物理多尺寸耦合核能系统数值分析平台的物理计算核心。


RMC的研发始于2001年，能够处理复杂几何结构、采用连续能量点截面对复杂能谱和材料进
行描述，并能够根据实际问题的需要对临界问题本征值和本征函数计算、精细核素链燃耗模
拟、中子动力学与瞬态过程分析、在线核截面并行处理、中子光子耦合输运、均匀化与并群
、S/U分析、核热耦合等进行计算。并针对蒙卡方法的特点，RMC中研发并应用了几何处理加
速、核截面处理优化、输运过程模拟新方法（含混合蒙卡）、源收敛判断与加速、计数器优
化、大规模计数与综合并行、模型可视化与可视化建模等提高计算效率的方法和技巧。

当前RMC版本为：RMC 3.5.0

分支号（git-sha）：4b6b173bda1b0ba77939a8e1f4b45a660b660576

|

.. figure:: logo/logo_real.png
   :width: 2.4 in
   :align: center

.. only:: html

=======
目录
=======

.. toctree::
   :maxdepth: 1

   theory/index
   compile/index
   install/index
   usersguide/index
   usersguide_english/index
   developguide/index
   codedesign/index


.. _REAL: http://www.reallab.org.cn
