# Mercado laboral argentino con datos de la EPH

Serie de análisis sobre la presión en el mercado laboral argentino, con foco en Gran Córdoba, a partir de los microdatos de la Encuesta Permanente de Hogares (EPH) del INDEC. Empezó con una pregunta que escuché muchas veces en Córdoba: ¿qué está pasando en el mercado laboral, que hay mil postulaciones para una sola vacante?

## Notebooks

| Notebook | Qué analiza | Período |
|---|---|---|
| [`01_la_foto.ipynb`](01_la_foto.ipynb) | La presión hoy en Gran Córdoba y en el total del país: quién busca, para qué, por qué no encuentran trabajo e informalidad | 1er trimestre 2026 |
| [`02_la_pelicula.ipynb`](02_la_pelicula.ipynb) | Cómo cambió la presión en el país, en las regiones y en Gran Córdoba | 1er trimestre 2017–2026 |
| `03_cordoba.ipynb` (próximamente) | Qué hay detrás de la suba en Gran Córdoba | 1er trimestre 2017–2026 |

## Hallazgos principales

- En Gran Córdoba, 39 de cada 100 personas en el mercado laboral están buscando empleo, contra 24 en el total de los aglomerados. La diferencia viene de quienes ya trabajan y buscan otro empleo.
- En el país, la presión hoy está en niveles parecidos a los de 2017, pero cambió quién busca: hay menos desocupados y más ocupados que buscan otro empleo.
- Cuyo, Noreste y Pampeana tienen hoy más presión que en 2017. En la región Pampeana, la suba se explica por Gran Córdoba, que pasó de 28 a 39.
- En Gran Córdoba, 6 de cada 10 personas que trabajan y buscan otro empleo quieren sumar un trabajo, no cambiar el que tienen.

## El indicador

**Presión** = (desocupados + ocupados que buscan otro empleo) / PEA, ponderado con `PONDERA`.

Es la parte activa del indicador de presión que publica el INDEC, que además suma a los ocupados que estarían disponibles para trabajar más aunque no estén buscando. Cada resultado se presenta con su margen de error al 95%.

## Datos

Encuesta Permanente de Hogares (EPH) del INDEC, base individual, primer trimestre de cada año de 2017 a 2026.
Las bases se descargan de https://www.indec.gob.ar/Institucional/Indec/BasesDeDatos

## Cómo correrlo

1. Descargar las bases y descomprimirlas dentro de una carpeta `datos/`, al lado de los notebooks.
2. Instalar las librerías: `pip install -r requirements.txt`
3. Abrir el notebook y ejecutar todas las celdas.

## Publicaciones

- La foto: [link al post]
- La película: [link al post]

## Autora

Soledad Salcedo, economista y data analyst. [LinkedIn](https://www.linkedin.com/in/soledadsalcedo)
