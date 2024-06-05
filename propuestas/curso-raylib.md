# Propuesta: curso videojuegos con RayLib

RayLib es una librería de gráficos simple destinada a crear videojuegos.

[https://www.raylib.com/](https://www.raylib.com/)

[https://github.com/raysan5/raylib](https://github.com/raysan5/raylib)

La propuesta es realizar un curso de creación de videojuegos usando esta librería y lenguaje C.
Se realizarán unos proyectos guiados, cada uno con duración una o dos sesiones,
para explorar los diferentes aspectos de la creación de videojuegos.
El objetivo del curso es preparar a los alumnos para el Game Jam que organiza CodeURV.

### Por qué no usar un motor como Unity, Unreal, Godot, etc.?

Cada motor tiene su forma de organizar objetos, sprites, sonidos, niveles, escenas...
Para hacer buen uso, el programador debe aprender a usar el motor -
cosa que no tiene nada que ver con aprender a hacer juegos.
Como consecuencia, hay mucho tiempo entre empezar a usar un motor y el primer resultado tangible.
Para aprender, es importante que el ciclo prueba-error sea lo más rápido posible.

RayLib es una librería pequeña que se integra en el lenguaje de programación.
Tiene pocas funciones, y un modo de funcionamiento simple y fácil de entender.
Esto hace posible construir y modificar prototipos de forma ágil,
que lo hace mucho más agradable de usar.

Aquí hay dos ejemplos de juegos simples que realicé en pocas horas:

- [Bounce](https://kristo144.github.io/curs-frontend/games/bounce.html), [Código](https://github.com/kristo144/curs-frontend/blob/main/games/bounce.c)
- [Pong](https://kristo144.github.io/curs-frontend/games/pong.html), [Código](https://github.com/kristo144/curs-frontend/blob/main/games/pong.c)

### Por qué usar C y no otro lenguaje más "fácil"?

C es un lenguaje pequeño.
Lenguajes como Java, Python, C#, C++, etc. tienen muchísimas funcionalidades
que el programador puede perder horas investigando y aplicando.
Básicamente el mismo motivo que no usamos un motor.

Por otro lado, todos los alumnos de ingeniería aprenden C en clase.
Si ya han hecho FP1, tendrán ya la base.
Si no han hecho FP1, pueden aplicar lo que aprenden aquí a clase.

### Idea general de las clases

La idea es proponer una serie de proyectos y resolverlos conjuntamente durante la sesión.
Estaría bien que los alumnos den ideas de cómo resolver un problema,
y el profesor las implementa y muestra a todos el resultado por proyector.
Así animamos a los alumnos a que participen en la programación.

### Proyectos y temas

Una lista de proyectos posibles que se me han ocurrido,
y qué conceptos se introducen en cada uno:

- Menu DVD: toolchain, abrir ventanas, lógica de juego.
- Pong: input usuario, estados de juego.
- Space invaders: sprites, sonidos, objetos dinámicos.
- Plataformas: texturas, cámara 2D.
- FPS: cámara 3D.
