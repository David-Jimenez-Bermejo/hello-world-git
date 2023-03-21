Soy un readme.

# Formatos de Cabecera
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Formatos de Underline

Underline 1
-----------

Underline 1
===========


# Formatos de Emphasis

- formato *italica (cursiva)* de la primera forma.
- formato _italica (cursiva)_ de la segunda forma.
- formato **bold o strong** de la primera forma
- formato __bold o strong__ de la segunda forma
- formato ~~tacahdo~~.
- aqui podemos usar formato *cursiva*, **negrita** y ~~tachado~~. También se pueden combinar ***combinado 1***, *~~combinado 2~~*, **~~combinado 3~~**


# Formatos de Listas

## Lista ordenada
1. Esto es un item de lista ordenada
2. Esto es un item de lista ordenada
3. Esto es un item de lista ordenada


## Lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada



# Links
- <a href="https://google.es">Link HTML </a>
- [Link en Markdown](https://google.es)
- [Link en Markdown al index](index.html)


# Imagenes
![Logo GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)


# Code Snippets
Se usa mediante highlightjs que es en este [enlace](https://highlightjs.org/static/demo/) para muestra. Se usa con la comilla hacia la derecha ` triple.

Código en JSON
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

Código en JavaScript
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
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi | Burgos | 123 |
| Yo | Yo | 254w



# Citas
Esto es un texto referente auna cita que pondremos debajo:
> Esto es una cita.
Si sigues escribiendo está dentro de la cita

Si dejas das una linea en blanco (doble enter) ya te sales de la cita.
Esto es otra cita
>Cita citosa

# Lineas divisorias
Esto es un texto que será dividido. Para dividirlo hay que dejar una linea en blanco (doble enter) y poner 3 guiones (-).

---
Esto es otro texto dividio por *.

***

Esto es otro texto dividio por _.

___




# Saltos de linea
Los saltos de linea se crean con doble enter (dejar una linea en blanco)

Esto es el primer parrafo.

Esto es el segundo parrafo.

Esto es el tercer parrafo.

# Lanzamos version nueva a producción


