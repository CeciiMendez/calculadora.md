def calculadora(numero_1,numero_2,caracter):
  if caracter == "+":
    resultado = numero_1 + numero_2
  elif caracter == "-": 
    resultado = numero_1 - numero_2
  elif caracter == "*":
    resultado = numero_1 * numero_2
  elif caracter == "/":
    resultado = numero_1 / numero_2

  else:
      resultado = "no encontrĂ³ la operacion"
  return resultado

numero_1 = int(input("ingrese el primer numero: "))
numero_2 = int(input("ingrese el segundo numero: "))
caracter = input("ingrese la operacion: ")

print(calculadora(numero_1,numero_2, caracter))