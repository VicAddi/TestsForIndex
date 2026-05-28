# EC_Estatus de la solicitud

> **Clasificación:** Internal

---

## Descripción

El usuario se comunica con la Mesa de Atención para reportar que su solicitud fue rechazada.

> **[IMAGEN - Tabla de dictamen de solicitud con estatus "No aprobado" para varios integrantes (Página 1)]**
> Se muestra una tabla de dictamen de riesgos de la plataforma AXA con encabezado:
> - "Contratante: RUIZ PRADO, SANTIAGO" (izquierda) | "Folio: GMMI-A-6688" (derecha).
> - Texto: "Derivado de la información que nos proporcionó, le presentamos los siguientes resultados:"
>
> Columnas de la tabla: **Nombre del cliente, Parentesco, Resultado, Observaciones/Requerimos Información adicional, Endoso de Exclusión/Inclusión, Extraprima, Deportes/Ocupación, Coberturas**.
>
> Filas de la tabla:
> | Nombre del cliente | Parentesco | Resultado | Observaciones/... | Endoso | Extraprima | Dep./Ocup. | Coberturas |
> |---|---|---|---|---|---|---|---|
> | RUIZ PRADO, SANTIAGO | Titular | **No aprobado** (texto en rojo) | — | — | 0% | 0% | — |
> | GAYTAN GONZALEZ, CINTHYA | Cónyuge | **No aprobado** (texto en rojo) | Texto largo: "En adición a lo previsto en las Condiciones Generales de la Póliza, por el presente Endoso se hace constar que desde el inicio de vigencia de esta Póliza quedan excluidos de la Cobertura Básica y las Coberturas Adicionales todo y cualquier gasto por y derivado o con motivo del diagnóstico y Tratamiento de la Enfermedad LEIOMIOMA DEL ÚTERO, incluyendo los que se generen por consecuencia inmediata o directa de su Tratamiento, así como por sus recurrencias o recaídas, complicaciones y secuelas. El presente Endoso forma parte de la Póliza." | — | 0% | 0% | — |
> | RUIZ GAYTAN, FATIMA | Hijo(a) | **No aprobado** (texto en rojo) | — | — | 0% | 0% | — |
> | RUIZ GAYTAN, MARIA | Hijo(a) | **No aprobado** (texto en rojo) | — | — | 0% | 0% | Flex Plus, Preexistencia(Flex Plus, Deducible Cero por Accidente) |
>
> Pie de tabla: "Mostrando de 1 a 4 registros de 4 registros en total".

---

## Clasificación y Prioridad

- **Tipo de ticket:** Incidente
- **Servicio de negocio:** -
- **Categoría:** Application
- **Subcategoría:** Other
- **Impacto:** - **Urgencia:** -

---

## Solución paso a paso

**I.** Informar al usuario que la solicitud se rechaza únicamente cuando el titular es quien tiene el estatus de "No aprobado". En el caso de otros integrantes que no sean el titular, la póliza podrá emitirse.

**II.** Una vez el área de emisión haya finalizado el análisis, en el Dashboard, el estatus de la solicitud debe ser "Solicitud con resultado de riesgos".

> **[IMAGEN - Dashboard con solicitud en estatus "Solicitud en análisis" (Página 2, parte superior)]**
> Pantalla del Dashboard de la plataforma AXA. Encabezado: logotipo AXA + "Trámites" (texto blanco sobre fondo azul oscuro). Esquina superior derecha: "Bienvenido: 90723-ESCOBAR JIMENEZ, JUAN CARLOS".
>
> Sección **"Seguimiento de trámites"**:
> - Botones: **"NUEVA COTIZACIÓN"** (azul) y **"SOLICITAR ENDOSO"** (blanco con borde).
> - Filtros: TODAS (•), NUEVO NEGOCIO, ENDOSO/MANTENIMIENTO, RENOVACIÓN.
> - Agente*: **ESCOBAR JIMENEZ, JUAN CARLOS** (con flecha ∨ de menú).
> - Buscar por Nro. de Folio: **GMMI-A-18595** (texto en campo de búsqueda).
> - Fechas: Inicio 19/03/2026 — Fin 26/03/2026. Botón **"Consultar"** (azul).
>
> Tabla con un único resultado:
> | Trámite | Folio | Intermediario | Póliza | Nº Endoso | Titular | Fecha Registro | Inicio Vigencia | Estatus | SLA | Acción |
> |---|---|---|---|---|---|---|---|---|---|---|
> | Nuevo Negocio | GMMI-A-18595 | ESCOBAR JIMENEZ, JUAN CARLOS | — | — | FRANCO ASFURA, JORGE BERNARDO | 26/03/2026 | — | **Solicitud en análisis** | 09/04/2026 | — |
>
> Pie: "Mostrando de 1 a 1 registros de 1 registros en total".

**III.** Consultar el dictamen de la solicitud correspondiente haciendo clic en la opción "…" de la columna "Acción".

> **[IMAGEN - Ventana "DICTAMEN" con tabla de resultados del análisis de riesgos (Página 2, parte media)]**
> Ventana del navegador Microsoft Edge. Barra de título: "DICTAMEN - Trabajo: Microsoft Edge". URL: `https://uat-int-axasalud.visualtime.cl/fasi/dli/forms/SOLAXA030Popup.html?uwCaseID=121542`
>
> Encabezado de la ventana: Logotipo AXA. Título centrado en grande: **"Póliza Nueva"**.
> - "Contratante: FRANCO ASFURA, JORGE BERNARDO" (izquierda) | "Folio: GMMI-A-18595" (derecha).
> - Texto: "Derivado de la información que nos proporcionó, le presentamos los siguientes resultados:"
>
> Tabla de dictamen con columnas: **Nombre del cliente, Parentesco, Resultado, Observaciones/Requerimos Información adicional, Endoso de Exclusión/Inclusión, Extraprima, Deportes/Ocupación, Coberturas, Elegibles**.
>
> Filas de la tabla:
> | Nombre del cliente | Parentesco | Resultado | Observaciones | Endoso | Extra | Dep./Ocu. | Coberturas | Elegibles |
> |---|---|---|---|---|---|---|---|---|
> | FRANCO ASFURA, JORGE BERNARDO | Titular | **Aprobado** (texto en verde) | — | — | 0% | 0% | — | — |
> | MORENO VERA, NAJLA | Cónyuge | **No aprobado** (texto en rojo) | Texto: "Me permito informarle que después de analizar la información proporcionada, AXA Seguros S.A. de C.V. está imposibilitada para asumir el riesgo conforme a los antecedentes de salud registrados en la solicitud de seguro. Sin embargo, en AXA contamos con opciones de protección y podemos ofrecerle un Innovador producto para el cuidado de su salud con AXA Keralty." | — | 0% | 0% | — | — |
>
> Pie: "Mostrando de 1 a 2 registros de 2 registros en total".
>
> Dos botones en la parte inferior centrados: **"Cerrar"** (blanco/gris) y **"Emitir"** (azul).

**I.** Hacer clic en el botón "Emitir".

> **[IMAGEN - Modal de confirmación de emisión "La póliza se emitirá sin los integrantes no aprobados" (Página 2, parte inferior)]**
> Misma ventana DICTAMEN en Microsoft Edge (misma URL). Sobre la pantalla aparece un **cuadro modal** centrado titulado **"Emitir"** (encabezado azul/verde):
> - Texto: "Confirmar emisión de la póliza"
> - Texto en negrita/destacado: **"La póliza se emitirá sin [los] integrantes no aprobados. ¿Deseas continuar?"**
> - Botón azul: **"Continuar"** (izquierda del modal) | Botón blanco: **"Regresar"** (derecha del modal).
>
> Al fondo (semitransparente) se ve el encabezado de la ventana con el contratante FRANCO ASFURA, JORGE BERNARDO y el Folio GMMI-A-18595, así como el texto introductorio del dictamen.

**II.** Visualizar el mensaje con la leyenda "La póliza se emitirá sin los integrantes no aprobados ¿Desea continuar?".

**III.** Hacer clic en el botón "Continuar" para aceptar la emisión.

> **[IMAGEN - Modal "Póliza emitida" con número de póliza generada (Página 2, parte final)]**
> Misma ventana DICTAMEN en Microsoft Edge (misma URL). Aparece un nuevo **cuadro modal** centrado titulado **"Póliza emitida"** (encabezado azul/verde):
> - Texto en negro: **"Gracias por su solicitud, se ha generado la póliza 3326AB00"** (el número de póliza está resaltado/subrayado en azul, indicando que es un enlace o elemento destacado).
> - Botón azul: **"Continuar"**.
>
> Al fondo semitransparente se ve: logotipo AXA, "Contratante: FRANCO ASFURA, JORGE BERNARDO" y "Folio: GMMI-A-18595".

**IV.** Visualizar el mensaje con la leyenda "Gracias por su solicitud, se ha generado la póliza 3326AB00".

**V.** Hacer clic en el botón "Continuar".

**VI.** La herramienta muestra el Dashboard.

**a.** Visualizar la solicitud correspondiente con el estatus "Emitida".

> **[IMAGEN - Dashboard con solicitud en estatus "Emitida" (Página 3)]**
> Dashboard de la plataforma AXA. Encabezado: AXA logo + "Trámites". Esquina superior derecha: "Bienvenido: 90723-ESCOBAR JIMENEZ, JUAN CARLOS".
>
> Sección **"Seguimiento de trámites"**:
> - Botones: NUEVA COTIZACIÓN y SOLICITAR ENDOSO.
> - Filtros: TODAS (•), NUEVO NEGOCIO, ENDOSO/MANTENIMIENTO, RENOVACIÓN.
> - Agente*: ESCOBAR JIMENEZ, JUAN CARLOS (∨).
> - Buscar por Nro. de Folio: **GMMI-A-18595**.
> - Fechas: Inicio 19/03/2026 — Fin 26/03/2026. Botón "Consultar".
>
> Tabla con un único resultado:
> | Trámite | Folio | Intermediario | Póliza | Nº Endoso | Titular | Fecha Registro | Inicio Vigencia | Estatus | SLA | Acción |
> |---|---|---|---|---|---|---|---|---|---|---|
> | Nuevo Negocio | GMMI-A-18595 | ESCOBAR JIMENEZ, JUAN CARLOS | **3326AB00** | — | FRANCO ASFURA, JORGE BERNARDO | 26/03/2026 | 26/03/2026 | **Emitida** (resaltado en azul/celeste, como etiqueta de estado) | — | — |
>
> Pie: "Mostrando de 1 a 1 registros de 1 registros en total".
>
> La columna "Estatus" muestra el valor **"Emitida"** con fondo azul claro/celeste, indicando visualmente el estado exitoso de la póliza.

---

## Datos mínimos requeridos

> **En caso de no brindar una solución posterior a la aplicación de la "Solución paso a paso", se deberá proporcionar información de "Datos mínimos requeridos" para canalizar al siguiente nivel de soporte.**

- **Nombre completo:**
- **Usuario MX:**
- **Ubicación:**
- **Ext:**
- **Correo:**
- **Número de póliza/número de folio de la solicitud:**
- **Fecha y hora cuando se presentó el error:**
- **Descripción detallada del error: ¿Qué está pasando?**
  *(secuencia de pasos para replicar el problema reportado, indicando: ¿Qué ocurre? ¿Dónde ocurre (sistema / módulo)? ¿Desde cuándo ocurre? ¿A quién afecta (usuario))*
  Nota. Favor de adjuntar pantallas, archivos de entrada, archivos de salida, etc. Las pantallas deberán ser completas y cuando sea posible permitir visualizar: Fechas, Hora, URLS o sistema).
- **Descripción detallada del resultado esperado: ¿Qué debería de pasar?**
  *(Secuencia de pasos a seguir de la correcta funcionalidad, regla de negocio, etc.) Descripción clara del comportamiento esperado, adjuntar pantallas, archivos de entrada, archivos de salida, etc.*
- **Afectación al Negocio: ¿Cómo afecta que se presente este problema a tu negocio (Incluir # de usuarios)?**
  Ejemplo: 1 usuario y afecta los SLA del equipo de emisión.
- **Información adicional:**
  Cualquier tipo de información que aporte al desarrollo de la solución. Conjunto de datos en Excel, Interfaz, etc.

Se levanta ticket de incidencia y se asigna al grupo de soporte:

---

## Información ampliada

N/A
