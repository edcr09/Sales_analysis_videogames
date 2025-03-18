# Sales_analysis_videogames
DA-5 Analisis de datos de ventas y califiaciones de videojuegos
Descripción: Identificar patrones que determinen si un juego es exitoso o no
Objetivo: Detectar proyectos prometedores y planificar campañas publicitarias

Datos de la tienda online Ice que vende videojuegos por todo el mundo. Las reseñas de usuarios y expertos, los géneros, las plataformas (por ejemplo, Xbox o PlayStation) y los datos históricos sobre las ventas de juegos están disponibles en fuentes abiertas.
Se requiere identificar patrones que determinen si un juego tiene éxito o no.
Objetivo: Detectar proyectos prometedores y planificar campañas publicitarias.
Hay datos que se remontan a 2016. En este contexto es diciembre de 2016 y se planea una campaña para 2017.
El dataset contiene la abreviatura ESRB. The Entertainment Software Rating Board (la Junta de clasificación de software de entretenimiento) evalúa el contenido de un juego y asigna una clasificación de edad como Adolescente o Adulto.
El dataset contiene las siguientes columnas:
•	Name: Nombre del juego
•	Platform: Plataforma o consola del juego
•	Year_of_Release: Año de lanzamiento del juego
•	Genre: Género del juego
•	NA_sales: Ventas del juego en America del Norte (Millones de USD)
•	EU_sales: Ventas del juego en Unión Europea
•	JP_sales: Ventas del juego en Japón
•	Other_sales: Ventas del juego en otras regiones
•	Critic_Score: Calificación de la crítica
•	User_Score: Calificación de los usuarios
•	Rating: Clasificación del juego

Se conservaron los valores nulos y se pasaron al formato adecuado NaN
Se convirtieron los tipos de datos de acuerdo con el contenido de cada columna
Actividades destcadas realizadas:
•	Ventas totales por año
•	Ventas de cada plataforma por año
•	Ventas totales por plataforma
•	Se realizaron gráficos de barra, de dispersión, histograma y diagrama de caja
•	Promedios de venta por plataforma
•	Determinar correlación de las reseñas, tanto de la crítica como de los usuarios, con las ventas, en el caso del 3DS
•	Comparar las ventas de 3DS vs los mismos juegos de 3DS en otras plataformas,
•	Distribución de los juegos por género
•	Determinar un perfil de usuario para cada región (NA, EU, JP) con genero y rating por región, ligados a las ventas.
•	Realización de pruebas de hipótesis con la prueba T

Conclusion general

El periodo que se determinó para tomar datos es de 2012 a 2016 porque está posterior al auge de plataformas de los 2000 y empiezan a aparecer consolas sucesoras que definiran las nuevas tendencias para el futuro, lo cual es útil para el objetivo del análisis.
A lo largo del periodo evaluado, se observa como llega el auge de las ventas de videojuegos a finales de la de decada de los 2000s y en la primera mitad de la decada de los 2010s se va acentuando el declive de estas, aunque hay plataformas sucesoras de las anteriores que van estabilizandose y pronto deifinirán una tendencia en la que vuelvan a un auge de ventas, estas son para el caso de Xbox One y PS4, las mas actuales en el set de datos, junto con la PC que de igual manera conforme avanzan los avances tecnológicos estás van adquiriendo mas capacidades, lo que las hace factibles para tener capacidad para soportar mayores exigencias de las que demandan los usuarios de videojuegos, así como otros factores externos que pueden tener relación como el auge de plataformas de ventas digitales y plataformas de streaming que en 2016 van ganando popularidad.

En el caso de Nintendo sus ventas se estan yendo a la baja, necesitan renovarse, tal vez alguna nueva plataforma que pueda hacer frente a las sucesoras actuales de Microsoft y Sony. También se observa que en el resto del mundo las consolas portatiles ya no son tan relevantes como las de sobremesa, excepto en Japón, que estas plataformas todavia tienen ventas relevantes. No convendría apostarle tanto a titulos para plataformas portatiles en otras regiones fuera de Japón pero tampoco dejarlas abandonadas.
Para determinar el éxito de un juego en general, independiente de la región, de acuerdo con el análisis de ventas de 2012 a 2016, debería tener estas características:
•	Estar en plataformas modernas como PS3, Xbox 360, Xbox One, PS4 principalmente, incluso también 3DS (sobre todo en Japón)
•	Ser de estos géneros: Acción, Disparos, Deportes y Juegos de Rol

Es importante mencionar que los scores de la critica y los usuarios no tienen mayor efecto las ventas, por lo que no es un aspecto muy relevante a considerar.

También sería interesante traer al PC la compatibilidad con los titulos populares y promover campañas en plataformas web de streaming para los titulos en las plataformas que se busca generar un interés en los usuarios finales. Otra plataforma que no se contempla aquí y puede ser un área de oportunidad es el smartphone a través de aplicaciones que pueden darle un segundo aire a titulos antiguos y apelar a la nostalgia, en una modalidad freemium, app gratis con compras dentro de la app.
