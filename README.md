# Proyecto-4---EDA-con-Python
**Tabla de Contenidos**
1. Descripción
2. Requisitos
3. Instalación
4. Estructura del Proyecto
5. Resultados y conclusiones
6. Próximos pasos
7. Contribuciones
8. Licencia

**1. Descripción**
Este proyecto tiene como objetivo la realización y automatización con python de un análisis exploratorio de datos realizado sobre una base de datos de una campaña de marketing de una institución financiera.
Las instituciones financieras recurren con frecuencia a campañas de marketing. El éxito de estas campañas depende de múltiples factores: el perfil socioeconómico del cliente, el momento del contacto, el número de interacciones previas o el canal utilizado, entre otros. Este análisis exploratorio de datos se ha centrado en tratar de entender cuál es el perfil de cliente de aquellos clientes que al final acabaron suscribiendo un producto en esta institución financiera.
Este proyecto toma como punto de partida un dataset de una campaña de marketing de una institución bancaria y aplica técnicas de Análisis Exploratorio de Datos (EDA) para comprender la estructura de los datos, detectar anomalías, descubrir relaciones entre variables y extraer conclusiones que puedan orientar futuras decisiones de negocio.

**2. Requisitos**
*Software*
Python 3.1

*Librerías*
pandas
numpy
datetime
matplotlib
seaborn

**3. Instalación**

Antes de comenzar, asegúrate de que los siguientes requisitos se cumplen:
- Instalación funcional de Visual Studio Code.
- Instalación de las extensiones de VSC de Jupyter Notebook y Python.

Ejecución de las consultas:  
1. Asegúrate de que el fichero se abre en formato Jupyter. (.ipynb)
2. Instala Python y su extensión en VSC
3. Importa el archivo con los scripts de Python creados.
4. Ejecuta los scripts

**4. Estructura del Proyecto**
Proyecto 4 EDA con Python/
│
├── Original_data/                        # Datos originales sin modificar
│   └── bank-additional.csv
│   └── customer-details.xlsx
│
├── Clean_data/                  # Datos procesados en sus distintas versiones
│   ├── data_limpio.csv        # Tras la fase de limpieza
│   ├── data_transformado.csv  # Tras la fase de transformación
│   └── data_definitivo.csv        # Dataset listo para el análisis
│
├── Jupyters/                    # Notebooks con el flujo completo del proyecto
│   ├── 1_Prework.ipynb         # Exploración inicial y configuración
│   ├── 2_Limpieza.ipynb         # Tratamiento de nulos, duplicados y outliers
│   ├── 3_Transformacion.ipynb   # Transformación de columnas de datos para su posterior análisis
│   └── 4_EDA.ipynb              # Análisis Exploratorio de Datos y visualizaciones
│
└── README.md                    # Documentación del proyecto

**5. Resultados y conclusiones**
El proyecto llevado a cabo ha permitido desarrollar mis habilidades de analista de datos utilizando python. Esto garantiza que he obtenido un mayor conocimiento de lectura y comprensión de Pythonn además de una habilidad para desarrollar EDAs en dicho lenguaje de programación. 
A la vez, veo muy aplicables los conocimientos adquiridos a lo largo de este proyecto que tanto tiempo me ha llevado en mi actual trabajo y a futuros facilitando mi dia a dia laboral. 

**6. Próximos pasos**
El presente proyecto se considera concluido en relación a su objetivo principal original de aprender a desarrollar EDAs utilizando Pyhon.
Sin embargo, de proseguir con su desarrollo, se sugiere como próximos pasos el refinamiento y mejora de los scripts ya creados con el objetivo de crear scripts más robustos y efectivos.
Este enfoque proporcionaría una mejora notable a los scripts ya creados, ayudando a cualquier futuro usuario del fichero a un uso más fácil y veloz de los scripts en sus propósitos. 

**7. Contribuciones**
Las contribuciones son bienvenidas. Por favor abra un issue primero para discutir los cambios que deseas realizar.
