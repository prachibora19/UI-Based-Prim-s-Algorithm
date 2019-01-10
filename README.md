## Project Title
UI Based Prim's Algorithm


## Problem Statement
Create a portal [GUI] in which user can upload excel files or a CSV file which contains the data of the connected graph in a manner [vertex1, vertex2, edge weight]. The portal should be able to display the original graph long with the minimum spanning tree graph using Prim's algorithm.
 

## Why is this particular topic has been chosen?
This topic is chosen because Prim's algorithm is significantly faster in the limit when you've got a really dense graph with many more edges than vertices. So working on this project helped us in understanding the Prim algorithm in a better way by making its user interface and along with that helped us in learning R which is a Data science language in this project to make a user interface so that project can be scaled in the future.

## Objective and Scope of the Project

### Objective
Our objective is to find the minimum cost spanning tree using a Prim’s Algorithm.

### Scope
Our project can be used to study for ways to lay out electrical networks in a way that minimizes the total cost of the wiring. In a minimum spanning tree, all the nodes(houses) would be connected to power by wires in a way that has minimum cost and redundancy (cutting any wire necessarily cuts the power grid into two pieces.)
It can be also used to generate mazes. Prim’s algorithm has been used this way for creating high-quality mazes.

## Methodology
In ui.R, we have made the Frontend of the project, where the user uploads a CSV file of the format (weight1, weight2, vertex).  In the UI , there are three main parts,
1)Title Panel:- The Header of the project
2)Sidebar Layout:- Where the user can upload the CSV file and can select options for displaying the data file.
3)Main Layout:- where the main MST graph is displayed.
  a)The red coloured edges are part of MST.
  b)The black colour edges are part of main graph
  
The server.R is the backend of our project. In the backend, we have prepared functions for each tab or button. Like when the user uploads the CSV file and clicks on following buttons and their corresponding functions are called:
1.About file : output$filedf : run the code for displaying the name, size, type and datapath of the data file.
2.Data : output$table : run the code for displaying the data of .csv file uploaded.
3.Summary : output$sum : run the code for displaying the summary of each coloumn of data like max, mean, median values.
4.Generate MST graph : output$PrimGraph : run the code for displaying the MST graph in which red coloured edges are part of MST and other edges are part of main graph.
5.Show MST table : output$PrimTable : run the code for displaying the matrix data of the MST graph.


## Hardware and Software used in this project
Hardware:- Laptop HP probook G3, Apple Macbook Pro
Software:- RStudio and RShiny

## What contribution would the project make?

Meeting the needs of rural people and thinking through what could potentially affect those who work and live in rural areas is vital for local authorities. The minimum spanning tree problem has important applications in network design which has been extensively studied in the literature. The minimum spanning tree problem on a graph with edge costs and vertex profits asks for a subtree maximizing the difference between the total cost of all edges in the subtree and the total profits of all vertices contained in the subtree. Minimum spanning tree problem appears in the design of utility networks (e.g. bus services, electrifications) where villages and the network connecting them have to be chosen in the most profitable way. This project demonstrates the application of Prim's algorithms to the design of local access networks. Our main contribution is an efficient algorithmic implementation using an undirected graph model.





