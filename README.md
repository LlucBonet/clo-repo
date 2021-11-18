# CLO-REPO
Repositorio para la asignatura optativa CLO-Cloud and Big Data del grado de Ingeniería Informática en la UCM

## Carpeta Asgmt1
Contiene 5 ejercicios que implementan diferentes patrones de diseño de MapReduce.  
Cada ejercicio contiene:
  - Un script con los comandos para ejecutar el ejercicio en la shell
  - Scripts en Python con los mapper y reducer necesarios
  - Fichero con los datos de entrada


### Ejercicio 1  
Develop a distributed version of the grep tool to search for words in very large documents. 
Use the design patterns explained in class. The output should be the lines that contain a given word. 

### Ejercicio 2
Develop a MapReduce job to find the frequency of each URL in a web server log.
Use the design patterns explained in class. The output should be the URLs and their frequency. 

### Ejercicio 3
Write a MapReduce job to calculate the average daily stock price at close of Alphabet Inc. (GOOG) per year since 2009. 
Use the design patterns explained in class. The output should be the year and the average price. 

### Ejercicio 4
Develop a MapReduce job to show movie ids with an average rating in the ranges:  
- Range 1: 1 or lower  
- Range 2: 2 or lower (but higher than 1)  
- Range 3: 3 or lower (but higher than 2)  
- Range 4: 4 or lower (but higher than 3)  
- Range 5: 5 or lower (but higher than 4)  
Use the design patterns explained in class. The job should have two MapReduce phases.
The output of the first phase should be the movie ids and their average rating. The output of the second phase should be ranges and the movie’s ids. 

### Ejercicio 5
 Table Meteorite_Landings.csv (downloaded from https://data.nasa.gov/Space-Science/Meteorite-Landings/gh4g-9sfh) 
 consists of 34,513 meteorites and includes fields like the type of meteorite, the mass and the year.  
  
Write a MapReduce job to calculate the average mass per type of meteorite. Use the design patterns explained in class.  
Preprocess the Meteorite_Landings.csv file to remove the header and do some data cleansing work.
