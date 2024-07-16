# :package: Introduction <br>
This repository contains a simple project to solve **Linear Progamming(LP)** problems, which is implemented just using `C++`. <br>
# :newspaper: Description <br>
The method I choose to solve LP problems is the **Two-Phase simplex algorithm**. <br>
Also, I use **Bland's rule** to choose the variables instead of the normal rule to **avoid cycling**. <br>
The solving processes will be displayed in the *dictionary form*, not the *tabular form*.
# :bulb: Installation <br>
Make sure you installed `GCC` on your computer.
If you don't, here is the [MinGW](https://sourceforge.net/projects/mingw/) installation file to install it. <br>

First, you need to download all files to your computer. <br>
Then, open your *Terminal* in the same place as source files and run this command:
``` shell
g++ main.cpp ExFuncs.cpp Problems.cpp Models.cpp -o LPSolver.exe
```
Finally, just run the *LPSolver* file to run the program.
## :question: How to input the problem into the program ? <br>

# :heavy_exclamation_mark: Notes <br>
During the calculating process, maybe sometime you can see some phase has abnormal values, but it's okay.
