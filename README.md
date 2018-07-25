# Least-Squares-Trilateration
Trilateration example using least squares method in scipy

##Method
This example takes 4 points which have a range to an unknown point. IN this example all the points are above the unknown point. This is simulating seismic data. 

Trilateration enables the unknown point to be found. However a since there are a number of samples a non linear least squares method needs to be used to find the soltuion that has the least error. 

##Result
Currently the depth is not well accounted for. 
