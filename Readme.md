"# Int-Practica2-250953" 
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

Separadores (SEPARATORS)
Si desea marcar una separación más visual de contenidos pordemos utilizarlos indicando tres caracteres de "-" continuos, en el maquetado.

EJEMPLO:

Texto sección
Después del separador.

### 2. Párrafos (PARAGRPAHS)
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

### 4. Texto Enfatizado (BOLD, ITALIC, BOLD/ITALIC)
Si el texto que deseamos enfatizar se encuentra de un párrafo, podemos utilizar algunos trucos para ubicarlos en la documentación.

Texto en Negrita (BOLD)
Para poder poner el texto en negrita, este deberá ser encerrado entre dobles **

EJEMPLO:

Texto Texto Texto Texto Texto Texto Texto Importante Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto

Texto en Cursiva (ITALIC)
Algunas veces es necesario resaltar algunas secciones o textos en cursiva para que el lector detecte el texto importante, dentro del maquetado con el estándar Markdown lo podemos realizar ubicando el texto entre * (asteríscos).

EJEMPLO:

Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Cursivo Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto

Texto en Negrita y Cursiva (BOLD & ITALIC)
De igual manera podemos unir ammbos estilos Negrita y Cursiva para resaltar los textos que consideremos importantes dentro de la documentación de nuestros proyectos de software, utilizando un triple * (asterísco).

EJEMPLO:

Texto Texto Texto Texto Texto Texto en Negrita y Cursiva Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Cursivo Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto

Subrayado (UNDERLINE)
Algunas veces necesitaremos subraya texto dentro de la documentación, para ello, si bien markdown no tiene un atajo o codificación rápida podemos utilizar el estilo que usa el estándar de HTML usando el tag <ins> y cerrando con </ins>.

EJEMPLO:

Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Cursivo Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Subrayado Texto.

Integradora-Practica03
Continuamos con los comandos básicos de Git y Github para el maquetado de la documentación

### 5. Cuadros para Código o Reseñas (BLOCKQUOTES)
Estos elementos son utilizados para resaltar instrucciones específicas para la instalación, configuración y/o inicialzación o mostrar secciones de código fuente. Se maqueta iniciando el texto con un símbolo de mayor que (>)

EJEMPLO: Para listar las carpetas y archivos en desde una terminal de sistema operativo Windows debemos ingresar el comando:

C:/dir

Después oprimimos la tecla "Enter".

También podemos ingresar textos multilínea

EJEMPLO:

Aquí se ingresan un conjunto de instrucciones para explicar al usuario, cómmo instalar el software que hemos diseñado.

Y si deseamos inclur viñetas para enlistar pasos podemos utilizar el caracter - dentro del texto a documentar.

EJEMPLO: Pasos para Instalar la Base de Datos:

Descargar MySQL Server del Sitio Oficial
Instalar el Sistema Gestor de Bases de Datos, definiendo el puerto y contraseña para el usuario root
Descargamos el archivo de respaldo de la base de datos (.sql)
Restauramos la Base de Datos usando el comando *mysql *
C:/Program Files/MySQL/MySQL Server 8.0/bin/mysql -u root -p password < respaldo.sql

### 6. Listas Ordenadas y Listas Desordenadas
Si en nuestra documentación necesitamos incluir información en modo de lista, un elemento tras otro podemos hacerlo utilizando los número con un punto decimal si las deseamos ordenadas o un guión medio - si solo queremos una viñeta.

EJEMPLO: Para crear tu primer repositorio en GitHub deberás: 5. Contar con cuenta de GitHub.

Dar click en el boton: *Nuevo Repositorio
Asignarle un Nombre a tu repositorio, por ejemplo: practica03-3b
Asignarle un nivel de privacidad entre
Público: Si quieres que esté disponible para todos los usuarios.
Privado: Si deseas que solo a quien tu decidas puedan y colaborar con tu proyecto.
Definir si incluye un archivo de descripción llamado : README.md
Definir si habrá exclusiones de archivo a través del archivo: .gitignore
Guardar los cambios.
Si queremos usar un orden que comientce en número específico debemos utilizar código HTML, usando los tags <ol> y <li>:

EJEMPLO:

Quinto
Sexto
Séptimo
### 7. Ligas (Hipervínculos)
Las ligas son utilizadas para vincular elementos o referencias del proyecto dentro del mismo repositorio o fuera de el. Y se maquetan utilizanlo los corchetes [ ], inmediatamente despues pondrémos la liga de referencia entre parentesis ( )

EJEMPLO: Mi buscador favorito es: Google.

Pero si deseamos poner solo las ligas directas o un correo electrónico podemos utilizas los simbolos < >

EJEMPLO:

Documentación creada por: Juan Fernando Hernandez Lopez
250953@utxicotepec.edu.mx

http://www.utxicotepec.edu.mx

### 8. Tablas (TABLES)
Si la documentación lo requiere podemos presentar información en formato de tablas con filas y columnas, para maquetarlas podemos utiliziar el carácter | para delifitar las columnas y - para delimitar las filas.

EJEMPLO:

Encabezado 1	Encabezado 2	Encabezado 3	Encabezado 4
Fila 1 Celda 1	Fila 1 Celda 2	Fila 1 Celda 3	Fila 1 Celda 4
Fila 2 Celda 1	Fila 2 Celda 2	Fila 2 Celda 3	Fila 2 Celda 4
Fila 3 Celda 1	Fila 3 Celda 2	Fila 3 Celda 3	Fila 3 Celda 4
En caso de necesitar la fusión de celdas en columnas usaremos la propiedad colspan del tag <td> y en el caso de necesitar la fusión de filas utilizaremos la propiedad rowspan .

EJEMPLO:

Encabezado 1	Encabezado 2	Encabezado 3	Encabezado 4
Fila 1 Celda 1	Fila 1 Celda 2	Fila 1 Celda 3	Fila 1 Celda 4
Fila 2 Celda 1	Fila 2 Celda 2	Fila 2 Celda 3		
Fila 3 Celda 1	Fila 3 Celda 2	Fila 3 Celda 3	Fila 3 Celda 4
Fila 4 Celda 2	Fila 4 Celda 3	Fila 4 Celda 4
Fila 5 Celda 2	Fila 5 Celda 3	Fila 5 Celda 4
Fila 6 Celda 1	Fila 6 Celda 2	Fila 6 Celda 3	Fila 6 Celda 4
Dado que en el ejemplo pasado usando solo markdown no se puede realizar la fusión de filas debemos utilizar el estandar de HTML, usando los tags: <th> para los encabezados, <tr> para las filas y para las celdas, y en ellos utilizar la propiedad de colspan y rowspan

EJEMPLO:

Encabezado 1	Encabezado 2	Encabezado 3	Encabezado 4
Fila 1 Celda 1	Fila 1 Celda 2	Fila 1 Celda 3	Fila 1 Celda 4
Fila 2 Celda 1	Fila 2 Celda 2
Fila 3 Celda 1	Fila 3 Celda 2	Fila 3 Celda 3	Fila 3 Celda 4
Fila 4 Celda 2	Fila 4 Celda 3	Fila 4 Celda 4
Fila 5 Celda 2	Fila 5 Celda 3	Fila 5 Celda 4
Fila 6 Celda 1	Fila 6 Celda 2	Fila 6 Celda 3	Fila 6 Celda 4
### 9. Imágenes
Si la documentación requiere de incorporar imágenes, equemas , modelos, fotografías, o cualquier representación gráfica, utilizaremos la estuctura de la ligas, maquetanto el nombore de la imagen entre corchetes con un signo de admiración de cierre y la liga de referencia a la imagen usando parentesis.

EJEMPLO:

Picachu
