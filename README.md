# MCOC-Proyecto-2-Entrega-4
Tiempos de procesamiento para una simulación son con un dt de 0.0001 segundos, un t max de 2. segundos y diametro de particula de 0.15 mm.

## Caracteristicas del Pc:

### Edicion de Windows
- Windows 10 Home

### Sistema
- Procesador: Intel(R)Core(TM) i3-4005U CPU @ 1.7GHz 1.7 GHz
- Memoria instalada(RAM): 8,00 GB
- Tipo de sistema: Sistema operativo de 64 bits, procesador x64

## Tiempos de Procesamiento
Los tiempos de procesamiento del codigo son variables debido a que el procesador realiza distintas tareas mientras corre el codigo haciendo que demore algunas veces más y otras menos en finalizar, pero debido al tiempo disponible y la tardanza en procezar todo el codigo se procesará solo una vez cada codigo. El tiempo con diferente cantidad de particulas es exponencial debido a que mientras más particulas se tendran que realizar mas ciclos como es el caso de comparar radios y saber si chocan con el suelo o entre particulas.
Los graficos expuestos son el comportamiento de las particulas en el eje x e y en el tiempo de 2. segundos, donde se muestran las reacciones con las fuerzas de lift, drag y masa mientras se observan colisiones entre particulas y con el suelo creado por particulas del mismo diametro.
Los resultados no representan del todo la realidad, en primer lugar porque no se concideran fuerzas como Magnus y Basset, además de no ser del todo reales las constantes de lift, drag ni de masa, idealizandolas. Al momento del impacto se consideraron "resortes" que le aplicaban fuerzas en la direccion opuesta. Se usaron particulas perfectamente esfericas y por último el suelo es una cama de particulas circularesen perfecto orden y sin capacidad de movimiento en ninguna direccion.

- Con 2 Particula: 10.7 Segundos
![dos particulas](https://user-images.githubusercontent.com/53497030/66689184-429b4b80-ec60-11e9-807a-e6c207e085f0.png)

- Con 5 Particulas: 1 minuto 43 Segundos
![cinco  particulas](https://user-images.githubusercontent.com/53497030/66689185-429b4b80-ec60-11e9-85b0-b9f08e570bfd.png)

- Con 10 Particulas: 19 minutos 19 segundos
![diez particulas](https://user-images.githubusercontent.com/53497030/66691694-8b5a0100-ec6e-11e9-8147-a40c879820fa.png)

- Con 20 Particulas: Tras 1 hora 25 minutos se decide detener la operacion.









