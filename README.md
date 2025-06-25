# campeta-1
### Hola Mundo ###

# Nuestro hola mundo en Python
print("Hola profe adamo")
print('Hola profe adamo')

# Esto es un comentario

"""
Este es un
comentario
en varias líneas
"""

'''
Este también es un
comentario
en varias líneas
'''

# Cómo consultar el tipo de dato
print(type("Soy un dato str"))  # Tipo 'str'
print(type(5))  # Tipo 'int'
print(type(1.5))  # Tipo 'float'
print(type(3 + 1j))  # Tipo 'complex'
print(type(True))  # Tipo 'bool'
print(type(print("Mi cadena de texto")))  # Tipo 'NoneType'

##variables##
a = "Hola"
print(a)

b = 7
print(b)

c = str(b)
print(c, type(c))

d = True
print(d)

print(a, c, d)
print("Valor:", d)

print(len(a))

x, y, z, n = "Ana", "Pérez", "Ani", 20
print(f"Me llamo: {x} {y}. Mi edad es: {n}. Y mi alias es: {z}")

x = input("Tu nombre: ")
n = input("Tu edad: ")
print(x, n)

x = 30
n = "Mario"
print(x, n)

lugar: str = "Casa"
lugar = 3.14
print(type(lugar))

# operaciones Aritméticos #
print(1+2, 5-2, 2*3, 6/2, 9%2, 9//2, 2**2, 2**2+2-4//2)

print("Hi" + " " + "GPT")
print("Num: " + str(9))

print("Hey " * 2)
print("Yo " * (2**2))

x = 1.5 * 2
print("Go " * int(x))

# Comparativos
print(2 > 3, 2 < 3, 2 >= 3, 3 <= 3, 2 == 3, 2 != 3)

print("A" > "Z")
print("a" < "z")
print("abc" >= "aac")
print(len("abc") >= len("aac"))
print("A" <= "Z")
print("A" == "A")
print("A" != "Z")

# Lógicos
print(2 > 3 and "A" > "Z")
print(2 > 3 or "A" > "Z")
print(2 < 3 and "A" < "Z")
print(2 < 3 or "A" > "Z")
print(2 < 3 or ("A" > "Z" and 1 == 1))
print(not(2 > 3))

# strings #
s1 = "hola"
s2 = "mundo"

print(len(s1), len(s2))
print(s1 + " " + s2)

s3 = "linea\nnueva"
print(s3)

s4 = "\tcon tab"
print(s4)

s5 = "\\n texto \\t"
print(s5)

n, a = "Ana", 20
print(f"{n} tiene {a}")

txt = "code"
x, y, z, w = txt
print(x, z)

print(txt[1:3])
print(txt[1:])
print(txt[-1])
print(txt[::2])
print(txt[::-1])

print(txt.upper(), txt.count("o"), "1".isnumeric(), txt.startswith("c"))

# lits #
a = [1, 2, 3, 4, 5, 5]
b = [10, 1.5, "Ana"]

print(len(a), type(b))
print(b[0], b[-1], a.count(5), b.index("Ana"))

x, y, z = b[0], b[1], b[2]
print(z)

print(a + b)

b.append("XD")
b.insert(1, "Rojo")
b[1] = "Azul"
b.remove("Azul")
a.remove(5)

print(b, a)

a.pop()
print(a)
q = a.pop(1)
print(q, a)

del a[0]
print(a)

c = a.copy()
a.clear()
print(a, c)

c.reverse()
print(c)
c.sort()
print(c)

print(c[0:2])

a = "hola"
print(a, type(a))
