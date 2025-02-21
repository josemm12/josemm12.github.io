# josemm12.github.io

## Parte Teorica


### HTML


1. **¿Que es HTML Y cual es su funcion en la WEB?**

Es un Lenguaje de Marcas de Hipertexto estandar para la creacion   
de paginas web. Su funcion principal es que define el significado  
y la estructura del contenido Web.

2. **¿Que es una etiqueta HTML y mencione las mas comunes?**

Es un elemento que define la estructura y contenido de una paginas  
web. Cada etiqueta tiene una funcion especifica y se representa  
entre "< >".

**Algunas de las etiquetas mas comunes son:**

- `<html>`: Define el inicio y el fin de un documento HTML.
- `<head>`: Contiene metadatos y enlaces a archivos externos.
- `<title>`: Define el titulo de la pagina web.
- `<body>`: Contiene todo el contenido visible de la pagina.
- `<h1> - <h6>`: Encabezados de diferentes niveles.
- `<p>`: Define un parrafo de texto.
- `<a>`: Crea enlaces a otras paginas o secciones.
- `<img>`: Muestra imagenes en la Web.
- `<ul>` y `<ol>`: Listas desordenadas y ordenadas.
- `<div>`y `<span>`: Contenedores para organizar el contenido.

3. **¿Que es un atributo de etiqueta HTML y las mas comunes?**

Es una informacion adicional que se añade a una etiqueta para  
modificar su comportamiento o apariencia. Los atributos siempre  
van dentro de la etiqueta de apertura y tienen un formato  
clave-valor: `atributo="valor"`.

**Algunos atributos comunes en HTML son:**

- `href`: Se usa en la etiqueta `<a>`para definir la URL de un  
enlace .
- `src`: Se usa en `<img>`para especificar la ruta de la imagen.
- `alt`: Texto alternativo para imagenes, util para accesibilidad. 
- `id`: Identifica un elemento de manera unica en el documento.
- `class`: Permite aplicar estilos CSS a varios elementos con la  
misma clase.
- `style`: Agrega estilos CSS directamente en el elemento.
- `target`: Indica como abrir un enlace.


### CSS 


4. **¿Que es CSS y como se utiliza para el diseño web?**

Es el lenguaje utilizado para definir la apariencia de los elementos  
HTML. Permite modificar colores, fuentes, espaciados y disposicion de  
los elementos de la pagina.

5. **¿Que es una propiedad en CSS y mencione las propiedades mas comunes?**

Una propiedad en CSS define un aspecto del estilo de un elemento. Se  
usa con un valor para aplicar estilos.

**Ejemplos de propiedades comunes**
- `color`: Define el color del texto.
- `backgroundColor`: Define el color de fondo.
- `font-size`: Tamaño de la fuente.
- `margin`: Margen externo del elemento.
- `padding`: Espacio interno dentro del elemento.

6. **¿Que es un selector en CSS y cuales tipos existen?**

Un selector en CSS define que elementos HTML seran estilizados. 

**Tipos de selectores**
-**Selector de etiqueta:** Aplica estilos a un tipo de elemento.
-**Selector de clase:** Se usa con el atributo `class`.
-**Selector de ID:** Se usa con el atributo `id`.


### JavaScript

7. **¿Que es Javascript y como añade interctividad a las paginas web?**

JavaScript es un lenguaje de programacion que permite agregar dinamismo  
a las paginas web. Se usa para validar formularios, manipular el DOM,  
realizar peticiones HTTP y manejar eventos.  

8. **¿Cuales son los tipos de datos primitivos en Javascript?**

- `String`: Cadena de texto.
- `Number`: Numeros (enteros y decimales).
- `Boolean`: Valores `true`o `false`.
- `Undefined`: Variable declarada sin valor asignado.
- `Null`: Valor intencionalmente vacio.
- `Symbol`: Identificadores unicos.
- `BigInt`: Numeros enteros muy grandes.

9. **¿Como funcionan las estructuras de control de flujo como if, else, switch y bucles en Javascript?**

Estas estructuras de control permiten controlar el flujo del programa.

- **Condicionales:**
```Js 
if (condition) {
    // Codigo si es verdadero
} else {
    // Codigo si es falso
}
``` 
- **switch:**
```js
switch (key) {
    case value1:
        // Codigo
        break;
    case value2:
        // Codigo
        break;
    default:
        // Codigo si no coincide
}
``` 
- **Bucles:**
  - `for`: Se ejecuta un numero determinado de veces.
  - `while`: Se ejecuta mientras una condicion sea verdadera.
  - `do while`: Se ejecuta al menos una vez.


### Buenas Practicas


10. **¿Por que es importante usar nombres significativos para variables y metodos?**

Facilita la lectura y mantenimiento del codigo. Un buen nombre  
describe la funcion de la variable o metodo.

**Ejemplo**
```Js
let nombreUsuario = "Jose" ; // Correcto
let x = "Jose"; // Incorrecto
```
11. **¿Que es una variable de entorno y por que son importantes para JavaScripto la programacion en general?**

Son valores configurables que afectan el entorno de ejecucion.  
Se usan para almacenar claves API, rutas de base de datos, etc.


### Herramientas de Desarrollo


12. **¿Que son las herramientas de desarrollo de chrome y como se accede a ellas?**

Son herramientas integradas en chrome para depurtar, inspeccionar y  
analizar paginas web. Se accede presionando `F12` o `Ctrl + Shift + I`.

13. **¿Que se puede hacer en el panel "Elements" de las herramientas de desarrollo y para que es util?**

Se usa para depurar codigo JavaScript, ver errores y ejecutar  
comandos en tiempo real.

15. **¿Que informacion se puede obtener del panel "Network" y por que es importante?**

Muestra todas las solicitudes HTTP realizadas por la pagina, tiempos de  
de carga y posibles errores en la red.