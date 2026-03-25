# Landing Academica AWS SaaS Payments

Landing page academica de parte de la actividad de transferencia Ucompensar en la materia de desarrollo de soluciones en la nube, sobre el diseno de una solucion SaaS para una pasarela de pagos de alto rendimiento en AWS.

## Descripcion
Este proyecto presenta, de forma visual y tecnica, una propuesta de arquitectura en AWS para procesar mas de 1 millon de transacciones diarias con picos de hasta 30x, manteniendo alta disponibilidad, baja latencia y seguridad de extremo a extremo.

## Caracteristicas
- Diseno moderno estilo neon orientado a presentacion academica.
- Secciones tecnicas por temas: desafio, arquitectura, seguridad, observabilidad y evaluacion.
- Diagramas visuales y tarjetas explicativas para facilitar la exposicion.
- Diseno responsive para escritorio y dispositivos moviles.
- Implementado con tecnologias base (sin frameworks): HTML y CSS.

## Tecnologias
- HTML5
- CSS3
- Google Fonts
- Recursos visuales locales y remotos

## Estructura del proyecto

```text
PresentacionFinal/
|- Principal/
|  |- index.html
|  |- styles.css
|- img/
|  |- auroralogo.png
|  |- EC2logo.png
|  |- iamlogo.png
|  |- imagenservidoraltademanda.png
|- README.md
```

## Vista previa

![Vista previa principal](img/imagenservidoraltademanda.png)

## Como ejecutar localmente
1. Descarga o clona el repositorio.
2. Abre la carpeta del proyecto en VS Code.
3. Ejecuta un servidor local (por ejemplo, Live Server) desde la raiz del proyecto.
4. Abre en el navegador la ruta Principal/index.html.

## Publicacion en GitHub
1. Crea un nuevo repositorio en GitHub.
2. Sube el contenido de la carpeta PresentacionFinal.
3. Agrega este README.md en la raiz.
4. Realiza commit y push.

Comandos sugeridos:

```bash
git init
git add .
git commit -m "feat: landing academica AWS SaaS"
git branch -M main
git remote add origin https://github.com/USUARIO/NOMBRE-REPO.git
git push -u origin main
```

## Publicar con GitHub Pages (opcional)
1. En GitHub, entra a Settings > Pages.
2. En Build and deployment, selecciona Deploy from a branch.
3. Elige la rama main y la carpeta root.
4. Guarda cambios y espera el despliegue.

Nota: Si publicas en una subruta de GitHub Pages, revisa las rutas absolutas de imagenes usadas en el HTML para asegurar compatibilidad.

## Autor
Jorge Isaac Espitia Cardozo

## Licencia
Este proyecto fue creado con fines academicos.
