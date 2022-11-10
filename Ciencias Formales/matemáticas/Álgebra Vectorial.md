**contenido:**
```ad-info
el contenido a continuacion es para vectores en R² y R³
```
1. Vectores
	1. Ingeniería y vectores
	2. Vector
	3. Operaciones entre vectores
	4. Vectores en sistemas de coordenadas
	5. Vector definido mediante las coordenadas de su origen y su punto extremo
	6. Módulo de un vector
	7. Ángulos directores
	8. Versor o vector unitario asociado a un vector
	9. Introducción a espacios vectoriales reales.
2. Producto entre vectores
	1. Ingeniería y vectores
	2. Producto escalar, angulo entre vectores y proyecciones
	3. Producto vectorial
	4. Producto mixto
```ad-danger
el álgebra vectorial propiamente dicho no abarca todo este temario, ya que este seria solo especificamente la parte donde se estudian las operaciones algebraicas entre vectores
```
----
# Álgebra Vectorial
## Ingeniería de vectores.
Se explica la importancia de los vectores en la física, y del uso de magnitudes en diversas situaciones de nuestras vidas.
+ [[magnitudes escalares]]
+ [[magnitudes vectoriales]]
## Vector
```ad-quote
Un segmento de recta queda determinado por sus puntos extremos, cuando estos puntos están dados en cierto orden se dice que el segmento esta orientado, y a este segmento orientado se le denomina vector ¹.
```
+ Se denomina vector a cualquier **[[segmento orientado]]**.
+ [[segmento de recta]]
### Representación geométrica de un vector
![[representacion geométrica de un vector.excalidraw|Representación geométrica de un vector]]
+ En la recta $r$ elegimos dos puntos $A$ y $B$.
+ "Si consideramos al punto $A$ como el origen y al punto $B$ como el extremo tendremos un [[segmento orientado]], entonces queda definido el vector $\overrightarrow{AB}$ ¹. Por ser un vector geométrico (magnitud vectorial) es posible identifica en ella una dirección, un sentido y una magnitud ¹. "
+ **Dirección (recta de acción):** Está dada por la recta $r$. 
+ **Sentido:** Al decir: "con origen en $A$ hasta el extremo $B$ " estamos fijando un sentido.
+ **Módulo:** Es la longitud del origen en $A$ hasta el extremo $B$, se simboliza como: $\left\| \overrightarrow{AB} \right\|$

```ad-important
title: Módulo de un vector
**Punto de vista geométrico:**
+ El módulo de un vector es la longitud del segmento orientado que define al vector.

**Punto de vista Físico:**
+ El módulo de un vector es la propia intensidad o magnitud del vector
```
+ **Cuando el módulo de un vector es 1, se le denomina vector unitario o versor $\breve{v}$**

### Clasificación de vectores
En física, especialmente y teniendo en cuenta el contexto en el cual se aplica, los vectores pueden clasificarse como fijos, deslizantes y libres ¹. 

#### Vectores fijos
+ Los vectores fijos quedan definidos cuando, ademas de especificar módulo, dirección y sentido, se indica el punto sobre el que están aplicados ¹.
	Por ejemplo:
	+ Una magnitud vectorial fija es aquella donde puede cambiar el efecto de una fuerza aplicable a un solido dependiendo con el punto de aplicación. Si una fuerza se aplica en un centro de gravedad el objeto se mueve, si se aplica en una esquina el objeto se va a volcar.
#### Vectores deslizantes
+ Los vectores deslizantes quedan definidos cuando, ademas de especificar módulo, dirección y sentido, se indica la línea de acción.

#### Vectores libres
+ Un vector libre $\vec{v}$ es el representante de todos los vectores que son equipolentes a un vector dado.
#### Vectores equipolentes
+ Dos vectores son equipolentes cuando tienen el mismo módulo, el mismo sentido y la misma dirección o sus rectas de acción son paralelas.

### Vectores en la física
+ La aplicación de los vectores en el contexto de la física **implica restricciones**, tales como tener que **considerar el punto de aplicación** para describir un fenómeno o el movimiento sobre una línea de acción.

---
## Operaciones entre vectores libres
### Suma de vectores libres
#### Regla del paralelogramo:
```ad-quote
Se considera un punto de aplicación $O$, y con el origen en ese punto se representa al veco $\vec v$ y al vector $\vec w$. Se traza una recta paralela a la direccion del vector $\vec w$ en el extremo del vecto $\vec v$, y en el extremo del vector $\vec w$ se traza una recta paralela a ala dirección del vector $\vec v$. estas rectas se coran en un punto $P$, formando un paralelogramo. Luego, el vector suma $\vec v + \vec w$ se obtiene uniendo el punto de aplicación. $O$ con el punto $P$ ¹.
```
#### Propiedades de la suma de vectores libres
1. Ley de composición interna: La suma de dos vectores es un vector.$$
\vec u = \vec v + \vec w
$$
2. La suma de vectores es conmutativa: $$
\vec v +\vec w =\vec w+ \vec v
$$
3. La suma de vectores es asociativa: $$
 \vec v + (\vec w + \vec u) = (\vec v + \vec w) + \vec u
$$
4. Elemento neutro: Existe un vector denominado vector nulo, simbolizado mediante $\vec 0$ , tal que para cualquier vector $\vec v$ se cumple que $\vec v + \vec 0 = \vec 0  + \vec v =  \vec v$   y se conoce como elemento neutro para la suma de vectores.
5. Elemento opuesto: Para todo vector $\vec v$ existe un vector opuesto $- \vec v$ tal que $\vec v + (-  \vec v) = -\vec v + \vec v = \vec 0$

##### Vector nulo
El vector nulo $\vec 0$ , se representa como el vector cuyo origen y punto extremo coinciden; el modulo del vector nulo es cero: $$
\| \vec 0 \|= 0
$$
##### Vector opuesto
El vector opuesto, $- \vec v$, del vector  $\vec v$ tiene la misma dirección e igual módulo que el vector $\vec v$, pero sentido opuesto.

### Resta de vectores libres
```ad-important 
Mis profesores, en la escela profesional de física (UNSA), concuerdan en que los vectores no se pueden restar, pero se le puede sumar a un vector el opuesto de otro. **La resta de vectores no existe**.
```
+ Es posible definir la resta de vectores como una consecuencia de las propiedades (4) y (5) de la suma de vectores libres.
```ad-quote
Sean $\vec v$ y $\vec w$ dos vectores cualesquiera; entonces el vector $\vec v - \vec w$, que e la resta entre los vectores $\vec v$ y $\vec w$, se obtiene al sumar a $\vec v$ el vector opuesto de $\vec w$. 

En símbolos: $\vec v - \vec w = \vec v + (-\vec w)$
```
### Producto de un escalar  por un vector

Sean $\vec v$ un vector y $\lambda$ un número real; entonces el producto del vector $\vec v$ por el escalar $\lambda$, simbolizado mediante $\lambda \vec v$, es un vector con las siguientes características:
El módulo del vector $\lambda \vec v$ es $\| \lambda \vec v \|= |\lambda |\|\vec v\|$, donde 
$$
\begin{align}
&\| \lambda \vec v \|<\|\vec v\|, si\; |\lambda|<1 \\
&\| \lambda \vec v \|>\|\vec v\|, si\; |\lambda|>1 \\
&\| \lambda \vec v \|=\|\vec v\|, si\; \lambda = 1 \vee\lambda = -1
\end{align}
$$
La dirección de $\lambda \vec v$ coincide con la dirección de $\vec v$ cuando $\lambda \neq 0$  y $\vec v  \neq \vec 0$; esto es, la dirección permanece invariante. Y la dirección de $\lambda \vec v$ es no determinada cuando $\lambda = 0$ o $\vec v = \vec 0$, o ambos igual a 0.
El sentido de $\lambda \vec v$ coincide con el sentido de $\vec v$ si $\lambda >0$, y es opuesto a $\vec v$ cuando $\lambda < 0$.
#### Propiedades del producto de un vector por un escalar
1. Ley de **composición externa**: El producto de un vector por un escalar es un vector.
2. Asociatividad mixta: $$
\begin{align}
&\lambda_{1} (\lambda_{2} \vec v) \\
= &(\lambda_{1} \lambda_{2} ) \vec v  \\
= &\lambda_{2}(\lambda_{1} \vec v) 
\end{align}
$$
7. Propiedad **distributiva** del producto de un vector por un escalar con respecto a la suma de vectores: $\lambda(\vec u + \vec v) =\lambda \vec u + \lambda  \vec v$
8. Propiedad distributiva del producto de un vector por un escalar con respecto a la suma de escalares: $(\lambda_{1} + \lambda_{2}) \vec v = \lambda_{1} \vec v + \lambda_{2} \vec v$ 
9. **Elemento neutro**: El escalar 1 es el neutro para el producto de un vector por un escalar: $1 \vec v = \vec v$

```ad-note
Al vector $\lambda \vec v$ se le llam múltiplo escalar del vector $\vec v$ ¹.
```
![[Pasted image 20220913073310.png]]



# Notas relacionadas

# Referencias:
1. [@kozakNocionesGeometriaAnalitica2007]
2. 
3. 