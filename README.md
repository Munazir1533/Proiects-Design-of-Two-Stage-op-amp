# Proiects-Design-of-Two-Stage-op-amp
`Specification`
![image](https://github.com/Munazir1533/Proiects-Design-of-Two-Stage-op-amp/assets/93303360/d01bcb39-730e-4ff9-b7ee-bbac353dd555)

`Calculation`
`Specification for first stage`

Specification:

Gain(Av)=40

Rout=150 KΩ

BW=25 MHz


Formula Used

BW(3dB freq)  = 1/(2π.𝑅𝑜𝑢𝑡.𝐶𝐿)		Av=gm.Rout

Rout= ro1 // ro2


CL=42.44 fF

gm/id=10  (Choose)

gm=0.266 mS

Id=26.6 μA

gm/gds= 81.72   ……from chart	 id/w=13.6

gds=3.25 μS				 W1=1.95 μm

Ro1=307.21 KΩ

Ro2=293.12 K Ω

gds2=3.41 μS

(Id/gds)2=7.8 

(gm/id)2= 7.106 …… from chart

(Id/w)2=7.312  …… from chart

Vgs2=712.9 mV

W2= 3.63 μm

`Stage one schematic`
![image](https://github.com/Munazir1533/Proiects-Design-of-Two-Stage-op-amp/assets/93303360/ee79a1d2-1eb3-496e-9462-dfaa7f0b339f)

`Calculation for Second stage`
Specs:

Av=40

Rout=93 KΩ

Formula Used
Av=gm.Rout		Rout=Ro1 // Ro3 	gds=1/𝑟𝑜
W=𝑖𝑑/(𝑖𝑑/𝑤)

gm=0.43 mS

gm/id=12  		gm/gds=70.92		 Id/W=9.896

Id=35.8 μA		gds=6.06 μS		W1=3.61 μm

Ro1=165 KΩ	Ro3= 213.125 KΩ

gds3= 4.69 μS

(Id/gds)3=7.63

gm/id=6.315		Id/W=9.133

W3=3.91 μm

`Schematics for Second Stage`

![image](https://github.com/Munazir1533/Proiects-Design-of-Two-Stage-op-amp/assets/93303360/5b85a4c4-dd28-4636-beb5-80d2e8fd501a)



`Schematic for Two stage op amp`
![image](https://github.com/Munazir1533/Proiects-Design-of-Two-Stage-op-amp/assets/93303360/f379b53e-01c3-46a5-8791-efe83a603c8b)

`capacitor Modelling`
![image](https://github.com/Munazir1533/Proiects-Design-of-Two-Stage-op-amp/assets/93303360/43a8fe77-a9e9-4ed1-9e84-d109298db5da)

C1=Capacitance at Node(Vout1)= Cgd4 + Cgd1 + { (Cgd6 + Cc)*(1+Av2)}

C1= 1.3 pF

C2=Capacitance at Node(Vout2)= CL + Cgd7 + { (Cgd6 + Cc)*(1 + 1/𝐴𝑣2)}

C2=73.52 fF

`Pole And Zero`

Dominant Pole 

Fp1 =1/(2𝜋.𝑅𝑜𝑢𝑡1.𝐶1)

Fp1= 1.2 MHz		where Rout1=97.25 KΩ


Fp2= Beyond 1GHz


Sz=1/(𝐶𝑐(1/𝐺𝑚6  −𝑅𝑧))

Fz= -1.36GHz	           where Rz=12k, Gm2=2.95mS

`Frequency Compensation`

Cc=10 fF  (generally Cc=(0.3 – 0.5)*CL)

Rz=12 KΩ    (generally Rz=1⁄𝐺𝑚2)

But we have taken 12 KΩ  for achieving Phase Margin of 45º.

`Result`

![image](https://github.com/Munazir1533/Proiects-Design-of-Two-Stage-op-amp/assets/93303360/b6a21ed3-97dd-4de7-a209-4212e3f91450)

`Table of Parameters`
![image](https://github.com/Munazir1533/Proiects-Design-of-Two-Stage-op-amp/assets/93303360/ba3a8e8f-cc5d-4a08-a7f8-87b6be4f08a8)

`Outputs`
`Frequency Response`
![image](https://github.com/Munazir1533/Proiects-Design-of-Two-Stage-op-amp/assets/93303360/df662fc0-e394-438d-9124-0aee06de27d2)

`Transient Analysis`

![image](https://github.com/Munazir1533/Proiects-Design-of-Two-Stage-op-amp/assets/93303360/c3eaea7c-d236-40f2-ba8c-b5fb34c06f6d)









