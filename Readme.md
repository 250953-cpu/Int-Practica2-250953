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

EJEMPLO:

Texto sección
Después del separador.

### 3. Párrafos (PARAGRPAHS)
Son utilizados para por presentar grandes secciones de texto que describen detalladamente las secciones de la documentación del proyecto.

EJEMPLO:

Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1.

Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2 
Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2 
Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2Este texto pertenece al párrafo 2 
Este texto pertenece al párrafo 2

Lo que en una página utilizariamos usando la etiqueta <P>.

También podemos aplicar estilos básicos de alineación:

Este párrafo está alineado a la izquierda por defecto Este párrafo está alineado a la izquierda por defecto Este párrafo está alineado a la izquierda por defecto Este párrafo está alineado a la izquierda por defecto Este párrafo está alineado a la izquierda por defecto Este párrafo está alineado a la izquierda por defecto

Este párrafo está alineado a la derecha utilizando la propiedad de alineación Este párrafo está alineado a la derecha utilizando la propiedad de alineación Este párrafo está alineado a la derecha utilizando la propiedad de alineación Este párrafo está alineado a la derecha utilizando la propiedad de alineación Este párrafo está alineado a la derecha utilizando la propiedad de alineación

Este párrafo esta centrado usando la propiedad de alineación Este párrafo esta centrado usando la propiedad de alineación Este párrafo esta centrado usando la propiedad de alineación Este párrafo esta centrado usando la propiedad de alineación Este párrafo esta centrado usando la propiedad de alineación Este párrafo esta centrado usando la propiedad de alineación Este párrafo esta centrado usando la propiedad de alineación Este párrafo esta centrado usando la propiedad de alineación Este párrafo esta centrado usando la propiedad de alineación Este párrafo esta centrado usando la propiedad de alineación

Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación Este párrafo estará justificado utilizando la propiedad de alineación

### 4. Texto Enfatizado 

- Texto en Negritas: Para resaltar texto importante que no sea un título
por que esto inicialmente están en negrita, deberemos encerrar el texto
deseando entre dobles asteríscos (**).

Ejemplo: Este texto esta en **Negrita**.

- Texto en cursiva(Itálico): Para hacer referencia a texto utilizando el
formato inclinado o itálico bastará con encerrar el texto deseado entre
dos asteríscos simples(*).

Ejemplo: Este *texto* estará *inclinado*.

- Texto en Cursiva y Negrita: Para lograr esta estilización en la
documentación basta con ajuntar ambas configuraciones, es decir
encerramos el texto en unu triple asterísco (***).

Ejemplo: ***Este texto esta en Negrita e Itálico.***

- Texto Tachado: En algunas ocasiones es necesario dar formato al texto
con un efecto de como es incorrecto, generalmente esta idea se transmite
por que el texto esta tachado, es decir con una línea que lo marca por la
mitad. Para lograr este efecto tendremos que encerrar el texto entre una
doble tílde de (~).

Ejemplo: Se dice haya no ~haiga~.
 
- Texto Subrayado: En este tipo de formato el texto queda sobre una línea imferior para detonar su relevancia,
este formato no tiene una versión rápida en el estandár MARKDOWN, pero dado su similaridad a HTML podemos
utilizar las etiquetas ``` <u> ``` y ``` </u> ```

Ejemplo: El <u>texto</u> debe estar <u>subrayado</u>.

- Texto Superíndice: En algunas ocasiones se requere dar formatos a fórmulas estadísticas que requiere
potencias entre otras aplicaciones, podemos utilizar el tag de HTML ``` <sup> ``` y ``` </sup> ```.

Ejemplo: Para elevar x al cuadrado tendríamos lo siguiente x<sup>2</sup>

- Texto en Subíndice: En el caso de Química se utilizan subíndices para representar fórmulas, para ellos podemos
utilizar el formato con la etiqueta HTML ``` <sub> ``` y ``` </sub> ```.

Ejemlo: La fórmula del agua es H<sub>2</sup>O.

### 5. Listas

Cuando realizamos documentación utilizando el estandár de MARKDOWN, es común que tengamos que listar elementos,
requisitos de hardware, requisitos de software, respetando
**Desordenadas (Viñetas)** y **Mixtas (Viñetas y Números)**.

1. Listas ordenadas
Estas deberán estar enumeradas con un número segi¿uido por un punto y espacio en blanco
para comenzar con el listado.
1. PC
2. Wifi
3. Módem
4. Smartphone
6. Smart TV
5. Tablet

Ejemplo:
Para reiniciar el conteo se debe poner una línea de texto sin numeria.

2. Listas Desordenadas 
Estas listas no llevan un número, sino una viñeta (símbolo), y suele listar elementos que no
requieren un orden específico.

- Pan
- Leche
- Huevo
- Azúcar

3. Listas Mixtas
Son aquellas que se mezclan con ambos elementos
- 3° A DSM
    1. Juan
    2. Pedro
    3. Alejandra
- 3° B DSM
    1. Romina
    2. Daniel
- 3° A DSM
    1. Yahir
    2. Lizbeth
    3. Jeovanny
    4. Erick

    ### 6. Bloques de Código (CODE BLOCKS) o Citas (BLOCK QUOTES)
    
    Estos estilos de texto se utilizan para llamar la atención del lector, en pasos que son
    importantes realizar alguna reseña o segmentar líneas de código que se deberám ingresar en 
    una terminal de comandos o líneas de ejjecución.

    - Cuadro de Citas (BLOCK QUOTES)
    Son cajas estilizadas en colores grises por defecto con un margen más claro.

    Ejemplo:

    Para listar las carpetas y archivos desde una terminal de comandos en el sistema operativo de Windows debemos usar 
    el siguiente comando:
    <C:/dir

    Después oprimimos la tecla *Enter*.
    
    También podemos usar texto multilínea.

    **EJEMPLO**
    Pasos para instalar MySQL
    > - Descargar el archivo instalador desde la página oficial www.mysql.com
    > -Instalar el Servidor de Base de Datos
    > -Definir el puerto y contraseña para el usuario ***root***
    > -Inicializar el Servidor de Base de Datos usando el comando *mysql*
    > -Conectarnos a la base de datos para verificar que se instaló correctamente.

    - Bloques de código 

    Es común en la documentación del proyecto de software demos  al usuario un par de 
    instrucciones de como instalar, configurar, desplegar y testear (pruebas), nuestro producto
    desarrollado. Por tal motivo estándar Markdown nos permite enfatizar estas instrucciones,
    simulando estar en una terminal del Sistema Operativo(SO)para delimitar este código basta
    encerrarlo con triples carácteres de bacltic (acento a tilde ``` ' ```)

    Para clonar el proyecto ingresa la siguiente instrucción 
    
    C:\Users\PC-20\Desktop>git clone https://github.com/250953-cpu/Int-Practica2-250953.git

    A diferencia de los bloques de citas,la tipografia y significado cambian.

    ### 7. Tablas 
    En caso de que necesitemos estructurar datos  o información relevante
    para la documentación podemos utilizar el formato de tablas, para lo que tenemos que considerar la estructura de la base de una tabla;

    - Usa | para delimitar las columnas
    - Usa --- para separar las filas del encabezado 

    Ejemplo:

    |Título 1 |Título 2 |Título 3 |
    |--- |--- |--- |--- |
    |Fila 1, Celda 1 |Fila 2, Celda 2 |Fila 3, Celda 3 |Fila 4, Celda 4 |
    |Fila 1, Celda 1 |Fila 2, Celda 2 |Fila 3, Celda 3 |Fila 4, Celda 4 |
    |Fila 1, Celda 1 |Fila 2, Celda 2 |Fila 3, Celda 3 |Fila 4, Celda 4 |


    ### 8. Hipervínculos (Links)

    Para poder hacer referencia a documentos internos o externos dentro del repositorio, debemos respetar la siguiente estructura:

    ...
    [Texto que el usuario leera] (URL a donde te dirigirá) "Texto que aparecerá cuando pongas el cursor sobre la liga"
    ...
    
    Ejemplo:

    - Ligas externas:
    [Google](http://google.com)

    ### 9. Imágenes

    El estándar de markdown nos permite incrustar imágenes dentro de la documentación lo que nos permitira poner logotipos, capturas de pantalla o cualquier archivo gráfico importante .

    La estructura varia un poco de las residencias de hipervínculos, siento:

    ```
    ![Texto que el usuario leerá](URL donde se encuentra la imagen)
    ```

    Ejemplo:

    ![Si tu te vas - Charles Ans](./imagenes/image.png)

    Es importante entender que la resolución de la imagen será original del archivo

    ***Tip PRO***

    Si el tamaño de la imagen no se ajusta a lo que deseas para tu documento, lo más recomendable es ajustar el tamaño del archivo original con algún software de procesador de imagenes como: PaInt, Illustraitor, Int o Photoshop, pero si quieres modificarlos desde el código, el estándar no tiene parámetros definidos por lo que necesitaremos hechar líneas de código HTML.

    Cambiando la estructura con la etiqueta ```<img>```

    Ejemplo:

    <img src=".imagenes/image.png" width="350" height="350">

 