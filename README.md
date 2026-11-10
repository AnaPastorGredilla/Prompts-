→ INTRO
  Portafolio de prompt engineering aplicado a Customer Success (CS) en empresas SaaS B2B. Proyecto del Máster de IA 
  
→ EL PROBLEMA 
  Un equipo de Customer Success escribe decenas de comunicaciones al mes: bienvenidas, seguimientos de onboarding, check-ins de adopción, propuestas de expansión y
  preparación de renovaciones. Hoy esto genera tres problemas:
    - Tiempo: Cada email se escribe casi desde cero. 
    - Inconsistencia: El tono y la calidad dependen de quien lo escriba y de su día. 
    - Detección tardía del riesgo: Las señales de que una cuenta se está enfriando entán dispersas entre varias herramientas y se ven tarde. 
    
→ La solución
  - Generación mediante prompts de unas comunicaciones por fase del ciclo de vida del cliente, iterando cuando sea necesario con más información para llegar
    a la mejor versión de dicha comunicación generada mediante prompts. 
  - Asistente de Health de la cuenta que clasifica el riesgo de la cuenta, solicita datos que falten y genera un plan de acción personalizado.
  - Tegistro del proceso, pruebas y fallos.

→ Ciclo de vida cubierto
  1. Bienvenida.
  2. Onboarding.
  3. Adopción.
  4. Expansión.
  5. Renovación.

→ Estructura
  - Prompts: Los prompts utilizados para las diferentes comunicaciones para los distintos ciclos de vida del ciente junto con un changelog que explique que cambió y porqué.
  - Asistente: Instrucciones del asistente personalizado en Claude y resultado de dicho asistente.
  - Diario del proceso: Casos de uso y primer resultado de plan de acción para cliente.

→ Metodología
  1. Versión simple de un primer prompt utilizando un cliente de prueba con un caso preciso.
  2. Corrección de el resultado con los distintos prompts complementarios para llegar a la versión definitiva.
  3. identificación del fallo inicial y replica en los distintos mensajes.
  4. Generación del asistente mediante artefactos de Claude e introducción de información necesaria para que el asistente pueda generar el aporte necesario.

→ Progreso
  - [x] Fase 1 — Definición del problema y estructura del repositorio.
  - [ ] Fase 2 — Prompts e iteración de las 5 comunicaciones.
  - [ ] Asistente Health configurado y probado.
  - [ ] Diario con casos de uso y primera conversación concluyente.
