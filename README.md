# Pythonexercises
Ejercicios de Python











Exercise 4n/
Create a program that asks the user for a number and then prints out a list of all the divisors of that number. (If you don’t know what a divisor is, it is a number that divides evenly into another number. For example, 13 is a divisor of 26 because 26 / 13 has no remainder.)
respuesta=int(input ("Introduce un número :"))
divisores= list(range (1,respuesta + 1))
lista_divisores=[]
 
for e in divisores:
 if respuesta % e == 0:
   lista_divisores.append(e)
print (lista_divisores)
