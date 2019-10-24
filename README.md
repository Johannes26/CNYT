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
## Proyecto 2: Sistemas Dinamicos, 1 Oct 2019, Johan Stiven Guerrero Pineda
## FUNCIONALIDADES
    -SistemaCuantico(V): recibe un estado de posicion de una particula, debe de retorna un vector con las probabilidades para los estados basicos, esto se realiza dividiendo le modulo cuadrado de cada uno de los estados sobre la norma de el vector total, que es la suma de todas las normas del vector.
    -VectorNormalizado(V): recibe un vector de estados, debe retornar un vector normalizado, esto lo realiza determinando la norma total de vector, y dividiendo cada uno de los componentes sobre esta norma
    -amplitud(V1,V2): recibe 2 vectores con los cuales debe determinar la amplitud de transicion de pasar de un vector inicial a uno final,el vector1 es el vector final y el vector 2 es el inicial, para realizar este proceso, se ha de hacer el producto interno entre el vector final y el inicial, no al contrario, por eso el orden de los parametros.
    -valorEsperado(O,phi): el valor esperado se define como el producto interno entre la accion de un observable con phi y el mismo vector phi, que se tiene que tener en cuenta que el observable es una matriz hermitiana. La funcion retorna el valor esperado de un observador con respecto a phi.
    -delta(O,phi): el operador delta se define como la resta entre la matriz del observador menos la identidad multiplicada por el valor esperado del observador con respecto a phi, se ha de tener en cuentra que la identidad tiene que ser de la misma dimension del observable paraque se puedan restar.La funcion ha de retornar el operador delta
    -Varianza(O,phi): la varianza de un observable se define como el valor esperado de el delta cuadrada con respecto a phi. Esta funcion determina la varianza utilizando las funciones implementadas anteriormente.
    -Valorespropios(O,phi): esta funcion ha de ingresarse un observable y el phi correspondiente, sin embargo, la entrada de esta es diferente a los anteriores, puesto que esta se hizo implementado metodos de la libreria numpy de python, por lo cual a la hora de ingresar la matriz ha de tenerse en cuenta que los valores complejos ha de ingresarse en forma de suma y la parte imaginaria se representa con j.Esta funcion determina los valores propios, vectores propios implementando la funcion linalg.eig de la libreria numpy, y luego se determina las probabilidades de colapso de estos phi con respecto a los vectores propios del observable, para este ultimo se reliza normalizacion de los vectores y se determina el modulo cuadrado de el producto interno entre el vector propio y phi respectivamente.
    
## Pruebas: 
Cada una de las funcionalidades del proyecto se encuentran probadas, se adjunta un grafico de barras que respresenta el estado final de los sistemas segun ciertos clicks.
Para el proyecto 3 las pruebas se encuentrar validas excepto la ultima funcion puesto que no arroja el valor correcto de colapsos, sin embargo el metodo se encuentra correctamente implementado

## Ambiente:
Si desea utilizar el contenido del proyecto, debe descargar anaconda, puesto que es el pla plataforma de desarrollo en la cual soporta jupiter notebooks que es el libro de diseño al cual fue sometido este proyecto. Si desea puede descargarlo y utilizar el contenido de esta repositorio para verificar las diferentes operaciones que se pueden realizar en el mundo de los complejos.
