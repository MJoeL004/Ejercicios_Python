# Clase padre
class Vehiculo:

    # Constructor de la clase padre
    def __init__(self, marca, color):
        self.marca = marca
        self.color = color


# Clase hija que hereda de Vehiculo
class Carro(Vehiculo):

    # Constructor de la clase hija
    def __init__(self, marca, color, modelo):

        # Hereda los atributos de la clase padre
        super().__init__(marca, color)

        # Nuevo atributo de la clase hija
        self.modelo = modelo

    # Método o acción
    def mostrar(self):
        print(f"El Carro es {self.marca}, Su color es {self.color}, El modelo es {self.modelo}")
        print("La marca del carro es", self.marca,"El color del carro es", self.color, ", Su modelo es", self.modelo)

# FUERA DE LA CLASE

# Instanciar el objeto
carro1 = Carro("Toyota", "Rojo", "Corolla")

# Llamar al método
carro1.mostrar()
