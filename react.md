# Bootcamp
## React
## Estructura
En la carpeta public van los recursos estáticos de nuestra página web (index.tml, favicon.ico,etc.)

En src estará el código fuente:
  * App.css
  * App.js
  * App.test.js
  * index.css
  * index.js -> punto de entrada de la aplicación
  * logo.svg
  * reportWebVitals.js -.> web performance
  * setupTest.js -> setup de los tests

### index.js
Está utilizando ecmascript, por lo que utiliza `import`

### Explicaciones
* Los componentes se declaran como funciones. Con componentes de UI reutilizables en  la aplicación
<code>
    <pre>
        function App() {
        return (
            <div className="App">
            Hola mundo
            </div>
        );
    </pre>
</code>

* EL código que hay dentro del JS como HTML se llama JSX y lo transforma en JS cuando se compila

* ReactDOM es una librería para poder utilizar React en el navegador