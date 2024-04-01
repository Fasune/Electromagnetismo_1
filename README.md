## Uso del programa
El código adjunto permite la resolución de la ecuación de Laplace para el voltaje en una región rectangular con coordenadas cartesianas dadas unas condiciones de forntera.
El código se encuentra a su disposición y permitiendo variar los números de puntos con los que cuenta la red (N dimensión *x* y M en la dimensión *y*); además, tambipen se puede modificar el paso de la discretización (h).
Cabe resaltar que el largo (a) y alto (b) del rectangulo depende de la cantidad de puntos y el paso de la discretización.

Aquí, la conidicón de forntera es de la forma:
- V(x,y)=0 si *x=0* o *x=a*
- V(x,y)=*-V0* si *y=0*
- V(x,y)=*V0* si *y=b*

De igual forma, puede alterar el valor de *V0* en programa con la constante de su preferencia.
Con todo lo anterior, el programa resuelve la ecuación mediante el método de relajación y gráfica la solución.
