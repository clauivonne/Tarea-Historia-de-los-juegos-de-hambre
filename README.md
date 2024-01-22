nombre=input("Cual es tu nombre= ").lower()
print("Hola ",nombre, "Bienvenido a los juegos del hambre!")

pregunta=input("Estamos reclutando jovenes para encontrar al proximo lider pero tendrás que pasar pruebas exhaustivas de vida o muerte. ¿Aceptas si o no? ").lower()

if pregunta == "no":
  pregunta=print("no tienes opcion, mueres")

elif pregunta == "si":
  pregunta=input("Preparada para luchar hasta morir. Escoge si vienes sola o acompañada: ").lower()

  if pregunta == "sola":
    pregunta=print("Que empiece el juego")

  elif pregunta == "acompañada":
    pregunta=print("Busque a su acompañante y mañana empiezan los juegos del hambre. HAHAHA")

else:
  pregunta=input("No es una opcion valida. ¿si o no? ")

  if pregunta == "no":
   pregunta=print("no tienes opcion, mueres")

  elif pregunta == "si":
   pregunta=input("Preparada para luchar hasta morir. Escoge si vienes sola o acompañada: ").lower()

   if pregunta == "sola":
    pregunta=print("Que empiece el juego")

   elif pregunta == "acompañada":
    pregunta=print("Busque a su acompañante y mañana empiezan los juegos del hambre. HAHAHA")
