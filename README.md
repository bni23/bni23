from math import * 

 

print("Tere!") 

print("3 + 8 / (4 - 2) * 4=") 

print(3 + 8 / (4 - 2) * 4) 

print() 

r=3 

a=2*r 

S1=a**2 

print("S1=",S1) 

P1=4*a 

print("P1=",P1) 

S2=pi*r**2 

print("S2=",round(S2,2)) 

P2=2*pi*r 

print("P2=",round(P2,2)) 

print() 

evro=0.000026 

r2=6378 

c=2*pi*r2 

print("c=",round(c,1)) 

n=c/evro 

print("n=",round(n,1)) 

print() 

kl="kill-koll " 

kd="killadi-koll " 

ki="killkoll " 

print((kl*2+kd)*2+kl*2+ki+kl) 

print() 

tekst1="Rong see sõitis tsuhh tsuhh tsuhh,"+"\npiilupart oli rongijuht."+"\nRattad tegid rat tat taa,"+"\nrat tat taa ja tat tat taa."+"\nAga seal rongi peal,"+"\nkas sa tead, kes olid seal?" 

print(tekst1) 

tekst2="Rong see sõitis tuut tuut tuut,"+"\npiilupart oli rongijuht."+"\nRattad tegid kill koll koll,"+"\nkill koll koll ja kill koll kill." 

if input("Хотите увидеть текст второй песни? Если хотите напишите yes ") =="yes": 

 print(tekst2) 

print() 

while 1: 

 try: 

 a1=float(input("Напишите длину первой стороны прямоугольника ")) 

 except: 

 print("Неправильный формат, допустимы только числа ") 

 continue 

 try: 

 b1=float(input("Напишите длину второй стороны прямоугольника ")) 

 except: 

 print("Неправильный формат, допустимы только числа ") 

 continue 

 break 

P=2*(a1+b1) 

print("P= ",P) 

S=a1*b1 

print("S= ",S)
