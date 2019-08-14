# Limpieza de datos
## Data cleaning
Usaremos pandas para la limpieza de datos. (Yo) usaré spyder como IDE. 
## Data frame
Un dataset es un fichero. Al cargarlo en python se convierte en un data frame. Los datasets pueden estar en csv, xls, txt, etc. en csv el delimitador es la coma, de ahí el nombre (CSV. Comma separated values). Para ver cuál es el delimitador lo mejor es intentar abrir el archivo como texto plano y echarle un vistazo. 
[repo con datasets](https://github.com/joanby/python-ml-course)
Muy util que los datasets tengan un archivo descriptor de lo que significa cada variable, así como las unidades, por ejemplo. 
`import pandas as pd`
`data = pd.readcsv('nombre_archivo')`

Tiene un muchos parámetros extra de entrada a parte del nombre del archivo. ME salto la clase. 



Los datos tambien pueden ser cargados A MANO, con la función open. 



'titanic = pd.read_excel("path")'

Creación de un csv o excel: funciones tocsv y toexcel

titanic.to_csv("path.csv")
titanic.to_excel("path.xlsx")

También funciona con json 


Las funciones básicas de resumen, estructura, dimensiones y cabecera.


