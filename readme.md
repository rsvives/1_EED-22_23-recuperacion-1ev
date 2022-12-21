# Entornos de desarrollo | Recuperación 1ª Evaluación

## Examen Práctico de contenidos mínimos

Leer atentamente todo el enunciado antes de realizar ninguna acción.

### Intrucciones:

Antes de comenzar:

1. Abrir una nueva ventana del VSCode `Ctrl +  Shift + N`.
2. Clonar el siguiente repositorio: `https://github.com/rodri-afa/1_EED-22_23-recuperacion-1ev`.
3. Guardarlo en local, por ejemplo en la carpeta documentos. Es necesario que dicha carpeta no sea ya un repositorio.
4. Asegurarse de que la carpeta clonada se encuentra abierta como carpeta raiz en el VSCode

### Enunciado

Se van a realizar una serie de acciones en commits separados. Es **MUY IMPORTANTE** que cada commit, contenga los cambios que se piden y el **mensaje de commit adecuado**. Para ello se puede proceder de dos formas:

- Hacer commit cada vez que se termine de hacer el conjunto de acciones descritas en cada commit **(opción recomendada)**
- Utilizar la fase Stage, previa al commit, e ir seleccionando los diferentes archivos (con el icono del `+`) sobre los que se va a hacer commit.

> <p style="color:#D29922"><b>⚠️ Aviso!</b></p> 
> Es necesario tener al menos 3 de los 4 commits para aprobar

#### Commit 1 (mensaje: crear script)

- Crear un fichero llamado `script.js` y en su interior, pegar el siguiente texto:

  ```
  console.log("Hola mundo");
  ```

#### Commit 2(mensaje: modificar html)

- Sustituir la **línea 30** del archivo `index.html` por: `<script src="./script.js"></script>`

#### Commit 3(mensaje: borrar css)

- Borrar el archivo style.css

#### Commit 4(mensaje: carpeta)

- Crear una carpeta llamada `carpeta` y en su interior crear dos archivos con el siguiente texto:

  - `pagina1.html` : `<h1>Esto es la página 1</h1>`
  - `pagina2.html` : `<h1>Esto es la página 2</h1>`

### Entrega

1. Hacer push y crear una bifurcación (fork) en github.
2. Comprimir la carpeta 1_EED-22_23-recuperacion-1ev en formato .zip y subirlo al campus.
