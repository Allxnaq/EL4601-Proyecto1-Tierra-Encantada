# Registro de uso de herramientas de Inteligencia Artificial

## Proyecto
**Diseño de un Sistema de Detección y Alarma Contra Incendios para Tierra Encantada – Addison, Texas**

Curso: **EL-4601 Normalización Técnica para Electrónica**  
Instituto Tecnológico de Costa Rica

## Herramienta principal utilizada
ChatGPT (OpenAI)

La herramienta de inteligencia artificial se utilizó como apoyo para la
organización del documento, investigación y revisión normativa, análisis
del edificio, selección y verificación de equipos, estructuración de los
planos del sistema, cálculos eléctricos y revisión de consistencia del
informe.

La información técnica generada o sugerida mediante IA fue posteriormente
contrastada con fuentes oficiales, códigos, normas, documentación del
Town of Addison y hojas técnicas de los fabricantes.

---

# 1. Estructuración inicial del proyecto

## Prompt 1 – Estructura general del informe

Necesito desarrollar el Proyecto 1 del curso EL-4601 Normalización Técnica
para Electrónica. El proyecto consiste en diseñar un sistema de detección
y alarma contra incendios para un edificio real ubicado en Estados Unidos.

El edificio seleccionado es Tierra Encantada – Addison, ubicado en
14450 Marsh Lane, Addison, Texas.

Ayúdame a estructurar el documento completo tomando en cuenta los
requerimientos del proyecto. El informe debe incluir investigación
normativa, análisis del edificio, selección de equipos, diseño del sistema,
planos, cálculos eléctricos, Device Schedule, Bill of Materials, análisis,
conclusiones, referencias y apéndices.

Quiero trabajar el documento en LaTeX con formato académico. No inventes
datos que no puedan verificarse. Cuando exista información incompleta,
indícalo claramente y diferencia entre hechos documentados, decisiones de
diseño y aspectos que necesiten confirmación de la AHJ.

---

# 2. Investigación normativa

## Prompt 2 – Normativa aplicable en Addison, Texas

Investiga qué códigos, normas y requisitos son aplicables al diseño de un
sistema de detección y alarma contra incendios para Tierra Encantada –
Addison, Texas.

Revisa especialmente:

- International Building Code (IBC).
- International Fire Code (IFC).
- NFPA 72.
- NFPA 70 / National Electrical Code.
- Modificaciones locales del Town of Addison.
- Requisitos de producto y listados UL.
- Requisitos de la Authority Having Jurisdiction (AHJ).

Identifica las ediciones utilizadas y explica qué función cumple cada
documento dentro del proyecto.

Utiliza preferentemente fuentes oficiales del Town of Addison, ICC, NFPA,
UL y fabricantes. No inventes números de artículos. Si algún requisito no
puede verificarse directamente, indícalo.

---

## Prompt 3 – Requisitos locales del Town of Addison

Revisa las modificaciones locales del Town of Addison al International
Fire Code y determina cuáles afectan directamente nuestro sistema de
alarma contra incendios.

Necesito identificar requisitos relacionados con:

- sistema manual y automático;
- dispositivos iniciadores direccionables;
- notificación audible y visual;
- cantidad de FACP permitidos;
- remote annunciator;
- supervisión y monitoreo remoto;
- horn/strobe exterior;
- Fire Department Connection;
- hidrantes;
- señalización de la FDC.

Relaciona cada requisito con una decisión concreta del diseño y crea una
matriz normativa que muestre fuente, sección, requisito y aplicación al
proyecto.

---

# 3. Análisis del edificio

## Prompt 4 – Análisis de Tierra Encantada – Addison

Analiza los planos y la documentación pública de Tierra Encantada –
Addison correspondientes al Town of Addison Case 1842-SUP y al registro
TDLR.

Extrae únicamente información verificable relacionada con:

- dirección;
- uso del edificio;
- número de niveles;
- área;
- número de aulas;
- distribución de espacios;
- pasillos;
- accesos y salidas;
- cocina;
- lavandería;
- cuarto mecánico;
- lobby;
- oficina;
- áreas exteriores;
- estacionamientos;
- hidrantes y acceso de emergencia.

No inventes dimensiones que no aparezcan en los documentos.

Si diferentes fuentes presentan áreas o capacidades distintas, conserva
la discrepancia y explícala en el informe en lugar de escoger un valor
arbitrariamente.

---

## Prompt 5 – Clasificación de ocupación

Analiza la clasificación de ocupación aplicable a Tierra Encantada –
Addison según el IBC.

Compara específicamente Group E – Educational y Group I-4 – Day Care,
considerando que el edificio funciona como daycare y educación preescolar
y atiende niños de distintas edades.

Explica las condiciones que podrían permitir clasificar determinadas áreas
como Group E y cuáles podrían mantener consideración I-4.

No determines una clasificación definitiva si los planos no permiten
demostrar todas las condiciones. En ese caso utiliza un criterio
conservador y deja la clasificación final sujeta a confirmación de la AHJ.

---

# 4. Arquitectura del sistema

## Prompt 6 – Sistema convencional vs. direccionable

Compara un sistema convencional de alarma contra incendios con un sistema
direccionable para el edificio Tierra Encantada – Addison.

Explica las ventajas y desventajas de ambos y determina cuál resulta más
apropiado considerando:

- las modificaciones locales del Town of Addison;
- identificación individual de dispositivos;
- transmisión descriptiva de alarmas;
- supervisión;
- mantenimiento;
- capacidad de expansión;
- complejidad y costo.

La selección debe quedar técnicamente justificada y no basarse únicamente
en preferencia.

---

# 5. Selección de equipos

## Prompt 7 – Selección de una familia comercial compatible

Selecciona equipos reales y comercialmente disponibles para implementar
el sistema direccionable propuesto.

Preferiblemente utiliza una familia principal de un mismo fabricante para
facilitar la compatibilidad.

Necesito seleccionar como mínimo:

- Fire Alarm Control Panel;
- detector fotoeléctrico direccionable;
- detector térmico direccionable;
- estación manual direccionable;
- strobe;
- speaker/strobe;
- horn/strobe exterior weatherproof;
- sistema de evacuación por voz;
- módulo de monitoreo;
- remote annunciator;
- comunicador hacia estación supervisora;
- baterías;
- cableado.

Para cada equipo indica fabricante, modelo, función, características
eléctricas relevantes, compatibilidad y razón por la cual resulta
apropiado para el proyecto.

Utiliza exclusivamente documentación oficial del fabricante para justificar
especificaciones.

---

## Prompt 8 – Selección de Potter e IPA-100

Compara opciones comerciales de paneles direccionables y determina si el
Potter IPA-100 es apropiado para este proyecto.

Comprueba su capacidad de dispositivos direccionables, capacidad del SLC,
NAC disponibles, fuente de alimentación, baterías admitidas y
compatibilidad con dispositivos Potter PAD.

También compara brevemente la solución con opciones equivalentes de
Fire-Lite y Siemens para justificar por qué Potter puede utilizarse como
fabricante principal.

---

## Prompt 9 – Matriz de compatibilidad

Revisa todos los equipos Potter seleccionados y crea una matriz de
compatibilidad.

La matriz debe indicar:

- equipo origen;
- equipo conectado;
- interfaz utilizada;
- protocolo o tensión;
- evidencia de compatibilidad.

Incluye como mínimo las relaciones entre:

- IPA-100 y PAD300-PD;
- IPA-100 y PAD300-HD;
- IPA-100 y PAD100-PSDA;
- IPA-100 y PAD100-TRTI;
- IPA-100 y RA-6500F;
- IPA-100 e IntelliCom;
- IPA-100 y EVAX-5070;
- EVAX-5070 y PE-SPST;
- IPA-100 y los dispositivos visuales PE;
- IPA-100 y el horn/strobe exterior.

Diferencia entre compatibilidad mediante protocolo propietario y
compatibilidad mediante interfaces eléctricas documentadas.

---

# 6. Diseño sobre planos

## Prompt 10 – FA-01: ubicación de dispositivos

Utiliza la planta arquitectónica de Tierra Encantada – Addison para
proponer la ubicación de los dispositivos del sistema de alarma.

Necesito representar:

- FACP;
- detectores de humo;
- detectores térmicos;
- estaciones manuales;
- speaker/strobes;
- strobes;
- remote annunciator;
- comunicador;
- EVACS;
- módulo de monitoreo.

Justifica las ubicaciones utilizando IFC, NFPA 72, las modificaciones
locales de Addison y las condiciones de cada espacio.

No coloques detectores arbitrariamente. Considera que cocina, lavandería y
cuarto mecánico pueden requerir un criterio diferente a las aulas.

---

## Prompt 11 – FA-02: diagrama general de interconexión

Ayúdame a elaborar un diagrama general de interconexión del sistema.

El diagrama debe representar funcionalmente:

- FACP-01 Potter IPA-100;
- SLC-1;
- dispositivos direccionables;
- NAC-1 y NAC-2;
- EVACS-01 Potter EVAX-5070;
- SPK-1 y SPK-2;
- ANN-01;
- COM-01;
- interfaz de control entre FACP y EVACS;
- alimentación primaria;
- baterías de respaldo;
- integración preliminar del sistema de rociadores.

El objetivo no es mostrar cada conductor individual, sino que el profesor
pueda comprender claramente cómo se relacionan todos los subsistemas.

---

## Prompt 12 – FA-03: circuitos y cableado

Define la topología de los circuitos que deben representarse en FA-03.

Utiliza la nomenclatura:

- SLC-1;
- NAC-1;
- NAC-2;
- SPK-1;
- SPK-2;
- P-LINK-1;
- ETH-1;
- CTRL-1.

Determina qué dispositivos pertenecen a cada circuito y representa los
recorridos de forma legible.

El proyecto utilizará configuración Class B para SLC, NAC y circuitos de
altavoces cuando sea compatible con los equipos seleccionados.

Verifica también qué resistencias EOL corresponden a los NAC y a los
circuitos de altavoces. No asumas que el SLC utiliza la misma resistencia
que un NAC.

---

## Prompt 13 – FA-04: coordinación exterior

Analiza el plano exterior del edificio y desarrolla una propuesta para
FA-04.

Debemos mostrar:

- un hidrante existente identificado como FH-EX;
- una FDC propuesta identificada como FDC-01;
- señalización FDC SIGN;
- un horn/strobe exterior EHS-01.

Aplica las modificaciones locales de Addison relacionadas con FDC,
hidrantes, fire lane, señalización y horn/strobe exterior.

No presentes una FDC como existente si no aparece claramente documentada
en el plano original. Su ubicación debe mostrarse como propuesta y quedar
sujeta a aprobación del Fire Marshal.

---

# 7. Diseño eléctrico y cálculos

## Prompt 14 – Cálculos eléctricos completos

Realiza los cálculos eléctricos necesarios para verificar la viabilidad
del sistema propuesto.

Incluye:

1. Capacidad utilizada del SLC del IPA-100.
2. Corriente de standby y alarma de los dispositivos direccionables.
3. Corriente de NAC-1.
4. Corriente de NAC-2, incluyendo preliminarmente EHS-01.
5. Capacidad disponible de los NAC del IPA-100.
6. Caída de tensión utilizando conductor Belden 5300UL 18 AWG.
7. Capacidad de SPK-1 y SPK-2.
8. Potencia total utilizada del EVAX-5070.
9. Consumo total del FACP en standby y alarma.
10. Consumo del EVAX-5070.
11. Dimensionamiento de las baterías del FACP.
12. Dimensionamiento de las baterías del EVACS.

Utiliza exclusivamente valores obtenidos de datasheets y manuales oficiales
de los equipos.

Muestra las fórmulas, sustituciones, resultados y unidades.

Aclara cuáles longitudes corresponden a estimaciones académicas debido a
las limitaciones de los planos públicos.

---

## Prompt 15 – Verificación de caída de tensión

Revisa específicamente los cálculos de caída de tensión de NAC-1 y NAC-2.

Utiliza la resistencia especificada por el fabricante del conductor
Belden 5300UL de 18 AWG.

Verifica el voltaje disponible al dispositivo más alejado y compáralo con
el rango de operación permitido por los dispositivos Potter.

Realiza también una comprobación conservadora utilizando una tensión de
partida equivalente al 85 % de 24 V, dejando claro que esta condición es
una hipótesis académica de diseño y no un requisito atribuido a NFPA o al
fabricante.

No declares verificado el tramo exterior hacia EHS-01 si no conocemos su
longitud real.

---

## Prompt 16 – Baterías y EVAX-5070

Verifica el dimensionamiento de baterías del sistema de evacuación por voz
EVAX-5070 utilizando el procedimiento y las corrientes indicadas por el
fabricante.

Comprueba los valores de standby y alarma directamente en el manual o
datasheet oficial y calcula la capacidad necesaria para 24 horas en
standby y 15 minutos en alarma, incluyendo el factor de seguridad indicado.

Determina si un banco de 24 V y 8 Ah es suficiente.

No sustituyas las corrientes del fabricante por estimaciones de potencia
del amplificador si el procedimiento oficial de cálculo de batería utiliza
corrientes específicas.

---

# 8. Documentación técnica

## Prompt 17 – Circuit Schedule, Device Schedule y BOM

Genera la documentación técnica final del proyecto.

Necesito:

1. Circuit Schedule con identificación, tipo, origen, clase y función de
   cada circuito.
2. Device Schedule con código, tipo de dispositivo, fabricante, modelo y
   cantidad.
3. Bill of Materials con todos los equipos y componentes principales.

Verifica que las cantidades sean consistentes con FA-01, FA-02, FA-03,
FA-04 y los cálculos eléctricos.

No incluyas como equipo electrónico del sistema elementos exteriores de
coordinación como el hidrante existente o la FDC propuesta.

---

# 9. Datasheets y referencias técnicas

## Prompt 18 – Documentación oficial de los equipos

Identifica los datasheets y manuales oficiales de los principales equipos
utilizados en el diseño.

Necesito documentación para:

- Potter IPA-100;
- EVAX-5070;
- PAD300-PD;
- PAD300-HD;
- PAD100-PSDA;
- PE-SPST;
- PE-ST;
- PE-3RHS/4XHS;
- PAD100-TRTI;
- RA-6500F;
- IntelliCom Advanced Gateway;
- Potter BT-80;
- Belden 5300UL.

Proporciona únicamente enlaces oficiales del fabricante cuando sea posible.

Indica qué páginas son realmente relevantes para respaldar las
especificaciones utilizadas en el informe para evitar incorporar manuales
completos innecesariamente extensos.

---

# 10. Análisis y conclusiones

## Prompt 19 – Análisis técnico del diseño

Redacta el análisis final del sistema diseñado.

Incluye:

- por qué se seleccionó una arquitectura direccionable;
- ventajas;
- desventajas y compromisos;
- cumplimiento de las principales normas;
- resultados eléctricos;
- limitaciones del proyecto;
- mantenimiento, inspección y pruebas.

Diferencia entre lo que quedó demostrado mediante documentación y cálculos
y aquello que en una instalación real necesitaría medición de campo,
planos constructivos o aprobación de la AHJ.

No presentes el diseño académico como un diseño aprobado para construcción.

---

## Prompt 20 – Conclusiones finales

Redacta las conclusiones del proyecto utilizando únicamente los resultados
que realmente obtuvimos.

Resume:

- arquitectura seleccionada;
- normas que más influyeron;
- principales equipos;
- resultados de capacidad del SLC;
- carga de NAC;
- potencia de altavoces;
- baterías;
- importancia de utilizar equipos listados y compatibles;
- dificultades al aplicar normativa sobre planos públicos;
- aspectos que necesitarían verificarse en una implementación real.

Evita repetir literalmente el desarrollo del informe. Las conclusiones
deben responder a los objetivos planteados inicialmente.

---

# 11. Revisión final del informe

## Prompt 21 – Auditoría completa contra el enunciado

Revisa el informe completo punto por punto contra el enunciado del
Proyecto 1 de EL-4601.

Comprueba que se cumpla con:

1. Investigación de códigos y normas.
2. Análisis de un edificio real.
3. Selección de equipos reales y comercialmente disponibles.
4. Diseño completo del sistema.
5. Diagramas, circuitos y cálculos eléctricos.
6. Análisis técnico de la solución.
7. Conclusiones.
8. Entregables solicitados.

Busca inconsistencias entre el texto, FA-01, FA-02, FA-03, FA-04, Device
Schedule, Bill of Materials, cálculos y datasheets.

No inventes información para cerrar un requisito. Si algún punto depende
de mediciones reales, planos constructivos o aprobación de la AHJ,
indícalo explícitamente.

---

# 12. Matriz normativa final

## Prompt 22 – Trazabilidad normativa

A partir de la matriz normativa principal, crea una matriz ampliada que
muestre la trazabilidad completa entre los requisitos y el diseño.

Incluye para cada requisito:

- ID;
- fuente;
- sección;
- requisito o criterio;
- aplicación al proyecto;
- evidencia dentro del proyecto;
- estado de verificación.

Utiliza estados como:

- Verificado.
- Verificado en diseño.
- Verificación final requerida.

La expresión "verificación final requerida" debe reservarse para aspectos
que dependan de información dimensional no disponible, mediciones de campo,
configuración definitiva o aprobación de la AHJ, y no para trabajo que el
grupo simplemente haya dejado sin realizar.
