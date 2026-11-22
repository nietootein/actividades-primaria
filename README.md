# Actividades de primaria

Actividades interactivas para repasar en casa (5.º de primaria, Comunidad de Madrid).

## Publicar en GitHub Pages
1. Sube el contenido de esta carpeta a un repositorio nuevo (por ejemplo `actividades-primaria`).
2. En el repositorio: **Settings → Pages → Deploy from a branch**, rama `main`, carpeta `/ (root)`.
3. La web quedará en `https://TU-USUARIO.github.io/actividades-primaria/`.

Enlace a la web actual [aquí](https://nietootein.github.io/actividades-primaria/).

## Añadir una actividad
1. Nombra el archivo `asignatura-recurso-NN.html` (por ejemplo `mates-recurso-01.html`). Asignaturas: `lengua`, `mates`, `naturales`, `sociales` e `ingles`.
2. Súbelo a la raíz del repositorio.
3. Añade una línea a la lista `RECURSOS` de `index.html`, indicando el curso (`curso:5`).

La numeración es por asignatura y no se repite aunque en el futuro haya varios cursos (por ejemplo, si `lengua-recurso-01` es de 5.º, la siguiente actividad de Lengua será `lengua-recurso-02`, sea del curso que sea).

## Recursos
| Archivo | Curso | Asignatura | Título |
|---|---|---|---|
| lengua-recurso-01.html | 5.º | Lengua | Academia de Dragones |
| mates-recurso-01.html | 5.º | Matemáticas | La Noche de los Números |
| naturales-recurso-01.html | 5.º | Ciencias de la Naturaleza | El Laboratorio de las Mil Especies |
| sociales-recurso-01.html | 5.º | Ciencias Sociales | La Fábrica de los Paisajes |

## Informe para la familia o el profesorado
Cada actividad tiene, en su pantalla principal, el botón **«Informe para tu familia o tu profe»**. El informe muestra:

- Actividad, fecha del informe, fecha desde la que hay datos registrados, número de sesiones y fechas de la primera y la última.
- Zonas completadas y logros conseguidos.
- Porcentaje de aciertos al primer intento, en total y por zona.
- **Conviene repasar**: en Lengua y Matemáticas, los conceptos con menos del 70 % de aciertos (mínimo, 2 retos); en Ciencias de la Naturaleza y Ciencias Sociales, las mesas o salas con menos del 70 % (mínimo, 3 retos) y los enunciados de los retos más fallados.

Se puede **compartir** (menú del dispositivo), **copiar como texto** o **imprimir / guardar en PDF**. El texto para el alumno o la alumna usa la forma elegida al empezar; el informe para el adulto está redactado en lenguaje neutro.

Los datos del informe se guardan solo en el navegador (`localStorage`), en una clave propia (`…-informe`) que no modifica el progreso del juego. No se envía nada a ningún servidor. Desde el propio informe se pueden borrar sus datos sin tocar el progreso.

## Licencia
© 2026 NietooteiN. Estas actividades se publican bajo la licencia [Creative Commons Atribución/Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es).

Puedes usarlas, copiarlas y adaptarlas siempre que:
- **Cites la autoría:** «Actividades de primaria, por NietooteiN, CC BY-NC-SA 4.0».
- **No las uses con fines comerciales.**
- **Compartas tus adaptaciones con la misma licencia.**

El texto legal completo está en el archivo [LICENSE](LICENSE).
