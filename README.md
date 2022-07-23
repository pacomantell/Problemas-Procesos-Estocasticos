# Resolucion de un problema de Procesos Estocásticos mediante un script en Python


El proceso de contacto es uno de los modelos arquetipos del no equilibrio. 
Este modelo representa una dinámica muy sencilla de creacción y destrucción de partículas en una red.
No obstante su sencillez tiene mucha riqueza física y ha sido utilizado con éxito, por ejemplo,
en el estudio de epidemias. 
En este ejercicio vamos a analizar en detalle su formulación de campo medio, o sea sin infuencia del espacio. 

Llamamos un nodo de la red "activo" si está ocupado por una partícula, un nodo puede estar ocupado por maximo una partícula.
Nuestra variable es \rho = \frac{activos / N}
N donde N es el numero total de sitios de la red. Si un nodo
activo de la red A tiene al lado un nodo vaco puede crear una partcula con una tasa  en
este ultimo (activacion). Tambien un nodo activo A puede desactivarse con la muerte de una
partcula con un tasa . Finalmente, un nodo inactivo puede convertirse espontaneamente
en activo con tasa h (creacion de un partcula):
A + ; 􀀀
! 2A (activacion)
A
􀀀
! ; (desactivacion)
; h􀀀
! A (1)
2.1
Deriva la ecuacion Maestra con estas tasas.
2.2
Con un desarrollo en un 1
N deriva la ecuacion de Fokker Planck. Escribe tambien la
ecuacion de Langevin equivalente.
