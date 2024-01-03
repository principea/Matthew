Práctica Arduino #2: Ciclos y Funciones.
Problema #1:
Un botón y dos leds, un led verde y otro rojo:
a) Cuando el botón es presionado más de 10 veces, debe encender el led rojo en señal
de alarma. Apagar el led verde.
b) Cuando el número de veces que presiones el botón esté entre 5 y 10, debes
encender el led verde, Apagar el led rojo.
c) En caso de que el número de veces que sea presionado, el botón sea mayor a 15,
los dos leds deben parpadear al mismo tiempo (1 segundo).
Problema #2:
Un potenciómetro y 3 leds.
a) Secuencia #1: Crear una secuencia de luces donde vas encendiendo cada led al
pasar un segundo. Al inicio de la secuencia debes tener todos los leds apagados y al
final todos los leds encendidos.
b) Secuencia #2: Otra secuencia debe ser el encendido de un led a la vez cada
segundo, de derecha a izquierda. Debes empezar la secuencia con el led de la
derecha encendido y los demás apagados. Termina la secuencia con el led de la
izquierda encender
c) La secuencia #1 debe activarse si el valor del potenciómetro está entre 0 y 500.
d) La secuencia #2 debe activarse si el valor del potenciómetro está entre 0 y 1000.
Problema #3:
Dos botones (Izquierda y Derecha) y 5 Leds.
a) Inicial con el led #3 encendido y los demás apagados.
b) Al presionar el botón de la izquierda debes cambiar el led encendido, una posición a
la izquierda, parpadear 3 veces cada un segundo y quedarse encendido. Si el led es
el último de la izquierda, debes pasar al otro extremo.
c) Al presionar el botón de la derecha debes cambiar el led encendido, una posición a
la derecha, parpadear 3 veces cada un segundo y quedarse encendido. Si el led es
el último de la derecha, debes pasar al otro extremo.
d) Cada vez que cambies de extremo debes poner a parpadear todos los leds 4 veces
en intervalos de 500 ms.
Problema #4:
Un botón, un potenciómetro y 5 leds.
a) Encender un solo led de forma aleatoria. Usando random funciones en Arduino. Los
cambios deben ser en cada segundo.
b) Cuando presiones el botón debes cambiar el número de leds que enciendas de
forma aleatoria, primero dos, luego tres, hasta que enciendan todos al mismo
tiempo. Al presionar con todos los leds encendidos debes volver a empezar con un
solo led.
c) El valor del potenciómetro debe cambiar la velocidad con la cual cambias de led. Al
aumentar el valor del potenciómetro aumenta los cambios de led y viceversa.
