# tabla de contenido
[introduccion](#introduccion)
[instalcion y requisitos](#instalcion-y-requisitos)
[estructura del proyecto](#estructura-del-proyecto)
[uso y Ejecución](#uso-y-ejecución)
[Datos y Fuentes](#Datos-y-Fuentes)
[concluciones](#concluciones)
[autores](#autores)

# introduccion

este proyecto tiene como objetivo analizar las telecomunicaciones de argentina haciendo un enfasis en las tecnologias y velocidades de internet a las que acceden las personas, utilizando tecnicas de data analitics se busca generar informacion que ayude a mejorar la toma de deciciones estrategicas de cara al futuro

# instalcion y requisitos

### requisitos:
- Python 3.7 o superior
- pandas
- matplotlib
- seaborn
- power BI

### Pasos de instalación:

Clonar el repositorio: git clone https://github.com/Miguel-David-Llanos-Lopez/PI-2-henry
Crear un entorno virtual: python -m venv venv
Activar el entorno virtual:
Windows: venv\Scripts\activate
macOS/Linux: source venv/bin/activate
Instalar las dependencias:
pip install pandas
pip install matplotlib
pip install seaborn

# Estructura del proyecto

- data/entrada: estan los archivos utilizados para realizar el ETL y posterior EDA
- data/salida: se encuentran los archivos limpios, estos mismos son los que se usaron para crear el dashboard
- notebooks: se encuentra el archivo donde se realizo el ETL y el EDA
- analisis.pbix: este es el dashboard
- readme.md: es el archivo de documentacion del proyecto

# uso y Ejecución
1) Para ejecutar el EDA, abrir el notebook EDA.ipynb en la carpeta notebooks/.
2) El notebook guiará a través de las diferentes etapas del análisis, incluyendo carga de datos, la limpieza de los mismos y las visualizaciones.
3) para ver un analisis interactivo abrir el archivo analisis.pbix

# Datos y Fuentes
Los datos utilizados en este proyecto provienen de [enacom](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Findicadores.enacom.gob.ar%2FFiles%2FDatos_Abiertos%2FInternet.xlsx&wdOrigin=BROWSELINK). Los datos incluyen información sobre la cantidad de accesos a internet por cada 100 personas y hogares, los accesos por velocidad y tecnologia entre otros. El archivo se encuentra en la carpeta data/entrada en formato xlsx.<br>
los datos creados y transformados para poder visualizarlos en power BI estan en la carpeta data/salida 

# concluciones

Ha habido una tendencia al aumento accesos a internet a lo largo del pais se cree que la pandemia pudo influyo en ese aumento, pero se puede observar la tendencia desde el 2014 con un aumento significativo desde el 2016. <br> <br>

aunque en el 2014 la tecnogia mas usada era el ADSL desde el 2020 el cable modem es la tecnologia mas usada y a fecha del 2023 la fibra optica es la segunda mas usada a nivel nacional y aunque la cantidad de usuarios de ADSL ha disminuido todavia lo usa una parte importante de la poblacion <br> <br>

con respecto a la distibucion geografica de las velcidades categorias se ve una concentracion de la cantidad de personas con velocidades de internet superiores a 30 Mbps en caba, buenos aires y las provincias aledañas se cree que esto es porque hay una mayor poblacion en esos lugares ademas de un mayor cantidad de conecciones por hogar. <br>
ademas si lo comparamos con la cantidad de personas con velocidades de 1 a 6 Mbps hay un comportamiento similar pero cabe resaltar que hay una mayor cantidad de personas con acceso a esa velocidad a lo largo del pais y ademas hay una reduccion significativa de las personas que utilizan esas velocidades en los ultimos años

# autores

proyecto realizado por Miguel Llanos <br>
gmail: llanoslopezmigueldavid@gmail.com