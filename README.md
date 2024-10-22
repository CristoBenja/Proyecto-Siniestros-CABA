Los accidentes de tránsito son una de las tragedias más cotidianas y, sin embargo, más devastadoras de nuestra sociedad.
En un abrir y cerrar de ojos, una vida puede cambiar para siempre, ya sea para aquellos que sufren directamente
las consecuencias o para las familias que quedan con un vacío irreparable. Cada año, miles de personas pierden
la vida en incidentes viales, y aún más quedan con lesiones que impactan su calidad de vida. Lo que podría ser
un simple trayecto cotidiano se transforma en un evento con consecuencias trágicas. Los accidentes no discriminan,
afectando a todas las edades y clases sociales, y se presentan en las formas más diversas: desde el choque de un auto,
una colisión entre una motocicleta y un camión, hasta el atropello de un peatón que cruzaba la calle.

<br>

El impacto de estas tragedias va más allá de las estadísticas, porque detrás de cada número hay una historia, 
un rostro, un nombre. Los accidentes de tránsito dejan un rastro de dolor y desolación en las comunidades,
además de un coste económico significativo para los sistemas de salud y de seguridad. En el fondo, nos obligan
a reflexionar sobre la fragilidad de la vida y la importancia de la prevención y la seguridad vial.
Pero también nos llevan a preguntarnos: ¿cómo podemos entender mejor estas tragedias para prevenirlas? 
¿Cómo podemos convertir los datos fríos en soluciones que protejan a las personas?

<br>

Con estas preguntas en mente, emprendí un proyecto de análisis y estudio de los accidentes de tránsito, 
utilizando Python para llevar a cabo un proceso de extracción, 
transformación y carga (ETL) de datos, seguido de un análisis exploratorio de datos (EDA). Mi objetivo fue 
procesar y analizar la información de CABA sobre siniestros viales para identificar patrones, factores 
de riesgo y áreas críticas que demandan especial atención.

<br>

Este gráfico índica que la mayoría de accidentes ocurre en las fechas de agosto, noviembre y diciembre. Pero, esto
necesariamente no ímplica que en determinados meses ocurran más accidentes.

<br>

![image](https://github.com/user-attachments/assets/a3e8ed03-9113-4e85-8e3c-b17cacba2334)

<br>

Este gráfico sigiente, se podría decir que es la refutación del anterior, demostrando que no hay (al menos con los datos que se 
tiene) una relación de la cantidad de accidentes por mes.

<br>

![image](https://github.com/user-attachments/assets/ae26f1f8-e5ad-4c1b-9bfc-d3bfaac40667)

<br>

Otra cosa que en la que presté suma antención, eran la cantidad de accidentes que ocurren en las intersecciones 
Esto nos da que pensar y podriamos tomar medidas al respecto. Por ejemplo, puede que falten semáforos, 
o es que acaso las personas no prestan atención al cruzar. Aún no sabemos demasiado, pero, tenemos una pista y 
ya sabemos donde enfocar una parte de la atención.

<br>

![image](https://github.com/user-attachments/assets/2477ec7f-2153-4eb3-a071-435cb49170c9)

<br>

Luego, pensé detenidamente si el tipo de calle estaría relacionado con los incidentes y, basta con ver el gráfico 
para entender.

<br>

![image](https://github.com/user-attachments/assets/36fccdcb-c1b2-4818-baaf-1a267a648eb2)

Con esto, pensé que quizá estas avenidas  tenían las calles rotas o estaban mal iluminadas, quizá falta de semáforos.
Sin importar cual sea la razón, se puede ver claramente que alli es donde ocurren la mayoría de accidentes.

<br>

También se me pasó por la cabeza ¿Puede deberse más accidentes a la edad?

<br>

![image](https://github.com/user-attachments/assets/fe210148-3d36-4907-9ce0-b323b3e19832)

<br>

Cabe recalcar, que estás personas son las que perdieron su vida en el accidente y no por ello tenían que estar 
conduciendo, podrían haber sido peatones varios de ellos. Aún así, se observa que la mayoría de accidentados son
de 18 a 29, 30 a 39 y mayores de 60. Una conclusión a la que llegué fue pensar que a la edad de 18 a 29 se tienen las
hormonas aún, un poco más sensibles y quizá los lleva a cometer ciertas cosas que otras personas estarían más atentos.
De los 30 a los 39, se me ocurre que en esas edades una persona ya cuenta con su propio móvil y es posible que entonces,
la mayoría de las personas sean de dicha edad y por ello también sería lógico pensar que al ser más, son más los 
accidentes de ellos. Y las personas con más de 60, creo que puede deberse a la facultades reducidas, 
por ejemplo, en su salud.

<br><br>

Hay muchos más datos que pueden verse a través de este repositorio. Aquí solo doy varios puntos clave,
pero agradecería que puedan tomarse el tiempo de leer sobre este estudio que he hecho.

<br><br>

Después de esta etapa de análisis, di el siguiente paso en mi estudio: trasladar los hallazgos y conclusiones 
a una plataforma más accesible y visual como Power BI. Con esta herramienta, logré presentar la información de 
una manera clara y concisa, permitiendo a cualquier persona observar de manera intuitiva cómo evolucionan los 
accidentes a lo largo del tiempo, cómo se distribuyen geográficamente, y cuáles son los indicadores más relevantes 
que debemos monitorear.

<br><br>

Mi esperanza es que este análisis y los conocimientos derivados de él contribuyan, aunque sea mínimamente,
a la toma de decisiones más informadas en el ámbito de la seguridad vial. Porque, aunque no podemos devolver
la vida a quienes ya la han perdido en accidentes de tránsito, sí podemos trabajar para que sus historias no 
se repitan. Este estudio es un llamado a la acción, una invitación a entender mejor la compleja dinámica de los
siniestros viales para que, algún día, podamos vivir en un entorno donde la tragedia de los accidentes sea cada
vez menos frecuente y, algún día inexistentes.

<br><br>

Trabajo realizado por: Cristo Benjamín Morales Saucedo
