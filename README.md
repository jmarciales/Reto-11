# Reto-11
------------
1. Métodos de strings en python: 
- **endswith** <br>
 Verifica si una cadena termina con un sufijo específico.
   ```python
   nombre = "Light Yagami"
   es_yagami = nombre.endswith("Yagami")  # Devuelve True
   ```
- **startswith** <br>
  Verifica si una cadena comienza con un prefijo específico.
  ```python
  detective = "L Lawliet"
  empieza_con_l = detective.startswith("L")  # Devuelve True
   ``` 
- **isalpha** <br>
Verifica si todos los caracteres son alfabéticos (letras).
  ```python
  nombre_kira = "Kira"
  solo_letras = nombre_kira.isalpha()  # Devuelve True
   ``` 
- **isalnum** <br>
 Verifica si todos los caracteres son alfanuméricos (letras o números).
  ```python
  codigo = "Death123"
  alfanumerico = codigo.isalnum()  # Devuelve True
   ```
- **isdigit** <br>
 Verifica si todos los caracteres son dígitos.
  ```python
  victimas = "40"
  solo_numeros = victimas.isdigit()  # Devuelve True
  #True
   ```  
- **isspace** <br>
 Verifica si todos los caracteres son espacios en blanco.
  ```python
  espacio = "   "
  solo_espacios = espacio.isspace()  # Devuelve True
   ```  
- **istitle** <br>
Verifica si la cadena sigue el formato de título (primera letra de cada palabra en mayúscula).
  ```python
  titulo = "Death Note"
  formato_titulo = titulo.istitle()  # Devuelve True
   ```  
- **islower** <br>
Verifica si todos los caracteres están en minúsculas.
  ```python
  mensaje = "kira es justicia"
  todo_minusculas = mensaje.islower()  # Devuelve True
   ```  
- **isupper** <br>
Verifica si todos los caracteres están en mayúsculas:
  ```python
  grito = "SHINIGAMI"
  todo_mayusculas = grito.isupper()  # Devuelve True
   ```  
