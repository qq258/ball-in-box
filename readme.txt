this repository is used to store homework for software engineering 2018Spring 
members in this group:Shuhuai Ren,Junao Liu,Zhenyu Zhou,Xiaohu Luo,Guanhua Zhao,Xingyu Zhou,Xiaoyang Qi.

********************************************************************************************************************
week1:

Warm-up Project:
In a box bounded by [-1, 1], given m balloons(they cannot overlap) with variable radio r and position mu. And some tiny blocks are in the box at given position {d}; balloons cannot overlap with these blocks. find the optimal value of r and mu which maximizes 
sum r^2.

Tasks:
found a team of 7.
write a user story.
break down the user story to tasks.
be familiar with git.
think out your algorithm to solve the problem.
write down your test cases.
start to code with Python.
use git to store your coding progress and document.


算法：box预设的长和宽的范围都是[-1, 1]，长度均为2；因此，每行取长度*100个点，每列取宽度*100个点;这样总共就有2*100*2*100个点，把这些点都作为圆心;
算每个圆心到障碍点的距离，取每个圆心对应的最短距离，作为每个圆心对应的半径；将所有的最短距离求出后，取最大的m个，这样就找到了m个满足条件的最大圆


********************************************************************************************************************