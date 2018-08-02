# Least-Squares-Trilateration
Trilateration example using least squares method in scipy

## Method
This code uses the [scipy.optimize.least_squares](https://docs.scipy.org/doc/scipy/reference/generated/scipy.optimize.least_squares.html) method. 

## Discussion
The first file, [scipy.optimize.least.squares.ipynb](https://github.com/etymologisk/Least-Squares-Trilateration/blob/master/scipy.optimize.least_squares.ipynb), takes 9 points which have a range to an unknown point. This was used as a test bed and can be manually manipulated to prove the method.   

The second file, [Result Using Simulated Points In Pandas](https://github.com/etymologisk/Least-Squares-Trilateration/blob/master/Result%20Using%20Simulated%20Points%20In%20Pandas.ipynb), takes a large number of points, finds the "best" 500 and uses these in the least squares equations. 

Trilateration enables the unknown point to be found. However a since there are a number of samples a non linear least squares method needs to be used to find the solution that has the least error. 

It is distinct from triangulation which has a series of angles to an unknown point. Trilateration uses a series of distances to an unkown point. 

## Development
Further development required to remove dependancy on the hard coded equations in the simulated file. Also a clean up of the code as most of the graphing could be done by a function. 








