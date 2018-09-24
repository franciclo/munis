# Comentarios a Páginas de Municipios del Conurbano

Este fue el proyecto final para el curso de Data Science de Digital House.
La idea fue recolectar comentarios en las páginas públicas de Facebook de los Municipios para analizarlos que categorías se podían encontrar.
El procesamiento de los comentarios fue usando la técnica de bolsa de palabras posterior a una limpieza que dejo solo las letras, además se aplico stemming para maximizar la cantidad de terminos repetidos. Luego se aplico tf-idf para armar una matriz que describiera la frecuencia de los terminos en cada comentario.
Finalmente se uso LDA para encontrar las categorías.
