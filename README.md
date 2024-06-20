# Integradora-Practica02

En está práctica aprenderemos autilizar las herramientas Git y GitHub para el control de versiones,documentación, Desarrollo Colaborativo y Respaldo del Proyecto Integrador para la Asignatura de Integradora I

## Comandos Básicos para la documentación, utilizando el estandar de Markdown (md)
Markdown es el estandar utilizado por Git y Github para maquetar la documentación de proyectos, lo que permite 
a usuarios y colaboradores del proyecto entender el contexto y operació del mismo.

### 1. Encabezados o Títulos (HEADERS)
Para poder realizar una buena documentación del proyecto debemos, distribuir correctamente los contenido, para poder delimitar o hacer enfásis (enfatizar) es decir resaltar las secciones importantes, podemos utilizar los siguientes:

EJEMPLOS:
# Encabezado de Nivel 1 - similar a H1 en HTML
## Encabezado de Nivel 2 - similar a H2 en HTML
### Encabezado de Nivel 3 - similar a H3 en HTML
#### Encabezado de Nivel 4 - similar a H4 en HTML
##### Encabezado de Nivel 5 - similar a H5 en HTML
###### Encabezado de Nivel 6 - similar a H6 en HTML
####### Encabezado de Nivel 7 - solo son los niveles permitidos, a partir de este el maquetado será ignorado.

### 2.Separadores (SEPARATORS)
Si desea marcar una separación más visual de contenidos podemos utilizarlos indicando tres carácteres de guión medio "-"continúos, en el maquetado


EJEMPLO
---
*Esto es similar a un tag de < HR > en HTML.

### 3.Párrafos (PARAGRAPHS)
Son utilizados para presentar grandes secciones de texto que describen detalladamente las secciones de ladocumentación del proyecto. 

EJEMPLO:
Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1
Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1
Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1 Este texto pertenece al párrafo 1
Este texto pertenece al párrafo 1

Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2
Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 
Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2
Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2
Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2
Este texto pertenece al párrafo 2 Este texto pertenece al párrafo 2

Lo que en una página utilizariamos usando la etiqueta < P >.

También podemos aplicar estilos básicos de alineación:

Este párrafo esta alineado a la izq por defecto Este párrafo esta alineado a la izq por defecto Este párrafo esta alineado a la izq por defecto
Este párrafo esta alineado a la izq por defecto Este párrafo esta alineado a la izq por defecto Este párrafo esta alineado a la izq por defecto
Este párrafo esta alineado a la izq por defecto Este párrafo esta alineado a la izq por defecto Este párrafo esta alineado a la izq por defecto
Este párrafo esta alineado a la izq por defecto

<p align="right">
Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion. Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion.
Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion. Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion. Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion. Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion. Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion. Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion. Este párrafo esta alineado a la derecha utilizando la propiedad de alineacion.
</p>

<p align="center">
Este párrafo esta centrado usando la propiedad de alineacion.  Este párrafo esta centrado usando la propiedad de alineacion.  Este párrafo esta centrado usando la propiedad de alineacion.  Este párrafo esta centrado usando la propiedad de alineacion. Este párrafo esta centrado usando la propiedad de alineacion.  Este párrafo esta centrado usando la propiedad de alineacion.  Este párrafo esta centrado usando la propiedad de alineacion.  Este párrafo esta centrado usando la propiedad de alineacion. Este párrafo esta centrado usando la propiedad de alineacion.  Este párrafo esta centrado usando la propiedad de alineacion. 
</p>

<p align="justify">
Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación.Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación. Este párrafo estará justificado utilizando la propiedad de alineación.
</p>

### 4. Texto enfatizado (BOLD,ITALIC, BOLD/ITALIC)

Si el texto que deseamos enfatizar se encuentra en un párrafo, podemos utilizar algunos trucos para ubicarlos en la documentación.

##### Texto en Negrita (BOLD)
Para poder poner el texto en negrita, este debera ser encerrado en dos **

EJEMPLO:
Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto **Texto importante**Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto 

##### Texto en Cursiva (ITALIC)
Para poder poner el texto en cursiva, es anteponer un asterisco (*) o un guión bajo (_)

EJEMPLO:
Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto *Texto importante* Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto _Texto importante_ Texto Texto Texto Texto Texto Texto Texto 


##### Texto en negrita y cursiva (BOLD/ITALIC)
Para poder poner el texto en negrita y cursiva debe ser encerrado entre tres asteriscos (***)

Ejemplo:
Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto ***Texto importante*** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto ***Texto importante*** Texto Texto Texto Texto Texto Texto Texto 

##### Texto subrayado (UNDERLINE) 

Algunas veces necesitaremos subrayar texto dentro de la documentación, para ello, si bien markdown no tiene un atajo o codificación rápida podemos utilizar el estilo que usa el estándar de HTML usando el tag \<ins> y cerrando con \</ins>.

Ejemplo:
Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto ***Texto importante*** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto <ins>Texto importante Texto Texto</ins> Texto Texto Texto Texto Texto 


# Integradora-Practica03

Continuamos con los comandos básicos de Git y Github para el maquetado de la documentación.

### 5. Cuadros para código o Reseñas (BLOCKQUOTES)

  Estos elementos para resaltar instrucciones específicas para la instalación, configuración y/o inicialización o mostrar secciones de código fuente. Se maqueta iniciando el texto con un símbolo de mayor que (\>).
  
  **EJEMPLO:**
  Para listar las carpetas y archivos desde una terminal de sistema operativo Windows debemos ingresar el comando: 

  > C:/dir

Después oprimimos la tecla "enter". 

También podemos ingresar textos multilineales

**EJEMPLO:**

>Aquí se ingresa un conjunto de instrucciones
>para explicar al usuario, como instalar el
>software que hemos diseñado.

 Y si deseamos incluir viñetas para enlistar pasos podemos utilizar el caracter 
 -dentro del texto a documentar.

**EJEMPLO**
 **Pasos para instalar la base de datos**
 > - Descargar MySQL Server delsitio oficial
>  - Instalar el SistemaGestor de Base de Datos, definiendo el puerto y contraseña para el usuario ***root***
>  - Descargamos el archivo de respaldo de la base de datos (.sql)
>  - Restauramla Base de Datos usando el comando *mysql *
>> C:/Program Files/MySQL/MySQL Server 8.0/bin/mysql -u root -p password \< respaldo.sql

### 6.Listas Ordenadas y Listas Desordenadas

Si en nuestra documentación necesitamos incluir información en modo de lista, un elemento tras otro podemos hacerlo utilizamos los números con un punto decimal si las deseamos ordenadas o un guión medio - si solo queremos una viñeta.

**EJEMPLO**
Para crear tu primer repositorio en GitHub deberás:
1. Contar con cuenta de GitHub.
1. Dar click en el boton: **Nuevo Repositorio*
2. Asignarle un Nombre a tu repositorio, por ejemplo:  *practicas3-3b*
8. Asignarle un nivel de privacidad entre
   - **Público:** Si quieres que éste disponible para todos los usuarios.
   - **Privado:** Deseas que solo a quien tu decidas puedan ver y colaborar con tu proyecto.
5. Definir si incluye un archivo de descripción llamado : *README.md*
50. Definir si habrá exclusiones de archivo a través de archivo: *.gitignore*
3. Guardar los cambios.  

#### 7. Ligas (HIPERVINCULOS)
Las ligas son utilizadas para víncular elementos o referencias delproyecto dentro del mismo repositorio o fuera de él. Y se maquetan utilizando los corchetes \[ \]

**EJEMPLO**
Mi buscador favorito es: [Google](https://www.google.com)

Pero si deseamos ponersolo lasligas directas o un correo electrónico podemos utilizas los símbolos \< \>

**EJEMPLO**

Documentación creada por: ***Tania Ibarra Salgado***

<230369@utxicotepec.edu.mx>

<http://www.utxicotepec.edu.mx>

#### 8. Imágenes 

Las imágenes son utilizadas para representar y demostrar los elementos/pasos creados durante la documentación de nuestro proyecto. Es importante que se demuestre con claridad.
Para poder subir un archivo, antes que nada se tiene que añadir al repositorio, y subirlo con especificaciones correspondientes. Para despues ingresar a este y **copiar la ruta.**
De primera mano, el primer símbolo a ingresar es una cierre de admiración, para después colocar dos corchetes y dos llaves en donde entre ellas  se copiara la ruta de la imagen deseada.


![](https://github.com/ibarra-tania/Integradora-Pr-ctica02/blob/main/github.jpg)


#### 8. Tablas(Tables)

Si la documentación lo requiere podemos presentar información en formato de tablas con filas y columnas, para maquetarlas podemos utilizar el carácter \| para delimitar las columnas y \- para delimitar las filas.



**EJEMPLO:**

| Encabezado 1 | Encabezado 2 | Encabezado 3 | Encabezado 4|
|--------------|--------------|--------------|-------------|
| Fila 1 Celda 1 | Fila 1 Celda 2 | Fila 1 Celda 3 | Fila 1 Celda 4 |
| Fila 2 Celda 1 | Fila 2 Celda 2 | Fila 2 Celda 3 | Fila 2 Celda 4 |
| Fila 3 Celda 1 | Fila 3 Celda 2 | Fila 3 Celda 3 | Fila 3 Celda 4 |


En caso de necesitar la fusión de celdas en columnas usaremos la propiedad *colspan* del tag \<td> y en el caso de necesitar la fusión de filas utilizaremos la propiedad *rowspan* .

**EJEMPLO**

| Encabezado 1 | Encabezado 2 | Encabezado 3 | Encabezado 4|
|------------|--------------|--------------|-----------|
| Fila 1 Celda 1 | Fila 1 Celda 2 | Fila 1 Celda 3 | Fila 1 Celda 4 |
| Fila 2 Celda 1 <td colspan-2> Fila 2 Celda 2 | Fila 2 Celda 3 |
| Fila 3 Celda 1 | Fila 3 Celda 2 | Fila 3 Celda 3 | Fila 3 Celda 4 |
|                | Fila 4 Celda 2 | Fila 4 Celda 3 | Fila 4 Celda 4 |
|                | Fila 5 Celda 2 | Fila 5 Celda 3 | Fila 5 Celda 4 |
| Fila 6 Celda 1 | Fila 6 Celda 2 | Fila 6 Celda 3 | Fila 6 Celda 4 |


Dado que en el ejemplo pasado usando solo markdown no se puede realizar la fusión de filas debemos utilizar el estándar de HTML, usando los tags: \<tr> para las filas y \<td> para las celdas, y en ellos utilizar la propiedad de *colspan* y *rowspan*


**EJEMPLO:**

<table>
<tr>
<th> Encabezado 1</th>
<th> Encabezado 2</th>
<th> Encabezado 3</th>
<th> Encabezado 4</th>
</tr>

<tr>
<td>Fila 1 Celda 1</td>
<td>Fila 1 Celda 2</td>
<td>Fila 1 Celda 3</td>
<td>Fila 1 Celda 4</td>
</tr>

<tr>
 <td> Fila 2 Celda 1</td>
<td colspan-3 align="center">Fila 2 Celda 2</td>
</tr>

<tr>
<td rowspan-3 align="center">Fila 3 Celda 1</td>
<td>Fila 3 Celda 2</td>
<td>Fila 3 Celda 3</td>
<td>Fila 3 Celda 4</td>
</tr>

<tr>
<td>Fila 4 Celda 2</td>
<td>Fila 4 Celda 3</td>
<td>Fila 4 Celda 4</td>
</tr>

<tr>
<td>Fila 5 Celda 2</td>
<td>Fila 5 Celda 3</td>
<td>Fila 5 Celda 4</td>
</tr>


<tr>
<td>Fila 6 Celda 1</td>
<td>Fila 6 Celda 2</td>
<td>Fila 6 Celda 3</td>
<td>Fila 6 Celda 4</td>
</tr>

</table>



#### 9.- Imágenes 

Si la documentación requiere de incorporar imágenes, esquemas, modelos, fotografías o cualquier representación gráfica, utilizaremos la estructura de la liga, maquetando el nombre de la imagen entre con un signo de admiración de cierre y la liga de referencia a la imagen usando paréntesis.

**EJEMPLO**

![Pikachu](https://github.com/ibarra-tania/Integradora-Pr-ctica02/blob/main/pikachu.jpg)
