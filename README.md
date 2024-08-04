# Optmization Fast Path Planning
## Description
this was project was Optimization course project supervised by prof: Mohamed Karmose and prof: Karim Benwan and was ranked as level two achieving first place among 10 teams
## Abstract
The paper try to propse Fast algorithm for design of smooth path through multiple constriants from one point to another to minimize cost and time taken for a drone to move from edge of plane to the other edge avoiding collision with presented obstacles along this path. Number of the safe box ( the area that is safe from collision) is considered large. The alogrithm proposed provide two preprocessing : offline preprocessing and online processing (generate quickly and smooth path). the algorithm designs trajectories that are guaranteed to be safe at all times, and it detects infeasibility whenever such a trajectory does not exist. Subproblems like finding shortest path in weighted graph and solving (multiple) convex optimal control problems. An efficient open-source software implementation, fastpathplanning is provided in this paper. 
## Project Content
<ul>
  <li>Powerpoint includes all slides used in presentation of this project</li>
  <li>Two MATLAB code demonstrating different phases of fast path planning
  <ul>
    <li>
      Offline Preprocessing: construct a graph that stores the intersections of the safe boxes and solve a convex optimization problem 
      to label the edges of this graph with approximate distances and it is done once.
    </li>
    <li>
      Polygonal Phase: use the graph constructed offline to design a polygonal curve of short length that 
      connects the given initial and terminal points and solve a sequence of convex optimal control problems to 
      transform the polygonal curve into a smooth path that approximately minimizes a given objective function.
    </li>
  </li>
  </ul>
  </li>
</ul>

## Acknowledge
this project was team effort of 4 engineers :

Mostafa Sayed Ahmed            <br />
Mohamed Rizq Amin              <br />
Mohamed Abdelhakim Hassan      <br />
Abdullah Hisham Abdelmonem     <br />

