# ¿Velocidad o Calidad? El impacto de la Deuda Técnica en Scrum

**Programa:** Análisis y Desarrollo de Software (ADSO)  
**Tema:** Documentación y buenas prácticas de desarrollo.  

---

## Un problema común en los proyectos de software

Cuando empezamos a trabajar con metodologías ágiles como **Scrum**, lo primero que nos enseñan es la importancia de entregar valor rápido al cliente. Entregar un incremento de software funcional en cada *Sprint* suena excelente en la teoría, pero en la práctica diaria del desarrollo genera una pregunta clave: **¿Qué pasa cuando la prisa por entregar nos hace escribir código desordenado?**

Ahí es donde entra el concepto de **Deuda Técnica**. No se trata de un error financiero, sino del costo invisible que pagamos más adelante por tomar atajos hoy.

---

## ¿Cómo se acumula la deuda técnica sin darnos cuenta?

En un equipo de desarrollo suele haber mucha presión por cumplir las fechas de entrega. Algunas situaciones típicas donde se genera esta deuda son:

* **Priorizar solo lo que el usuario ve:** Muchas veces el *Product Owner* quiere ver pantallas y funciones nuevas, dejando en segundo plano la optimización de las bases de datos o la estructura interna del código.
* **Saltarse las pruebas por falta de tiempo:** Para alcanzar a cerrar una tarea antes de que termine el *Sprint*, el equipo decide no hacer pruebas unitarias ni revisiones de código (*Code Reviews*).
* **Parches rápidos sobre código viejo:** En lugar de reestructurar una función mal hecha, se le agrega más código encima. A corto plazo funciona, pero a largo plazo hace que el sistema sea inestable.

---

## Las consecuencias a futuro

Si la deuda técnica no se controla, llega un punto donde el proyecto se vuelve **inmantenible**. Los desarrolladores gastan más tiempo intentando arreglar errores (*bugs*) que creando nuevas funcionalidades. Lo que al principio era un desarrollo "ágil" termina convirtiéndose en un sistema lento y frustrante de actualizar.

---

## ¿Cómo podemos evitarlo desde ADSO?

Para que un proyecto sea ágil y al mismo tiempo sostenible, es importante aplicar buenas prácticas desde el primer día:

1. **Aplicar la regla del Boy Scout:** Intentar dejar el código un poco más limpio y ordenado de como lo encontramos cada vez que trabajamos en un archivo.
2. **Definir bien cuándo una tarea está terminada (*Definition of Done*):** Una historia de usuario no debería considerarse lista solo porque "funciona en mi PC". Debe incluir pruebas y una estructura limpia.
3. **Negociar tiempo para refactorizar:** Reservar un porcentaje de tiempo en el desarrollo para organizar el código y pagar la "deuda" acumulada antes de que sea demasiado tarde.

---

## Conclusión

Scrum no significa programar rápido a cualquier costo. La verdadera agilidad consiste en encontrar un equilibrio entre responder a las necesidades del cliente y mantener un código limpio, legible y escalable. Como futuros analistas y desarrolladores, entender esto es fundamental para no construir software que colapse con el tiempo.