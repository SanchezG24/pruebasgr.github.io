Figura =(input("Ingrese el nombre de la figura a la que quiera calcular el área:")).lower()
base = float (input("base (b):")) 
altura = float (input ("altura(h):"))


if Figura == "cuadrado":
   print (base * altura) 

elif Figura == "triangulo":
   print((base* altura)/2)

elif Figura == "circulo":
    radio = float(input("Ingrese el radio del círculo: "))
    area = math.pi * radio ** 2
    print("El área del círculo es:", area)
else : print ( "Figura no valida")

print("GRACIAS!") 


