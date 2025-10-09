##  Ruptures
Este archivo muestra unos análisis que s epueden hacer con esta librería
es de analissi de series de tiempo y sirve para identificar ciertos cambios en la tendencia
vienen varias configuraciones para ver cambios pequeños y crisis
sirve mas que nada como análisis
## Paper 7 categorías
es un intento de replica de un paper llamado Clustering and classification of time series using topological data analysis
es un codigo de clasificacion creando embeddings con las series de tiempo de diferentes tickers y tratar d eclasificarlos respecto a la industria
tiene ciertas modificaciones, lo primero fue un intento medio fallido, pero despues logré ciertas modificaciones para que funcione bien, 
usé todos los tickers del s&P500
## Indice aleatorio
es literalmente como crear nuestro S&P pero con menos tickers, fueron muchos hechos de manera aleatoria y muestra los resultados
de como quedó cada indice financiero, sorprendentemente la mayoria le gana al S&P500 en un año, 
aunque es de esperarse ya que el S&P tiene tantos que se suaviza mucho y por eso es seguro, mientras que los demás pueden ser muy volátiles
## Mapper creacion indice financiero
Es usar el medoto de TDA Mapper, para cre cree por su cuenta diferentes indices, ya que mapper hace clusters, es decir grupos, por lo que hice que hicera estos clusters
y cada cluster sería un indice, llégo a una ganancia mucho mayor que los aleatorios, pero esto también se puede deber a que hizo indices más pequeños y demás
por lo que quiero poner una condicion en el análisis de que solo cuente los que tienen cierto numero tickers
## Analisis indice combinación v3
ignoren ese, hice varios de estos codigos en este doc y los acomodé en lso demás, por lo que no importa mucho pero aun no lo borro porque me quiero asegurar de que esté lo importante



# impormación importante o util, dentro des estos codigo
hay partes en las qu emotré como sacar la lista del s&P500 de una pagina, e incluso viene con los pesos de cada empresa en el índice, pero no es tan necesaria porque también tengo como calcularlo
ciertas partes también tienen métricas interesantes que podrían usar
