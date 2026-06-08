# Int-Practica2-250953 
En esta práctica aprenderas a utilizar las herramientas de Git y GitHub para el control 
de versiones de proyectos de desarrollo de software, aplicando principios de buenas prácticas 
de Documenrtación, Desarrollo Colaborativo y Respaldo en la Nube del Proyecto Integrador.

Elaborado por:**Juan Fernando Hernandez Lopez** \
Materia: **Proyecto Integrador** \
Semestre: **3** \
Grupo: **C** \
 Docente:**M.T.I Marco Ramírez Hernández** \
 Periodo: *Mayo-Agosto 2026* \

## Comandos Básicos para Maquetado de la Documentación utilizando el estandar de Markdown(.md)
---

Markdown es el estándar utilizado por Git y GitHub, para estilizar (Maquetar)
la documentación de proyectos, lo que permite a usuarios y colaboradores del
proyecto entender el contexto y operación del mismo.

### 1. Encabezados o Títulos (HEADERS)

Para poder realizar una buena documentación del proyecto debemos distribuir
correctamente los contenidos, para poder delimitar o hacer énfasis
(enfatizar), es decir resaltar las secciones más importantes, podemos utilizar lo siguiente:

**EJEMPLOS**

# Encabezado de Nivel 1
## Encabezado de Nivel 2
### Encabezado de Nivel 3
#### Encabezado de Nivel 4
##### Encabezado de Nivel 5
###### Encabezado de Nivel 6
####### Encabezado de Nivel 7 - *El estándar solo permite 6 niveles para títulos,  a partir
del séptimo serán presentado como texto plano(sin estilo)*

### 2. Separadores (SEPARATORS)
Si desea marcar una separación más visual de contenidos pordemos utilizarlos indicando tres caracteres de "-" continuos, en el maquetado.

**EJEMPLO:**

#### Título de la sección
---
Texto después del separador


### 3. Párrafos (PARAGRPAHS)
Son utilizados para por presentar grandes secciones de texto que describen detalladamente las secciones de la documentación, detallan procesos, explican código o cotexto teórico. 

EJEMPLO:

Párrafo 1:  Este texto es del párrafo 1 este texto es del párrafo 1  este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1 este texto es del párrafo 1.

Párrafo 2: Este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2 este texto es del párrafo 2, el estándar de markdown distingue los párrafos con un doble salto de línea de texto, si no se desea alinear, es decir estará alineado a la izquierda por defecto.

En caso de que necesitemos alinear el párrafo a **izquierda**, **derecha**, **centrado** o **justificado**, deberemos utilizar una etiqueta ```<p>``` con la proipiedad align y la dirección deseada. 

<p align="left">Párrafo alineado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierdapárrafo alienado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierda párrafo alienado a la izquierda.</p>

<p align="center"> Párrafo alienado al centro párrafo alieando al centro párrafo alieando al centro párrafo alieando al centro párrafo alieando al centro párrafo alieando al centropárrafo alieando al centropárrafo alieando al centropárrafo alieando al centro párrafo alieando al centro párrafo alieando al centropárrafo alieando al centropárrafo alieando al centro párrafo alieando al centro párrafo alieando al centro párrafo alieando al centropárrafo alieando al centropárrafo alieando al centro párrafo alieando al centropárrafo alieando al centro. </p>

<p align="right"> Párrafo alienado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha párrafo alineado a la derecha.

<p align="justify"> Párrafo justificado párrafo con texto justificado párrafo con texto justificado párrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificado párrafo con texto justificado párrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificado párrafo con texto justificado párrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificado párrafo con texto justificado párrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificadopárrafo con texto justificado párrafo con texto justificado.

### 4. Texto Enfatizado 

- Texto en Negritas: Para resaltar texto importante que no sea un título por questo incialmente están en negrita, deberemo encerrar el texto desdeado entre dobles asteríscos (**).

Ejemplo:   Este texto esta en **negrita**.

- Texto en Cursiva (Itálico): Para hacer referencia a texto utilzando el fomato inclinado o itálico bastará con encerrar el texto deseado entre dos asteríscos simples (*).

Ejemplo:  Este *texto* estará *inclinado*.

- Texto en Cursiva y Negita:  Para lograr esta estilización en la documentación basta con juntar ambas configuraciones , es decir encerramos el texto en un triple asterísco (***)

Ejemplo:   ***Este texto esta Negrito e Itálico.***

- Texto Tachado: En algunas ocaciones es necesario dar formato al texto con un efecto de como es incorrecto, generalmente esta idea se transmite por que el texto esta tachado, es decir con una línea que lo marca por la mitad. Para lograr este efecto tendremos que encerrar el texto entre una doble tílde de (~).

Ejemplo: Se dice haya no ~~haiga~~. 

- Texto Subrayado: En este tipo de formato el texto queda sobre una línea inferior para denotar su relevancia, este formato no tiene un versión rápida en el estándar MARKDOWN, pero dado su similiaridad a HTML podemos utilizar las etiquetas ``` <u> ``` y ``` </u> ```.

Ejemplo: El <u>texto</u> debe estar <u>subrayado</u>.

- Texto en Superíndice:  En algunas ocaciones se requiere dar formato a fórmulas estadísticas que requiere potencias entre otras aplicaciones, podemos utilizar el tag de HTML ``` <sup> ``` y ``` </sup>``` para delimitar el formato.

Ejemplo: Para elevar x al cuadrado tendriamos lo siguiente  x<sup>2</sup>

- Texto en Subíndice:  En el caso de Química se utilizan subíndices para representar formulas, para ello podemos utilizar el formato de texto con la etiqueta HTML ``` <sub> ``` y ``` </sub>```.

Ejemplo: La formula del Agua es  H<sub>2</sub>O.

### 5. Listas

Cuando relizamos documentación utilizando el estándar de MARKDOWN, es común que tengamos que listar elementos, requisitos de hardware, requisitos de software o enumerar pasos de cómo el software debe ser instalado paso a paso, por eso debemos saber como crear listas de las cuales hay de 3 tipos :  **Ordenadas (Números)** , **Desordenadas (Viñetas)** y **Mixtas (Viñetas y Números)**.

1. Listas Ordenadas

Estas deberán estar enumeradas con un número seguido por un punto y un espacio en blaco para comenzar con el listado. 

1. PC 
2. Wifi
3. Modém
4. Smartphone
6. Smart TV
5. Tablet 

Para reiniciar el conteno se debe poner una línea de texto sin numeralia. 

2. Listas Desordenadas

Estas listas no llevan un número , sino una viñeta (simbolo), y suele listar elementos que no requieren un orden específico.

- Pan
- Leche
- Huevo
- Azucar

3. Listas Mixtas

Son aquellas que mezcla ambos elementos

- 3° A DSM
    1. Juan
    2. Pedro
    3. Alejandra
- 3° B DSM
    1. Romina
    2. Daniel
- 3° C DSM
    1. Yahir
    2. Liseth
    3. Jeovany
    4. Erick


    ### 6. Bloques de Código (CODE BLOCKS) o Citas (BLOCK QUOTES)
    
    Estos estilos de texto se utilizan para llamar la atención del lector, en pasos que son importantes , realizar alguna reseña o  segmentar líneas de código que se deberán ingresar en una terminal de comandos o líneas de ejecución. 


- Cuadro de Citas (Block Quotes)
Son cajas estilizadas en colores grises por defecto con un margén más claro. 

Ejemplo:

Para listar las carpetas y archivos desde una terminal de comandos en el sistema operativo de Windows debemos usar el comando: 

> C:/dir

Después oprimimos la tecla *Enter*.

Tambien podemo usar texto multilínea

Ejemplo:

Pasos para instalar MySQL
> - Descargar el archivo instalador desde la página oficial  www.mysql.com
> - Instalar el Servidor de Bases de Datos
> - Definir el puerto y contraseña para el usuario **root**
> - Inicializar el serviro de bases de datos
> - Conectarnos a la base datos para verificar que se instaló correctamente.


- Bloques de código

Es común que en la documentación del proyecto de software demos al usuario un par de instrucciones de como instalar , configurar , desplegar y testear (pruebas), nuestro producto desarrollado. Por tal motivo el estándar markdown nos permite enfatizar estas instrucciones, simulando estar en una terminal de sistema operativo, para delimitar este código basta encerrarlo un triples carácteres de bacltic (acento o tilde inversa ``` ` ```)

Ejemplo: 

Para clonar el proyecto ingresa la siguiente instrucción
```
C:\Users\PC-DOCENTE\Desktop>git clone https://github.com/250953-cpu/Int-Practica2-250953.git
```

A diferencia de los bloques de citas, la tipografía y significado asociado cambian.


### 7. Tablas

En caso de que necesitemos estructurar datos o información relevante para la documentación podremos utilizar el formato de tablas , para lo que tenemos considerar la estructura base de una tabla:

- Usa | para delimitas las columnas
- Usa --- para separar las filas del ecabezado

Ejemplo :

|Título 1 | Título 2 | Título 3 | Título 4 |
|---|---|---|---|
|Fila 1, Celda 1|Fila 1, Celda 2|Fila 1, Celda 3|Fila 1, Celda 4|
|Fila 2, Celda 1|Fila 2, Celda 2|Fila 2, Celda 3|Fila 2, Celda 4|
|Fila 3, Celda 1|Fila 3, Celda 2|Fila 3, Celda 3|Fila 3, Celda 4|

   

### 8. Hipervínculos (Links)

Para poder hacer referencias a documentos internos o externos dentro del repositorio, debemos respestar la siguiente estrucutura

```
[Texto que el usuario leera](url a donde te dirigirá) "texto que aparecerá cuando pongas el cursor sobre la liga"
```

Ejemplo

- Ligas externas
[Google](http://google.com)

- Ligas internas
[Acera del Autor](./aboutme.md "Cónoceme más!")


### 9. Imágenes 

El estándar de markdown nos permite incrustrar imágenes dentro de nuestra documentación lo que nos permitirá poner logotipos, capturas de pantalla o cualquier archivo gráfico importante.


La estructura varia un poco de las referencias de hipervínculos, siendo: 
```
![Texto que el usuario leera](url a donde se encuentra la imágen) 
```

Ejemplo:
![!\[image\]imagenes/image.png](imagenes/image.png)

Es importante comprender que la resolución de la imagén será la original del archivo.


**Tip PRO:**
Si el tamaño de la imagén no se ajusta a lo que deseas para tu documento, lo más recomendable es ajustar el tamaño del archivo original con algún software procesador de imágenes cómo : Paint, Illustrator , Ink o Photoshop. pero si quiere modificarlo desde el código, el estandár no tiene parametros definidos por lo que necesitaremos echar líneas de código HTML 

Cambiando la estructura de maquetado por la etiqueta ``` <image> ```


Ejemplo:

<img src="imagenes/image.png" width="100" heigth="50">


### 10. Notas al pie

Si nuestra documentación requiere ubicar notas de importancia o relevancia posterior podemos usar notas al pie de manera dinámica

Nota al pie 1 [^first].

Nota al pie 2 [^second].

Referencias al pie dentro de un párrafo ^[Nota interna] extenso dentro de nuestra documentación

Segunda referencia a la nota 2[^second].

[^first]: Nota al pie **pueder ser formateada**

    y tener multiples líneas de párrafo

[^second]: Texto de la segunda nota al pie.

### 11. Abreviaciones

Las abreviaciones nos permiten definir el significado de siglas o términos técnicos dentro del documento. Al pasar el cursor sobre la palabra, se mostrará su definición.

Este es un ejemplo de abreviatura HTML.

Esto también lo convierte a "HTML", pero conserva las entradas parciales intactas, como "xxxHTMLyyy", etc.

*[HTML]: Lenguaje de Marcado de Hipertexto

### Contenedores personalizados

Los contenedores personalizados nos permiten destacae bloques de información importante dentro de la documentación, como advertencias, notas o tips.

La sintaxis estándar con markdown-it es la siguiente:
Los contenedores personalizados nos permiten destacae bloques de información importante dentro de la documentación, como advertencias, notas o tips.

La sintaxis estándar con markdown-it es la siguiente:
::: advertencia
*¡Aquí hay dragones!*
:::