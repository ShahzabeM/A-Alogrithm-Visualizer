# A*_Alogrithm_Visualizer

## Introduction

In project I used Python and the Pygame module in order to create a visuliazationa and implementaion of the A Star alogrithm.

The A Star algorithm select a path that minimizes f(n)=g(n) + h(n) where n = next node, g(n) = distance from start node to n and
h(n) is a heuristic function that approximates the cost of the shortest path n to the desired point. The goal is to find the 
shortest path/ path with the least cost from the starting to the end point. 

## Visualization

My implementation of this was on a 50 by 50 grid where each spot/node repersents a step. The possible moves are 
UP, DOWN, LEFT, RIGHT all with a cost of 1.

The h(n) function is calcualted using Taxicab distance also known as Manhattan Distance, which is just sum of the absoulte vectors of 2 vectors.

![image](https://user-images.githubusercontent.com/81199764/140628919-aca899f7-97c6-4aae-b753-f7a7d8bcd504.png)

## Instructions

1) Run the "AStar.py" file and a pop up window should appear

![image](https://user-images.githubusercontent.com/81199764/140628962-05e220c9-f8e5-4c43-8f7d-da4163c66e70.png)

2) Click on any square to be your start point , the selected square should be orange

![image](https://user-images.githubusercontent.com/81199764/140628986-df80ce60-3b4c-4ae5-b54e-79bf4ddb43fb.png)

3) Click on any other square to be your end point, the selected sqaure should be turquiose

![image](https://user-images.githubusercontent.com/81199764/140629008-ff91aae2-8d03-4035-a442-f0c421833895.png)

4) Click anywhere and create black boxes which will be the barriers/obstacles, barriers can be erased be clicking with the right mouse button

![image](https://user-images.githubusercontent.com/81199764/140629032-b2f2ed56-9abe-4dab-9790-841c0717c76a.png)

5) Press the spacebar to start the algorthim and the end result should highlight your the shortest path in purple

![image](https://user-images.githubusercontent.com/81199764/140629073-e022c21b-e194-4580-8ded-c1382f335362.png)








                        
