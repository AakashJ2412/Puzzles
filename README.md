# Abstract

The fundamental idea behind puzzles or games lie in making decisions to a well-defined problem. Thus there are two aspects to a puzzle: defining it, and solving it. Our team was interested in formally exploring puzzles, targeting depth to get a proper understanding of the field.

Thus, we looked at mazes, defined formally as a problem where you have to find the path from 0,0 to n,m in a Cartesian Grid, with an arbitrary number of edges having a cost of infinity. From a design perspective, the only major concern in solving such a problem is coming up with a correct algorithm. The interesting aspect that we quickly discovered, though, was that the positioning and number of such "arbitrary number of edges having a cost of infinity" is an interesting problem all in itself. 

We started off working on building mazes, and solving mazes. We found multiple algorithms for each, and had to remove some of them for redundancy. We used suggested software engineering principle of abstraction and DRY, allowing each person to work on their algorithm independently. 

After this, we worked on more advanced concepts with respect to mazes, which we came up with. We played around with mazes that change as the solving agent moves around in them (termed dynamic mazes) and mazes that have 'fake' walls (they appear as walls to the solving agent but in reality are pathways). If this document lacks in any sense, it is probably the combination of the above, or a dynamic mirage maze. 

As per our initial motive to explore this field in depth, we looked at antagonistic search algorithms and application in the Video Game Industry, making a game of our own to play on. To add depth to our understanding, we read multiple research papers and summarized them, with multiple discussions during the process. 

With this project, our entire team has gained a concrete understanding of maze-puzzles and how they are applied, along with exploring existing research and books in this field. We have spent time on making sure our work is reproducible and extensible, and we look forward to add more content to it apart from the timeline of the project.
