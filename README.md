# What is the optimal angle to maximize the distance of a ballistic trajectory

It's a well known fact that if you neglect air resistance when throwing a ball for example the best angle to maximize the distance is 45 degrees. But that angle is best if we include a complicated dependence in the air resistance? I use a complicated drag term and solve Newton's equation using a 4-order runge kutta. To find the the best angle is use an adaptive hillclimb to iterate angles from som starting angle. It's adaptive since it changes the step length of the hillclimb if it has to change the direction of it search so as to get a better resolution of the best angle.

![](https://github.com/bolibomp/OptimalThrow/blob/main/optthrow.png?raw=true)
