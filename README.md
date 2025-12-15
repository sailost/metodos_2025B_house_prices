# metodos_2025B_house_prices
Proyecto Métodos Numericos:  predicción de precios de viviendas


En este apartado se mostrara el avance técnico del proyecto, cuyo objetivo esla implementación del modelo hedónico para la predicción del precio de viviendas usando Métodos de Mínimos Cuadrados 

Para las primeras pruebas del código se ha dedicido hacer de forma matricial pero esta no sera definitiva se estudiara como se comporta el código con esta forma de presentarlo:

Minimizar || A·x − b ||²

Lo cual conduce al sistema normal de ecuaciones:

Aᵀ · A · x = Aᵀ · b

Donde "A" es la matriz de caracteristicas (Variables que ya acordamos en el avance anterior estan seran 10 a utilizar)
"B" es la matriz columna que denotara los precios reales esta columna esta nombrada como SalePrice
"X" es la matriz columna de coeficientes del modelo 

Para la resolucción del sistema se usara metódos como eliminación Gaussiana y Gauss-jordan 

Algunos de los criterios de parada seran la convergencia del error y el numero máximo de iteraciones, sin embargo al ver esta forma tentativa parece complicar innecesariamente podria descartarse



Otra opcion de resolucion que estamos analizando es la siguiente:

El modelo se planteara de forma matricial, donde se relaciona el precio de venta de las viviendas con las variables seleccionadas mediante un modelo lineal.

Se formula a partir de la minimización del error cuadrático entre los valores reales y los valores estimados del precio de las viviendas, lo que conduce al sistema normal de ecuaciones asociado al Método de Mínimos Cuadrados. En este planteamiento, la matriz A representa las variables seleccionadas, el vector b corresponde a los precios reales (SalePrice) y el vector x contiendra los coeficientes del modelo

Para la resolución del sistema resultante, se utilizaran tecnicas de álgebra lineal, apoyasdose en herramientas computacionales que permitan obtener los coeficientes de manera directa, sin recurrir a metodos iterativos ni procedimientos mas avanzados 
