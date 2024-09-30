# proyectos-web

Historial de commits:

commit fb4e711f0d0e915e750a063009fc38743d0b1aef (HEAD -> main, origin/main, origin/HEAD)
Author: morfi02 <morfijorge489@gmail.com>
Date:   Mon Sep 30 08:50:26 2024 +0100

    Update README.md

commit 0cfaa42535407cffbb4e5da9449978c123535ab4
Merge: 34f6d37 bc3e13f
Author: morfi02 <morfijorge489@gmail.com>
Date:   Mon Sep 30 08:46:29 2024 +0100

    Merge branch 'main' of github.com:morfi02/proyectos-web
    documentacion

commit 34f6d3779da9796f82d0c6bc9a9a702fca40e071
Author: morfi02 <morfijorge489@gmail.com>
Date:   Mon Sep 30 08:45:21 2024 +0100

    documentacion

commit a3773ec405da941d87fdf73d140863c0f727032d
Author: morfi02 <morfijorge489@gmail.com>
Date:   Mon Sep 30 08:40:32 2024 +0100

    documentacion

commit bc3e13f359ed1df411e5b90c7e81b90c73c8ece3
Author: Eduardo <121913464+LarryKatulav1@users.noreply.github.com>
Date:   Wed Sep 25 12:44:05 2024 +0100

    Update README.md

commit a42286df3033ccecc5deae28fa3277bf874e2e41
Merge: 95f2d8f bf205c5
Author: Eduardo <121913464+LarryKatulav1@users.noreply.github.com>
Date:   Wed Sep 25 12:41:39 2024 +0100

    Merge pull request #3 from morfi02/header
    
    añadir seccion encabezado

commit 95f2d8f07a3fcfe6d72e31a76f97b8c7c7af84b1
Merge: 509684e 351e685
Author: morfi02 <morfijorge489@gmail.com>
Date:   Wed Sep 25 13:39:46 2024 +0200

    Merge pull request #2 from morfi02/footer
    
    Añadir seccion de pie de pagina

commit 351e68505300c9da83fbde25bbd3f91635671170 (origin/footer)
Author: Eduardo <eduardofp640@gmail.com>
Date:   Wed Sep 25 12:15:11 2024 +0100

    Añadir seccion de pie de pagina

commit 509684e33c853ab2452538ab49919795af6b6980
Author: Eduardo <121913464+LarryKatulav1@users.noreply.github.com>
Date:   Wed Sep 25 11:48:29 2024 +0100

    Update README.md

commit bf205c53df3d8142a801ae82ec43676e0ab4a8ce (origin/header)
Author: morfi02 <morfijorge489@gmail.com>
Date:   Wed Sep 25 10:06:41 2024 +0100

    añadir seccion encabezado

commit 7dc4ce56087f33c0dd1c0ffec20c1f49b4fc8521
Author: morfi02 <morfijorge489@gmail.com>
Date:   Wed Sep 25 09:47:46 2024 +0100

    Agregar estructura básica de index ahora.html

commit f065db1177004bd5727ec38497509da26c8a93de
Author: morfi02 <morfijorge489@gmail.com>
Date:   Wed Sep 25 09:42:10 2024 +0100

    Agregar estructura básica de index.html

commit 9887caa31cfcb83664c2b2f0e0d79d12382c5735
Author: morfi02 <morfijorge489@gmail.com>
Date:   Wed Sep 25 09:39:13 2024 +0100

    borrar prueba de index

commit 30e3ad55f8dfa62ee7040a67ec1a413771924604
Author: morfi02 <morfijorge489@gmail.com>
Date:   Wed Sep 25 09:29:51 2024 +0100

    subiendo index

commit b791fcc6a3c38cae656b1249e14618e76bfa1d84
Author: morfi02 <morfijorge489@gmail.com>
Date:   Wed Sep 25 09:22:16 2024 +0100

    primer commit


1. Configuración Inicial
jorge:
Creo un repositorio en GitHub llamado proyecto-web.(cree una carpeta en el escritorio y accedo mediante la terminal a la carpeta para iniciar elgit init desde ahi y poder crear un repositorio)
desde el repositorio mismo accedemos a "Settings" , selecciono "Manage Access" y añado a edu como colaborador.
edu:
Recibe la invitación y acepta ser colaborador del repositorio.
Ambos:
Clonamos el repositorio en sus computadoras locales con el siguiente comando:
git clone github.com/AlumnoA/proyecto-web.git
2. Estructura Básica del Proyecto
Alumno A:
Crea un archivo index.html con la estructura básica de una página HTML:

Realiza un commit inicial:

git add index.html
git@github.com:morfi02/proyectos-web.git

Hace push al repositorio remoto:

git push origin main
3. Creación de Ramas para Nuevas Funcionalidades
jorge (rama header):
Cree una nueva rama llamada header para trabajar en la sección del encabezado:

git checkout -b header(para acceder a la rama header a la vez que se crea)
Modificamos el archivo index.html para agregar un encabezado:

Realiza commits:

git add index.html
git commit -m "Añadir sección de encabezado"
git push origin header

edu (rama footer):
Creo una nueva rama llamada footer para trabajar en la sección del pie de página:

git checkout -b footer
Modifica el archivo index.html para agregar un pie de página:

despues 

git add index.html
git commit -m "Añadir sección de pie de página"
git push origin footer

4. Desarrollo Simultáneo
Ambos alumnos pueden continuar trabajando en sus respectivas ramas añadiendo archivos CSS.

jorge: creo un archivo styles.css para los estilos del encabezado.
edu: creo otro archivo styles-footer.css para los estilos del pie de página.
Ambos enlazamos nusetros archivos CSS en el index.html:

5. Revisión y Fusión de Cambios
jorge y edu:
Cada uno crea una Pull Request (PR) desde su rama (header y footer) hacia la rama main.
En "Pull Requests" de GitHub, se puede revisar el código del otro y dejar  comentarios.
Después de la revisión y aprobación, proceden a fusionar las ramas header y footer con main.
6. Resolución de Conflictos (si aplica)
Si ambos alumnos editaron las mismas líneas en el archivo index.html, puede haber conflictos al fusionar. Aquí está cómo resolverlos:

7. Actualización del Repositorio Local
Después de fusionar las ramas en main, ambos alumnos deben actualizar su rama main local para tener la versión más reciente del proyecto:

git checkout main
git pull origin main

8. Mejoras Adicionales

jorge crea una rama estilos-header para mejorar el diseño del encabezado.
edu  crea una rama contenido-footer para agregar más detalles al pie de página.

