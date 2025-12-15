# metodos_2025B_house_prices
Proyecto Métodos Numericos:  predicción de precios de viviendas usando regresión lineal

En este apartado se mostrara el avance técnico del proyecto, cuyo objetivo esla implementación del modelo hedónico para la predicción del precio de viviendas usando Métodos de Mínimos Cuadrados 

Para las primeras pruebas del código se ha dedicido hacer de forma matricial pero esta no sera definitiva se estudiara como se comporta el código con esta forma de presentarlo:

Minimizar || A·x − b ||²

Lo cual conduce al sistema normal de ecuaciones:

Aᵀ · A · x = Aᵀ · b

Donde "A" es la matriz de caracteristicas (Variables que ya acordamos en el avance anterior estan seran 10 a utilizar)
"B" es la matriz columna que denotara los precios reales esta columna esta nombrada como SalePrice
"X" es la matriz columna de coeficientes del modelo 

Para la resolucción del sistema se usara metódos como eliminación Gaussiana y Gauss-jordan 

Algunos de los criterios de parada seran la convergencia del error y el numero máximo de iteraciones.
