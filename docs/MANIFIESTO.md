# Manifiesto / Ingeniería con intención

[← Presentación](../README.md)

Quiero construir software que responda, que se pueda entender y que respete la máquina de quien lo usa. Me atraen el bajo nivel, Rust, la disposición de los datos y la posibilidad de mirar debajo de una abstracción para comprender su coste. Me encanta experimentar y sigo aprendiendo.

## Cada ciclo cuenta cuando el trabajo lo necesita

Una interfaz puede parecer sencilla y esconder una cantidad absurda de trabajo. Me interesa encontrar ese trabajo: lo que se repite, lo que se copia, lo que se asigna y lo que se calcula sin necesidad.

Pienso en localidad de memoria, estructuras contiguas, alineación con líneas de caché y recorridos de datos. Mis conocimientos de Assembly forman parte de esa curiosidad por cómo ejecuta realmente la máquina. Primero observo el problema; después decido dónde merece la pena bajar de nivel.

Acepto invertir más esfuerzo en una pieza importante cuando eso reduce un coste que el usuario sufriría en cada sesión. El tiempo de ingeniería y el tiempo de uso no pesan igual: una decisión tomada una vez puede repetirse miles de veces en manos de otras personas.

## Las dependencias tienen que justificar su sitio

Un paquete entra por una función concreta. Quiero entender qué añade, qué arrastra, cómo falla y cuánto cuesta mantenerlo. El tamaño, el arranque, la memoria y la complejidad forman parte de la decisión.

Electron no es mi opción por defecto. Para escritorio me atraen Tauri, Rust y las soluciones que me permiten mantener un control más directo sobre el coste de la aplicación. Elegiría una tecnología por lo que exige el producto y por cómo se comporta en él, no por inercia.

También soy pragmático: si una herramienta existente resuelve bien el problema y cumple mis requisitos, la uso. Reutilizar buen trabajo es una ventaja. Reescribir solo tiene sentido cuando gano control, rendimiento, claridad o una capacidad que necesito de verdad.

## Data-driven también significa cambiar de opinión

Una preferencia es un punto de partida. Una medición puede desmontarla. Quiero formular hipótesis, observar tiempos y recursos con una carga concreta y comparar cambios en condiciones equivalentes.

Una optimización tiene que mejorar algo que importe. Si añade complejidad sin una mejora útil, también hay que saber descartarla. No convierto un lenguaje, un framework ni una cifra aislada en una religión.

## Local-first: la máquina del usuario debe tener un papel real

Me gustan las aplicaciones que conservan datos, recursos y continuidad de trabajo en el dispositivo. Quiero que el usuario entienda dónde está su trabajo y pueda conservarlo y exportarlo.

Un servicio externo debe aportar una función concreta. La colaboración y la sincronización pueden necesitar infraestructura remota; la dependencia no debería extenderse por comodidad a cada interacción que podría resolverse localmente.

## Densidad útil, sobriedad y accesibilidad

Quiero escritorio con información a mano: jerarquía, navegación rápida y herramientas que ayuden a pensar. El minimalismo debe quitar ruido y pasos innecesarios. El diseño responsivo adapta el recorrido al contexto, especialmente en móvil.

La accesibilidad visual es una prioridad personal. Texto legible y escalable, contraste, foco, teclado, estados claros y movimiento reducido forman parte del producto. Exprimir recursos y cuidar a quien utiliza la interfaz son dos partes del mismo trabajo.

## Aprender construyendo mis propias herramientas

Mi recorrido también pasa por experimentar con Minecraft. Dart y Flutter han tenido una etapa importante en mi trabajo y sigo disfrutando con ellos. Ahora estoy especialmente volcado en Expo para aplicaciones móviles, mientras Rust y el bajo nivel mantienen un lugar central en mi interés técnico.

Me gusta hacer mis propias herramientas. Buena parte de ese trabajo vive en proyectos privados o experimentos que no publico. Aquí enseño una selección de productos, decisiones y resultados, no toda mi actividad. Prefiero que un proyecto explique lo que permite hacer a convertir el número de líneas de código en una medida de valor.

## La responsabilidad de elegir

Quiero entender lo suficiente para elegir con criterio: medir con honestidad, reutilizar buenas soluciones y asumir el trabajo adicional cuando el producto lo necesita. La ambición técnica se demuestra en lo que una persona puede hacer con el software y en lo bien que responde cuando lo necesita.
