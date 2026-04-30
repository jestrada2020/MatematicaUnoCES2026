# Geometría Analítica {#Geometria-Analitica}



**Podcast**
<audio controls>
  <source src="podcasts/cap08_geometria_analitica.mp3" type="audio/mpeg">
</audio>

## Definición del plano cartesiano

::: {.definition #def-plano-cartesiano}
El **plano cartesiano** es un sistema de coordenadas formado por dos rectas numéricas perpendiculares: el **eje horizontal** $X$ (eje de las abscisas) y el **eje vertical** $Y$ (eje de las ordenadas), que se intersectan en el **origen** $O(0,0)$. Cada punto del plano se representa por un par ordenado $(x,y)$.
:::

**Podcast explicativo**
<audio controls style="width:100%;max-width:600px;">
  <source src="podcasts/bloques/08-Geometria-Analitica_def-plano-cartesiano.mp3" type="audio/mpeg">
</audio>


## Distancia entre dos puntos

::: {.theorem #teorema-distancia}
La **distancia** entre dos puntos $P_1(x_1,y_1)$ y $P_2(x_2,y_2)$ en el plano cartesiano está dada por:
$$d(P_1,P_2)=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2}$$
:::

**Podcast explicativo**
<audio controls style="width:100%;max-width:600px;">
  <source src="podcasts/bloques/08-Geometria-Analitica_teorema-distancia.mp3" type="audio/mpeg">
</audio>


### Ejemplo 1

Determinar la distancia entre los puntos $A(1,2)$ y $B(4,6)$.

**Solución:**

$$d(A,B)=\sqrt{(4-1)^2+(6-2)^2}=\sqrt{3^2+4^2}=\sqrt{9+16}=\sqrt{25}=5$$

## Punto medio

::: {.theorem #teorema-punto-medio}
El **punto medio** $M$ del segmento que une los puntos $P_1(x_1,y_1)$ y $P_2(x_2,y_2)$ tiene coordenadas:
$$M=\left(\dfrac{x_1+x_2}{2}, \dfrac{y_1+y_2}{2}\right)$$
:::

**Podcast explicativo**
<audio controls style="width:100%;max-width:600px;">
  <source src="podcasts/bloques/08-Geometria-Analitica_teorema-punto-medio.mp3" type="audio/mpeg">
</audio>


### Ejemplo 2

Encontrar el punto medio entre $A(-2,3)$ y $B(4,7)$.

**Solución:**

$$M=\left(\dfrac{-2+4}{2}, \dfrac{3+7}{2}\right)=\left(\dfrac{2}{2}, \dfrac{10}{2}\right)=(1,5)$$

## Definición de recta

::: {.definition #def-recta}
Una **recta** es el conjunto de todos los puntos $(x,y)$ del plano cartesiano que satisfacen una ecuación de primer grado en dos variables. La forma general de la ecuación de una recta es:
$$Ax+By+C=0$$
donde $A$, $B$ y $C$ son constantes reales, con $A$ y $B$ no simultáneamente nulos.
:::

**Podcast explicativo**
<audio controls style="width:100%;max-width:600px;">
  <source src="podcasts/bloques/08-Geometria-Analitica_def-recta.mp3" type="audio/mpeg">
</audio>


## Pendiente de una recta

::: {.definition #def-pendiente}
La **pendiente** $m$ de una recta que pasa por los puntos $P_1(x_1,y_1)$ y $P_2(x_2,y_2)$, con $x_1 \neq x_2$, se define como:
$$m=\dfrac{y_2-y_1}{x_2-x_1}$$
Geométricamente, la pendiente representa la inclinación de la recta respecto al eje $X$.
:::

**Podcast explicativo**
<audio controls style="width:100%;max-width:600px;">
  <source src="podcasts/bloques/08-Geometria-Analitica_def-pendiente.mp3" type="audio/mpeg">
</audio>


## Ecuaciones de la recta

::: {.proposition #prop-ecuaciones-recta}
Sea una recta con pendiente $m$ que pasa por el punto $P_1(x_1,y_1)$. Entonces se cumplen las siguientes formas de la ecuación de la recta:

1). **Punto-pendiente:** $y-y_1=m(x-x_1)$

2). **Pendiente-intercepto:** $y=mx+b$, donde $b$ es la intersección con el eje $Y$

3). **Forma general:** $Ax+By+C=0$
:::

**Podcast explicativo**
<audio controls style="width:100%;max-width:600px;">
  <source src="podcasts/bloques/08-Geometria-Analitica_prop-ecuaciones-recta.mp3" type="audio/mpeg">
</audio>


### Ejemplo 3

Hallar la ecuación de la recta que pasa por el punto $(2,3)$ y tiene pendiente $m=4$.

**Solución:**

Usando la forma punto-pendiente:
$$y-3=4(x-2)$$
$$y-3=4x-8$$
$$y=4x-5$$

### Ejemplo 4

Hallar la ecuación de la recta que pasa por los puntos $(1,2)$ y $(3,8)$.

**Solución:**

Primero calculamos la pendiente:
$$m=\dfrac{8-2}{3-1}=\dfrac{6}{2}=3$$

Luego usamos la forma punto-pendiente con el punto $(1,2)$:
$$y-2=3(x-1)$$
$$y-2=3x-3$$
$$y=3x-1$$

## Rectas paralelas y perpendiculares

::: {.theorem #teorema-paralelas-perpendiculares}
Sean $L_1$ y $L_2$ dos rectas no verticales con pendientes $m_1$ y $m_2$ respectivamente. Entonces:

1). $L_1$ y $L_2$ son **paralelas** si y sólo si $m_1=m_2$.

2). $L_1$ y $L_2$ son **perpendiculares** si y sólo si $m_1 \cdot m_2 = -1$.
:::

**Podcast explicativo**
<audio controls style="width:100%;max-width:600px;">
  <source src="podcasts/bloques/08-Geometria-Analitica_teorema-paralelas-perpendiculares.mp3" type="audio/mpeg">
</audio>


## Definición de parábola

::: {.definition #def-parabola}
Una **parábola** es el conjunto de todos los puntos del plano cartesiano que equidistan de un punto fijo llamado **foco** $F$ y de una recta fija llamada **directriz** $L$. El punto medio entre el foco y la directriz se llama **vértice** $V$ de la parábola.
:::

**Podcast explicativo**
<audio controls style="width:100%;max-width:600px;">
  <source src="podcasts/bloques/08-Geometria-Analitica_def-parabola.mp3" type="audio/mpeg">
</audio>


## Ecuaciones de la parábola con vértice en el origen

::: {.proposition #prop-parabola-origen}
Una parábola con vértice en el origen $(0,0)$ tiene una de las siguientes ecuaciones estándar:

1). Si abre hacia arriba o hacia abajo: $x^2=4py$, donde $p$ es la distancia del vértice al foco. El foco es $(0,p)$ y la directriz es $y=-p$.

2). Si abre hacia la derecha o hacia la izquierda: $y^2=4px$, donde el foco es $(p,0)$ y la directriz es $x=-p$.
:::

**Podcast explicativo**
<audio controls style="width:100%;max-width:600px;">
  <source src="podcasts/bloques/08-Geometria-Analitica_prop-parabola-origen.mp3" type="audio/mpeg">
</audio>


## Ecuaciones de la parábola con vértice en $(h,k)$

::: {.proposition #prop-parabola-vertice}
Una parábola con vértice en $(h,k)$ tiene una de las siguientes ecuaciones estándar:

1). Eje vertical: $(x-h)^2=4p(y-k)$. El foco es $(h,k+p)$ y la directriz es $y=k-p$.

2). Eje horizontal: $(y-k)^2=4p(x-h)$. El foco es $(h+p,k)$ y la directriz es $x=h-p$.
:::

**Podcast explicativo**
<audio controls style="width:100%;max-width:600px;">
  <source src="podcasts/bloques/08-Geometria-Analitica_prop-parabola-vertice.mp3" type="audio/mpeg">
</audio>


### Ejemplo 5

Hallar el vértice, foco y directriz de la parábola $x^2=8y$.

**Solución:**

Comparando con $x^2=4py$, tenemos $4p=8$, por lo tanto $p=2$.

- **Vértice:** $(0,0)$
- **Foco:** $(0,2)$
- **Directriz:** $y=-2$

### Ejemplo 6

Hallar la ecuación de la parábola con vértice en $(2,3)$ y foco en $(2,5)$.

**Solución:**

Como el vértice y el foco tienen la misma coordenada $x$, la parábola tiene eje vertical. La distancia $p=5-3=2$.

Usando $(x-h)^2=4p(y-k)$:
$$(x-2)^2=4(2)(y-3)$$
$$(x-2)^2=8(y-3)$$

## Evaluación (Geometría Analítica)

1). Calcular la distancia entre los puntos $A(-3,2)$ y $B(1,5)$.

2). Hallar el punto medio del segmento que une $P(-4,6)$ y $Q(2,-2)$.

3). Determinar la ecuación de la recta que pasa por $(3,-1)$ con pendiente $m=-2$.

4). Hallar la ecuación de la recta que pasa por $(2,3)$ y $(4,7)$.

5). Determinar si las rectas $L_1: 2x+3y-5=0$ y $L_2: 4x+6y+1=0$ son paralelas o perpendiculares.

6). Hallar el vértice, foco y directriz de la parábola $y^2=12x$.

7). Hallar la ecuación de la parábola con vértice en $(-1,2)$ y foco en $(-1,5)$.
