# proyectos-web
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

html
Copiar código
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proyecto Web</title>
</head>
<body>
    <h1>Bienvenidos a nuestro proyecto web</h1>
</body>
</html>
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

