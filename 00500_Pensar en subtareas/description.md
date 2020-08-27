¡Vamos a dibujar un cuadrado! :raised_hands: 

<gs-board>
 GBB/1.0
 size 3 3
 cell 0 0 Negro 1
 cell 0 1 Negro 1
 cell 0 2 Negro 1
 cell 1 0 Negro 1
 cell 1 1 Negro 1
 cell 1 2 Negro 1
 cell 2 0 Negro 1
 cell 2 1 Negro 1
 cell 2 2 Negro 1
 head 0 0
</gs-board>

Dividiendo cada parte del problema en procedimientos más pequeños, vamos a plantear la siguiente **estrategia**: construir el cuadrado con tres líneas de tres bolitas, una encima de la otra. ¿Y cómo se ve una línea hecha con bolitas? Así:

<gs-board> 
  GBB/1.0 
  size 3 3 
  cell 0 0 Negro 1 
  cell 1 0 Negro 1 
  cell 2 0 Negro 1 
  head 0 0 
</gs-board>

¡Partamos por ahí! :muscle:

> Define el procedimiento `DibujarLineaNegra3` que, como su nombre lo indica, _dibuje una línea_ poniendo 3 bolitas negras consecutivas hacia el este y dejando el cabezal donde comenzó. Invócalo en un `program`.
> 
> En la Biblioteca vas a encontrar el procedimiento `VolverAtras`. ¡Eso significa que puedes invocarlo sin tener que definirlo! :gift: