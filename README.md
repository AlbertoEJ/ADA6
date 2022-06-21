# Proyecto 6
Alumno: Alberto Espinosa Juárez

Programa Académico: Maestría en Ciencias de la Computación

## ¿Qué contiene el proyecto 6?
Dado un grafo, y utilizando pygame, generar una visualización del mismo. 
Force-directed: calcula la disposición de un grafo mediante el algoritmo de equilibrio de fuerzas de Fruchterman y Reigold (1991). O(n^2)


Los archivos que contiene la carpeta "Proyecto_06" son: 
+ nodo.py Archivo que contiene la clase que define a un nodo y sus métodos
+ arista.py Archivo que contiene la clase que define a una arista y sus métodos
+ grafo.py y archivos para cada algoritmo. Archivos que contienen la clase que define a un grafo y sus métodos, además, contiene los algortimos descritos para el proyecto 1 y contiene los algoritmos DFS (recursivo e iterativo) y BFS, correspondientes al proyecto 02, así como Dijkstra para el proyecto03 y KruskaID, KruskalI y Prim para el proyecto 4. Así como el método método Spring del proyecto 5 y lo correspondiente al proyecto 6.
+ main.py Archivo que contiene la generación y guardado de cada uno de los grafos, tanto los generados como los calculados.
+ Carpeta imagenes que contiene las imágenes correspondientes a la generación del método Force-directed


## ¿Cómo veo la documentación?
Para revisar la documentación es necesario hacer uso del método *help(método)* que nos brindará información sobre cómo y qué hace un método.

**Ejemplo**

help(guardar_grafo)

**Desplegará información sobre el método guardar_grafo así como también de los parámetros que recibe**

## Resúmen del proyecto 6

### Modelo de malla 100 nodos
![Grafo en malla de 100 nodos][malla1]
Video: Video: https://drive.google.com/file/d/1KKF82fRr_alO0EFVbrT71E4C6x38E_Rb/view?usp=sharing

[malla1]: https://github.com/AlbertoEJ/ADA6/blob/main/img/malla_100_nodos.png

### Modelo de malla 500 nodos
![Grafo en malla de 500 nodos][malla2]
Video: Video: https://drive.google.com/file/d/1YeOCi0VL38AeaqHilo390VNJPTiBWMaD/view?usp=sharing

[malla2]: https://github.com/AlbertoEJ/ADA6/blob/main/img/malla_500_nodos.png

### Modelo de Gilbert de 100 nodos y probabilidad de 0.02
![Grafo en gilbert de 100 nodos][gilbert1]
Video: Video: https://drive.google.com/file/d/12PTSlQvrNDs_cEPBPvUFBBDDU5ZAAC7H/view?usp=sharing

[gilbert1]: https://github.com/AlbertoEJ/ADA6/blob/main/img/gilbert_100_noos.png

### Modelo de Gilbert de 500 nodos y probabilidad de 0.002
![Grafo en gilbert de 500 nodos][gilbert2]
Video: Video: https://drive.google.com/file/d/1eYwp3YjsN_ti7VvkhXCUnnAU73sFpIG4/view?usp=sharing

[gilbert2]: https://github.com/AlbertoEJ/ADA6/blob/main/img/gilbert_500_noos.png

### Modelo de Erdos y Renyi de 100 nodos y 200 aristas
![Grafo en erdos y renti de 100 nodos][renyi1]
Video: Video: https://drive.google.com/file/d/1c16QPWdLnWQZ3PE-IOynvMGueS6XY8fA/view?usp=sharing

[renyi1]: https://github.com/AlbertoEJ/ADA6/blob/main/img/erdos_100_nodos.png

### Modelo de Erdos y Renyi de 500 nodos y 600 aristas
![Grafo en erdos y renti de 500 nodos][renyi2]
Video: Video: https://drive.google.com/file/d/1-BG5YbuYvEa49WO6mBOnHroaqf31KuG9/view?usp=sharing

[renyi2]: https://github.com/AlbertoEJ/ADA6/blob/main/img/erdos_500_nodos.png

### Modelo de Babarasi-Albert de 100 nodos y grado 10
![Grafo en babarasi-albert de 100 nodos][babarasi]
Video: Video: https://drive.google.com/file/d/1CFD2tGsfg9ngn6YcxvfvUj5S_mJYAFHv/view?usp=sharingg

[babarasi]: https://github.com/AlbertoEJ/ADA6/blob/main/img/babarasi_100_nodos.png

### Modelo de Babarasi-Albert de 500 nodos y grado 10
![Grafo en babarasi-albert de 500 nodos][babarasi2]
Video: Video: https://drive.google.com/file/d/1VVM4AH58BnCvrmlNknOKn8WOm2cBA5_c/view?usp=sharing

[babarasi2]: https://github.com/AlbertoEJ/ADA6/blob/main/img/dorogovtsev_500_nodos.png

### Modelo de Geográfico de 100 nodos y r=0.21
![Grafo en geografico de 100 nodos][geografico]
Video: Video: https://drive.google.com/file/d/1pa19ZweUS6DEVa0h7we-1ZrBie8AKydp/view?usp=sharing

[geografico]: https://github.com/AlbertoEJ/ADA6/blob/main/img/geografico_100_nodos.png

### Modelo de Geográfico de 500 nodos y r=0.93
![Grafo en geografico de 500 nodos][geografico2]
Video: Video: https://drive.google.com/file/d/1MnnMLwWi9Q1dWjbel8VOwyIr7Iy4Repy/view?usp=sharing

[geografico2]: https://github.com/AlbertoEJ/ADA6/blob/main/img/geografico_500_nodos.png

### Modelo de Dorogovtsev_mendes de 100 nodos
![Grafo en Dorogovtsev_mendes de 100 nodos][Dorogovtsev_mendes]
Video: Video: https://drive.google.com/file/d/1vXFSnIQdX7QADHSKpRdQwvnWc5otO3Ov/view?usp=sharing

[Dorogovtsev_mendes]: https://github.com/AlbertoEJ/ADA6/blob/main/img/dorogovtsev_100_nodos.png

### Modelo de Dorogovtsev_mendes de 500 nodos
![Grafo en Dorogovtsev_mendes de 100 nodos][Dorogovtsev_mendes2]
Video: Video: https://drive.google.com/file/d/1WV4avFqtbw31AtiiVNvTiqH_9KtAm9f7/view?usp=sharing

[Dorogovtsev_mendes2]: https://github.com/AlbertoEJ/ADA6/blob/main/img/dorogovtsev_500_nodos.png

