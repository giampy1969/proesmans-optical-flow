# proesmans-optical-flow
Optical flow using the Proesmans method


Optical flow calculation using the gradient-based method devised by Marc Proesmans.
Look at the beginning of the cpp file for instructions on how to compile and call the proesmans function from MATLAB&reg;.

The algorithm is described and used in a couple of journal papers, look in the cpp file to find out more.

Incidentally, this also works as a good example on how to call c and cpp files from MATLAB.

Note that this has been tested mostly with Microsoft Visual C++ compilers, it's not guaranteed to work with other compilers.

Based on the original paper: 
McCane, B., Novins, K., Crannitch, D., and Galvin, B. (2001) "On Benchmarking Optical Flow", Computer Vision and Image Understanding, 84(1), 126-143.

Compared with other OF algorithms here:
Mammarella, M., Campa, G., Fravolini, M. L., and Napolitano, M. R., "Comparing Optical Flow Algorithms Using 6-DOF Motion of Real-World Rigid Objects"; IEEE Transaction on Systems, Man, and Cybernetics-Part C: Applications and Reviews, Vol 42, No. 6, Nov. 2012, 1752-1762
