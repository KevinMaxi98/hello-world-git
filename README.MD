# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1.
-----------

Underline 2.
=========

# Formato de enfásis
- formato *italica* de primer forma.
- formato _italica_ de segunda forma.
-formato **bold o strong** de primer forma.
- formato __bold o strong__ de segunda forma.
-formato ~~tachado~~.

# Listas
1. Esto es un ítem
2. Esto es un ítem
3. Esto es un ítem 
- Esto es un ítem de lista ordenada

# Links
- <a href="http://www.google.com">Esto es un link html</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imágenes
![Logo Github](https://github.githubassets.com/images/modules/open_graph/github-mark.png)

# Code snippets
Código en Json
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
Código en Javascript
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
| Nombre | Apellido | Documento|
| ------ | ------ | ------ |
| Maxi | Burgos | 3456887
| Tomás | Tompson | 5856549

# Citas
Esto es un texto referente a una cita: 
> Esto es una cita.

Esto es otro texto que se relaciona con la cita anterior: 
> Esto es otra cita

