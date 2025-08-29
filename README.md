# BayesianOptimizationwithSpline
Nella repository sono contenute le funzioni  f_1,f_2,f_8,f_18,f_21 bbob. Con algoritmo presentato, e plot delle varie iterazioni

Ogni codice presenta la funzionalità di plottare le funzioni con la logica riportata, questa sarà carattersticamente il primo codice di ogni jupyter notebook. Mentre l'ultimo sarà il codice usato per salvare i vari risultati coi seed diversi.

Si crea il potenziale problema che andando a moltiplicare l'arcotangente per numeri troppo piccoli, si rischia semplicemente di andare a creare un fattore scalare. Infatti per x<<1, arctg(x) si comporta come x. Per questo una buona scala può essere composta secondo me da un fattore moltiplicativo moderato (5) e aspettare con le varie iterazioni che quest'ultimo diminuisca. Altrimenti si rischia che tutto il peso che viene dato alla varianza viene semplicemente "mangiato" dal fattore moltiplicativo presente nell'arctg.
