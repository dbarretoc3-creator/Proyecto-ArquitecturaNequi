# Proyecto de Arquitectura Empresarial y Tecnológica
## Independencia Tecnológica y Operativa de Nequi

**Integrantes:** Esteban Barreto · Bryan Camilo Garavito · David Verdugo

---

## Introducción

Nequi nació asociado a Bancolombia y actualmente busca consolidar su operación como entidad financiera. Este proyecto plantea una transformación orientada a fortalecer la independencia tecnológica y operativa de Nequi, sin afectar la experiencia de los usuarios ni la continuidad de los servicios.

La problemática central consiste en reducir las dependencias tecnológicas y estructurales que pueden limitar la autonomía de Nequi, manteniendo la seguridad de la información, la disponibilidad de la plataforma, la interoperabilidad con terceros y la capacidad de crecimiento. La arquitectura propuesta busca que Nequi controle directamente sus servicios, datos y componentes tecnológicos principales, mientras conserva integraciones puntuales y seguras con Bancolombia cuando sean necesarias.

## 1. Establecer el proyecto de arquitectura

El propósito es diseñar una arquitectura tecnológica objetivo que permita a Nequi avanzar hacia una mayor independencia tecnológica y operativa frente a Bancolombia. No se pretende eliminar todas las relaciones existentes, sino transformar las dependencias estructurales en integraciones controladas, documentadas y seguras.

Necesidades principales:

- Fortalecer la autonomía tecnológica y operativa de Nequi.
- Proteger usuarios, datos y transacciones.
- Mantener una alta disponibilidad de los servicios.
- Reducir dependencias tecnológicas externas.
- Conservar integraciones seguras con Bancolombia y otros terceros.
- Preparar la plataforma para el crecimiento de usuarios y transacciones.

## 2. Partes interesadas, preocupaciones y requisitos del negocio

- **Clientes:** seguridad, disponibilidad, facilidad de uso y continuidad de los servicios.
- **Nequi:** independencia tecnológica, crecimiento sostenible y control sobre sus sistemas.
- **Área de tecnología:** estabilidad, escalabilidad, mantenibilidad e interoperabilidad.
- **Equipos de seguridad:** protección de datos, monitoreo y controles de acceso.
- **Bancolombia:** separación segura y continuidad de las integraciones necesarias.
- **Grupo Cibest:** continuidad, control y transformación organizada.
- **Reguladores:** cumplimiento de las normas aplicables al sector financiero.
- **Comercios y aliados:** continuidad de pagos e integraciones confiables.

Las principales preocupaciones del negocio son la seguridad, la protección de datos, la disponibilidad, la interoperabilidad, la escalabilidad y la continuidad. Estos elementos se convierten en requisitos fundamentales de la arquitectura.

## 3. Objetivos, impulsores y limitaciones

### 3.1 Objetivos del negocio

- **Independencia tecnológica:** administrar progresivamente servicios y sistemas propios.
- **Seguridad de la información:** proteger datos, cuentas y transacciones.
- **Alta disponibilidad:** mantener los servicios activos y accesibles.
- **Continuidad del negocio:** evitar interrupciones durante la transición.
- **Reducción de dependencias:** disminuir la dependencia de tecnologías o estructuras externas.
- **Interoperabilidad:** mantener integraciones seguras con Bancolombia.
- **Escalabilidad:** soportar el crecimiento de usuarios y transacciones.
- **Innovación tecnológica:** facilitar nuevos servicios y soluciones financieras.
- **Transformación digital:** modernizar la operación y los servicios.
- **Autonomía operativa:** aumentar la capacidad de decisión sobre los procesos.
- **Competitividad:** fortalecer la posición de Nequi frente a otras plataformas.
- **Experiencia del cliente:** mejorar la facilidad y rapidez de los servicios.
- **Eficiencia operativa:** optimizar procesos y reducir la complejidad tecnológica.

### 3.2 Impulsores del negocio

El principal impulsor es la necesidad de consolidar a Nequi como una operación con mayor autonomía, capaz de controlar sus capacidades tecnológicas y responder con mayor flexibilidad a sus necesidades futuras.

- La consolidación de Nequi como entidad financiera.
- La necesidad de mayor autonomía y control tecnológico.
- El crecimiento de usuarios y transacciones.
- La necesidad de modernización e innovación.
- El fortalecimiento de la competitividad.
- La necesidad de reducir complejidad y dependencias.

### 3.3 Limitaciones

- **Presupuesto de transformación:** la separación tecnológica requiere inversiones importantes.
- **Sistemas heredados:** existen tecnologías y procesos que deben adaptarse o reemplazarse.
- **Regulación financiera:** los cambios deben cumplir las normas aplicables.
- **Acuerdos con terceros:** algunos servicios requieren conservar relaciones con otras organizaciones.
- **Tiempo de transición:** la transformación debe realizarse de forma gradual.
- **Riesgo operativo:** un cambio incorrecto podría afectar procesos o servicios existentes.

## 4. Evaluar las capacidades del negocio

Nequi cuenta con capacidades relevantes para ejecutar la transformación, especialmente por ser una plataforma digital que ya gestiona usuarios y operaciones financieras.

- Gestión digital de usuarios y servicios financieros.
- Gestión de transacciones y pagos.
- Operación de servicios digitales.
- Capacidad de integración con sistemas externos.
- Gestión y protección de información crítica.
- Capacidad de escalar servicios según el crecimiento de la demanda.
- Capacidad para adoptar nuevas tecnologías y servicios.

La principal brecha no está en la existencia de una operación digital, sino en lograr que las capacidades críticas puedan administrarse con mayor independencia y menor dependencia estructural de terceros.

## 5. Evaluar la preparación para la transformación del negocio

La preparación de Nequi para la transformación puede considerarse favorable. Su modelo 100 % digital y su experiencia gestionando operaciones financieras proporcionan una base tecnológica y operativa adecuada.

Sin embargo, la transformación no debe realizarse como un cambio inmediato, debido al impacto potencial sobre los datos, la seguridad, las integraciones y la continuidad. Los principales retos son la migración de datos, la separación de dependencias, la protección de la información y la continuidad del servicio.

Se requiere una estrategia gradual, acompañada de pruebas, respaldos, monitoreo y mecanismos de recuperación. El nivel de preparación puede resumirse como alto, pero condicionado a una gestión rigurosa del cambio.

## 6. Definir el alcance

El alcance comprende el diseño de la arquitectura tecnológica de Nequi necesaria para fortalecer su independencia, manteniendo seguridad, disponibilidad, continuidad e interoperabilidad.

### 6.1 Dentro del alcance

- Arquitectura tecnológica de Nequi.
- Gestión de usuarios y transacciones.
- Protección y gestión de datos.
- Seguridad y controles tecnológicos.
- Disponibilidad y continuidad de servicios.
- Servicio de retiros e integración necesaria con Bancolombia.
- Migración y separación tecnológica progresiva.
- Integraciones externas relacionadas con las capacidades objetivo.

### 6.2 Fuera del alcance

- Diseño interno de Bancolombia.
- Hardware y funcionamiento interno de los cajeros.
- Contabilidad y regulación completa de Bancolombia.
- Diseño detallado de la aplicación móvil.

Bancolombia se considera un sistema externo. El proyecto no busca reemplazar todo lo relacionado con Bancolombia, sino establecer una relación de integración puntual, especialmente para los servicios que todavía requieren interoperabilidad.

## 7. Principios de la arquitectura

- **Independencia tecnológica:** los componentes críticos de Nequi deben poder administrarse sin depender estructuralmente de Bancolombia.
- **Seguridad desde el diseño:** la protección de datos y transacciones debe incorporarse desde la arquitectura.
- **Continuidad del servicio:** ninguna etapa debe comprometer innecesariamente los servicios actuales.
- **Datos bajo control de Nequi:** los datos críticos deben permanecer y administrarse dentro del entorno controlado por Nequi.
- **Interoperabilidad:** las integraciones externas deben realizarse mediante interfaces definidas, seguras y controladas.
- **Escalabilidad:** la arquitectura debe soportar incrementos de usuarios y transacciones.
- **Modularidad:** los servicios deben organizarse para evolucionar y migrarse progresivamente.
- **Observabilidad y trazabilidad:** las operaciones críticas deben poder monitorearse y auditarse.
- **Cumplimiento:** las decisiones tecnológicas deben considerar las obligaciones aplicables al sector financiero.
- **Experiencia del usuario:** la transformación tecnológica debe ser transparente para el cliente siempre que sea posible.

## 8. Visión de la arquitectura

La visión propuesta es que Nequi disponga de una arquitectura tecnológica propia, modular, segura, escalable y altamente disponible, donde los servicios esenciales —usuarios, transacciones, pagos, seguridad y datos— estén bajo su control.

La arquitectura objetivo plantea un **API Gateway** como punto central para dirigir y controlar las solicitudes hacia los diferentes servicios. Los datos permanecerán dentro del entorno de Nequi, mientras que Bancolombia dejará de representar una dependencia estructural y pasará a funcionar como un punto de integración específico cuando el negocio lo requiera.

La transición se realizará progresivamente:

1. Identificar y desacoplar dependencias.
2. Migrar capacidades y datos de manera controlada.
3. Consolidar el modelo independiente.

Cada etapa deberá contar con pruebas, respaldos, monitoreo y mecanismos de recuperación.

## 9. Propuestas de valor de la arquitectura objetivo y KPI

La arquitectura objetivo aporta valor porque aumenta el control de Nequi sobre sus sistemas y datos, fortalece la seguridad, disminuye dependencias, facilita el crecimiento y protege la continuidad de los servicios.

- Mayor control sobre sistemas, servicios y datos.
- Mayor protección de la información crítica.
- Menor dependencia tecnológica estructural.
- Mayor capacidad de crecimiento y escalabilidad.
- Mejor capacidad para innovar y lanzar nuevos servicios.
- Integraciones externas más controladas y seguras.
- Mayor resiliencia y capacidad de recuperación.

### 9.1 Indicadores clave de desempeño (KPI)

| Indicador | Meta propuesta | Propósito |
|---|---:|---|
| Disponibilidad | ≥ 99,9 % | Garantizar continuidad del servicio. |
| Transacciones exitosas | ≥ 99,5 % | Reducir fallos en operaciones. |
| Recuperación ante fallos | ≤ 30 min | Restablecer servicios críticos rápidamente. |
| Integraciones seguras | 100 % | Asegurar que las conexiones externas cumplan controles. |
| Pérdida de datos | 0 | Proteger la integridad de la información. |

*Las metas anteriores son propuestas del proyecto, no resultados medidos.*

## 10. Riesgos de la transformación y actividades de mitigación

| Riesgo | Impacto | Mitigación |
|---|---|---|
| Pérdida de información | Alto | Copias de seguridad, validación y reconciliación de datos antes y después de cada migración. |
| Caída del servicio | Alto | Arquitectura redundante, despliegues graduales y planes de recuperación. |
| Ataques informáticos | Alto | Controles de seguridad, monitoreo, gestión de accesos y pruebas de seguridad. |
| Error en la migración | Alto | Migración progresiva, pruebas piloto, validación y posibilidad de reversión. |
| Problemas con Bancolombia | Medio/Alto | Diseñar integraciones independientes, documentadas y con mecanismos de contingencia. |
| Incumplimiento regulatorio | Alto | Controles, auditorías y validación de requisitos regulatorios durante el proyecto. |
| Resistencia al cambio | Medio | Gestión del cambio, capacitación y comunicación entre equipos. |
| Sobrecostos o retrasos | Medio | Priorización por fases, seguimiento de hitos y control del presupuesto. |

## 11. Declaración de Trabajo de Arquitectura y aprobación

La Declaración de Trabajo de Arquitectura establece qué se realizará, con qué propósito y cuáles serán los resultados esperados. El trabajo busca lograr una mayor independencia tecnológica y operativa de Nequi frente a Bancolombia sin afectar la experiencia de los usuarios.

### 11.1 Objetivo

Diseñar una arquitectura tecnológica objetivo que permita a Nequi controlar progresivamente sus servicios, datos y componentes tecnológicos críticos, reducir dependencias estructurales y conservar únicamente las integraciones externas necesarias y seguras.

### 11.2 Actividades principales

- Levantar y documentar las dependencias tecnológicas actuales.
- Identificar servicios y capacidades críticas.
- Definir la arquitectura objetivo.
- Diseñar la estrategia de desacoplamiento e integración.
- Planificar la migración progresiva de datos y servicios.
- Definir mecanismos de seguridad, respaldo, monitoreo y recuperación.
- Establecer indicadores KPI y mecanismos de seguimiento.
- Realizar pruebas antes de cada migración.
- Documentar resultados, riesgos y decisiones de arquitectura.

### 11.3 Entregables

- Documento de arquitectura actual y objetivo.
- Mapa de capacidades y dependencias.
- Modelo de integración con sistemas externos.
- Estrategia de migración y transición.
- Plan de seguridad y continuidad.
- Matriz de riesgos y mitigaciones.
- Modelo de KPI y seguimiento.
- Declaración de Trabajo de Arquitectura.

### 11.4 Aprobación

La aprobación debe realizarse por los responsables del negocio, tecnología, seguridad y demás áreas que participen directamente en la transformación. La aceptación debe confirmar que el alcance, objetivos, principios, riesgos, indicadores y entregables son coherentes con la estrategia de independencia de Nequi.

Como criterio de aprobación, el proyecto debe demostrar que la arquitectura propuesta permite avanzar hacia una mayor autonomía sin comprometer la seguridad de la información, la continuidad de los servicios, el cumplimiento de las obligaciones aplicables ni la experiencia del usuario.

## 12. Matriz de evaluación de brechas

La matriz compara la situación actual de Nequi con la situación objetivo para identificar qué capacidades, procesos y componentes tecnológicos deben fortalecerse. La prioridad indica qué tan importante es cerrar cada brecha para alcanzar la arquitectura objetivo.

| Dominio | Situación actual | Situación objetivo | Brecha identificada | Prioridad | Acción propuesta |
|---|---|---|---|---|---|
| Independencia tecnológica | Nequi mantiene dependencias tecnológicas y operativas relacionadas con Bancolombia. | Nequi controla sus servicios y componentes tecnológicos críticos. | Dependencias estructurales que limitan la autonomía. | Alta | Desacoplar progresivamente servicios y establecer componentes propios. |
| Gestión de datos | Existen datos y procesos que deben separarse y migrarse de forma controlada. | Los datos críticos permanecen bajo el control del entorno de Nequi. | Dependencias y riesgos asociados a la migración de información. | Alta | Diseñar una estrategia de migración, respaldo, validación y reconciliación. |
| Seguridad de la información | La seguridad es crítica por el carácter financiero de la plataforma. | Seguridad incorporada desde el diseño, con monitoreo y controles de acceso. | Necesidad de fortalecer controles durante la transformación. | Alta | Implementar controles de seguridad, monitoreo, auditoría y gestión de accesos. |
| Disponibilidad | Los servicios actuales deben mantenerse activos durante la transición. | Disponibilidad objetivo de al menos 99,9 %. | Riesgo de interrupciones durante migraciones y cambios. | Alta | Arquitectura redundante, pruebas y mecanismos de recuperación. |
| Interoperabilidad | Nequi necesita conservar determinadas integraciones con Bancolombia y terceros. | Integraciones puntuales, seguras, documentadas y controladas. | Dependencias que deben convertirse en integraciones desacopladas. | Alta | Controlar las integraciones mediante APIs y mecanismos seguros. |
| Escalabilidad | La plataforma debe responder al crecimiento de usuarios y transacciones. | Arquitectura capaz de crecer sin afectar el servicio. | Necesidad de asegurar capacidad tecnológica para el crecimiento futuro. | Media/Alta | Diseñar componentes modulares y escalables y monitorear capacidad. |
| Continuidad del negocio | Una transformación incorrecta podría afectar servicios existentes. | Transición gradual con respaldo y recuperación ante fallos. | Falta de tolerancia al riesgo en cambios críticos. | Alta | Definir planes de continuidad, contingencia, respaldo y reversión. |
| Migración tecnológica | Existen sistemas y dependencias que deben adaptarse o reemplazarse. | Migración progresiva hacia componentes bajo control de Nequi. | Complejidad y riesgo de errores durante la migración. | Alta | Realizar pilotos, pruebas, migraciones por fases y validaciones. |
| Arquitectura de servicios | Las capacidades deben evolucionar hacia una mayor autonomía. | Servicios propios para usuarios, transacciones, pagos, seguridad y datos. | Necesidad de separar y modularizar capacidades críticas. | Alta | Definir una arquitectura modular y servicios desacoplados. |
| Gobierno y control tecnológico | La transformación requiere decisiones coordinadas entre negocio, tecnología y seguridad. | Mayor autonomía y control sobre decisiones y activos tecnológicos. | Necesidad de fortalecer mecanismos de gobierno y seguimiento. | Media/Alta | Definir responsables, indicadores, políticas y mecanismos de seguimiento. |

### 12.1 Resumen de las brechas prioritarias

- **Independencia:** reducir las dependencias estructurales con Bancolombia.
- **Datos:** garantizar que la información crítica pueda ser gestionada directamente por Nequi.
- **Seguridad:** mantener y fortalecer los controles de protección.
- **Continuidad:** realizar migraciones sin afectar los servicios de los usuarios.
- **Interoperabilidad:** mantener las relaciones necesarias con Bancolombia como integraciones controladas.
- **Escalabilidad:** preparar la arquitectura para el crecimiento de usuarios y transacciones.
- **Migración:** aplicar una estrategia gradual con pruebas, respaldos y mecanismos de reversión.

### 12.2 Interpretación de la matriz

Las brechas de mayor prioridad están relacionadas con independencia tecnológica, datos, seguridad, disponibilidad, continuidad, interoperabilidad y migración. Estas áreas tienen una relación directa con la problemática principal del proyecto y deben atenderse antes de considerar consolidada la arquitectura objetivo.

La brecha no significa necesariamente que Nequi carezca de estas capacidades. En varios casos, la capacidad ya existe, pero debe evolucionar para funcionar con mayor autonomía, control y resiliencia. Por esta razón, el proyecto debe plantearse como una transformación progresiva y no como un reemplazo inmediato de todos los sistemas.

---

## Nota

Este repositorio contiene la documentación académica de la propuesta de arquitectura. Las metas, acciones y estados objetivo descritos representan el planteamiento del proyecto y no deben interpretarse como una auditoría de la arquitectura interna real de Nequi.
