# AI for Tetris

The code for project "AI for Tetris" in CS181, ShanghaiTech University.

## Introduction

\TBD

### **What task does our code (method) solve?**

we design three AI agents for  Tetris,  including  heuristics  algorithm,  genetic-beam  search,and  deep  Q-learning,  and  conduct  a  comprehensive  evaluation. Experiments  show  that  (TBD)has  the  best  performance,  which arrives(T BD)for  average  scores,(T BD)for  average  tetrominoes,  and(T BD)for  average  cleared  lines.



## Code Structure

```
|--TetrisAI/
|   |--src/
|      |--arg_parser.py		/* Files 
|      |--tetris.py     /* Files for the implementation of Tetris game
|   |--genetic.py      /* Files for ...
```



### Notations and Definitions

The notations used throughtout following sections are shown in Table.Ⅰ.

![image-20220110230059220](C:\Users\MSI-PC\AppData\Roaming\Typora\typora-user-images\image-20220110230059220.png)

Before diving into the detail of three AI agents, we briefly describe three definition used in the following algorithms.

__Holes__. We define an empty position as a hole if it is surrounded by non-zero numbers or the border of the board.

__Block height__. The distance from the lowest non-zero number to the highest non-zero number of each column is the height of the column.

__Bumpiness.__ The list of difference between the column heights of two adjacent columns.

![image-20220110230136458](C:\Users\MSI-PC\AppData\Roaming\Typora\typora-user-images\image-20220110230136458.png)





### Heuristic Agent

介绍这个Agent

- Usage

```
python PLRperiodic.py #这里只是example，需要修改
```



### Genetic-Beam Agent

介绍这个Agent

- Usage

```
python predictor.py #这里只是example，需要修改
```



### Q-Learning Agent

介绍这个Agent

- Usage

```
python strategy.py #这里只是example，需要修改
```



## Evaluation

**Experiment settings.**

To cater for the needs of our methods, we modify  and integrate some Tetris implementations on GitHub. To evaluate the three methods of Tetris agent, we set $N=10$, $M=20$ (i.e., a $N\times M$ grid) as our test environment.



In order to evaluate the efficiency of methods implementing Tetris agent, we choose three scoring criteria to quantify the performance of different methods. To see the full evaluation, please read our report article.

## Conclusion

TBD