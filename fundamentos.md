# Bootcamp
## Ampliar información de HTML & CSS
[Code academy](www.codeacademy.com)

[Google](https://learndigital.withgoogle.com)

[Full Stack Open](https://fullstackopen.com/es)


## Leyendo del DOM
* Obtiene los elementos de tipo 'a'

    `document.querySelectorAll('a')` 
  
* Modifica el texto
  
    `document.querySelector('a.home-article strong).textContent = 'Esto es un texto'` 

* Modifica el HTML del nodo

    `document.querySelector('a.home-article strong).innerHtml = '<h2>Esto es un texto</h2>'` 
  
* Obtiene la altura de un elemento   

    `document.querySelector('li).clientHeight` 
  

## Peticiones a servidor
Según se van descubriendo, se van realizando las peticiones al servidor. Se pueden dar pisas al servidor para establecer prioridades pero lo suele hacer automáticamente.

Por ejemplo, `<link rel='preload' ...> permite establecer la prioridad de que tiene que precargarlo.

## Notas JS
### Mutable o inmutable
String es inmutable -> No se puede modificar un string

`let firstName = 'Pepe'` 


`firstName.toUpperCase()` no modifica el valor de firstName

Las listas sin mutables
<code>

const list = []

list.push(1)<code>
