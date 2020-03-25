# linearRegression
Linear Regression Matrix and Normal Equetion model (Octave)

Task has been done in Octave 5.2 (in minor version should work as well)

Functions:
  computecost.m -  Cost function for linear regression
  computecostMulti - Cost function for polinomial regression
  
  featureNormalize.m - feature normalization function using Mean and Standard Deviation
  
  gradientDescent.m - gradient descent algorithm to find Theta
  gradientDescentMulti.m - gradient descent algorithm to find Theta for n-features
  normalEqn.m -  Normal Equation algorithm (good to use on data sets up to 10,000 samples)
  
  For number of samples more than 10,000 is better to use gradient descent as it is more time saving way.
