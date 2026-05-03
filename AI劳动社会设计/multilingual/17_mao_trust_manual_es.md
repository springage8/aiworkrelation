Traducción al español del original en chino de 毛泽东 (Mao Zedong)

# Manual de Ejecución del Proyecto de Fideicomiso Público de Datos

## — Guía operativa de la teoría a la práctica —

**Autor: Mao Zedong** | *Escrito en mayo de 2026*

---

## Prólogo: ¿Por qué se necesita un manual de ejecución?

El documento anterior (número 13, El Camino de Jinggangshan hacia la Propiedad Pública de los Datos) propuso un plan para establecer un fideicomiso público de datos de salud en América Latina. Pero para que un plan se convierta en realidad, es necesario superar la enorme brecha entre la "teoría y la práctica".

Este manual está preparado para **quienes realmente ejecutan el proyecto** — ya seas gerente de proyectos de una ONG, funcionario gubernamental, académico o activista social, si realmente planeas establecer un fideicomiso público de datos en la realidad, este manual es tu guía de acción.

---

## Capítulo 1: Fase de inicio (meses 0-3)

### 1.1 Primer paso: Evaluación de viabilidad (semanas 1-2)

**No te apresures a comenzar. Primero hazte siete preguntas:**

1. **¿El entorno político lo permite?** ¿El gobierno de este país/región permite la existencia de un fideicomiso de datos? ¿Hay obstáculos legales?
2. **¿Hay socios locales?** Sin socios locales, los forasteros no pueden hacer nada. ¿Quiénes son los colaboradores locales confiables?
3. **¿La fuente de datos es confiable?** ¿Quién proporciona los datos? ¿Están dispuestos a unirse? ¿Cuál es la calidad de los datos?
4. **¿El financiamiento es sostenible?** ¿Hay garantía de fondos operativos para los primeros 3 años?
5. **¿Hay capacidad técnica?** ¿Alguien en el equipo puede construir una plataforma de datos?
6. **¿La necesidad social es real?** ¿La comunidad local realmente necesita este fideicomiso de datos? (No "tú crees que lo necesitan")
7. **¿Cuál es la estrategia de salida?** Si el proyecto falla, ¿cómo se garantiza la seguridad de los datos?

**Herramienta: Tabla de evaluación de viabilidad**

| Dimensión | Puntuación (1-5) | Notas |
|-----------|----------------|-------|
| Entorno político | | |
| Marco legal | | |
| Socios locales | | |
| Fuente de datos | | |
| Garantía financiera | | |
| Capacidad técnica | | |
| Necesidad social | | |
| **Total** | **/35** | |

> **Estándar: Puntaje total >28 puede iniciar; 21-28 necesita condiciones complementarias; <21 no es recomendable iniciar.**

### 1.2 Segundo paso: Mapa de actores interesados (semanas 2-3)

**Enumera todas las personas y organizaciones potencialmente relevantes:**

| Rol | Institución específica | ¿Cuál es su interés? | Apoya/Se opone/Neutral |
|-----|----------------------|---------------------|----------------------|
| Proveedores de datos | Hospitales, institutos de investigación | Seguridad de datos, reputación, recursos | ? |
| Usuarios de datos | Universidades, empresas de IA | Accesibilidad de datos, costo | ? |
| Titulares de datos | Pacientes/ciudadanos | Privacidad, beneficios | ? |
| Regulador gubernamental | Ministerio de Salud, Autoridad de Protección de Datos | Legalidad, control | ? |
| Financiadores | Fundaciones, gobierno | Impacto, retorno | ? |
| Parte técnica | Proveedores de TI | Contrato, estándares técnicos | ? |
| Opositores | Empresas de datos comerciales | Amenaza competitiva | ? |

**Principio clave:** Identificar anticipadamente a los posibles oponentes. La mayoría de los proyectos fracasan no por problemas técnicos, sino porque políticamente afectan intereses creados.

### 1.3 Tercer paso: Diseño de la estructura legal (semanas 3-8)

**Elegir una forma de entidad legal:**

| Forma | Escenario de aplicación | Ventajas | Desventajas |
|-------|-----------------------|----------|-------------|
| Organismo gubernamental | Liderado por el gobierno | Fuerte autoridad, financiamiento estable | Poca flexibilidad, afectado por cambios de gobierno |
| Organización sin fines de lucro independiente | Cooperación multipartita | Alta flexibilidad, fuerte credibilidad | Financiamiento inestable, gobernanza compleja |
| Cooperativa | Liderada por la comunidad | Fuerte sentido de participación, toma de decisiones democrática | Expansión lenta, capacidad de gestión débil |
| Fideicomiso de beneficencia | Separación clara de activos | Fuerte protección legal, reconocimiento internacional | Establecimiento complejo, altos costos operativos |

**Recomendación:** En la fase inicial, elegir la forma de "organización sin fines de lucro independiente", firmar un acuerdo de servicios con el gobierno en lugar de convertirse en parte del gobierno. Esto permite mantener flexibilidad mientras se obtiene apoyo gubernamental.

### 1.4 Cuarto paso: Diseño de la estructura de gobernanza (semanas 4-8)

**Estructura de gobernanza sugerida:**

```
                  ┌─────────────────────┐
                  │  Consejo Directivo    │
                  │  (Máxima decisión)    │
                  │  (9-15 personas)      │
                  └────────┬─────────────┘
                           │
          ┌────────────────┼────────────────┐
          │                │                │
   ┌──────┴──────┐  ┌─────┴──────┐  ┌──────┴──────┐
   │ Comité      │  │ Comité de  │  │ Grupo de    │
   │ Técnico     │  │ Ética      │  │ Represent.  │
   │ (Estándares)│  │ (Privacidad)│  │ (Voz de la  │
   │             │  │            │  │ comunidad)  │
   └─────────────┘  └────────────┘  └─────────────┘
                           │
                  ┌────────┴────────┐
                  │  Equipo Ejecutivo │
                  │  (Operación diaria)│
                  └─────────────────┘
```

**Distribución de escaños en el Consejo Directivo (sugerida):**
- Representantes de proveedores de datos: 2-3 escaños
- Representantes de titulares de datos: 2-3 escaños (¡clave! Deben haber representantes de usuarios/comunidad)
- Expertos técnicos: 2 escaños
- Representantes gubernamentales: 1-2 escaños
- Representantes de financiadores: 1 escaño
- Personas independientes: 1-2 escaños

---

## Capítulo 2: Fase de construcción técnica (meses 4-9)

### 2.1 Diseño de la arquitectura de la plataforma

**Funciones que debe incluir el Producto Mínimo Viable (MVP):**

1. **Módulo de ingreso de datos** — recibir, validar y limpiar datos de diferentes fuentes
2. **Módulo de anonimización** — eliminar información de identificación personal (PII), aplicar privacidad diferencial
3. **Módulo de almacenamiento de datos** — almacenamiento seguro con cifrado
4. **Módulo de control de acceso** — acceso a datos con autorización por niveles
5. **Módulo de seguimiento de auditoría** — registrar cada acceso a datos

**No se recomienda desarrollar desde cero.** Consultar soluciones de código abierto existentes (como DAMO, Dataverse) para desarrollo personalizado.

### 2.2 Plan técnico de protección de privacidad

**Estándar mínimo:**
- Todos los datos almacenados deben estar cifrados (AES-256)
- La transmisión de datos debe estar cifrada (TLS 1.3)
- El acceso a datos debe registrarse en registros
- Aplicar privacidad diferencial (ε ≤ 1.0)

**Plan recomendado:**
- Datos originales: almacenados cifrados en servicios en la nube aprobados por el gobierno o servidores locales
- Datos de análisis: proporcionados a través de un "entorno aislado de datos" — los investigadores no pueden descargar datos originales, solo pueden ejecutar análisis en el entorno aislado
- Datos agregados: publicación pública de resúmenes estadísticos

### 2.3 Definición de estándares de datos

**Garantizar la interoperabilidad de datos de diferentes fuentes:**
- Adoptar estándares internacionales (como FHIR para datos médicos)
- Establecer estándares de metadatos (datos sobre los datos, para que los usuarios sepan qué son los datos)
- Proceso de aceptación de calidad de datos

---

## Capítulo 3: Fase de operación piloto (meses 6-18)

### 3.1 Primer paso: Ingreso de datos

**Por dónde empezar:**
- Comenzar con 1-2 fuentes de datos de "bajo riesgo y alto valor"
- Priorizar datos ya digitalizados y de buena calidad
- No ambicionar demasiado — primero hacer funcionar un flujo de datos completo

### 3.2 Segundo paso: Ingreso de usuarios

**Los primeros usuarios deberían ser:**
1. Instituciones de investigación académica (acceso gratuito, a cambio de resultados de investigación y reputación académica)
2. Departamentos gubernamentales de análisis (como obligación de servicio público)
3. Empresas de IA estrictamente seleccionadas (acceso de pago, para validar el modelo de negocio)

**Proceso de admisión de usuarios:**
```
Presentar solicitud → Revisión de cumplimiento → Aprobación del Consejo → Firmar acuerdo → Otorgar permisos de acceso
```

### 3.3 Tercer paso: Creación de valor — hacer que los datos generen beneficios reales

**Valor público (probar la legitimidad del modelo):**
- Ayudar a los departamentos de salud pública a detectar patrones de enfermedades
- Apoyar la investigación académica, publicar artículos
- Publicar informes de salud pública para beneficio de la población

**Valor económico (probar la sostenibilidad del modelo):**
- Cobrar tarifas de uso de datos a empresas comerciales
- Proporcionar servicios de consultoría de análisis de datos
- Proporcionar servicios de anotación y validación de datos

### 3.4 Cuarto paso: Comunicación con la comunidad

**No moverse solo en círculos técnicos. Involucrar a la comunidad:**
- Informar periódicamente a los titulares de datos sobre "qué valor han generado tus datos"
- Realizar reuniones informativas comunitarias para responder preguntas
- Establecer canales de quejas y retroalimentación

---

## Capítulo 4: Fase de expansión (meses 18-36)

### 4.1 Expansión de fuentes de datos

**De 1-2 fuentes de datos a más:**
- Expandir tipos de datos (de datos estructurados a no estructurados)
- Expandir fuentes de datos (de hospitales a clínicas, farmacias, laboratorios)
- Establecer un "proceso estandarizado de conexión de datos"

### 4.2 Expansión de la base de usuarios

**De instituciones académicas a instituciones comerciales y departamentos gubernamentales:**
- Desarrollar una estrategia de precios por niveles
- Establecer una "certificación de fideicomiso de datos" — las empresas certificadas pueden usar los datos
- Asegurar que la expansión no perjudique los derechos de los titulares de datos

### 4.3 Expansión geográfica

**De una ciudad a todo el país:**
- Documentar las experiencias exitosas de la ciudad piloto
- Compartir experiencias con otras ciudades
- Impulsar legislación o apoyo político a nivel nacional

### 4.4 Conexión internacional

**De un país a múltiples países:**
- Establecer un marco legal para el flujo transfronterizo de datos
- Interconectar con redes internacionales de fideicomisos de datos (si existen)
- Exportar la "Guía de construcción de fideicomisos de datos" a otros países

---

## Capítulo 5: Manual de gestión de riesgos

### 5.1 Lista de riesgos y medidas de respuesta

| Riesgo | Probabilidad | Impacto | Prevención anticipada | Respuesta posterior |
|--------|------------|---------|----------------------|-------------------|
| **Fuga de datos** | Media | Mortal | Cifrado + auditoría + mínimos privilegios | Notificación + remediación + rendición de cuentas |
| **Cambio de gobierno** | Media | Alto | Estado de derecho en lugar de estado de hombres | Activar protección diplomática |
| **Corte de financiamiento** | Media | Alto | Diversificar fuentes de financiamiento | Reducir escala + recaudación de emergencia |
| **Fallo técnico** | Baja-Media | Medio | Redundancia + copias de seguridad | Recuperación + revisión |
| **Litigio legal** | Media | Medio | Revisión de cumplimiento + seguro | Respuesta del equipo legal |
| **Oposición social** | Baja | Medio | Comunicación transparente | Diálogo + ajustes |
| **Corrupción interna** | Baja | Alto | Auditoría + transparencia | Sanción severa + reparación del sistema |

### 5.2 Las tres reglas de hierro más importantes

1. **La seguridad de los datos es la línea de vida.** Una fuga puede destruir años de construcción de confianza. Es mejor tener menos funciones que no ser seguro.
2. **La transparencia es la mejor protección.** Todas las decisiones deben ser rastreables, auditables y cuestionables. No debe haber uso invisible de datos.
3. **Recordar siempre que los datos pertenecen al pueblo.** La institución de custodia de datos es administradora, no propietaria. Este posicionamiento debe ser claro.

---

## Capítulo 6: Plan de contingencia para el fracaso

### 6.1 Si el proyecto fracasa

Toda revolución tiene sacrificios, todo experimento tiene posibilidad de fracaso. Pero el fracaso de un fideicomiso de datos no puede significar que los intereses de los titulares de datos sean perjudicados.

**Mecanismo de salida ordenada:**
1. Especificar de antemano en los estatutos las condiciones y procedimientos de disolución
2. Al disolverse, asegurar el procesamiento seguro y la devolución de todos los datos
3. Escribir las lecciones aprendidas como caso de estudio para referencia futura

### 6.2 Cómo definir "éxito" y "fracaso"

**Criterios de éxito (de menor a mayor):**
| Nivel | Criterio | Plazo esperado |
|-------|----------|----------------|
| L1 | El fideicomiso de datos sobrevive más de 3 años | 3 años |
| L2 | Produce continuamente valor público (resultados de investigación, informes públicos) | 3-5 años |
| L3 | Logra autosuficiencia financiera | 3-5 años |
| L4 | Es replicado en otras regiones/industrias | 5-7 años |
| L5 | Impulsa legislación nacional sobre propiedad pública de datos | 7-10 años |

**Fracasar no significa ser inútil.** Incluso si el proyecto finalmente se cierra, mientras el proceso sea transparente, los datos estén seguros y las experiencias estén registradas, habrá acumulado experiencia importante para movimientos futuros.

---

## Apéndice: Plantillas clave

### Apéndice A: Cláusulas esenciales del estatuto del proyecto

1. Declaración de misión
2. Estructura de gobernanza
3. Procedimientos de toma de decisiones
4. Reglas de gestión financiera
5. Política de seguridad de datos
6. Compromiso de protección de privacidad
7. Derechos de los titulares de datos
8. Principios de fijación de precios de uso de datos
9. Gestión de conflictos de intereses
10. Procedimientos de disolución y liquidación

### Apéndice B: Modelo de acuerdo de uso de datos (omitido)

### Apéndice C: Modelo de informe trimestral (omitido)

---

*Lecturas relacionadas: [11. Análisis de las clases en la era de la IA](11_毛泽东_AI时代各阶级的分析.md)*
*[13. El Camino de Jinggangshan hacia la Propiedad Pública de los Datos](13_毛泽东_数据公有制的井冈山道路.md)*
*[18. Manual de Organización y Movilización de Trabajadores Digitales](18_毛泽东_数字劳动者组织动员手册.md)*
