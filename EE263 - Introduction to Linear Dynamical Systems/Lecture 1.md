# EE263 Lecture 1    
Prof. Stephen Boyd     
course mechanics      
prerequisites:linear algebra, Laplace transform, differential equations, control systems, circuits and systems, dynamics    

<b> Major topics  </b>     
linear algebra 代数学 modeling and applications    
autonomous linear dynamical systems  
linear dynamical systems with i/o    
basic quadratic 二次的 control and estimation    

x = Ax+Bu, y=Cx+Du.      
A,B,C,D are constant, don't depend on t; most linear systems encountered are time-invariant.   
when there is no input u(hence, no B or D), system is called autonomous   
very often there is no feedthrough, i.e., D=0     

discrete-time linear dynamical system   

why study this? applications arise in many areas, automatic control systems, signal processing, communications, economics, finanace, circuit analysis, simulation, design, mechanical and civil engineering, aeronautics 航空学, navigation, guidance.    

usefulness of Linear Dynamical Systems (LDS)     
depends on availability of computing power, which is large and increasing exponentially.    

Nonlinear dynamical systems   
most based on linear methods; methods for linear systems oftern work well, in practice, for nonlinear systems.   

Examples   
consider a specific system, x(up dot)=dx/dt=Ax, y=Cx.    
output waveform is very complicated; looks almost random and unpredictable.    
Input design. add two inputs, two outputs to system, x(up dot)=Ax+Bu, y=Cx, x(0)=0     
Use clever input waveforms, can do much better.   

Estimation/filtering   
signal u (piecewise constant, period 1s) - filtered by 2nd-order system H(s), step response s(t) - w - A/D runs at 10Hz, with 3-bit quantizer - y      

Use Matlab.  

