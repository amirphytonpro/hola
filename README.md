import random
your_information=[]
while True:
    a = input("Escribe algo sobre ti(¡con mayúsculas al inicio!): ")
    b = input('quieres que se imprima tu informacion')
    your_information.append(a)
#tu informacion
    if b == "si":
      print(your_information)
    
