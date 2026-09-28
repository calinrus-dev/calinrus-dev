# Manifiesto / Si pesa, que trabaje.

[← Presentación](../README.md)

Me gusta el software que responde. El que abre, trabaja y se aparta. Me gusta mirar debajo de las abstracciones, entender qué hacen los datos y quitar trabajo que sobra. Rust, bajo nivel, herramientas propias y muchas ganas de seguir aprendiendo.

Tengo unas cuantas manías. Casi todas pasan factura en CPU, memoria o tiempo de usuario.

## 01. La RAM no es un trastero

Cada copia, asignación y recorrido tiene un coste. Me interesan la disposición de los datos, las estructuras contiguas, la localidad de memoria y la alineación con las líneas de caché cuando el problema lo exige. Assembly me ayuda a entender qué acaba ejecutando la máquina.

Antes de pedir más hardware, reviso qué estoy haciéndole hacer. Un spinner no es una estrategia de rendimiento. Es un círculo pidiendo paciencia.

## 02. Cada dependencia se gana su sitio

Un paquete entra por lo que resuelve. Se queda por cómo funciona, cuánto cuesta y lo que permite mantener. Quiero saber qué arrastra, cómo falla y quién paga la fiesta cuando deja de funcionar.

Electron no entra por inercia. En escritorio prefiero explorar Tauri, Rust y soluciones que me den control sobre el coste de la aplicación. Si una herramienta pesada es la elección adecuada, tendrá que demostrarlo en el producto. La comodidad de instalarla aporta poca información sobre la comodidad de usarla.

Añadir capas encima de un problema puede dejar el mismo problema debajo. Eso sí: muy abrigado.

## 03. El benchmark manda

Perfilar. Medir. Cambiar una cosa. Comparar. Repetir.

Datos, carga y condiciones. Una cifra sin contexto es decoración. Si una medición desmonta mi intuición, cambio de idea. También descarto una optimización cuando su complejidad cuesta más que la mejora que aporta.

Acepto invertir más tiempo en una pieza crítica si ahorro un coste que el usuario sufriría en cada sesión. El trabajo de ingeniería se hace una vez; una mala decisión puede ejecutarse miles de veces.

## 04. Pragmatismo, con el cuchillo afilado

Si algo ya existe, funciona bien y cumple lo que necesito, lo uso. Hay demasiado trabajo interesante como para fabricar otra rueda por orgullo.

Reescribo cuando gano algo concreto: rendimiento, control, claridad o una capacidad que necesito. Conservar una dependencia por costumbre y eliminarla por postureo me parecen dos formas bastante parecidas de dejar de pensar.

## 05. El usuario ya tiene una máquina. Aprovechémosla

Local-first: datos y recursos cerca del trabajo, continuidad, control y exportación. Me interesa que una aplicación conserve una experiencia útil en el dispositivo.

Una base de datos externa o un servicio remoto deben resolver una necesidad real. Colaboración y sincronización pueden justificar infraestructura. Convertir cada clic en una dependencia de red exige algo más que encogerse de hombros.

## 06. Densidad útil. Ruido fuera

En escritorio quiero información a mano, jerarquía y recorridos rápidos. En móvil, una interacción adaptada al espacio y al tacto. Minimalismo es quitar estorbos; esconder herramientas necesarias también tiene un coste.

La accesibilidad visual es una prioridad personal: contraste, texto escalable, foco visible, teclado y estados que se entiendan sin adivinar colores. La letra microscópica no se vuelve elegante por tener mucho margen alrededor.

## 07. Construir, experimentar, aprender

Mi recorrido también pasa por Minecraft. Dart y Flutter han tenido mucho peso y sigo disfrutando con ellos. Ahora estoy especialmente metido en Expo para móvil, mientras Rust y el bajo nivel siguen tirando de mi curiosidad.

Hago mis propias herramientas y muchas se quedan en privado. Este perfil enseña una selección. Contar líneas puede ser entretenido; prefiero enseñar qué resuelve el programa y cómo responde cuando se le exige.

## El criterio

Exprimir donde importa. Reutilizar lo que funciona. Medir antes de presumir. Entender lo suficiente para elegir. Y asumir el trabajo extra cuando haga falta para que el software esté a la altura.

## Una afirmación trae su prueba

Si hablo de rendimiento, necesito carga, entorno y medida. Si publico un componente, enseño cómo ejecutarlo y qué rompe. Un badge verde prueba lo que ejecuta su workflow, nada más. La gráfica de actividad no es un benchmark de oficio.
