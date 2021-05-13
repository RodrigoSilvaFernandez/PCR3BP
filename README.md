# PCR3BP

This code computes the Planar and Circular Resctricted 3 Body Problem (PCR3BP) for a satellite of standard cubesat of 6 units, or 8 kg its equivalent in mass, in the Earth-Moon System.
The model considers three perturbations: atmospheric drag, oblate Earth (J2 factor) and Sun gravity.
The propulsion is modeled as a mean force over time.

To use the code, execute it once to obtain a final point, using an operation frequency of the thruster f1, measured in Hertz and represented as the variable f in the code; and a time of flight t1, represented as the varaible frac in the code and measured in periods of the system T (1T is approximately 27.3 days). This final point can be used as a new initial contidion executing the code again, using a second frequency f2, a second time t2 and a stop frequency fS.

Note: Even though there is not limit to the operation frequency of the thuster, it is suggested to use a maximum frequency of 20 Hz and a maximum stop frequency of 25 Hz. This is because a real thruster will have a limit on the operation frequency and it is necessary to consider it. 

The next examples in descending order are for the cases:

f1 =  5 Hz, t1= 16T, f2=6Hz, t2=4T and fS=25 Hz<br/>
f1 = 10 Hz, t1=  8T, f2=7Hz, t2=4T and fS=25 Hz<br/>
f1 = 20 Hz, t1=  4T, f2=8Hz, t2=4T and fS=20 Hz

<img align="left" src="https://user-images.githubusercontent.com/83910542/118006498-4e0d9780-b319-11eb-9bf9-b1793868d19e.png" width=45% height=45%>
<img align="right" src="https://user-images.githubusercontent.com/83910542/118006501-4f3ec480-b319-11eb-98cc-c6f780bef2f5.png" width=45% height=45%>

<img align="left" src="https://user-images.githubusercontent.com/83910542/118011642-47cdea00-b31e-11eb-85ef-a370f05aa1a6.png" width=45% height=45%>
<img align="right" src="https://user-images.githubusercontent.com/83910542/118011644-48ff1700-b31e-11eb-9faa-e3306f3c37b0.png" width=45% height=45%>

<img align="left" src="https://user-images.githubusercontent.com/83910542/118012035-a5623680-b31e-11eb-9267-a02fc6c2240a.png" width=45% height=45%>
<img align="right" src="https://user-images.githubusercontent.com/83910542/118012043-a6936380-b31e-11eb-9e05-e0f65cf9dcb7.png" width=45% height=45%>






