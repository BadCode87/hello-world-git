# Version del curso
Version actual: 1.2.2
# Cabeceras

# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines

Underline 1 (Simil cabecera H2)
-------------

Underline 2 (Simil cabecera H1)
=============

# Enfasis

- Formato *italica* de la primera forma. 
- Formato _italica_ de la segunda forma. 
- Formato **bold o strong** de la primera forma. 
- Formato __ bold o strong__ de la segunda forma. 
- Formato ~~tachado~~, formato normal . 

- Aqui podemos usar el _**formato italico bold**_ , pero tambien **~~bold tachado~~**

# Listas

 ## Listas Ordenadas. 
 1. Esto es un item.
 2. Esto es un item.
 3. Esto es un item.

## Listas Desordenadas.
- Esto es un item de lista desordenadas.
- Esto es un item de lista desordenadas.
- Esto es un item de lista desordenadas.

# Links
- <a href = "https://www.google.com"> Esto es un link en HTML </a>
- [Esto es un link en Markdown](https://www.google.com)

# Imagenes
![Logo Github](https://github.githubassets.com/assets/GitHub-Mark-ea2971cee799.png)

# Code Snippets
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

Código en Java
```JAVA
/**
 * @author John Smith <john.smith@example.com>
*/
package l2f.gameserver.model;

public abstract strictfp class L2Char extends L2Object {
  public static final Short ERROR = 0x0001;

  public void moveTo(int x, int y, int z) {
    _ai = null;
    log("Should not be called");
    if (1 > 5) { // wtf!?
      return;
    }
  }
}
```

# Tablas

| Nombre | Apellido | Documento | 
| ------ | -------  | --------- |
| Angelo | Massa    | 896362    | 
| Matteo | Massa    | 4803004   |  


# Citas (Blockquotes)

Esto lo dijo Seneca
> Admira a quien lo intenta, aunque fracase.

Este es otro texto que no esta relacionado con la cita anterior:
> Esto es otra cita.

# Lineas Divisoras. 

Esto es un texto que será dividido usando guiones medios.

---
Esto es otro texto dividido dividido por asteriscos. 

***
Esto es otro texto dividido dividido por guiones bajos. 

___

# Saltos de línea (Linebreaks)
Esto es nuestro primer parrafo.

Esto es el segundo parrafo.

Esto es el tercer parrafo. 
- Lista

