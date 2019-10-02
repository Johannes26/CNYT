# CNYT Ciencias naturales y tecnologia
## Proyecto 1: Calculadora de Complejos, 8 Sep 2019, Johan Stiven Guerrero Pineda

El siguiente proyecto realiza la funcion de una calculadora de complejos, el codigo esta implementado en python, y cada entrada y salida de numeros complejos esta determinada por tuplas donde la primera componente es la parte real y la segunda la parte imaginaria

## FUNCIONALIDADES
## 1. Las siguientes funcionalidades se encuentran disponibles para numeros complejos ya sea operaciones binarias como la suma  o unarias como el modulo.

- Suma
- Resta
- Producto
- División
- Módulo
- Conjugado
- Conversión entre representaciones polar y cartesiano

## 2. Las siguientes funcionalidades se encuentran disponibles para vectores complejos.
- Suma de vectores
- Inversa de vectores
- Multiplicacion escalar de vectores
- Norma de un vector
- Distancia entre dos vectores
- Producto interno de vectores

## 3. Las siguientes funcionalidades se encuentran disponibles para matrices complejas.
- Suma de matrices
- Inversa de matrices
- Multiplicacion escalar de matrices
- Traspuesta
- Conjugada
- Adjunta o Daga
- Acción de una matriz sobre un vector
- Producto entre matrices
- Revisar si es Unitaria
- Revisar si es Hermitiana
- Producto tensor

## Pruebas: 
Cada una de las funcionalidades del proyecto se encuentran probadas, se adjunto imagenes de la aplicacion wolframalpha para verificar la validez de algunas funcionalidades del proyecto.


## Proyecto 2: Sistemas Dinamicos, 1 Oct 2019, Johan Stiven Guerrero Pineda
## FUNCIONALIDADES
    - SistemasYDinamica, determina el estado de un sistema clasico,probabilistico y cuantico muestra su estado final despues de ciertos                           clicks.
                        parametros:  - Dinamica: Expresa la dinamica del sistema 0(Clasico,Determinista),1(Probabilistico),2(Cuantico).
                                     - Matriz: matriz de adyacencia correspondiente a la dinamica del sistema.
                                     - Vector: Vector de inicio del sistema.
                                     - clicks tiempo
                                     
    - SistemasEnsamblados, une dos sistemas de estados y determina su estado final despues de ciertos clicks.
                          parametros: - Matriz 1: Matriz de adyacencia de una primer dinamica de un sistema 
                                      - Matriz 2: Matriz de adyacencia de la siguiente dinamica de un sistema 
                                      - Vector 1: Estado inicial del primer sistema
                                      - Vector 2: Estado inicial del segundo sistema
                                      - t: Clicks de tiempo

    - rendijas, determina la probabilidad de estar en los diferentes estados del experimento de la doble rendija.
                parametros: - Dinamica: Expresa la dinamica del sistema 0(Probabilistico),1(Cuantico).
                            - num_rendijas: numero de rendijas.
                            - num_blancos_pared: numero de blancos que se encuentran detras de la pared.
                            - Vector_prob: Vector que determina la probabilidad de llegar a cada una de las rendijas
                                            En el caso de estar vacio, determina que la probabilidad ha de ser la misma

## Pruebas: 
Cada una de las funcionalidades del proyecto se encuentran probadas, se adjunta un grafico de barras que respresenta el estado final de los sistemas segun ciertos clicks

## Ambiente:
Si desea utilizar el contenido del proyecto, debe descargar anaconda, puesto que es el pla plataforma de desarrollo en la cual soporta jupiter notebooks que es el libro de diseño al cual fue sometido este proyecto. Si desea puede descargarlo y utilizar el contenido de esta repositorio para verificar las diferentes operaciones que se pueden realizar en el mundo de los complejos.
