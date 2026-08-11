# Dashboard de Búsqueda de Empleo

Dashboard web para organizar mi búsqueda de empleo en minería y gestión de agua.
Ingeniería Civil Hidráulica · ~3 años de experiencia.

## Cómo funciona

- `index.html` — el dashboard (página web, sin backend).
- `empleos.csv` — la "base de datos". Cada fila es una oferta o postulación.

El dashboard lee el CSV y muestra tarjetas con buscador, filtros por estado/área/match,
contadores y un botón directo para ir a postular.

## Actualizar las ofertas

Edita `empleos.csv` (en GitHub: botón lápiz ✏️ → editar → Commit). Columnas:

| columna   | valores |
|-----------|---------|
| empresa   | texto |
| cargo     | texto |
| ubicacion | texto |
| area      | ej. Minería / Agua, Hidráulica / Consultoría |
| estado    | Por postular · Postulado · Entrevista · Rechazado · Oferta |
| fecha     | AAAA-MM-DD |
| link      | URL directa a postular |
| notas     | texto libre |
| match     | Alto · Medio · Bajo |

Al guardar en GitHub, Vercel vuelve a publicar el sitio automáticamente en ~20 segundos.

## Publicado en

Vercel: _(pega aquí tu URL cuando esté desplegado)_
