1- Maximum bandwidth of 3.2MHz
2- Input impedence of 75 ohms
3- Uses 300mA
4- R820T - Min freq (24) and max freq(1766)
5- An SDR simply works by receiving an analog radio signal and then using an ADC
6- In practise an ADC will work up to a certain frequency
7- RTL2832U is a type of ADC which works up to 28.8MHz
8- To digitalize higher frequency signals we need an IF mixer stage to convert all received frequencies down to the frequencies that the ADC can use which is the job of the tuner chip(R820T)
9- It uses I/Q samlpling where 2 ADCs are used
10- Poor crystal tolerances
