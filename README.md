# Extension-del-codigo
Esta es la extension del codigo del 20/1/2026
class Persona:
  def __init__(self, nombre, edad):
    self.nombre = nombre
    self.edad = edad
  def saluda(self):
    print(f"Hola, soy {self.nombre} y tengo {self.edad} años.")

persona1 = Persona("Juan", 30)
persona2 = Persona("Ana", 25)
persona1.saluda()
persona2.saluda()

class Perro:
  def __init__(self, ladrido):
    self.ladrido = ladrido

  def ladrido(self):
    print("jau jau")


Perro1 = Perro("jau jau")
