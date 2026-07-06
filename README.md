Análisis Comparativo: LDA vs QDA
Este proyecto tiene como objetivo explorar y comparar el desempeño de dos modelos de clasificación estadística: Análisis Discriminante Lineal (LDA) y Análisis Discriminante Cuadrático (QDA), utilizando el conjunto de datos de vino (Wine dataset).

Cómo ejecutar el proyecto
Para ejecutar el código, tienes dos opciones principales:

Opción 1: Google Colab (Recomendado)
Haz clic en el siguiente enlace para abrir el cuaderno directamente en Google Colab:
Abrir en Google Colab (Nota: Sustituye JUANJOSEINIGUEZ por tu nombre de usuario de GitHub si es diferente).

Una vez en Colab, ve al menú Entorno de ejecución > Ejecutar todas.

El dataset se cargará automáticamente desde la librería scikit-learn, por lo que no necesitas descargar archivos adicionales.

Opción 2: Localmente (Jupyter Notebook)
Clona este repositorio en tu computadora:
git clone [[https://github.com/JUANJOSEINIGUEZ/analisis-discriminante-lda-qda_IniguezRuizJuanJose.git](https://github.com/JUANJOSEINIGUEZ/analisis-discriminante-lda-qda_IniguezRuizJuanJose.git)](https://colab.research.google.com/drive/1aUNHc8krq_DT08biFb3dZhtqV6QPMnSS#scrollTo=fQVTxJ0v5a4p)

Instala las dependencias necesarias:
pip install -r requirements.txt

Abre el archivo .ipynb utilizando Jupyter Notebook o VS Code.

Principales hallazgos
Tras la implementación y comparación de los modelos en el cuaderno, se obtuvieron las siguientes conclusiones:

Comportamiento de los modelos: El modelo LDA generó fronteras de decisión lineales, demostrando ser altamente eficiente y menos propenso al sobreajuste al simplificar la relación entre variables.

Flexibilidad: El modelo QDA permitió una mayor flexibilidad al utilizar matrices de covarianza individuales para cada clase, logrando fronteras de decisión cuadráticas que se adaptan mejor a la distribución real de los datos cuando estos no comparten varianza.

Resultados predictivos: Ambos modelos mostraron un desempeño sólido, aunque QDA tiende a ser más preciso en conjuntos de datos donde la heterogeneidad de las clases es evidente.

Limitaciones: Se concluyó que, mientras LDA es robusto incluso con muestras limitadas, QDA requiere un mayor número de observaciones para estimar correctamente los parámetros adicionales de las matrices de covarianza sin caer en errores de generalización.

Aplicabilidad: Ambos métodos resultan herramientas fundamentales en la ciencia de datos por su base estadística clara y su capacidad para interpretar cómo las variables predictoras influyen en la clasificación de las clases.
