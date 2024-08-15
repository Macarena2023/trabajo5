# GUIA BASICA DE PHYTON-CHEAT SHEET
**Conceptos basicos**

###### Los espacios son fundamentales en el lenguaje de phyton, si no tienes en cuenta esto, tu codigo no funcionará correctamente.


## condicional "if"

 if test:

 **realizar acción si test es True**
 elif test2:

 **realizar acción si test2 es True**
 else:

 **realizar acción si las anteriores
 son falsas (test y test2)**    

 ## Bucle “for”
 
for item in secuencia:

  **realizar acción para cada miembro**
  
  **(item) de secuencia. Por ejemplo:
  cada elemento de una lista, o
  cada caracter de una cadena.**
for i in range(10):

 **realizar acción 10 veces (0 a 9)**
 for i in range(5, 10):

 **realizar acción 5 veces (5 a 9)**

## Bucle “while”
while test:

**realizar acción mientras test
sea True**

# CADENAS

###### Una cadena es una secuencia de caracteres, generalmente utilizada para almacenar texto.

 **Creación**                     
cadena = “Hola mundo.”
cadena = ‘Hola mundo.’

 **Acceso**
cadena[4]

 **División**
cadena.split(‘ ’)
cadena.split(‘n’)

 **retorna** ‘a’

 **retorna** [‘Hola’, ‘mundo.’]
 
 **retorna** [‘Hola mu’, ‘do.’]

 ###### Para unir una lista de cadenas, utiliza la función join() como método de la cadena que utilizarás para separar cada uno de los elementos de la lista (o bien ‘’).

**palabras =** [‘Esto’, ‘es’, ‘una’, ‘lista’, ‘de’,‘cadenas’] 

 ‘ ’.join(palabras
 
 ‘ZOOL’.join(palabras)
  
  ‘’.join(palabras)

**retorna** “Esto es una lista de cadenas”

**retorna**  “EstoZOOLesZOOLunaZOOLlistaZOOLdeZOOLcadenas”

**retorna** “Estoesunalistadecadenas”

###### Formateo de cadenas: similar a la función de C printf(), utiliza en su lugar el operador % para añadir los elementos de una tupla a una cadena.

**cadena**  = “Python”

print(“Hola %s.” % cadena) “Hola Python.”

# TUPLAS

###### Una tupla consiste en un conjunto de valores separados por comas. Son útiles para pares ordenados y retornar varios valores desde una función.

**Creación**

**tupla =** ()

**otra_tupla =** (“spam”,) # Nótese la coma
**esta_tupla =** 12, 89, ‘a’, True
**esta_tupla =** (12, 89, ‘a’, True)

**Acceso**

 esta_tupla[0] retorna 12

# DICCIONARIOS

###### Un diccionario es un conjunto de pares clave:valor (o nombre:valor). Todos los nombres deben ser únicos.

**Creación**

**diccionario =**{}

**diccionario =** {‘a’:1, ‘b’:23, ‘c’:”huevos”}

**Acceso**
diccionario[‘a’]

**Borrado**

del diccionario[‘b’]

**Búsqueda**

diccionario.has_key(“e”)

diccionario.keys()

diccionario.items()

‘c’ in diccionario

‘otra_clave’ in diccionario

**retorna 1**

retorna False

retorna [‘a’, ‘c’]

retorna [(‘a’, 1), (‘c’, ‘huevos’)]

retorna True

retorna False

