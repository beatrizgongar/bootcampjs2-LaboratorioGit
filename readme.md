## Laboratorio Git Beatriz Gonzalez Garcia

## 1. Crear un repositorio en local

<p>Primero abrimos el  terminal en Visual Studio y navegamos hasta el directorio donde crearemos el repositorio</p>

**D:\MasterLemoncode\Repos-git**

> cd ..
>
> cd d:\masterlemoncode
>
> cd repos-git

![Navegando al directorio](./content/NavegandoDirectorio.png)

Creamos la carpeta con el nombre del repositorio LaboratorioGit

![Crear Carpeta](./content/CrearCarpeta.png)

También se puede crear desde línea de comandos con

> mkdir LaboratorioGit

Vamos a la carpeta que acabamos de crear

> cd LaboratorioGit/

![Navegando a la carpeta](./content/NavegandoRepositorio.png)

Inicializamos el repositorio

> git init

## 2. Subir el repositorio a GitHub

Para ello primero creamos un repositorio en GitHub

![Creando repositorio GitHub 1](./content/CrearRepositorioGitHub1.png)

Informamos el nombre del repositorio, una breve descripción y elegimos que sea Público

![Creando repositorio GitHub 2](./content/CrearRepositorioGitHub2.png)

Una vez creado copiamos la dirección SSH para poder asociarlo a nuestro repositorio en local

![Creando repositorio GitHub 3](./content/CrearRepositorioGitHub3.png)

Conectamos el repositorio de local con el que acabamos de crear en GitHub

> git remote add origin git@github.com:beatrizgongar/bootcampjs2-LaboratorioGit.git

Y comprobamos que la conexión se ha establecido correctamente

> git remote -v

![Creando repositorio GitHub 4](./content/CrearRepositorioGitHub4.png)

## 3. Hacer un commit y un push

Primero creamos un archivo en la carpeta del repositorio

![Hacer commit 1](./content/Hacercommit1.png)

Y le llamamos primerArchivo.html

![Hacer commit 2](./content/Hacercommit2.png)

Informamos el HTML

![Hacer commit 3](./content/Hacercommit3.png)

Añadimos el archivo al staging

> git add .

He incluimos un commit

> git commit -m "Añadimos primerArchivo.html"
