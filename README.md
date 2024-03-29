# Gbins
Program for GUPPI raw broadband injections. Injecting natural and artificial broad band signals both at the raw volatge and intensity domain is possible.

Considering the ISM as a cold ionised plasma the effect of ISM on pulsed signal can be modeled as the convolution of the signal with the impulse response of ISM. This introduces the frequency dependent time delay over the observed bandwidth(dispersion). 

## Workflow
![Workflow of the broadband injection pipeline](https://github.com/Akshay-E/G_BINS/blob/main/images/bb_inj.png)

## Results
### Dispersion by convolution (raw voltage) :

Broadband signal injected by convolving complex raw volatges with the transfer function of ISM. 

Dispersed Pulse             |  De-dispersed Pulse
:-------------------------:|:-------------------------:
![by convolution](https://github.com/Akshay-E/G_BINS/blob/main/images/neg5_conv.png)|![by convolution_de-dispersed](https://github.com/Akshay-E/G_BINS/blob/main/images/neg5_conv_de.png)

### Dispersion by sample shifting (raw voltage) :
Injecting natural and artificial broadband signals by computing delay between channels. 

#### Generating natural signal
Dispersed Pulse             |  De-dispersed Pulse
:-------------------------:|:-------------------------:
![by convolution](https://github.com/Akshay-E/G_BINS/blob/main/images/neg5_typeN.png)|![by convolution_de-dispersed](https://github.com/Akshay-E/G_BINS/blob/main/images/neg5_typeN_dedi.png)


#### Generating artificial broadband signals 
A1|A2|A3
:-------------------------:|:-------------------------:|:-------------------------:
![by convolution_de-dispersed](https://github.com/Akshay-E/G_BINS/blob/main/images/neg5_typeA1.png)|![by convolution](https://github.com/Akshay-E/G_BINS/blob/main/images/neg5_typeA2.png)|![by convolution_de-dispersed](https://github.com/Akshay-E/G_BINS/blob/main/images/neg5_typeA3.png)

#### Generating artificial signals with non-natural power law
x=1.8|x=2|x=2.2
:-------------------------:|:-------------------------:|:-------------------------:
![by convolution_de-dispersed](https://github.com/Akshay-E/G_BINS/blob/main/images/pl_1.8.png)|![by convolution](https://github.com/Akshay-E/G_BINS/blob/main/images/pl_2.png)|![by convolution_de-dispersed](https://github.com/Akshay-E/G_BINS/blob/main/images/pl_2.2.png)

### Injection in intensity domain :
Injection of broadband signal onto filterbank files

Natural and artificial dispersed pulse             |  Signals with non-natural power law
:-------------------------:|:-------------------------:
![by convolution](https://github.com/Akshay-E/G_BINS/blob/main/images/from_fil.png)|![by convolution_de-dispersed](https://github.com/Akshay-E/G_BINS/blob/main/images/plaw.png)







