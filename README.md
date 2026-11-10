# Actividad 6 — Dashboard de modelos de IA notables

Dashboard interactivo del análisis multivariante (PCA y k-medias) sobre
1.078 modelos de IA notables (Epoch AI, 1950–2026), elaborado para la
Actividad 6 de la Fase 3 de la Maestría en IA de la Universidad de La Salle.

**Ver:** <https://arherrera-lasalle-dev.github.io/actividad6-dashboard/>

## Qué muestra

- Biplot PC1–PC2 con los tres clústeres y las cargas de las variables activas.
- Cargas y varianza explicada (PC1 90,3 %, PC2 7,4 %).
- Perfiles de clúster en parámetros, cómputo y año.
- Composición por acceso, organización y dominio.
- Residuos del modelo M4 por clúster, con Kruskal–Wallis recalculado.
- Quince pruebas de hipótesis de las Actividades 5 y 6.
- Tabla filtrable y exportación PNG/CSV.

Filtros por año, dominio, organización y acceso. El dashboard es un único
archivo HTML con Plotly incrustado: no usa servidor, CDN ni conexión.

## Datos

Epoch AI, *Notable AI Models* (CC BY 4.0), snapshot congelado con SHA-256
`22bf8ee5f39e4cd85056f5ddd20a10aa6499a8e1ebdcc8bf7de936a97e7b9101`.
El análisis es observacional: describe asociaciones, no relaciones causales.

## Autoría

Ariel David Herrera Ahumada y José Arquímedes Soto Montaña.
Maestría en IA, Universidad de La Salle, noviembre de 2026.

El archivo `index.html` es la copia publicada de `docs/index.html` del proyecto
de la Actividad 6; se genera con `scripts/07_dashboard_html.py`.
