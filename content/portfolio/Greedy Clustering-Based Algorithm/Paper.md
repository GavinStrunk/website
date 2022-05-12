+++
date = "2022-05-01T19:41:01+05:30"
title = "Greedy Clustering-Based Algorithm for Improving Multi-point Robotic Manipulation Sequencing"
draft = false
image = "img/portfolio/algorithm_block_diagram.jpg"
showonlyimage = false
weight = 1
+++

Gavin Strunk  
May 2022

<!--more-->
[Full paper](https://arxiv.org/abs/2205.02662)

![](/img/portfolio/algorithm_block_diagram.jpg)

### Abstract

The problem of optimizing a sequence of tasks for a robot, also known as multi-point manufacturing, is a well-studied problem.  Many of these solutions use a variant of the Traveling Salesman Problem (TSP) and seek to find the minimum distance or time solution.  Optimal solution methods struggle to run in real-time and scale for larger problems. In online planning applications where the tasks being executed are fast, the computational time to optimize the ordering can dominate the total execution time.  The optimal solution in this application is defined as the computational time for planning plus the execution time.  Therefore, the algorithm presented here balances the quality of the solution with the total execution time by finding a locally optimal sequence.  The algorithm is comprised of waypoint generation, spatial clustering, and waypoint optimization.  Significant improvements in time reduction were seen and validated against a base case algorithm in simulation and on a real UR5 robot.  
