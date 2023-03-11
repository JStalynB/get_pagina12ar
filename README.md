# Análisis de sentimientos 
Las noticias que leemos a diario deben de ser neutrales por lo que se me vino a la idea a la cabeza, "¿de verdad las noticias son neutrales?" Siempre hay malas noticias en el mundo por lo que lo lógino sería que las noticias solo lleven malas noticias, pero de la misma forma los periodistas como personas profesionales nos deben de dat noticas que sean neutrales, el estudio realizado con 185 noticias quitando la neutralidad el 90% es negativo, ahora podemos ver otros resultados llegando a las siguientes conclusiones:  


<p align="center">
  <img src="https://user-images.githubusercontent.com/105129458/224512967-0c8e2ba8-2f25-4265-9f5c-e17ec931ea1b.png" />
</p>

hemos utilizado un modelo pre-entrenado de Vader, que nos ha permitido etiquetar cada una de las palabras del resumen con una polaridad positiva, negativa o neutra, y a partir de ello, hemos calculado la puntuación de sentimiento global para cada resumen, y títulos.

Con esta información, hemos analizado la distribución de los sentimientos en los resúmenes y hemos podido identificar que la mayoría de los artículos tienen una polaridad negativa o neutra, y solo unos pocos tienen una polaridad positiva.



<p align="center">
  <img src="https://user-images.githubusercontent.com/105129458/224513172-ea84f4ca-4b43-451d-ab86-d5b06e666c52.png" />
</p>
Si bien cierto el 85% de la noticia que leemos es neutral sólo un 0.5% de las noticias son positivas 
lo que podemos estar seguros es que al menos los títulos de las noticias son neutrales con 95.4% de los títulos de las noticias  

### data
get data of "pagina12.ar", all data was recopiled by me  


data of 9 march 2023
in this csv exist:
 - es Autor(muchos no tienen) 
 - fecha 
 - titulo 
 - subtiítulo 
 - resumen 
 - tags 
 
 
 
 it is all automated, to extract the data any day in the future
 the information recopilated is on data 
 you just need download this code and run ;)
 install pip, python 
