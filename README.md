# [Comparador de hipotecas españolas (octubre 2026)](https://hipotecas.arredon.do)

Simulador de hipotecas bonificadas: tipo fijo, variable o mixto, bonificaciones por productos vinculados con condiciones de los principales bancos españoles, y comparativa del ahorro frente al coste de cada combinación de productos.

Es una única página HTML sin dependencias: abre `index.html` en el navegador. Disponible en:

- https://arredond.github.io/hipotecas/
- https://hipotecas.arredon.do

## Condiciones de los bancos

`bancos.json` guarda, para cada banco, sus fuentes (`fuentes`: una por cada documento del que salen las cifras, con su enlace, la fecha de los datos —para una web, el día en que se consultó; para un PDF, la fecha del documento— y, si hay varias, qué datos aporta cada una), el resumen de lo publicado (`fuente`), el tope de bonificación, las comisiones de cuenta y los productos (bonificación en p.p., coste anual en €, requisitos, grupos de productos excluyentes y primas únicas). La página no lo lee: `PRESETS` en `index.html` es una copia, así que al actualizar un banco hay que cambiar ambos.

**Aviso:** no hay ninguna garantía de que la información mostrada sea actual ni correcta. Las condiciones de los bancos cambian con frecuencia y las primas de los seguros son estimaciones. Es una herramienta orientativa, no asesoramiento financiero: confirma siempre las condiciones con la entidad (FEIN).
