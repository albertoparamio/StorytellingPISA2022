# Storytelling PISA 2022

## 1. Descripción General

Este proyecto, desarrollado en un notebook de Jupyter, tiene por objeto generar **nueve datasets** que servirán como base para la creación de otras tantas visualizaciones interactivas en la plataforma *Flourish.com*. El análisis se centra en los datos del informe PISA 2022 (Programme for International Student Assessment), con el propósito de identificar patrones educativos relevantes mediante el uso de narrativas visuales. El trabajo forma parte de la asignatura *Visualización de Datos* del Máster en Ciencia de Datos Aplicada de la Universitat Oberta de Catalunya (UOC), correspondiente al segundo trimestre del curso académico 2024–2025.

## 2. Tabla de Contenidos

- [Descripción General](#1-descripción-general)
- [Motivación](#3-motivación)
- [Requisitos](#4-requisitos)
- [Instalación](#5-instalación)
- [Estructura del Proyecto](#6-estructura-del-proyecto)
- [Uso](#7-uso)
- [Resultados Destacados](#8-resultados-destacados)
- [Licencia](#9-licencia)
- [Autor](#10-autor)
- [Fuentes de Datos](#11-fuentes-de-datos)

## 3. Motivación

La motivación de este trabajo es la realización de la **segunda parte de la práctica de la asignatura de visualización de datos**. Para ello se escogió la base de datos del informe PISA 2022 que elabora la OCDE. El estudio PISA es una referencia internacional para evaluar el rendimiento académico de los estudiantes de 15 años. Este proyecto busca descubrir historias detrás de los datos mediante técnicas de visualización efectivas, destacando desigualdades educativas por país, género, estatus socioeconómico o actitud frente al aprendizaje.

## 4. Requisitos

- Python 3.8+
- Jupyter Notebook
- Bibliotecas:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

## 5. Instalación

1. Clona este repositorio o descarga los archivos.
2. Crea un entorno virtual (opcional pero recomendado):

```bash
python -m venv venv
source venv/bin/activate  # En Linux/macOS
venv\Scripts\activate     # En Windows
```

## 6. Estructura del Proyecto

```plaintext
PR2_code/
├── storytelling_PISA.ipynb         # Notebook principal del proyecto
├── README.md                       # Descripción del proyecto
├── requirements.txt                # Dependencias del entorno Python
├── data/                           # Dataset original del estudio PISA 2022
│   └── dataset_pisa_2022.csv
├── datasets_export/                # Datasets generados para las visualizaciones
│   ├── V1_medianas_por_pais_todas_variables.csv
│   ├── V2_motivacion_matematicas_genero.csv
│   ├── V3_motivacion_vs_rendimiento_muestra.csv
│   ├── V4_status_vs_science_muestra.csv
│   ├── V5_motivacion_vs_rendimiento_por_pais.csv
│   ├── V6_matriz_grupos_vs_paises.csv
│   ├── V6_rendimiento_nativos_vs_inmigrantes_con_region.csv
│   ├── V7_indices_bullying_por_pais.csv
│   ├── V8_proactividad_vs_rendimiento.csv
│   └── V9_promedios_por_pais_repetidor_no_repetidor.csv
└── .ipynb_checkpoints/             # Carpeta interna de Jupyter (ignorable)
```

## 7. Uso

1. Abre storytelling_PISA.ipynb en Jupyter.
2. Ejecuta las celdas paso a paso.
3. Lee las explicaciones y observa las visualizaciones generadas.
4. Puedes modificar filtros y parámetros para explorar diferentes aspectos del dataset.

## 8. Resultados Obtenidos

A lo largo del desarrollo del proyecto se han generado nueve (9) datasets derivados del análisis del informe PISA 2022. Cada uno de estos conjuntos de datos está diseñado para alimentar una visualización específica en la plataforma Flourish.com, enfocada en diferentes dimensiones del rendimiento académico, el contexto socioeconómico o las actitudes estudiantiles.

Los datasets exportados están disponibles en la carpeta `datasets_export/` y se describen brevemente a continuación:

1. **V1_medianas_por_pais_todas_variables.csv**  
   Contiene las medianas de diversas variables educativas por país, como base para un análisis comparativo general.

2. **V2_motivacion_matematicas_genero.csv**  
   Explora las diferencias de motivación hacia las matemáticas entre estudiantes de distintos géneros.

3. **V3_motivacion_vs_rendimiento_muestra.csv**  
   Relaciona el nivel de motivación académica con el rendimiento en pruebas, en una muestra representativa.

4. **V4_status_vs_science_muestra.csv**  
   Analiza el vínculo entre el estatus socioeconómico (ESCS) y el rendimiento en ciencias.

5. **V5_motivacion_vs_rendimiento_por_pais.csv**  
   Permite observar cómo se correlacionan motivación y rendimiento en diferentes países.

6. **V6_matriz_grupos_vs_paises.csv**  
   Agrupa estudiantes por características específicas para visualizar su distribución entre países.

7. **V6_rendimiento_nativos_vs_inmigrantes_con_region.csv**  
   Compara el rendimiento académico entre estudiantes nativos e inmigrantes, incluyendo segmentación regional.

8. **V7_indices_bullying_por_pais.csv**  
   Presenta indicadores de acoso escolar (bullying) desglosados por país.

9. **V8_proactividad_vs_rendimiento.csv**  
   Examina si existe relación entre la proactividad del estudiante y sus resultados académicos.

10. **V9_promedios_por_pais_repetidor_no_repetidor.csv**  
    Compara el rendimiento medio entre estudiantes repetidores y no repetidores, por país.

## 9. Licencia

Este proyecto está licenciado bajo los términos de la **Licencia Pública General GNU v3.0**.

Esto significa que tienes libertad para usar, estudiar, modificar y compartir este proyecto, siempre que mantengas la misma licencia en cualquier trabajo derivado. No se otorgan garantías. Para más información, consulta el texto completo de la licencia en el archivo [LICENSE](./LICENSE) o en:  
[https://www.gnu.org/licenses/gpl-3.0.html](https://www.gnu.org/licenses/gpl-3.0.html)

## 10. Autor

**Alberto Paramio Galisteo**  
Estudiante del Grado en Ciencia de Datos Aplicada  
Universitat Oberta de Catalunya (UOC)  
Curso 2024–2025  
📧 aparamio@uoc.edu

## 11. Fuentes de Datos

Los datos utilizados en este proyecto provienen del estudio internacional PISA 2022, desarrollado por la Organización para la Cooperación y el Desarrollo Económicos (OCDE). Este estudio evalúa el rendimiento académico de estudiantes de 15 años en matemáticas, lectura y ciencias, así como variables contextuales y actitudinales.

- **Fuente principal:**  
  [OCDE – Base de datos PISA 2022](https://www.oecd.org/pisa/data/2022database/)

- **Licencia de uso de los datos:**  
  Los datos están disponibles públicamente para fines de análisis, educación e investigación, bajo las condiciones establecidas por la OCDE.

## 12 Visualización interactiva

Puedes explorar la visualización de los resultados en Flourish aquí:

👉 [Ver en Flourish](https://public.flourish.studio/story/3156918/)

