## Para poder utilizar el CSS Nano
 
 **1º** Utilizamos el istalador de paquetes Node.js

 **2º** Utilizamos el siguiente comando:
 ``` bash
 npm install cssnano postcss --save-dev
 ```

 **3º** Utilizamos el siguiente comando que instala el PostCSS CLI
 ``` bash
 npm install --save-dev postcss-cli
 ```

 **4º** Creamos el archivo [postcss.config.js](postcss.config.js) y introducimos el siguiente codigo:

 ```code
module.exports = {
    plugins: [
        require('cssnano')({
            preset: 'default',
        }),
    ],
};
 ```

 **5º**  Una vez instalado y configurado ejecutamos en siguinte comando:
 ```bash
npx postcss input.css > output.css
 ```




## Uso de la Pseudoclases de CSS

**Fuente externa:** Linea 3

**Variables CSS:** Linea 22

**:hover:** Linea 133

**:focus:** Linea 208

**:link:** Linea 25

**:visited:** Linea 21

**:root** Linea 5

**:invalid** Linea 191

**Todos los campos son requeridos** Gracias al required 

**Validacion del email** Uso pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,}$"

**:before** Linea 235

**:after** Linea 137

**:selection** Linea 30
