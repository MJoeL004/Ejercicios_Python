# Ejercicio 1python
class Animal:

    def __init__(self, nombre, raza):
        self.nombre = nombre
        self.raza = raza


class Perro(Animal):

    def __init__(self, raza, nombre, edad):
        super().__init__(nombre, raza)
        self.edad = edad

    def ladrar(self):
        print(f"El perro se llama {self.nombre}, la raza es {self.raza} y tiene {self.edad} años")
        print("El perro se llama", self.nombre,
              "Y la raza es", self.raza, "Y tiene", self.edad, "años")


perro1 = Perro("Labrador", "Max", 4)
perro1.ladrar()
