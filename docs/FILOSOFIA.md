# Mi forma de construir

[← Presentación](../README.md)

## Medir, entender, ajustar

Trabajo con mentalidad data-driven: una intuición abre una hipótesis y los datos ayudan a decidir. Prefiero comparar una mejora sobre un recorrido definido, con la misma carga y condiciones observables. Una cifra aislada sin contexto explica poco.

## Arquitectura orientada a datos

Me interesa cómo se representan y recorren los datos, qué memoria se toca y cuánto trabajo se repite. En sistemas nativos pienso en localidad, estructuras contiguas, alineación con líneas de caché cuando corresponde, copias y asignaciones. Optimizar ciclos tiene sentido cuando mejora un coste medido y mantiene el sistema comprensible.

Mis conocimientos de Assembly ayudan a conectar las abstracciones de alto nivel con lo que ejecuta la máquina. No uso esa cercanía al hardware como sustituto de perfilar ni como promesa de rendimiento por sí misma.

## Local-first y dependencias deliberadas

Quiero que el dispositivo tenga un papel real: datos locales, continuidad del trabajo, recursos bajo control y exportación comprensible. Elegir una base externa o un servicio remoto debe responder a una necesidad concreta, como colaboración o distribución.

La sincronización añade conflictos, estados y costes operativos. Prefiero hacerlos explícitos y conservar una experiencia local útil donde el producto lo permita. Local-first es un criterio de diseño, no una afirmación de que todos mis proyectos carezcan de servicios externos.

## Sobriedad, densidad y adaptación

En escritorio me gustan las interfaces con información a mano, menos recorridos repetitivos y una jerarquía clara. Densidad útil significa poder encontrar, comparar y actuar con rapidez.

En móvil cambian el espacio, el agarre y el contexto. Un diseño responsivo debe adaptar la interacción además de reorganizar columnas. Minimalismo significa quitar ruido y mantener las señales que ayudan a decidir.

## Accesibilidad como requisito de producto

La accesibilidad visual es una prioridad personal de mi trabajo. Me importan el contraste, el tamaño de texto, el escalado, el foco, la navegación por teclado, el movimiento reducido y los estados que se entienden sin depender solo del color.

Estos criterios se aplican también a herramientas densas, editores y videojuegos: información del combate, menús, controles y feedback necesitan una lectura clara. La conformidad y el funcionamiento con tecnologías de asistencia requieren pruebas específicas; no los doy por hechos por usar un framework.

## Experiencias interactivas y videojuegos

Exploro sistemas de juego, herramientas y experiencias en Godot y Bevy. Me interesan tanto el bucle de interacción como el trabajo del creador: editar, probar y observar deben estar cerca. Rust, Tauri, Flutter y Dart conectan parte de esa búsqueda con aplicaciones nativas y multiplataforma.

## Evidencia antes que etiquetas

Un prototipo, una entrega verificada y una idea futura tienen valor distinto. Los casos de estudio indican su estado y separan capturas reales de ilustraciones. Los resultados de rendimiento necesitan escena, hardware, revisión y metodología.
