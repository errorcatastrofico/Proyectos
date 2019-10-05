# Proyectos
g = int(input("Cuàntas personas tomarán la encuesta "))
c = int(0)
d = int(0)
e = int(0)
for g in range(g):
    genero = input("Escriba M si es mujer o H si es hombre ")
    if genero == "M" or genero== "m":
        c+=1

    elif genero== "H" or genero== "h":
        d+=1

    else:
        print("no es una respuesta válida ")
        e+=1
print("Hay" ,c, "mujeres y",d, "hombres y",e, "respuestas inválidas")

