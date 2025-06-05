
## 📚 Libft

Libft es un proyecto fundamental del currículo de 42 Madrid. Su objetivo es crear una librería en C desde cero, reimplementando funciones estándar de la biblioteca <ctype.h>, <string.h>, <stdlib.h>, y añadiendo utilidades adicionales que facilitarán futuros proyectos.

Todo el código cumple con las reglas de Norminette, garantizando una sintaxis limpia, coherente y legible.

### 🔠 Clasificación y Conversión de Caracteres

| Función        | Descripción                                             |
|----------------|---------------------------------------------------------|
| `ft_isalpha`   | Verifica si un carácter es alfabético (A-Z, a-z)       |
| `ft_isdigit`   | Verifica si un carácter es un dígito numérico (0-9)    |
| `ft_isalnum`   | Verifica si un carácter es alfanumérico                |
| `ft_isascii`   | Verifica si un carácter pertenece al set ASCII (0-127) |
| `ft_isprint`   | Verifica si un carácter es imprimible                  |
| `ft_toupper`   | Convierte un carácter a mayúscula                      |
| `ft_tolower`   | Convierte un carácter a minúscula                      |

### 🔍 Búsqueda y Comparación de Cadenas

| Función         | Descripción                                                           |
|-----------------|-----------------------------------------------------------------------|
| `ft_strchr`     | Busca la primera ocurrencia de un carácter                            |
| `ft_strrchr`    | Busca la última ocurrencia de un carácter                             |
| `ft_strncmp`    | Compara dos cadenas hasta n caracteres                                |
| `ft_strnstr`    | Busca una subcadena dentro de otra hasta n caracteres                 |

### 🧵 Manipulación de Cadenas
| Función         | Descripción                                                             |
|-----------------|-------------------------------------------------------------------------|
| `ft_substr`     | Extrae una subcadena desde una posición                                 |
| `ft_strjoin`    | Une dos cadenas en una nueva                                            |
| `ft_strtrim`    | Elimina caracteres específicos al inicio y final                        |
| `ft_split`      | Divide una cadena según un delimitador                                  |
| `ft_itoa`       | Convierte un número entero en cadena                                    |
| `ft_strmapi`    | Aplica una función a cada carácter de una cadena (con retorno)          |
| `ft_striteri`   | Aplica una función a cada carácter de una cadena (sin retorno)          |


### 💾 Manejo de Memoria
| Función         | Descripción                                                   |
|-----------------|---------------------------------------------------------------|
| `ft_memset`     | Rellena un bloque de memoria con un valor                     |
| `ft_bzero`      | Pone en cero un bloque de memoria                             |
| `ft_memcpy`     | Copia memoria sin solapamiento                                |
| `ft_memmove`    | Copia memoria permitiendo solapamiento                        |
| `ft_memchr`     | Busca un byte en memoria                                      |
| `ft_memcmp`     | Compara dos bloques de memoria                                |


### 🛠️ Utilidades de Memoria y Conversión

| Función         | Descripción                                                |
|-----------------|------------------------------------------------------------|
| `ft_calloc`     | Reserva memoria y la inicializa en cero                    |
| `ft_strdup`     | Duplica una cadena en nueva memoria                        |
| `ft_atoi`       | Convierte una cadena en número entero                      |

### 📤 Salida por Descriptor

| Función         | Descripción                                                  |
|-----------------|--------------------------------------------------------------|
| `ft_putchar_fd` | Escribe un carácter en un file descriptor                    |
| `ft_putstr_fd`  | Escribe una cadena                                           |
| `ft_putendl_fd` | Escribe una cadena seguida de salto de línea                 |
| `ft_putnbr_fd`  | Escribe un número entero como string                         |

### ⚙️ Compilación

🔧 Compilar la librería

```bash
  make
```
Genera el archivo libft.a, una librería estática lista para usarse.

🧹 Limpiar archivos temporales

```bash
  make clean
```
Elimina archivos .o intermedios.

🗑️ Limpiar todo
```bash
  make fclean
```

🔄 Recomipilar desde cero
```bash
  make re
```
Hace un fclean y recompila todo.

🧪 Uso en tu Proyecto
Puedes utilizar libft fácilmente en tu código C:

```bash
 gcc -o your_program your_program.c libft/libft.a
```
Recuerda incluir el encabezado:

```bash
#include "libft.h"
```
