# Bike-Sales-Analytics
## Spanish
<p>Este es un proyecto guiado, tomado del canal de Youtube de Alex The Analyst. Puedes consultarlo aquí: https://www.youtube.com/watch?v=opJgMj1IUrc&list=PLUaB-1hjhk8Hyd5NiPQ9CND82vNodlFF5&index=7. <br>
El propósito de este dashboard es visualizar y analizar las ventas de bicicletas utilizando variables clave como ingresos, edad, distancia de desplazamiento, entre otros factores. Fue desarrollado tanto en Excel como en Power BI.
</p>

<h3>Proceso de limpieza y transformación de los datos en Excel:</h3>
<ul>
  <li>Se eliminaron registros duplicados.</li>
  <li>Se completaron las abreviaturas en las columnas Marital Status y Gender (por ejemplo, 'S' y 'M' se reemplazaron por 'Single' y 'Married', respectivamente; 'F' y 'M' por 'Female' y 'Male') con ayuda de la herramienta Reemplazar.</li>
  <li>Se creó una nueva columna llamada Age Brackets, segmentando a los clientes según su edad con la siguiente lógica: =SI(L2>54;"Old";SI(L2>=31;"Middle Age";SI(L2<31;"Adolescent";"Invalid")))</li><br>
    Esto clasifica a los clientes en:
    <ul>
      <li>Adolescent: menores de 31 años</li>
      <li>Middle Age: entre 31 y 54 años</li>
      <li>Old: mayores de 54 años</li>
    </ul>
</ul>

<h3>Visualizaciones creadas:</h3>
<ul>
      <li>Promedio de ingresos por compra, segmentado por género (gráfico de columnas agrupadas).</li>
      <li>Cantidad de bicicletas compradas según el grupo de edad del cliente (gráfico de líneas).</li>
      <li>Cantidad de bicicletas compradas según la distancia de desplazamiento (gráfico de líneas).</li>
</ul>

<h3>Filtros interactivos incluidos:</h3>
<ul>
      <li>Estado civil</li>
      <li>Región</li>
      <li>Nivel educativo</li>
</ul>
<p>Estos filtros permiten una exploración más dinámica y detallada de los datos.</p><br>

<b>Este proyecto es parte de mi proceso de aprendizaje y práctica en análisis de datos. ¡Gracias por leer!</b>

## English
<p>This is a guided project based on a tutorial from Alex The Analyst's YouTube channel. You can watch the original video here: https://www.youtube.com/watch?v=opJgMj1IUrc&list=PLUaB-1hjhk8Hyd5NiPQ9CND82vNodlFF5&index=7. <br>
The purpose of this dashboard is to visualize and analyze bike sales using key variables such as income, age, commute distance, among others. The dashboard was developed using both Excel and Power BI.
</p>

<h3>Data Cleaning and Transformation in Excel:</h3>
<ul>
  <li>Duplicate records were removed.</li>
  <li>Abbreviated values in the Marital Status and Gender columns were replaced (e.g., 'S' and 'M' became 'Single' and 'Married'; 'F' and 'M' became 'Female' and 'Male') with the help of Replace tool.</li>
  <li>A new column called Age Brackets was created to group customers by age using the following logic: =IF(L2>54,"Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adolescent","Invalid")))
</li><br>
    This categorizes customers into::
    <ul>
      <li>Adolescent: under 31 years old</li>
      <li>Middle Age: between 31 and 54 years old</li>
      <li>Old: over 54 years old</li>
    </ul>
</ul>

<h3>Visualizations Included:</h3>
<ul>
      <li>Average income per purchase, segmented by gender (clustered column chart).</li>
      <li>Number of bikes purchased by customer age group (line chart).</li>
      <li>Number of bikes purchased by commute distance (line chart).</li>
</ul>

<h3>Interactive Filters:</h3>
<ul>
      <li>Marital Status</li>
      <li>Region</li>
      <li>Education Level</li>
</ul>
<p>These slicers allow for a more dynamic and detailed exploration of the data.</p><br>

<b>This project is part of my learning journey in data analysis. Thanks for reading!</b>

<h3>Dashboard in Excel:</h3>

![image](https://github.com/user-attachments/assets/f73aa206-6b46-49f8-bad5-aba84e7b1ee5)

<h3>Dashboard in Power BI:</h3>

![image](https://github.com/user-attachments/assets/f764329e-fef6-4b0c-a3a9-837142ce7d73)

