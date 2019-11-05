# Pythonexercises
Ejercicios de Python











Ex.4 =
Create a program that asks the user for a number and then prints out a list of all the divisors of that number. (If you don’t know what a divisor is, it is a number that divides evenly into another number. For example, 13 is a divisor of 26 because 26 / 13 has no remainder.)
__
respuesta=int(input ("Introduce un número :"))
divisores= list(range (1,respuesta + 1))
lista_divisores=[]
 
for e in divisores:
 if respuesta % e == 0:
   lista_divisores.append(e)
print (lista_divisores)
Ex.5 =
Take two lists, say for example these two:
 a = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89]
  b = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13]
and write a program that returns a list that contains only the elements that are common between the lists (without duplicates). Make sure your program works on two lists of different sizes.
__
