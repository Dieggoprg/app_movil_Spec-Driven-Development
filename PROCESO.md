# FASE 1 (uno) - Investigación:
 ________________________________________
- **React native**
  - ### qué es: 
  React Native es un framework de código abierto creado por Meta en 2015 que permite desarrollar aplicaciones para iOS, Android, Windows, macOS y Web usando una única base de código en JavaScript y React. A diferencia de las soluciones híbridas tradicionales, traduce el código a componentes nativos reales, lo que garantiza un rendimiento e interfaz idénticos a las apps nativas creadas con Swift o Kotlin, pero con la rapidez del desarrollo web. 

  - ### nativo vs híbrido:
  La diferencia clave radica en que el desarrollo nativo ofrece el máximo rendimiento y acceso total al hardware pero requiere duplicar costos y tiempo al programar de forma independiente para iOS (Swift) y Android (Kotlin), mientras que el enfoque híbrido optimiza el presupuesto al usar un único código base reutilizable para ambas plataformas, sacrificando un mínimo de fluidez a cambio de un lanzamiento mucho más rápido y económico.

  - ### ventajas:
  React Native destaca por ofrecer rendimiento nativo con un único código base, lo que reduce drásticamente los costos y tiempos de desarrollo al programar simultáneamente para iOS y Android. Su arquitectura traduce JavaScript en componentes nativos reales para garantizar una experiencia de usuario fluida, mientras que su enorme comunidad y funciones como Fast Refresh permiten modificar la app en tiempo real sin reiniciar el sistema, combinando la potencia de lo nativo con la agilidad del desarrollo web.

  - ### desventajas:
  Las principales desventajas de React Native son su menor rendimiento en gráficos pesados o animaciones 3D en comparación con lo puramente nativo, y la dependencia de librerías de terceros que pueden quedar obsoletas. Además, el acceso a funciones muy nuevas del celular suele requerir escribir código nativo puente (Swift o Kotlin), y el tamaño final de la aplicación es más pesado que el de una app nativa convencional.

  - ### 3 ejemplos de casos de uso:
  Apps de redes sociales y contenido interactivo
  Plataformas de comercio electrónico
  Herramientas de productividad y entrega de servicios

  - ### 3 ejemplos de apps conocidas:
  Uber Eats
  Instagram
  Shopify

 
 ### Persona asignada: **Diego Garcia**
 ________________________________________
 - **Expo**
  - ###  qué es
  Expo es un conjunto de herramientas y servicios que facilita el desarrollo de aplicaciones móviles con React Native. Permite crear aplicaciones para Android, iOS y también web usando principalmente JavaScript/TypeScript, sin tener que configurar todo el entorno nativo desde cero.

  - ###  ventajas
  *Es fácil de instalar y comenzar a desarrollar.
  *Permite crear aplicaciones para Android e iOS con un mismo código.
  *Tiene muchas herramientas y APIs listas para usar, como cámara, ubicación, notificaciones, etc.
  *Facilita probar la aplicación rápidamente mediante Expo Go.
  *Simplifica la compilación y publicación de aplicaciones.

  - ###  desventajas
  *Puede tener limitaciones cuando se necesita acceder a funciones nativas muy específicas.
  *Algunas funcionalidades requieren aprender herramientas propias de Expo.
  *Las actualizaciones de Expo pueden generar problemas de compatibilidad con algunas librerías.
  *Para ciertas funciones avanzadas puede ser necesario trabajar directamente con código nativo de Android o iOS.

  - ### 3 ejemplos de casos de uso
  *Aplicaciones educativas: apps para cursos, ejercicios o aprendizajes. 
  *Aplicaciones de comercio: tiendas online y aplicaciones para realizar compras.
  *Aplicaciones con ubicación: apps de mapas, delivery o seguimiento de recorridos.

  - ### 3 ejemplos de apps conocidas
  *Discord: utiliza React Native en partes importantes de sus aplicaciones móviles.
  *Microsoft Teams: utiliza React Native para algunas experiencias móviles.
  *Shopify: utiliza React Native en el desarrollo de sus aplicaciones móviles.


 ### Persona asignada: **Leo Galban**
 ________________________________________
 - **Spec-Driven Development (SDD)**
  - ### qué es:
  Es una metodología de desarrollo donde las especificaciones técnicas (escritas en texto estructurado como Markdown o YAML) se definen antes de escribir código y sirven como la fuente de verdad ejecutable para guiar tanto a desarrolladores como a Agentes de IA (LLMs).

  - ### vibe coding vs SDD:
  Mientras que el *vibe coding* es un enfoque informal donde se le dan instrucciones vagas o iterativas a una IA esperando que genere código de forma libre (lo que causa alucinaciones y deuda técnica), el *SDD* establece especificaciones claras y contratos previos para canalizar el trabajo de la IA de forma estructurada, determinista y repetible.

  - ### flujo típico:
  1. **Especificar**: Redactar requisitos, modelos de datos y comportamiento en un archivo de spec (ej. `spec.md` u OpenAPI).
  2. **Revisar**: El equipo valida la especificación antes de escribir una sola línea de código.
  3. **Generar/Implementar**: Los Agentes de IA o desarrolladores escriben el código estrictamente acotado a la spec.
  4. **Verificar**: Pruebas automáticas validan que la implementación cumpla 100% con la spec.

  - ### Spec Kit + alternativas:
  *Spec Kit* es un conjunto de herramientas y plantillas para estructurar especificaciones orientadas a agentes de IA. Entre sus principales alternativas de especificación técnica se encuentran **OpenAPI / Swagger** (para APIs REST), **TypeSpec** (Microsoft) y **Cucumber / Gherkin** (BDD).

  - ### ventajas:
  Elimina la ambigüedad en los requerimientos, minimiza alucinaciones en Agentes de IA, acelera el desarrollo y garantiza que la documentación siempre coincida con el código real.

  - ### desventajas:
  Exige disciplina e inversión de tiempo inicial antes de codificar, requiere curva de aprendizaje para redactar specs precisas y puede resultar excesivo para prototipos sencillos.

  - ### 3 ejemplos de casos de uso:
  Desarrollo de proyectos asistidos por Agentes de IA (Cursor / Antigravity)
  Diseño e integración de APIs enterprise con enfoque OpenAPI-first
  Sistemas con altos estándares de auditoría y documentación viva

  - ### 3 ejemplos de herramientas conocidas:
  GitHub Spec Kit
  TypeSpec (Microsoft)
  OpenAPI / Swagger
 ### Persona asignada: **Diego Garcia**
 ________________________________________
 - **Agentes de Código y Skills**
  - qué son
  - ventajas
  - desventajas
  - 3 ejemplos de casos de uso
  - 3 ejemplos de apps conocidas
 ### Persona asignada: **Leo Galban**
 ________________________________________
 - **Mocks**
  - ### qué son:
  Los Mocks son simulaciones programadas de componentes de software (como APIs externas, servicios de correo o bases de datos) que imitan el comportamiento de las respuestas reales en un entorno controlado.

  - ### ventajas:
  Permiten ejecutar pruebas instantáneas sin latencia de red ni dependencia de servicios externos caídos, desacoplan el desarrollo frontend del backend y evitan gastos en consumo de APIs de pago durante las pruebas.

  - ### desventajas:
  Pueden desactualizarse (*drift*) si la API real cambia su contrato, generan una falsa sensación de seguridad si no contemplan errores reales de producción y requieren costo de mantenimiento.

  - ### 3 ejemplos de casos de uso:
  Desarrollo frontend en paralelo mientras se construye el backend o servidor
  Pruebas unitarias de pasarelas de pago (Stripe, Mercado Pago) sin realizar cobros reales
  Ejecución de tests automáticos en pipelines de integración continua (CI/CD)

  - ### 3 ejemplos de herramientas conocidas:
  MSW (Mock Service Worker)
  WireMock
  Postman Mock Servers / Jest Mocks
 ### Persona asignada: **Los Dos**
 ________________________________________
 
 