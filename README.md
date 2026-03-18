Evaluating N-body Simulation with Post-Newtonian correction on calculating eccentricity of binary black hole merger events

This research aims to evaluate the accuracy of N-body simulation with Post-Newtonian correction in calculating the eccentricity of binary black hole merger events at 1Hz frequency compared to the baseline eccentricity value given by the Peters' formula of eccentricity decay.
First, an eccentricity value of 0 (replaced with epsilon due to the non-zero eccentricity value that N-body simulation requires), 0.1, and 0.2 are each inputted to an N-body simulation EccentricTD model and it is forward propagated to the merger.
At the merger, the waveform from the N-body simulation is cross-correlated with the real waveform model given by LIGO open data source.
The initial eccentricity value at 1Hz frequency that yielded the highest matched score from matched filtering function is marked as the true eccentricity value.
Further fine search would be conducted after narrowing down the range of possible eccentricity values using matched filtering.
