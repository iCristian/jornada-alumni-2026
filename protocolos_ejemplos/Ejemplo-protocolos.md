# Ejemplo guiado: de los materiales existentes a un protocolo nuevo, con IA y el método PARTO

**Jornada Alumni 2026 · Taller «IA aplicada a la elaboración de protocolos y materiales en Matronería»**
Escuela de Obstetricia y Puericultura, Universidad de Valparaíso

> **Para quién es esta guía.** Para matronas y matrones que nunca han usado IA para algo tan complejo como un protocolo. No necesitas saber programar ni conocer términos técnicos. Si sabes escribir un correo y leer una norma, puedes seguir este ejemplo.
>
> **Qué vas a hacer.** Con la IA, revisar el material de dos carpetas (protocolos previos y normas del Ministerio de Salud), elegir un tema útil y obtener el **borrador de un protocolo breve**. Tú decides y verificas; la IA acelera la lectura y la redacción.
>
> **Tiempo.** Unos 35 minutos en el taller. Para ir más rápido, quien facilita entrega el «resultado de referencia» de cada paso, y tu grupo lo compara con lo que responda su propia IA.

---

## 0. Antes de empezar

### 0.1 Cuatro reglas que no se negocian

| # | Regla | Por qué |
|---|---|---|
| 1 | **Nunca subas datos de pacientes** (nombre, RUN, ficha, fotos). | El ejemplo trabaja solo con documentos públicos. |
| 2 | **La IA propone; tú decides.** | El protocolo es responsabilidad de un equipo, no de una herramienta. |
| 3 | **Todo dato se verifica contra el documento original.** | Las IA a veces inventan cifras, páginas o citas con total seguridad. |
| 4 | **Guarda cada prompt que uses** (el texto que le escribes a la IA). | Permite repetir, mejorar y enseñar lo que hiciste. |

### 0.2 El método PARTO en una tabla

Un *prompt* es la instrucción que le escribes a la IA. Un buen prompt responde cinco preguntas, y sus iniciales forman la palabra **PARTO**.

| Letra | Significa | Pregunta que debes responder | Ejemplo corto |
|---|---|---|---|
| **P** | Papel | ¿Quién quieres que sea la IA? | «Actúa como matrón experto en protocolos clínicos en Chile». |
| **A** | Antecedentes | ¿Qué necesita saber para ayudarte? | «Adjunto 5 protocolos y 7 documentos del MINSAL. Somos un equipo que redacta un protocolo local». |
| **R** | Requerimiento | ¿Qué tiene que hacer, paso a paso? | «1) Describe cada documento. 2) Propón 3 temas. 3) Indica qué falta». |
| **T** | Tono y formato | ¿Cómo quieres la respuesta? | «En tablas, con lenguaje simple, máximo una página». |
| **O** | Observaciones | ¿Qué reglas y límites debe respetar? | «Usa solo los documentos adjuntos. Si no lo encuentras, escribe “No encontrado”». |

**Truco para recordarlo:** el orden es el de una conversación clínica. Primero quién eres (P), luego qué sabes del caso (A), qué necesitas (R), cómo lo quieres (T) y qué cuidados debes respetar (O).

### 0.3 Mapa del ejemplo

| Paso | Qué haces | Quién trabaja | Tiempo |
|---|---|---|---|
| 1 | Reunir y mirar el material | Tú | 5 min |
| 2 | Pedir a la IA un inventario y una lista de temas posibles (**Prompt A**) | IA, y tú lees | 8 min |
| 3 | Elegir el tema y resolver diferencias entre fuentes | Tú, con el equipo | 5 min |
| 4 | Pedir el borrador del protocolo (**Prompt B**) | IA, y tú editas | 10 min |
| 5 | Revisar con una segunda pasada de IA y una lista de cotejo (**Prompt C**) | IA y tú | 7 min |
| 6 | Guardar el trabajo y el prompt | Tú | — |

---

## Paso 1. Reunir y mirar el material (tú, 5 min)

### Carpeta «Protocolos previos» (5 documentos)

Son ejemplos de **cómo se escribe** un protocolo. Sirven de modelo de estructura.

| Documento | Tipo | Para qué lo usamos |
|---|---|---|
| Prevención de endometritis puerperal, Hospital Puerto Montt (2017–2022) | Protocolo local de prevención de infecciones | Modelo de **indicador con umbral** (95 %) y pauta de supervisión. Vigencia vencida. |
| Prevención de endometritis puerperal, Hospital Dr. Hernán Henríquez Aravena, Temuco (2018) | Protocolo local | Comparar criterios con Puerto Montt (por ejemplo, el máximo de tactos vaginales). |
| Norma de registro de ficha clínica de parto, Hospital Dr. Gustavo Fricke (2025) | Norma de registro | Modelo de **portada con elaboró / revisó / aprobó**, objetivos, alcance y definiciones. |
| Protocolo de atención integral de víctima de violencia sexual (GES 86) | Protocolo clínico | Ejemplo de protocolo por problema de salud, con índice, roles, indicador clave, pauta de cotejo y flujogramas. |
| Uso del electrocardiógrafo portátil, Hospital Carlos Van Buren (2025) | Norma de equipo | Modelo de **índice**, tabla de responsables y tabla de cambios. |

### Carpeta «Materiales MINSAL» (7 documentos y un archivo de enlaces)

Son la **fuente obligatoria o de referencia**: de aquí salen las reglas que el protocolo debe respetar.

| Documento | Páginas | Tipo | Relevancia |
|---|---|---|---|
| Guía Perinatal 2015 | 466 | Guía clínica | Base clínica del parto y puerperio. |
| Norma 194 de atención del recién nacido | 207 | Norma | Atención inmediata del RN, contacto piel a piel. |
| Normas de regulación de la fertilidad (2018) | 252 | Norma | Anticoncepción. |
| Guía de experiencias: pertinencia cultural con pueblos indígenas en salud sexual y reproductiva (2021) | 76 | Guía de experiencias | Incluye **dos protocolos locales** de entrega de placenta. |
| Norma Técnica 189 de entrega de placenta (2017) | 14 | **Norma obligatoria** | Pide a cada establecimiento tener su protocolo. |
| Orientación técnica para la auditoría de la mortalidad materna (2016) | 15 | Orientación técnica | Notificación y auditoría de muertes maternas. |
| Agenda de salud de la mujer (2008) | 44 | Material educativo | Folleto para usuarias. |
| `links.md` | — | Enlaces | Dirección de salud de la mujer en minsal.cl. |

**Total:** unas **1.074 páginas** en la carpeta MINSAL. Es demasiado para leerlo todo en un taller, y justo por eso conviene que la IA ayude.

### Tres consejos prácticos antes de subir archivos

1. **Revisa que el PDF tenga texto.** Dos de los PDF de endometritis son fotografías de hojas: la IA «ve» páginas vacías. Si ocurre, pídele a la plataforma que aplique reconocimiento de texto (OCR) o usa la versión Word.
2. **No subas todo si la plataforma se queda corta.** Si la herramienta rechaza archivos, divide el trabajo en dos mensajes: primero «Protocolos previos», después «Materiales MINSAL».
3. **Cualquier plataforma sirve.** Este ejemplo funciona igual en ChatGPT, Gemini, Claude, DeepSeek u otra. Lo importante es el método, no la marca.

---

## Paso 2. Pedir a la IA un inventario y temas posibles (8 min)

### Prompt A · Revisar el material

Copia, pega y adjunta los archivos.

```text
[P] Actúa como matrón/a experto/a en elaboración y gestión de protocolos
clínicos en Chile.

[A] Somos un equipo de matronas y matrones que quiere crear un protocolo local
nuevo. Adjunto dos grupos de documentos:
 (1) "Protocolos previos": cinco protocolos de hospitales chilenos.
 (2) "Materiales MINSAL": normas, guías y orientaciones técnicas.
Es un ejercicio de taller; no hay datos de pacientes.

[R] 1. Describe cada documento en una línea: tipo (norma obligatoria, guía,
      protocolo local o material educativo), año y de qué trata.
   2. Identifica temas de matronería que el MINSAL norma, pero que NO tienen
      un protocolo local entre los "Protocolos previos".
   3. Propón 3 temas candidatos para un protocolo breve. Para cada uno indica:
      por qué sería útil, qué documentos lo respaldan (nombre y sección o
      página) y qué información falta.
   4. Señala diferencias entre documentos sobre un mismo tema.

[T] Usa tablas. Lenguaje sencillo, sin tecnicismos innecesarios. Máximo 2
páginas en total.

[O] Usa solo los documentos adjuntos. Cita siempre nombre del documento y
sección o página. Si algo no aparece, escribe "No encontrado". No inventes
cifras ni referencias. Avisa si algún archivo no se pudo leer.
```

**Por qué funciona.** Cada letra cumple un trabajo: **P** fija el nivel de experticia; **A** entrega el contexto (si no lo das, la IA adivina); **R** numera las tareas para que no se salte ninguna; **T** evita un texto largo e ilegible; **O** reduce las invenciones.

### Resultado de referencia (revisado contra los documentos)

> Las palabras de tu IA serán distintas. Lo importante es que **llegue a conclusiones parecidas** y que tú puedas comprobarlas.

**Tabla 1. Temas candidatos**

| Tema | Respaldo en los documentos | Qué falta |
|---|---|---|
| **1. Entrega de placenta** | Norma Técnica 189 (2017), §1: «Corresponderá a cada establecimiento de salud de atención cerrada, tanto público como privado, establecer un protocolo de entrega de placenta». La Guía de pueblos indígenas (2021) incluye los protocolos de Hospital Las Higueras y Hospital de Victoria. | Ninguno de los 5 protocolos previos lo trata. La norma de registro de parto solo pide describir peso de la placenta y longitud del cordón; no se encontró ningún campo para la solicitud ni la entrega. |
| **2. Contacto piel con piel e inicio de la atención inmediata del recién nacido** | Norma 194: recomienda contacto piel a piel de al menos 60 minutos en parto normal y 30 en cesárea, si las condiciones de salud lo permiten, y diferir los procedimientos no indispensables. | Los protocolos previos no lo abordan. El tema es más extenso y supone más decisiones clínicas. |
| **3. Comunicación y auditoría de una muerte materna** | Orientación técnica 2016 (Resolución Exenta N.º 297): información inmediata del fallecimiento e informe regional. | Tema de gestión; no hay protocolo local entre los previos. Requiere trabajo con la unidad de calidad. |

**Tabla 2. Una diferencia entre fuentes que conviene notar**

| Aspecto | Norma Técnica 189 (2017) | Experiencia Las Higueras (relatada en la Guía 2021) |
|---|---|---|
| Plazo de retiro | Como regla general, **al alta o a las 72 h** del parto, «sin perjuicio de la evaluación de cada caso». | Las organizaciones mapuche pidieron que la entrega **no superara las 24 h**. |
| Conservación | Refrigerada en refrigerador clínico. | La placenta **no debía congelarse**. |
| Exámenes | Exclusión por VIH, VHB o VHC. Para VHB y VHC se usa el diagnóstico previo: **no se exige un examen solo para entregar la placenta**. | Antes de julio de 2016, la revisión de la autoridad sanitaria regional sugirió agregar exámenes de Chagas y hepatitis B, lo que chocaba con el plazo de 24 h. Eso ocurrió **antes** de la norma de 2017. |

> **Qué enseña esta tabla.** Dos fuentes buenas pueden decir cosas distintas. En un protocolo se resuelve así: (1) manda la norma obligatoria y más reciente; (2) la experiencia local aporta ideas que la norma no prohíbe; (3) la decisión queda escrita, con su justificación. En el protocolo de endometritis ocurre lo mismo con el número máximo de tactos vaginales (cuatro en un protocolo, cinco en otro).

---

## Paso 3. Elegir el tema y resolver diferencias (tú y tu equipo, 5 min)

La IA entrega opciones; **la elección es humana**. Usa estos cuatro criterios (1 punto cada uno):

| Criterio | Pregunta |
|---|---|
| Necesidad | ¿Hay una norma que nos obliga o un vacío real en nuestro servicio? |
| Tamaño | ¿Se puede escribir en 2–3 páginas, adecuado para el taller? |
| Respaldo | ¿Tenemos documentos claros y vigentes que lo sustenten? |
| Utilidad | ¿Lo usaríamos a diario o con frecuencia? |

**Decisión del ejemplo: «Entrega de placenta».** Obtiene 4/4: la norma exige que cada establecimiento tenga su protocolo, el proceso es corto, hay norma y dos modelos locales, y es una situación frecuente en maternidades con población indígena y no indígena. Los otros dos temas pueden quedar como ejercicios para los grupos.

**Decisiones sobre las diferencias (quedan escritas en el protocolo):**

1. **Regla base = Norma Técnica 189.** Retiro al alta o a las 72 h, con refrigeración.
2. **Excepción permitida por la propia norma:** si la familia solicita retirar antes (por ejemplo, dentro de 24 h), se coordina caso a caso. La norma lo habilita con la frase «sin perjuicio de la evaluación de cada caso».
3. **No se exigen exámenes adicionales** a los que la norma ya establece.
4. **Contenedor ceremonial** (como el *metawe* del Hospital de Victoria): queda como **punto por consultar** con la unidad de IAAS, porque la norma exige doble bolsa.

---

## Paso 4. Pedir el borrador del protocolo (10 min)

### Prompt B · Redactar

```text
[P] Actúa como matrón/a experto/a en redacción de protocolos clínicos para
hospitales públicos de Chile.

[A] Vamos a redactar el "Protocolo local de entrega de placenta" de nuestra
maternidad. Fuente principal y obligatoria: la Norma Técnica 189 (2017).
Fuentes de apoyo: la Guía de experiencias de pertinencia cultural (2021) y,
como modelo de formato, la Norma de registro de ficha clínica de parto del
Hospital Fricke (2025) y el protocolo de Puerto Montt (indicador y pauta).
Decisiones del equipo:
 - Regla base: retiro al alta o a las 72 h, con refrigeración.
 - Si la familia pide retirar antes, se coordina caso a caso.
 - No se exigen exámenes adicionales a los de la norma.
 - Contenedor ceremonial: dejar como "por consultar con IAAS".

[R] Redacta el borrador con estas 10 secciones, en este orden:
 1. Portada: nombre, código, versión, fecha, vigencia (3 años), elaboró,
    revisó y aprobó (dejar espacios).
 2. Propósito.
 3. Alcance (quién, dónde, a quién).
 4. Responsables (tabla).
 5. Definiciones (máximo 6).
 6. Desarrollo, como pasos numerados: control prenatal; ingreso al parto;
    alumbramiento y envasado; conservación; entrega; casos en que no se
    entrega.
 7. Registros (tabla con los registros que exige la norma).
 8. Indicador: nombre, fórmula, umbral y frecuencia.
 9. Flujograma en texto (flechas simples).
 10. Referencias en formato Vancouver.

[T] Español claro, frases cortas, verbos en infinitivo en los pasos. Tablas
donde ayuden. Máximo 3 páginas.

[O] Usa solo los documentos adjuntos. Cada exigencia debe indicar su fuente
entre paréntesis (por ejemplo, NT 189, §10). Marca con [VERIFICAR] todo dato
que no esté en los documentos. No inventes plazos, cifras ni nombres de
cargos. Deja entre corchetes los datos propios de nuestro hospital.
```

### Resultado de referencia: borrador (se muestra completo, para comparar)

> **Borrador de taller. No es un documento institucional.** Un protocolo solo es institucional cuando lo aprueba la autoridad máxima del establecimiento, con nombre, firma y fecha. Los datos entre corchetes los completa cada equipo.

#### PROTOCOLO LOCAL DE ENTREGA DE PLACENTA

| Campo | Contenido |
|---|---|
| Código / versión | [PRO-OBS-__] / 1 |
| Establecimiento / unidad | [Hospital] / [Unidad de Partos y Maternidad] |
| Fecha de elaboración / vigencia | [dd/mm/aaaa] / 3 años desde la aprobación |
| Elaboró · Revisó · Aprobó | [Equipo de matronería] · [Jefatura de matronería e IAAS] · [Dirección] |

**1. Propósito.** Garantizar el derecho de las mujeres a disponer de su placenta para prácticas culturales significativas, de forma segura para quien la recibe y para quien la entrega (NT 189, §3 y §5).

**2. Alcance.** Todo el personal de la Unidad de Partos, pabellón y puerperio que atiende partos vaginales o cesáreas. Aplica a toda mujer que lo solicite, pertenezca o no a un pueblo indígena (NT 189, §2).

**3. Responsables**

| Quién | Qué hace |
|---|---|
| Profesional que controla el embarazo (matrona/ón) | Recibe la solicitud, orienta sobre requisitos y exclusiones, hace firmar el formulario y lo registra en la ficha y el carnet (NT 189, §9). |
| Profesional responsable del parto (médico, gineco-obstetra o matrona/ón) | Revisa exámenes al ingreso; **garantiza** el envasado, la identificación y el registro de la entrega (NT 189, §9). |
| Jefatura de matronería e IAAS [VERIFICAR cargos locales] | Supervisan el cumplimiento y miden el indicador. |

**4. Definiciones.** *Placenta*: órgano que une a la madre con el feto durante la gestación. *Práctica cultural*: acción colectiva y dinámica que organiza la vida cotidiana. *Causal de exclusión*: motivo sanitario por el cual no se entrega. *Residuo patológico*: destino de la placenta no entregada (DS 6/2009, art. 6 N.º 2).

**5. Desarrollo**

1. **Control prenatal.** La mujer solicita voluntariamente su placenta. El o la profesional explica requisitos y exclusiones, y el manejo seguro. La mujer firma la *Solicitud de entrega de placenta* (anexo 1 de la norma). Se anota en la ficha y en el carnet de control prenatal.
2. **Ingreso al parto.** Si no hubo solicitud previa, puede hacerse al ingreso. Revisar los exámenes de rutina del embarazo: deben ser negativos o no reactivos. Firmar la solicitud.
3. **Causales de exclusión.** No se entrega si hay diagnóstico de **VIH, VHB o VHC**, o si tras el alumbramiento se indica estudio microbiológico o histopatológico (por ejemplo, corioamnionitis o microinfartos). Para hepatitis B y C se considera el diagnóstico previo; **no se pide un examen solo para este fin**. Explicar el motivo a la mujer con claridad.
4. **Alumbramiento y envasado.** Colocar la placenta en **doble bolsa plástica gruesa, opaca e impermeable**. Rotular: nombre completo, RUN o documento, fecha del parto y establecimiento.
5. **Conservación.** Mantener en **refrigerador clínico** hasta el retiro. No congelar.
6. **Entrega.** Regla general: **al alta o a las 72 h**. Si la familia pide retirar antes, coordinar caso a caso. Quien retira firma el libro de registro. Entregar la hoja de **manejo seguro**: mantener en su envoltorio, evitar extravíos, no eliminar en basura común ni alcantarillado, no guardar en refrigerador con alimentos.
7. **Si no se solicitó o no se cumplen los requisitos.** Manejar como residuo patológico (NT 189, §9).

*Opcional, para decidir en el equipo y no exigido por la norma:* entrevista con facilitador intercultural, cuando exista en el hospital (experiencia de Las Higueras y Victoria). Contenedor ceremonial: **[VERIFICAR con IAAS]**.

**6. Registros (NT 189, §11)**

| Registro | Dónde queda |
|---|---|
| Solicitud firmada | Ficha clínica |
| Anotación de la solicitud | Carnet de control prenatal, o ficha clínica si se pide al ingreso |
| Entrega: nombre de la mujer, RUN, fecha de parto, fecha de entrega, nombre, firma, RUN y parentesco de quien retira | Libro de registro de entrega de placenta |
| Estadística mensual | REM 24, Sección A **[VERIFICAR que siga vigente en el REM actual]** |

**7. Indicador (propuesta)**

| Elemento | Contenido |
|---|---|
| Nombre | Entregas de placenta con los cuatro registros completos |
| Fórmula | (N.º de entregas con solicitud, ficha, libro y REM completos ÷ N.º total de entregas del período) × 100 |
| Umbral | [Definir por el equipo]. Referencia: el protocolo de Puerto Montt (2017) fijó un umbral de 95 %. |
| Frecuencia / fuente | [Mensual] / revisión de libro y fichas |

**8. Flujograma**

`Solicitud (control prenatal o ingreso) → Orientación y firma → Revisión de exámenes y causales → ¿Cumple? → Sí: alumbramiento → doble bolsa y rótulo → refrigerar → entrega al alta o a las 72 h → registros | No: residuo patológico, con explicación a la mujer`

**9. Referencias**

1. Ministerio de Salud (Chile). Norma General Técnica N.º 189 para la entrega de la placenta. Santiago: MINSAL; 2017. Decreto Exento N.º 208, 5 de junio de 2017.
2. Ministerio de Salud (Chile). Guía de experiencias significativas y recomendaciones para los equipos de salud: pertinencia cultural en el trabajo con pueblos indígenas en el ámbito de la salud sexual y salud reproductiva. Santiago: MINSAL; 2021.
3. Contreras Molina R, Berho Castillo M. Placenta: móviles, usos y significaciones en el centro-sur de Chile. Salud Colectiva. 2022;18:e4102. doi:10.18294/sc.2022.4102

> **Sobre el nivel de evidencia.** Este protocolo se apoya en una **norma obligatoria**, no en estudios clínicos. Por eso no lleva gradación A/B/C. Si añades recomendaciones clínicas (por ejemplo, manejo activo del alumbramiento), indica el nivel de evidencia de la Guía Perinatal 2015.

---

## Paso 5. Revisar el borrador (7 min)

La regla de oro: **un borrador de IA no está listo hasta que alguien lo verifique.** Hacemos dos revisiones: una con una segunda pasada de IA, y otra humana.

### Prompt C · IA revisora

Abre una **conversación nueva** (así no «defiende» lo que escribió) y adjunta el borrador y la Norma Técnica 189.

```text
[P] Actúa como revisor/a crítico/a de protocolos para la unidad de calidad de
un hospital chileno.

[A] Adjunto un borrador de "Protocolo local de entrega de placenta" y la Norma
Técnica 189 (2017) en la que se basa.

[R] 1. Compara cada exigencia del borrador con la norma. Marca: Correcto /
      Distinto / No está en la norma.
   2. Lista lo que la norma exige y el borrador omite.
   3. Revisa si falta alguno de estos elementos: responsables, indicador con
      umbral, registros, vigencia, aprobación.
   4. Marca frases ambiguas que un equipo podría interpretar de dos maneras.

[T] Tabla de tres columnas: sección, hallazgo, corrección sugerida. Termina
con las 3 correcciones más importantes.

[O] Sé estricto/a. No reescribas el protocolo, solo revisa. Si algo es dudoso,
dilo. Basa cada observación en una cita textual de la norma.
```

### Lista de cotejo humana (7 puntos, 5 minutos)

Marquen cada punto con la norma abierta en la mano.

| ✔ | Qué verificar | Cómo |
|---|---|---|
| ☐ | Cada **cifra o plazo** (72 h, doble bolsa, refrigeración) coincide con la norma. | Buscar la frase en el PDF. |
| ☐ | Las **causales de exclusión** son exactamente las de la norma. | Comparar con la sección 8 de la norma. |
| ☐ | Los **cuatro registros** están completos. | Comparar con la sección 11. |
| ☐ | Las **referencias existen**; el DOI abre el artículo correcto. | Pegar el DOI en el navegador. |
| ☐ | Todo lo marcado **[VERIFICAR]** tiene responsable y fecha. | Anotar quién lo confirma. |
| ☐ | **Vigencia de la norma:** ¿hay una versión posterior? ¿el REM sigue igual? | Consultar minsal.cl. |
| ☐ | El documento no dice «aprobado» hasta que lo firme la autoridad máxima. | Revisar portada. |

> **Nota de honestidad.** Al preparar este ejemplo no pudimos confirmar en línea si existe una versión posterior de la Norma 189 ni la numeración vigente del REM. Por eso esos dos puntos quedaron marcados **[VERIFICAR]**: es exactamente lo que debe hacer un equipo cuando la IA, o quien prepara el material, no puede comprobar algo.

---

## Paso 6. Guardar y registrar (tú)

1. Guarda el borrador con nombre y versión: `PRO-OBS-__ Entrega de placenta v0.1 BORRADOR`.
2. Pega tus tres prompts (A, B, C) en un documento llamado **Prompts**. Anota para cada uno: **qué pediste, qué te sirvió y qué mejorarías**.
3. Pasa el borrador al comité de calidad o a IAAS para completar los datos locales, aprobarlo y fijar la fecha de revisión.

---

## Errores frecuentes (y cómo evitarlos)

| Si pasa esto | Probablemente significa | Qué hacer |
|---|---|---|
| La IA responde algo genérico | Faltó **A** (antecedentes) o **R** (requerimiento). | Agrega el contexto y numera las tareas. |
| La IA cita páginas o autores que no encuentras | Está inventando. | Exige «cita textual» y vuelve a verificar. Los prompts A y B piden marcar lo que falta («No encontrado» o [VERIFICAR]); el C exige cita textual. |
| Dice que el archivo está vacío | El PDF es una imagen. | Usa OCR o la versión Word. |
| El texto es demasiado largo | Faltó **T** (tono y formato). | Define máximo de páginas y formato. |
| Dos fuentes se contradicen | Es normal. | Aplica la regla: norma obligatoria y más reciente > experiencia local. Anota la decisión. |
| La respuesta cambia cada vez | Las IA no son deterministas. | Guarda el resultado que usas y su prompt. |

---

## Otros temas para practicar en grupos

| Tema | Documento base | Qué pueden armar en 20 min |
|---|---|---|
| Contacto piel con piel en la atención inmediata | Norma 194, secciones de atención inmediata (60 min en parto normal; 30 min en cesárea) | Propósito, pasos numerados y registro. |
| Comunicación de una muerte materna | Orientación técnica 2016 | Flujo de información inmediata y responsables. |
| Material educativo para usuarias sobre entrega de placenta | Norma 189 (anexo 1, cara 2) | Folleto de una página en lenguaje simple (con el mismo método PARTO). |

---

## Referencias

1. Ministerio de Salud (Chile). Norma General Técnica N.º 189 para la entrega de la placenta. Santiago: MINSAL; 2017. Decreto Exento N.º 208, 5 de junio de 2017.
2. Ministerio de Salud (Chile). Guía de experiencias significativas y recomendaciones para los equipos de salud: pertinencia cultural en el trabajo con pueblos indígenas en el ámbito de la salud sexual y salud reproductiva. Santiago: MINSAL; 2021.
3. Contreras Molina R, Berho Castillo M. Placenta: móviles, usos y significaciones en el centro-sur de Chile. Salud Colectiva. 2022;18:e4102. doi:10.18294/sc.2022.4102 (DOI comprobado en Crossref).
4. Ministerio de Salud (Chile). Guía Perinatal 2015. Santiago: MINSAL; 2015.
5. Ministerio de Salud (Chile). Norma 194 de atención del recién nacido. Santiago: MINSAL.
6. Ministerio de Salud (Chile). Orientación técnica para la auditoría y vigilancia de la mortalidad materna. Resolución Exenta N.º 297, 31 de marzo de 2016.
7. Hospital Puerto Montt. Prevención de endometritis puerperal (2017–2022). Código UIAAS 14, edición 09. Documento de la carpeta «Protocolos previos».
8. Hospital Dr. Gustavo Fricke. Norma de registro de ficha clínica de parto. Edición 1; 2025. Documento de la carpeta «Protocolos previos».
9. Hospital Dr. Hernán Henríquez Aravena (Temuco). Prevención de endometritis puerperal, tercera versión; 2018. Documento de la carpeta «Protocolos previos».

---

*Material de trabajo del proyecto JORNADA ALUMNI 2026. Los resultados de referencia se verificaron contra los documentos originales de las carpetas «Protocolos previos» y «Materiales MINSAL». Nombres de plataformas de IA y funciones pueden cambiar; el método PARTO no depende de ninguna.*
