# Hubble_constant
Hubble constant's measurement is one of controversial problems in today's world. With the coming of new and powerful satellites, these measurements become more accurate and reliable.

Data:
------
I used Supernova data set from this precious site: https://sne.space/

For now, I only selected 110 data which includes SN data from 2017 onwards. 

Researchers can access my data in "data" folder.

Strategy:
----------
I employed linear regression to guess the Hubble constant. Using mean_square_error I calculated the sd of my conjecture.

In the following (thanks to pymc3!), I modified the constant with bayesian analysis's help (Note that my prior knowledge stems from Planck measurement)

Result:
----------
According to my calculations, the 95% HD interval was in [64.92, 69.63] range (Here my data was limited, but the pipeline will be the same for more complete data or another prior knowledge).


