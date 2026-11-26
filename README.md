# Tablero del Comité Oncológico de Coloproctología · HGGB

Tablero de una sola página con la carga de trabajo, el perfil de los casos, las decisiones del comité y la calidad del registro del Comité Oncológico de Coloproctología del Hospital Clínico Regional Dr. Guillermo Grant Benavente (Servicio de Salud Concepción). Elaborado por Data Bless.

**Datos.** La página lee en vivo el Google Sheet del comité mediante un servicio de Apps Script (dirección en `fuente.js`). Ese servicio entrega solo cifras resumidas: no entrega nombres, RUT, ficha, fechas exactas ni edades exactas, y el Sheet sigue siendo privado. Si el servicio no responde, la página muestra la copia de los datos que trae incluida y lo indica en «Fuente».

**Archivos.** `index.html` (tablero con la copia de respaldo), `fuente.js` (dirección del servicio en vivo) y `.nojekyll` (publicación tal cual en GitHub Pages).
