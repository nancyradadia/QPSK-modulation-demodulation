# QPSK-modulation-demodulation
Python script for QPSK modulation and demodulation

It first generates 16 bits binary signal then perform modulation, add noise and demodulate the signal. Since, we add some noise after modulation, demodulated signal obtained does not exactly matches with the original signal.

# How to use ?
To plot the graphs we use matplotlib and to store the data (which we want to plot) we use numpy, hence you need to install the following:

```
pip install matplotlib
pip install numpy
```
To run the code:
```
python QPSK_modulation_demodulation.py
```

# Output

The output generated is in the form of graph. There are total 6 graphs generated:

1. Carrier wave (sine wave)
2. Carrier wave (cosine wave)
3. Original signal (16 bits)
4. Modulated wave
5. Noise
6. Demodulated wave (16 bits)

Here, the original signal and demodulated signal will not be exact beacause of noise. For example:


![comparison](https://user-images.githubusercontent.com/65729151/82722384-f0390780-9ce3-11ea-91bc-91eee1a21001.PNG)

# Author
+ [Nancy Radadia](https://github.com/nancyradadia)
+ [Dhatri Kapuriya](https://github.com/dhatrikapuriya)
+ [Hardi Kadia](https://github.com/hardi15)
+ [Suhanee Patel](https://github.com/sp2605)




