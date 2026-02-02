# Acerca de mi
Con 8 años de experiencia en el mercado laboral, soy Economista y Financiera, estudiando para certificarme como Análista de Datos, con experiencia en extracción, limpieza, modelado de datos y visualizaciones.
Identifico patrones y genero genero insights accionables que optimizan procesos que aportan y mejoran decisiones.

Este repositorio de Github fue creado para mostrar proyectos que he desarrollado con el fin de demostrar mis habilidades en analisis de datos y el uso de las diversas herramientas tecnicas que he usado. Resaltando mi capacidad análitica ppara aplicar a problemas empresariales reales, aportando valor a los negocios.

## Habilidades Tecnológicas
- SQL (PostgreSQL)
- Python (Pandas, Matplotlib, Seaborn), Jupyter Notebook, Google Colab
- Excel, Power Query
- Power Bi

## Contactame
* LinkedIn: 
* Correo

***
# Proyectos

## 1. Movilidad Urbana vs Productividad Económica en LATAM  
Variables: PIB Per Capita, tiempo de demora en el tráfico, año:2024
Objetivo: Entender la relacion entre la movilidad urbana y la productividad económica de las ciudades de latinoamerica, para poder invertir en insfraestructura de trasporte. 
Preguntas:  ¿Qué ciudades de America Latina presenta alta congestion de tráfico? ¿Qué ciudad de America Latina presenta alta y baja productividad económica? 

### Herramientas utilizadas
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23357ebd.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![NumPy](https://img.shields.io/badge/NumPy-%23357ebd.svg?style=for-the-badge&logo=scipy&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de cohortes](https://img.shields.io/badge/Análisis_de_cohortes-295F98?style=for-the-badge)
![Visualizacion de datos](https://img.shields.io/badge/Visualización_de_datos-295F98?style=for-the-badge)
![Estadística Descriptiva](https://img.shields.io/badge/Estadística%20Descriptiva-295F98?style=for-the-badge&logo=chart&logoColor=white)

### Proceso 
Comencé con una limpieza preliminar a cada una de las fuentes, partiendo de entender como estan compuestas cada uno de los datasets, estandarizar los nombresde las columnas, corregir los formatos numéricos y de fechas de las variables, filtrar por el año de conveniencia, 2024. Se calcula el promedio de las métricas más relevantes del tráfico. Se unifica a traves de las claves (ciudad y año) los datasets y posteriormente se generan visualizaciones gráficas de relacionamiento entre economía y tráfico.

### Concluciones
* la mayoria de las ciudades latinoamericanas tienen un PIB promedio entre 5000 y 15000 USD, aun asi hay ciudades con un PIB superior, es decir que hay una amplia variedad de desarrollo económico, urbano o de productividad local.
* la mayoría de las ciudades tienen un rango moderado de congestión, con un sesgo hacia valores altos. La ciudad con má retraso en minutos provocados por el trafico es la Ciudad de México con 2833.05m y en segundo puesto estaría Sao Paulo 
* No hay una correlación estricta entre las variables PIB y Minutos de demora. Al revisar México ciudad de mayor demora en tráfico, es el segundo país con mejor PIB en latinoamerica; en cambio, Montevideo, ciudad con mejor PIB, no tiene un nivel significativo de tráfico; por otro lado, revisamos que Bogotá tiene un nivel promedio de PIB pero con un nivel promedio alto de demora en tráfico.
* Bogotá y Sao Paulo deben de ser ciudades prioritarias para inversión en infraestructura de transporte dado los altos niveles de congestión vehicular y bajos indicadores de productividad económica.
  
### Visualizaciones
1. **BoxPlot Minutos de Demora en el Tráfico**
Se identifica que hay sesgo hacia valores alto dado a que la mediana esta por debajo de la media (tringulo verde) y los bigotes se extienden a valores muy altos, outliers.
La mayoria de las ciudades tienen una congestión de rango moderado porque estan dentro del recuadro azul y el rombo negro me dice que debe haber al menos una ciudad con una congestión muy alta.   
  <img width="511" height="465" alt="Boxplot JamsDelay" src="https://github.com/user-attachments/assets/94f4991f-c495-4937-b57d-f52c23c77d4a" />

2. **Histograma Distribución de la Economía**
El promedio per capita es de 13,253.60 USD,es decir que la mayoria de las ciudades tienen un PIB entre 5000 y 15000 USD y hay pocas ciudades con un alto nivel de PIB.
Se puede ver una amplia variedad de desarollo economico, urbano o de productividad local entre las ciudades.
  <img width="830" height="482" alt="Histograma PIBperCapita" src="https://github.com/user-attachments/assets/d430593e-9ec1-4268-81f8-c6cd96cefb60" />
  
3. **Grafico de Barras: PIB vs Retraso de Tráfico**
El PIB no es la variable explicativa que buscamos para entender porque se da la congestion en las ciudades latinoamericanas, no estan estrictamente correlacionadas.
<img width="593" height="515" alt="Barras PiBvsTrafico" src="https://github.com/user-attachments/assets/ad1cfc7b-3d73-4f04-b779-e7ce9b1b8939" />

