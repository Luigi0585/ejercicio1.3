# despliegue-aplicaciones-web

Taller de Git y GitHub

Modificamos el archivo README.


Hola

## Encabezado h2

### Encabezado h3

T E X T O

**Texto en negrita**

*Texto en cursiva*

_Texto en cursiva_

# Instalación del servidor web apache

Para instalar el servidor ejecutamos el comando 
`apt update && apt install apache2`

```bash
apt update
apt install
```

```python
celsius = float(input('Introduce una temperatura en grados Celsius: '))
farenheit = (1.8 * celsius) + 32
print(f'La temperatura en grados Farenheit es: {farenheit}')
```

```yaml
version: '3'

services: 
  apache:
    build: ./apache
    ports: 
      - 80:80
    volumes:
      - ./src:/var/www/html
```

```SQL
SELECT * FROM usuarios
```

# HTML renderizado en GitHub

sudo systemctl start apache2

#!/bin/bash
echo "Hola mundo"

celsius = float(input('Introduce una temperatura en grados Celsius: '))
farenheit = (1.8 * celsius) + 32
print(f'La temperatura en grados Farenheit es: {farenheit}')

version: '3'

services: 
  apache:
    build: ./apache
    ports: 
      - 80:80
    volumes:
      - ./src:/var/www/html

# Referencias
[Web de AWS] (https://aws.com)

Enlace [Amazon][aws].

[1]: https://iescelia.org
[2]: https:github.com
[aws]: https://amazon.com

# Imágenes externas

![Texto](https://iescelia.org/web/wp-content/uploads/2012/05/iescelia_1950.jpg)

# Imágenes internas

![](main/images/01.jpg)

# Listas

- Item 1
   - Item 1.1
   - Item 1.2
- Item 2

* Item 1
  * Item 1.1
  * Item 1.2
* Item 2
  * Item 2.1
* Item 3
* Item 4


1. Item 1  
  1.1 Item 1.1  
  1.2 Item 1.2  
2. Item 2  
  2.1 Item 2.1  
3. Item 3  
4. Item 4  

# Tablas

| Encabezado 1 | Encabezado 2 | Encabezado 3
| --- | --- | --- | ---
| Fila 1.1 | Fila 1.2 | Fila 1.3
| Fila 2.1 | Fila 2.2 | Fila 2.3
| Fila 3.1 | Fila 3.2 | Fila 3.3

# Saltos de línea
Por ejemplo, en esta frase  
hemos forzado un salto de línea.

# Citas de texto

Este texto no es una cita.
> Este texto daría como resultado una cita.

# Comentarios

Párrafo 1.

<!- Este texto es un comentario y no será renderizado -->

Párrafo 2.

# Emojis



# ???

---

[Documento de tipo Markdown] ([Markdown.pl](https://github.com/Luigi0585/ejercicio1.3/blob/main/Markdown.pl))
