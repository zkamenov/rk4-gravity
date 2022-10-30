# RK4 Gravity Simulation

I created this project to simulate the effects of gravity between two bodies for a school Physics 2 (Calc) project. Determining the position of the body at a point in time requires integration. The motion cannot be accurately modeled using Euler’s method, since the orbit would decay. It also cannot be solved mathematically due to the position being the double integral of gravitational acceleration, while gravitational acceleration is dependent on position. The best way to solve for the position is to use the Runge-Kutta 4 method to more accurately integrate the force of gravity twice.
