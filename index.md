# Numerical Methods using Python

This set of tutorials are written at an introductory level for an engineering or physical sciences major. It is ideal for someone who has completed college level courses in linear algebra, calculus and differential equations. While prior experience with programming is certainly an advantage, it is not expected. At UC Davis, this is aimed at sophomore level Chemical and Biochemical Engineers and Materials Scientists: examples and the language used here might reflect this. At the same time, this is not meant to be an exhaustive course in Python or in numerical methods. The focus is on introducing the mathematical techniques and developing an insight for scientific computation, independent of programming language.

Interactive tutorials using the Jupyter framework are an engaging complement to learning numerical methods from a static textbook. Yet I was unable to find a set of pedagogic and interactive code notebooks that covered the range of topics suitable for this level of instruction. I have hoped to fill this gap. These notebooks were developed and tested using the [Anaconda](https://www.anaconda.com/download/) distribution.

### [Introduction](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_00.ipynb)
- [0.1 Context and Scope](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_00.ipynb#scope)
- [0.2 Getting Used to Python](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_00.ipynb#install)
	- [0.2.1 Installing and Using Python](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_00.ipynb#start)
	- [0.2.2 Useful Tips](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_00.ipynb#tips)

### [1. Basic Operations and Control](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb?flush_cache=true)
- [1.1 Data Types and Basic Operations](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#intro)
	- [1.1.1 Integers](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#int)
	- [1.1.2 Floats](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#float)
	- [1.1.3 String](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#string)
	- [1.1.4 Tuples](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#tuples)
	- [1.1.5 Lists](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#lists)
	- [1.1.6 Numbers and Math: Numpy](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#numpy)
	
- [1.2 User-defined Functions](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#functions)
	- [1.2.1 Defining Functions](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#func)
	- [1.2.2 Single-line lambda function](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#lambda)
	
- [1.3 Logic and Repetition](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#structure)
	- [1.3.1 The IF condition](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#if)
	- [1.3.2 The FOR and WHILE loops](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#loops)
	
- [1.4 Vectorization: Manipulating Scientific Data](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#vector)
	- [1.4.1 Introduction to Arrays](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#arrays)
	- [1.4.2 Sequences](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#sequences)
	- [1.4.3 Slicing](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#slicing)
	- [1.4.4 Vectorizing](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#vectorizing)
	
- [1.5 Formatting and Storing Data](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#format)
	- [1.5.1 Formatting Output](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#output)
	- [1.5.2 Storing Arrays](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#storing)
	
- [Practice Problems](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_01.ipynb#exer)

### [2. Plotting and Visualization](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_02.ipynb?flush_cache=true)
- [2.1 Plotting 1D Data Sets](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_02.ipynb#plot)
	- [2.1.1 Basic Plotting: The pyplot Interface](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_02.ipynb#pyplot)
	- [2.1.2 Multiple graphics: Subplots](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_02.ipynb#subplot)
	- [2.1.3 Object-oriented plotting](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_02.ipynb#oop)
	- [2.1.4 Scatter plots](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_02.ipynb#scatter)
		
- [2.2 Multi-dimensional Data](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_02.ipynb#multiplot)
	- [2.2.1 2D data: Pseudocolors and contours](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_02.ipynb#pcolor)
	- [2.2.2 3D visualization: Surface plotting](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_02.ipynb#surfplot)

- [Practice Problems](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_02.ipynb#exer2)

### [3. Statistics and Data Analysis](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_03.ipynb?flush_cache=true)
- [3.1 Elementary Statistics](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_03.ipynb#stat)
	- [3.1.1 Measures of Spread](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_03.ipynb#measures)
	- [3.1.2 Distributions and histograms](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_03.ipynb#hist)
- [3.2 Pandas: a powerful data platform](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_03.ipynb#pandas)
	- [3.2.1 Introduction to data frames](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_03.ipynb#df)
	- [3.2.2 A real example: the data science of lead in lipsticks](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_03.ipynb#lipstick)

- [Practice Problems](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_03.ipynb#exer)

### [4. Systems of Linear Equations](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_04.ipynb?flush_cache=true)
- [4.1 Elimination Methods](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_04.ipynb#lineq)
	- [4.1.1 Linear Systems and Computational Cost](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_04.ipynb#cost1)
	- [4.1.2 Gauss Elimination](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_04.ipynb#Gauss)
	- [4.1.3 Pivoting: Choosing the Right Row](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_04.ipynb#GaussPiv)
	- [4.1.4 Gauss-Jordan: Gauss on steroids!](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_04.ipynb#GaussJ)
	- [4.1.5 LU Decomposition](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_04.ipynb#LU)
	- [4.1.6 Computational Cost Revisited](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_04.ipynb#cost)

- [4.2 Inbuilt Python Routines](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_04.ipynb#inbuilt)
	- [4.2.1 Solving Linear Systems: linalg.solve](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_04.ipynb#solve)
	- [4.2.2 Fast and Easy Linear Algebran](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_04.ipynb#linalg)

- [Practice Problems](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_04.ipynb#exer)


### [5. Fitting and Interpolation](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_05.ipynb?flush_cache=true)
- [5.1 Line and Curve Fitting](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_05.ipynb#fitting)
	- [5.1.1 Least-squares linear fit](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_05.ipynb#leastsquares)
	- [5.1.2 Goodness of fit](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_05.ipynb#rsquared)
	- [5.1.3 Nonlinear fits using linear regression](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_05.ipynb#nonlinear)
	- [5.1.4 Polynomial Fits](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_05.ipynb#polynom)

- [5.2 Interpolation](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_05.ipynb#interp)
	- [5.2.1 Lagrange Interpolation](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_05.ipynb#lagrange)
	- [5.2.2 Splines](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_05.ipynb#spline)

- [Practice Problems](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_05.ipynb#exer)


### [6. Solutions of Nonlinear Equations](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_06.ipynb?flush_cache=true)
- [6.1 Numerical Root Finding](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_06.ipynb#roots)
	- [6.1.1 Exact and Numerical Roots](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_06.ipynb#exact)
	- [6.1.2 Errors and Tolerance](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_06.ipynb#error)

- [6.2 Nonlinear equations in one variable](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_06.ipynb#methods)
	- [6.2.1 Bisection Method](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_06.ipynb#bisection)
	- [6.2.2 Regula Falsi Method](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_06.ipynb#falsi)
	- [6.2.3 Newton's Method](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_06.ipynb#Newton)
	- [6.2.4 Halley's and higher-order methods](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_06.ipynb#householder)

- [6.3 More general root-finding](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_06.ipynb#general)
	- [6.3.1 Equations with multiple solutions](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_06.ipynb#multiple)
	- [6.3.2 Systems of nonlinear equations](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_06.ipynb#systems)
	- [6.3.3 Inbuilt Python routines](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_06.ipynb#inbuilt6)

- [Practice Problems](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_06.ipynb#exer)

### [7. Filtering Data and Images](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_07.ipynb?flush_cache=true)
- [7.1 Convolutions](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_07.ipynb#convolutions)
	- [7.1.1 Moving averages as low-pass filters](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_07.ipynb#moving)
	- [7.1.2 Matrix convolutions](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_07.ipynb#matrixconv)

- [7.2 Image Processing](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_07.ipynb#images)
	- [7.2.1 Image matrices and color schemes](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_07.ipynb#color)
	- [7.2.2 Image filters: box blur and Gaussian blur](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_07.ipynb#blur)
	- [7.2.3 Edge detection](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_07.ipynb#edge)

- [Practice Problems](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_07.ipynb#exer)


### [8. Numerical Differentiation](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb?flush_cache=true)
- [8.1 Finite Differences](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb#fd)
	- [8.1.1 Derivatives from discrete points](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb#discrete)
	- [8.1.2 Finite differences from Taylor series expansions](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb#taylor)
	- [8.1.3 End corrections](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb#end)
	- [8.1.4 Higher derivatives and higher-order methods](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb#higher)


- [8.2 Numerical Partial Differentiation](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb#others)
	- [8.2.1 Partial finite differences](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb#partial)
	- [8.2.2 An application: heat conduction](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb#heat)
	- [8.2.3 Inbuilt Python routines](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb#inbuilt)

- [Practice Problems](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb#exer)


### [9. Numerical Integration](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_09.ipynb?flush_cache=true)
- [9.1 Integrals as Finite Sums](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_09.ipynb#sums)
	- [9.1.1 Rectangle methods or Riemann sums](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb#rectangle)
	- [9.1.1 Taylor series expansions and truncation errors](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb#taylor)
	- [9.1.1 Trapezoidal rule](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb#trapz)
	- [9.1.1 Simpson's rule](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb#simpson)

- [9.2 More Integration Strategiess](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_09.ipynb#more)
	- [9.2.1 Multidimensional integrals](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb#multi)
	- [9.2.1 Inbuilt Python routines](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_08.ipynb#inbuilt9)

- [Practice Problems](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_09.ipynb#exer)


### [10. Ordinary Differential Equations: Initial Value Problems](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_10.ipynb?flush_cache=true)
- [10.1 Ordinary Differential Equations](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_10.ipynb#odes)
	- [10.1.1 First Order Initial Value Problems](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_10.ipynb#ivp)
	- [10.1.2 Euler's method: explicit versus implicit](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_10.ipynb#euler)
	- [10.1.3 Multi-stage solutions: the Runge-Kutta methods](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_10.ipynb#rk)

- [10.2 Coupled and Higher-order ODEs](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_10.ipynb#coupled)
	- [10.2.1 Systems of first-order ODEs: predators and prey](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_10.ipynb#systems)
	- [10.2.2 Higher-order initial value problems](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_10.ipynb#higher)
	- [10.2.3 Inbuilt python routines](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_10.ipynb#inbuilt10)

- [Practice Problems](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_10.ipynb#exer10)


### [11. Ordinary Differential Equations: Boundary Value Problems](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_11.ipynb?flush_cache=true)
- [11.1 Linear Boundary Value Problems](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_11.ipynb#BVP)
	- [11.1.1 Shooting method](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_11.ipynb#shooting)
	- [11.1.2 Finite difference method](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_11.ipynb#FD)

- [11.2 Inbuilt Python Function](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_11.ipynb#inbuilt)

- [11.1 Extending to Partial Differential Equations](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_11.ipynb#PDE)

- [Practice Problems](https://nbviewer.jupyter.org/github/hmanikantan/ECH60/blob/master/Chapter_11.ipynb#exer)



**License Requirements.** This repository is maintained on GitHub at [hmanikantan/ECH60](https://github.com/hmanikantan/ECH60) and published under an [MIT license](https://github.com/hmanikantan/ECH60/blob/master/LICENSE). This means you are free to use, copy, modify and adapt any part of this module for non-commercial purposes. The license terms require you to give attribution and share your work under the same terms. I welcome feedback of any kind, including pull requests for corrections and additions.

**Acknowledgements.** My ECH 60 students beta tested these tutorials. Their learning styles, feedback and comments crafted the structure of this series. The world of Python is a fantastic testament to the power of open-source science and learning. I thank the countless selfless nameless strangers whose stackoverflow comments have informed me, and whose coding styles have inadvertently creeped into these modules. And I thank the generous online notes of [John Kitchin](https://kitchingroup.cheme.cmu.edu/pycse/pycse.html), [Patrick Walls](https://www.math.ubc.ca/~pwalls/math-python/), [Vivi Andasari](http://people.bu.edu/andasari/courses/numericalpython/python.html), [Charles Jekel](https://github.com/cjekel/Introduction-to-Python-Numerical-Analysis-for-Engineers-and-Scientist), and [Jeffrey Kantor](https://github.com/jckantor) whose works directly or indirectly inspired and influenced this project. I am happy to contribute to this collective knowledge base, free for anyone to adapt, build on, and make it their own.
