# CDA_2
Ciencia de datos aplicada Taller2

Apoyo del Banco Mundial a países en desarrollo.<br>
Estrategia elebaorada por:<br>
Oscar Duvan Giraldo Romero  &nbsp; &nbsp;&nbsp; &nbsp;&nbsp;  202324939   <br>  

Estructura de carpetas:<br>
Taller_2 <br>
├── RegresionLinealBM.ipynb<br>
├── InformeEjecutivoBancoMunial.pdf<br>
└── Archivos<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── gapminder_final.csv (Datos utilizados como input para el entrenamiento del modelo) <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── dictionary.txt (Diccionario con el detalle de la explicación de cada variable utilizada en el entrenamiento)<br>

El archivo con extension .pdf contienen la interpretacion del taller asi:
- Informe Ejecutivo BancoMunial: Contiene el desarrollo del taller, como se indicó en bloque Neon, asi como la interpretación de datos de este Notebook, interpretación de los errores y las estrategias seleccionadas para el entrenamiento del modelo, asi como las politicas propuestas para mejorar un crecimiento en economia y desarrollo.

Para el Notebook RegresionLinealBM.ipynb, este carga el archivo de la carpeta Archivos, que comparten los valores del dataset seleccionado para realizar el entrenamiento y analisis de resultados.

El cuaderno contiene se divide en las siguientes fases:
  * Cargue de datos.
  * Analisis Univariado para las variables internetuserate, lifeexpectancy, breastcancerper100th, relectricperperson, urbanrate.
  * Analisis bivariado donde se añade una nueva columna con el continente de acuerdo al pais.
  * Entrenamiento de un primer modelo.
  * Entrenamiento del modelo con normalización
  * Supuestos.
