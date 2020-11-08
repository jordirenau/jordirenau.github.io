---
layout: post
title: Las pilas de combustible
summary: Una pila de combustible se comporta exactamente como una batería, pero cargada de forma infinita, o hasta que termines el combustible.
---

## Cómo se construyen

El nombre "*pila de combustible*" es una palabra compuesta interpretada del término inglés "*fuel cell stack*" que en realidad se debería traducir como "*apilamiento de celdas de combustible*", o “*células de combustible*”, nunca lo he tenido muy claro. Estas celdas están construidas igual que las de una batería. Por un lado tenemos el cátodo, por el otro el ánodo y para separarlas tenemos el electrolito. Las pilas se clasifican en función del tipo de electrolito, siendo las más comunes o estudiadas las de membrana polimérica (PEMFC) y las de óxido sólido (SOFC), pero también hay pilas alcalinas, de ácido fosfórico

![montaje_aperion_sin_alfa](https://i.loli.net/2020/11/09/rux6DaFml8hfn2S.png)



El hecho de tratarlas como células o celdas es porque la pila o apilamiento se construye a través de unidades indivisibles de este tipo. En la figura anterior se puede observar un despiece sencillo de una celda de combustible de una pila de tipo PEM (*Polymeric Exchange Membrane*). Marcadas con el número (2) las placas que hacen de cátodo y de ánodo. En este caso son placas monopolares, es decir, hay una por cada cátodo y otra por cada ánodo, por lo que estas placas se repiten tantas veces como celdas haya. En otras ocasiones las placas son bipolares por lo que una placa de ánodo en un lado comparte el cátodo de la siguiente celda en el otro lado, ayudando así a completar el "apilamiento". Las placas marcadas con el (1) son las placas colectoras de corriente y se colocan siempre en los extremos, permiten conectar el último cátodo y último ánodo al circuito eléctrico externo. La marcada con el número (4) es la placa terminal de presión, la cual tiene una forma estructural y su función es presionar uniformemente todas las placas para garantizar el correcto contacto eléctrico y garantizar la estanqueidad de los gases reactantes. Por último, y más importante, la lámina anaranjada marcada con el número (3) es la MEA (*Membrane Electrode Assembly*), la esencia de la tecnología PEM, es la membrana conductora de protones, mediante la cual se canaliza la reacción entre el hidrógeno (ánodo) y el oxígeno (cátodo).

## Cómo funcionan

El electrolito de las pilas de combustible funciona de la misma forma que las baterías convencionales: es un material que permite la conducción de los iones libres pero no de electrones, de forma que es posible separar las dos corrientes en una reacción electroquímica y canalizar la corriente eléctrica para poder aprovecharla. Las pilas PEM son las más sencillas con las que se explica el fenómeno de estas reacciones redox: el hidrógeno (H<sub>2</sub>) en el ánodo se rompe en dos protones (H<sup>+</sup>) que pueden atravesar libremente la membrana, liberando dos electrones que no pueden pasar por dicha membrana, por lo que deben buscar un camino alternativo hasta el cátodo, donde se separa el oxígeno y se recombina con los protones de hidrógeno para formar moléculas de agua. Este proceso se muestra gráficamente en la siguiente figura.

![Fuel cell](https://upload.wikimedia.org/wikipedia/commons/thumb/9/90/Solid_oxide_fuel_cell_protonic.svg/913px-Solid_oxide_fuel_cell_protonic.svg.png)

Durante la operación de la pila de combustible hay un cierto exceso de combustible y **calor** que se emite al entorno reduciendo el rendimiento energético del sistema, al igual que sucede en los motores térmicos de combustión interna. Y al igual que se plantea con estos, es posible diseñar el sistema para poder aprovechar dicho calor residual, convirtiendo la pila de combustible en una instalación de cogeneración tal y como hemos planteado en el proyecto MICA-PEM.

![PolarizacionFuelCellPBI](https://i.loli.net/2020/11/09/sWpDnLjKgxNBwMz.png)