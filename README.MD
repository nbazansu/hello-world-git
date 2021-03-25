# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
------------

Underline 2
===========

# Formatos de enfasis
- formato *italica* de la primera forma.
- formato _itaalica_ de la segunda forma.
- formato **bold** o __strong__.
- formato ~~tachado~~.
- ~~***TODOS***~~

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links
- <a href="https://google.com">Esto es un link HTML<a>
- [Esto es un link de Markdown](https://google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png)

# Code Snippets
[Link a Highlights JS](https://highlightjs.org/static/demo/)
###### JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```

###### JavaScript
```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas

|   Nombre  |   Apellido    |   Documento   |
|   ------  |   --------    |   ---------   |
|   Maxi    |   Burgos      |   3546481     |
|   Tomas   |   Tompson     |   3243242     |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otra  cita:
> Aquí otra cita.

# Lineas  divisoras
Esto es un texto que será dividido por guiones

---
Esto es otro texto dividido por asteriscos.

***
Esto es otro dividido por guiones bajos.

___

# Saltos de linea
Esto es el primer párrafo

Esto es el segundo párrafo
Este es el tercer párrafo sin salto de línea

Este es el cuarto párrafo con salto de línea.