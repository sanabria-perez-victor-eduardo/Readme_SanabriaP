# Readme_SanabriaP
Hora en la que termine un evento proporcionando los datos La hora en que inicia, los minutos y la duración.
#Start code here
#Victor Eduardo Sanabria Perez # your own code
#Ciencia de Datos e Información # your own code
print("Horas") # your own code
#Entrada de datos # your own code
horas = int(input("Escribe la hora en que inicia el evento: "))
min2 = int(input("Escribe los minutos en la cual inicia el evento:"))
dura = int(input("Cuantos minutos dura el evento:"))
suma = min2 + dura
hora = (suma // 60 + horas)
b = suma % 60
hr = hora % 24
#Salida de datos # your own code
print("Tu evento acaba a las:", hr, ":", b)
