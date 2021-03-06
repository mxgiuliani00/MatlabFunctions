MatlabFunctions
===============

Some examples of Matlab functions implemented for my research activities:

`plotPareto4D.m` creates a 4-dimensional (i.e., x,y,z,w) representation where 'x' and 'y' are plotted on the primary axes, the dimension of the circles is proportional to 'z' and the colors represent 'w'. Examples can be found in [Castelletti et al. (2013)](http://ascelibrary.org/doi/abs/10.1061/(ASCE)WR.1943-5452.0000348?mi=3d26f5&af=R&filter=multiple&text1=progressive+collapse&field4=all&field3=all&field2=all&field1=articletitle&startPage=0&pageSize=20&displaySummary=true).

`tuples_shuffling.m` performs a random shuffling of the tuples (rows) of the input dataset. This operation has been demonstrated to enhance the performance of the Iterative Input Selection algorithm ([Galelli and Castelletti, 2013](http://onlinelibrary.wiley.com/doi/10.1002/wrcr.20339/abstract)).

`plotIIS.m` creates colormaps showing the set of input (on the rows) selected over multiple runs (on the columns) of the Iterative Input Selection algorithm ([Galelli and Castelletti, 2013](http://onlinelibrary.wiley.com/doi/10.1002/wrcr.20339/abstract)) and the corresponding model perfomance. In addition, it creates a parallel-axes plot (using the plotParallelAxes function) showing some metrics supporting the results' analysis.

`plotParallelAxes.m` creates a parallel-axes plot ([Inselberg, 1997](http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=636793&tag=1)) to represent a multi-dimensional dataset. Examples can be found in [Giuliani et al. (2014)](http://onlinelibrary.wiley.com/doi/10.1002/2013WR014700/full).

Copyright (C) 2013-2014 Matteo Giuliani (matteo.giuliani@polimi.it).

The functions in this repository are free software: you can redistribute it and/or modify it under the terms of the GNU Lesser General Public License. This code is distributed WITHOUT ANY WARRANTY. See the GNU Lesser General Public License for more details.