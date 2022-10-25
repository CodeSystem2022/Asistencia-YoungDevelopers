# Asistencia-YoungDevelopers
Integrantes :
Ceschin Agustin-Diaz Micaela-Funes Nahuel-Moyano Pablo-Moyano Lucas-Morbidelli Valentin-Rebolledo Lujan-Rebolledo Lourdes-Zambrana Ana

Diaz Micaela Ejercicio Cubo Python

class Cubo:
    def __init__(self, ancho, alto, profundidad):
        self.ancho = ancho
        self.alto = alto
        self.profundidad = profundidad

    def Volumen(self):
        return self.ancho * self.alto * self.profundidad

ancho = int(input('Ingrese el ancho del cubo: '))
alto = int(input('Ingrese el alto del cubo: '))
profundidad = int(input('Ingrese la profundidad  del cubo: '))

cubo1 = Cubo(ancho,alto,profundidad)
print(f'El volumen del cubo es :{cubo1.Volumen()}')
