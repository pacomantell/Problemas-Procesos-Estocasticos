# Problema Procesos Estocásticos

## **ENUNCIADO**

El proceso de contacto es uno de los modelos arquetipos del no equilibrio. 
Este modelo representa una dinámica muy sencilla de creacción y destrucción de partículas en una red.
No obstante su sencillez tiene mucha riqueza física y ha sido utilizado con éxito, por ejemplo,
en el estudio de epidemias. 
En este ejercicio vamos a analizar en detalle su formulación de campo medio, o sea sin infuencia del espacio. 

Llamamos un nodo de la red "activo" si está ocupado por una partícula, un nodo puede estar ocupado por maximo una partícula.
Nuestra variable es $\rho = activos /N$ donde N es el número total de sitios de la red. Si un nodo
activo de la red A tiene al lado un nodo vacío puede crear una partícula con una tasa $\lambda$ en
este último (activación). También un nodo activo A puede desactivarse con la muerte de una
partícula con un tasa $\mu$. Finalmente, un nodo inactivo puede convertirse espontáneamente
en activo con tasa h (creación de un partícula):
$$ A+ \emptyset \overset \lambda \rightarrow 2A \quad (Activación)$$
$$ A \overset \mu \rightarrow \emptyset \quad (Desactivación)$$
$$\emptyset \overset h \rightarrow A $$

### **Apartado 1**

Deriva la ecuación Maestra con estas tasas.

### **Apartado 2**

Con un desarrollo en un $1/N$ deriva la ecuación de Fokker Planck. Escribe también la
ecuación de Langevin equivalente.
