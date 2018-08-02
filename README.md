# Least-Squares-Trilateration
Trilateration example using least squares method in scipy.

Trilateration enables the unknown point to be found. However a since there are a number of samples a non linear least squares method needs to be used to find the solution that has the least error. 

It is distinct from triangulation which has a series of angles to an unknown point. Trilateration uses a series of distances to an unkown point.


## Method
This code uses the [scipy.optimize.least_squares](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.least_squares.html) method. 


## Discussion
The first file, [limited simulated points](https://github.com/etymologisk/Least-Squares-Trilateration/blob/master/Trilateration%20Using%20Limited%20Simulated%20Points%20With%20scipy.optimize.least_squares.ipynb), takes 9 points which have a range to an unknown point. This was used as a test bed and can be manually manipulated to prove the method.   

The second file, [multiple simulated points](https://github.com/etymologisk/Least-Squares-Trilateration/blob/master/Trilateration%20Using%20Multiple%20Simulated%20Points%20With%20scipy.optimize.least_squares.ipynb), takes a large number of points, finds the closest n points and uses these in the least squares equations. 

[Equations.py](https://github.com/etymologisk/Least-Squares-Trilateration/blob/master/equations.py) is the output from the simulated script and is the next step in the implementation process. 

 

## Development
Next step is to implement this code with real world data. 








