# ECstudio-circuits
This repository contains the Analog circuits simulated in Electric circuit studio application
# 1. The full wave rectifier
Rectifier is a circuit which converts Alternating signal into steady signal,in common AC to DC.
At the output we don't get the pure DC but we obtain the pulsating DC signal(a signal which contains both the AC component along with the DC).
The function of the full wave rectifier is to clip the negative half cycle of the input AC signal. The pulsating DC signal can be converted into pure DC signal by connecting 
the filter at the output.
![image](https://user-images.githubusercontent.com/85921230/153843191-14415c22-c5bf-4ab1-895f-1675cf709061.png)
The AC source is connected to the centertapped transformer. The center tapped transformer provide the necessary phase signal to the diodes, that is, the diodes conduct only when
they get forward biased, means the positive half cycle of AC. So when D1 is fetched with the raising sinusoidal signal,simultaneously the transformer provide the falling 
sinusoidal signal to the D2. Input of both diodes are out of phase with respect to each other. From this diodes the signal is combined and the only positive half cycle is obtained at the resistor output.
