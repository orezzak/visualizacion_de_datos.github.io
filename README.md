

# Analisis Clubes y Jugadores

A través de las visualizaciones expuestas a lo largo de este informe trataremos despejar y aclarar algunas ideas preconcebidas sobre el mundo del futbol. El objetivo es arrojar un poco de conocimiento sobre el rendimiento de los jugadores, así como de sus respectivos clubes

* **Tipologia de los datos:** Estructurados , csv
* **Origen de los datos:** [zenodo](https://zenodo.org/record/5758756#.YdsWhmDMKUl)
* **Tematica:** Cualidades y atributos de los jugadores de futbol en el año 2019.

# 1.Histograma

* **Codigo fuente:** [Jupyter script](https://zenodo.org/record/5758756#.YdsWhmDMKUl)

Antes de empezar veamos que distribución sigue la variable de puntuación global en todo el conjunto de datos.

![image](https://user-images.githubusercontent.com/93130320/148691519-51a5b2d7-a6b0-41f0-9eeb-e09e1881ef66.png)

Observamos que parece que sigue una distribución normal (campana de gauss). Tal y como se puede apreciar la mayoría de los jugadores tienen una puntuación entre 40 y 50

# 2.Grafico de cajas

* **Codigo fuente:** [Jupyter script](https://zenodo.org/record/5758756#.YdsWhmDMKUl)

Existe cierta tendencia a pensar que los jugadores zurdos son mejores que los diestros. Vamos a hacer uso de un diagrama de bigote para analizar esta afirmación.

![image](https://user-images.githubusercontent.com/93130320/148691661-9d77caf0-50ee-4f58-8652-0301257972ab.png)

Tal como se puede apreciar la media de los atributos de los jugadores zurdos supera a la de los diestros. Llama especialmente la atención la elevada diferencia en el lanzamiento de faltas.

# 3.Diagrama de dispersion

* **Codigo fuente:** [Jupyter script](https://zenodo.org/record/5758756#.YdsWhmDMKUl)

Otra afirmación bastante extendida es que para tener un mejor regate hay que tener un buen control del balón y en detrimento de otras cualidades físicas como la aceleración o la velocidad.
Vamos a analizar la correlación entre los atributos "Dribbling" y "Ball_Control".

![image](https://user-images.githubusercontent.com/93130320/148691819-b8d16b44-9601-46cf-a47c-be7cb2052209.png)

En este caso podemos ver que existe una correlación clara, cuanto más control de balón se tenga mejor será la habilidad de regate.

# 4.Diagrama de densidad

* **Codigo fuente:** [Jupyter script](https://zenodo.org/record/5758756#.YdsWhmDMKUl)

Como regla general siempre se ha pensado que los jugadores más altos deben jugar de defensas. Por otro lado, también ha cambiado la tendencia a un tipo de portero más alto.

![image](https://user-images.githubusercontent.com/93130320/148691922-b4785b72-a56c-4378-b744-87385ae6583a.png)

Observamos que para la posición de defensa central (CB - Center Back) sobre 190cm se concentra la mayor densidad de jugadores , de forma análoga sucede con los porteros (GK) pero en este caso con una densidad ligeramente superior

# 5.Grafico de araña

* **Codigo fuente:** [Jupyter script](https://zenodo.org/record/5758756#.YdsWhmDMKUl)

Existe una tendencia a pensar que los jugadores brasileños son mejores por el mero hecho de su procedencia. 
Vamos a comparar los jugadores de origen brasileño con los de origen español.

![image](https://user-images.githubusercontent.com/93130320/148692154-d036aa21-3dde-4d53-964f-52d02de62e88.png)

![image](https://user-images.githubusercontent.com/93130320/148692160-252c6b3e-0293-46eb-b79c-398973d728b1.png)

Tal y como se puede apreciar, ambas telas de araña dibujan una figura parecida, de modo que no se puede afirmar que los jugadores de origen brasileño son mejores que el equipo nacional. Hay que destacar que dicho análisis se basa en el origen del jugador y no en equipo de la selección.

# 6.Diagrama de burbujas

En lo que respecta a los equipos, vamos a someter a análisis a los principales clubes europeos para analizar su capacidad de ataque,defensa y balance (Ataque--> Defensa)

* **Plataforma de visualizacion:** [Flourish](https://public.flourish.studio/visualisation/8342962/)

# 7.Mapa de conexiones

Una afirmación también comúnmente extendida es la diferencia de estrategia deportiva seguida por Real Madrid y F.C. Barcelona. Se suele afirmar que mientras el Real Madrid ficha a jugadores europeas el  F.C. Barcelona prefiere talentos de Latinoamérica.

* **Plataforma de visualizacion:** [Flourish](https://public.flourish.studio/visualisation/8343379/)
