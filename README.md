# __ARREGLO DE ANTENAS PARCHE MICROCINTA CON PERFIL DE PATRÓN DE RADIACIÓN COSECANTE CUADRADO__ // _MICROSTRIP PATCH ANTENNA ARRAY WITH COSECANT-SQUARED RADIATION PATTERN PROFILE_
## ACERCA DE ESTE PROYECTO // _ABOUT THIS PROJECT_ 
Las __ANTENAS TIPO PARCHE__ se basan en la tecnología microcinta. Su uso tiene un gran auge para aplicaciones en las que el tamaño reducido es importante como, por ejemplo: la aviación, aeronáutica, satélites, aplicaciones en misiles, dispositivos móviles, comunicaciones inalámbricas en general y trabajan mayormente en las frecuencias de microondas y ondas milimétricas.  
 
En este informe se plantea el __diseño de dos modelos de antena parche (con inset y sin inset)__ los dos modelos se implementan con acoplador de impedancias lambda/4. Se desarrolla el análisis de las dimensiones de la antena así mismo como sus parámetros de reflexión S11, frecuencia de resonancia, ancho de banda, impedancia real e imaginaria, directividad y ganancia de la antena, por último, los patrones de radiación.  

![An_patch_noinset](Git_Images/An_patch_noinset.png)
### Antena parche sin inset

![An_patch_inset](Git_Images/An_patch_inset.png)
### Antena parche con inset 

Este diseño de antenas parche será posteriormente utilizado para elaborar un arreglo de antenas parche que en este paper se __plantea como primera medida un arreglo 1x2__, optimizando el número de antenas del arreglo, donde se espera obtener un patrón de radiación de cosecante cuadrado. Finalmente una vez se analiza el comportamiento del arreglo 1x2, se desarrolla el __análisis y diseño de antenas 8x2__ y se comparan los resultados con el paper escogido en cuanto a sus parámetros. Para la implementación de un arreglo de antenas parche se tienen las siguientes caracteristicas de radiación:
* Ancho de banda de 1,93 GHz
* Radiación en la frecuencia X – de 8 a 12 GHz
* Ganancia pico de 14,95 dBi
* Polarización lineal

![An_patch_2x1](Git_Images/An_patch_2x1.png)
### Antena parche 2x1
![An_patch_8x2](Git_Images/An_patch_8x2.png)
### Antena parche 8x2
![Rad_Pat](Git_Images/Rad_Pat.png)
### Patro de Radiacion
  
# Referencias // _Referencess_
* [UWB Microstrip Antenna Based on Circular Patch Topology with Stepped Feedline and Partial Ground Plane](https://ieeexplore.ieee.org/document/6237932)
* [A Design Rule for Inset-fed Rectangular Microstrip Patch Antenna](https://www.researchgate.net/publication/228897496_A_design_rule_for_inset-fed_rectangular_microstrip_patch_antenna) 
* [Inset Feed Microstrip Patch Antenna](https://ijcsmc.com/docs/papers/February2016/V5I2201662.pdf)
* [Microstrip patch antenna array with cosecant-squared radiation pattern profile](https://doi.org/10.1016/j.aeue.2019.05.003)
