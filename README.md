# =========================================
# EJERCICIO 1 — Mesa y MesaDeMadera
# =========================================

# Clase padre
class Mesa:

    # Constructor con 3 atributos
    def __init__(self, color, material, tamaño):

        # Atributo color
        self.color = color

        # Atributo material
        self.material = material

        # Atributo tamaño
        self.tamaño = tamaño

    # Método 1
    def sostener(self):
        print("La mesa sostiene objetos")

    # Método 2
    def limpiar(self):
        print("La mesa está limpia")


# Clase hija que hereda de Mesa
class MesaDeMadera(Mesa):
    pass


# Crear objeto
mesa1 = MesaDeMadera("Café", "Madera", "Grande")

# Mostrar atributo
print(mesa1.material)

# Llamar métodos
mesa1.sostener()
mesa1.limpiar()
