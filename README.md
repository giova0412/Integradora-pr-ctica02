# Integradora-practica02
Práctica de clara para aprender a utilizar Git hub como herramienta para desarrollo colaborativo,control de versiones y documentación del proyecto integrador de la asignatura 

### comandos basicos para maqueado
### Encabezado (Meadings)
Para poder dar enfasis a los contenidos de la documentación podemos utilizar los encabezados (Headings), para marcar alguna sección estos se marcan utilizando el simbolo #, entre menos repeticiones tengas mayor tamaño e importancia tendra el texto



# Encabezado de Nivel 1
## Encabezado de Nivel 2
### Encabezado de Nivel 3
#### Encabezado de Nivel 4
#### Encabezado de Nivel 5
###### Encabezado de Nivel 6
###### Encabezado de Nivel 7

### 2.separadores(Separators)-practica 03
si desea marcar una separacion mas visual de contenidos podemos utilizarlos indicando tres caracteres de "-"continuos,en el maquetado
Ejemplo:
*Esto es similar a un tag de HR en HTML
### 3.PARRAFOS
son utilizados para por presentar grandes secciones de texto que describen detalladamente las secciones de la documentacion del proyecto.
ejemplo:ESTE texto pertenece al parrafo 1   ESTE texto pertenece al parrafo 1   ESTE texto pertenece al parrafo 1 ESTE texto pertenece al parrafo 1 


ESTE texto pertenece al parrafo 1  ESTE texto pertenece al parrafo 1  ESTE texto pertenece al parrafo 1  ESTE texto pertenece al parrafo 1 

lo que en pagina utilizariamos usando la etiqueta {p}
   
Tambien podemos aplicar a la izquierda por defecto Este parrafo esta alineado a la izquierda por defecto

Tambien podemos aplicar a la izquierda por defecto Este parrafo esta alineado a la izquierda por defecto
Tambien podemos aplicar a la izquierda por defecto Este parrafo esta alineado a la izquierda por defecto
Tambien podemos aplicar a la izquierda por defecto Este parrafo esta alineado a la izquierda por defecto
{p}
### 4.Texto enfatizado (B0LD, ITALIC, BOLD/ITALIC)
si el texto que deseamos enfatizar se encuentra de un parrafo ,podemos utilizar algunos trucos para ubicarlos en la documentacion
#### texto en negrita(bold)
para poder poner el texto en negrita este debera estar encerrado entre dos 
documentacion

### Texto en Negrita (BOLD)
Para poder porer el texto en negrita, este deberá ser encerrado entre ** **

texto Texto Texto Texto Texto Texto **Texto** Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Texto Terto Texto Texto Terto Texto Texto Texto Texto Texto Texto Texto Texto.

### ITALIC

Para poner en cursiva 

**EJEMPLO**


texto texto *texto* texto texto 

#### Subrayado (UNDERLINE)
algunas veces necesitaremos subrayar texto dentro de la documentación, para ello, si bien markdown no tiene un atajo o codificación rápida podemos utilizar el estilo que use el estándar de HTML usando el tag /<ins> y cerrando con /</ins>.

**EJEMPLO**

TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO 
TEXTO TEXTO TEXTO TEXTO *TEXTO Cursivo* TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO 
TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO 
TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO TEXTO <ins> TEXTO Subrayado  </ins> TEXTO 

# Integradora practica 03

Continuamos con los comandos básicos de Git y GitHub para el maquetado de la documentación 

### 5. Cuadros de código o reseñas (BLOCKQUOTES)

Estos elementos son utilizados para resaltar instrucciones especificas para la instalación, configuración y/o inicializar mostrar secciones de código fuente. Se maqueta iniciando el texto con un símbolo de mayor que (>). 

**EJEMPLO**

Para listar las carpetas y archivos es desde una terminal de sistema operativo Windows debemos ingresar el comando:

C:/dir

Después oprimimos la tecla "enter"

También podemos ingresas textos multilínea 

**EJEMPLO**

>Aquí se ingresa un conjunto de instrucciones 
>para explicar al usuario, como instalar el
>que hemos diseñado.

Y si deseamos incluir viñetas para enlistar los pasos  podemos utilizar el carácter dentro del texto a documentar

 **EJEMPLO**

**PASOS PARA INSTALAR LA BASE DE DATOS**

>- Decargar MySQL Server del Sitio Oficial 
>- instalar el Sistema Gestor de Base de Datos definiendo el puesto y la contraseña para el usuario ***root***
>-Descargamos el archivo de respaldo de la base de datos (.sql)
>-restauramos la Base de Datos usando el comando *mysql*
C:/ProgramFiles/MySQL/MYSQLServer8.0/bin/mysql-u root -p
password < respaldo sql

**6. Listas ordenadas y Desordenadas**

síes en nuestra documentación necesitamos incluir información de texto en modo de lista, un elemento tras otro podemos hacerlo utilizando los números con un punto decimal si las deseamos ordenadas o un guion en medio - si solo queremos una viñeta 


**EJEMPLO**

  Para poder crear tu primero repositorio en GitHub deveras;
  
1. Contar con una cuenta GitHub
   
2.Dar clic en el botón **Nuevo Repositorio*

3.Asignarle un nombre a tu repositorio, por ejemplo: 'ptactica03-3b'

4.Asignarle un nivel de privacidad entre 

-**PUBLICO** Si quieres que este disponible para todos los usuarios.

-**PRIVADO** Si deseas que solo a quien decidas puedan colaborar con tu proyecto.

10.Definir si incluye un archivo de descripción llamado: *README.md*

11.Definir si habrá exclusiones de archivo a través del archivo a través del archivo : *gitignore*
***ejemplo***
5.quinto
6.sexto
7.septimo



#### 7. Ligas (Hipervínculos)

las ligas utilizadas para vincular elementos o referencias del proyecto dentro del mismo repositorio o fuera de el. Y se maquetan utilizando lo corchetes \[ \], inmediatamente después pondremos la liga de referencia entre paréntesis /()

**EJEMPLO**

Mi buscador favorito es: [www.google.com].

Pero si deseasa poner solo las ligas directas a un correo electrónico podemos utilizar los símbolos \<\>

**EJEMPLO**

Documentación creada por: **giovany raul pazos cruz*** (<pazoscruzgiovany@gmail.com>)

(<http://www.utxicotepec.edu.mx>)
#### 8.Tablas (Tabs)

Si la documentacion lo requiere podemos presentar informacion en formato de tablas con filas y columnas,
para maquetarlas podemos utilizar el caracter | para delifitar las columas y - para delimitar

**EJEMPLO**

| Encabezado 1 | Encabezado2 | Encabezado 3 | Encabezado4|
|--------------|-------------|--------------|------------|
|Fila 1 Celda 1|Fila 1 Celda 2|Fila 1 Celda 3|Fila 1 Celda 4|
|Fila 1 Celda 2|Fila 2 Celda 2|Fila 2 Celda 3|Fila 2 Celda 4|
| Fila 1 Celda3|Fila 3 Celda 2|Fila 3 Celda 3|Fila 3 Celda 4|

En caso de necesitar la fusión de celdas en columnas usaremos la propiedad *colspan* del tag \<td> y en el caso de necesitar la fusión de filas utilizaremos la propiedad *rowspan* .


**EJEMPLO**
| Encabezado 1 | Encabezado2 | Encabezado 3 | Encabezado4|
|--------------|-------------|--------------|------------|
|Fila 1 Celda 1|Fila 1 Celda 2|Fila 1 Celda 3|Fila 1 Celda 4|
|Fila 2 Celda 2<td colspan=2>Fila 2 Celda 2 | Fila 2 Celda 4|              
| Fila 3 Celda3|Fila 3 Celda 2|Fila 3 Celda 3|Fila 3 Celda 4|
|              |Fila 4 Celda 2|Fila 4 Celda 3|Fila 4 Celda 4|
|              |Fila 5 Celda 2|Fila 5 Celda 3|Fila 5 Celda 4|
| Fila 6 Celda5|Fila 6 Celda 2|Fila 6 Celda 3|Fila 6 Celda 4|

Dado que en el ejemplo pasado usando solo markdown no se puede realizar la fusión de filas debemos utilizar el estandar de HTML, usando los tags: \<th> para los encabezados, \<tr> para las filas y <td> para las celdas, y en  ellos utilizar la propiedad de  *colspan* y *rowspan*

**EJEMPLO:**

<table>
 <tr>
  <th>Encabezado 1</th>
 <th>Encabezado 2</th>
 <th>Encabezado 3</th>
 <th>Encabezado 4</th>
</tr>
 <tr>
   <td>Fila 1 Celda 1</td>
  <td>Fila 1 Celda 2</td>
  <td>Fila 1 Celda 3</td>
  <td>Fila 1 Celda 4</td>
 </tr>
 
 <tr>
   <td>Fila 2 Celda 1</td>
  <td colspan=3 align="center">Fila 2 Celda 2</td>
 </tr>

 <tr>
  <td rowspan=3> Fila 3 Celda 1</td>
  <td> Fila 3 Celda 2</td>
  <td> Fila 3 Celda 3</td>
  <td> Fila 3 Celda 4</td>
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

#### 9.Imágenes 

Si la documentación requiere de incorporar imágenes, equemas , modelos, fotografías, o cualquier representación gráfica, utilizaremos la estuctura de la ligas, maquetanto el nombore de la imagen entre corchetes con  un signo de admiración de cierre y la liga de referencia a la imagen usando parentesis. 

**EJEMPLO:**

#### texto importate ###
### Encabezado de Nivel 1
