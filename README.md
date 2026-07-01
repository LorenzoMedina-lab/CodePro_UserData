# CodePro_UserData
# Análisis de Actividad de Usuarios

## Descripción

Este proyecto corresponde a un desafío de análisis de datos cuyo objetivo es evaluar la calidad de un conjunto de datos de actividad de usuarios, detectar inconsistencias, realizar un proceso de limpieza y obtener métricas que permitan tomar decisiones basadas en evidencia.

El análisis fue desarrollado en Python utilizando un Jupyter Notebook.

---

## Objetivos

- Explorar el dataset.
- Detectar datos inconsistentes.
- Limpiar y normalizar la información.
- Separar registros inválidos en un conjunto Quarantine.
- Calcular métricas descriptivas y de engagement.
- Analizar la actividad de los usuarios.
- Generar visualizaciones.
- Proponer decisiones de producto respaldadas por los datos.

---

## Tecnologías utilizadas

- Python 3
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Estructura del proyecto

```
├── product_activity.csv
├── analisis.ipynb
├── clean_product_activity.csv
├── quarantine_product_activity.csv
├── metrics_summary.csv
└── README.md
```

---

## Proceso realizado

El proyecto se desarrolló siguiendo las siguientes etapas:

1. Carga y exploración del dataset.
2. Validación de tipos de datos.
3. Conversión de fechas.
4. Recalculo de `days_since_signup`.
5. Normalización de valores categóricos.
6. Creación del conjunto Quarantine.
7. Generación del Dataset Core.
8. Elaboración del Data Quality Report.
9. Cálculo de métricas descriptivas.
10. Análisis de engagement.
11. Análisis de concentración y temporalidad.
12. Visualización de resultados.
13. Conclusiones y propuestas de mejora.
14. Exportación de archivos finales.

---

## Archivos generados

Al finalizar el análisis se generan los siguientes archivos:

| Archivo | Descripción |
|----------|-------------|
| `clean_product_activity.csv` | Dataset limpio utilizado para el análisis. |
| `quarantine_product_activity.csv` | Registros excluidos junto con el motivo de exclusión. |
| `metrics_summary.csv` | Resumen de las principales métricas de calidad de datos. |

---

## Cómo ejecutar el proyecto

1. Clonar el repositorio.

```bash
git clone <url-del-repositorio>
```

2. Ingresar a la carpeta del proyecto.

```bash
cd nombre-del-proyecto
```

3. Instalar las dependencias.

```bash
pip install pandas matplotlib notebook
```

4. Abrir el notebook.

```bash
jupyter notebook
```

5. Ejecutar todas las celdas en orden.

---

## Autor

**Lorenzo Medina**
Penguin Academy
Proyecto desarrollado como parte de un desafío práctico de análisis de datos.
