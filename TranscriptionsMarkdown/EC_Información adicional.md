# EC_Información adicional

> **Clasificación:** Internal

---

## Descripción

El usuario se comunica a la Mesa de Atención notificando que no tiene la opción para cargar el documento cuando se requiere información adicional.

> **[IMAGEN - Dictamen de la solicitud con resultado "Requerimos información adicional"]**
> Pantalla "Póliza Nueva". Contratante: SAENZ NEGRETE, AGUSTIN JOSE | Folio: GMMI-A-9350. Texto: "Su solicitud fue turnada al análisis de selección de riesgos."
>
> Tabla de resultados:
> | Nombre del cliente | Parentesco | Resultado | Observaciones/Requerimos Información adicional |
> |---|---|---|---|
> | SAENZ NEGRETE, AGUSTIN JOSE | Titular | Aprobado con endoso de exclusión | — |
> | RODRIGUEZ GIL FLORES, TANIA | Cónyuge | Aprobado | — |
> | SAENZ RODRIGUEZ GIL, DIEGO | Hijo(a) | Aprobado | — |
> | SAENZ RODRIGUEZ GIL, ANA PAOLA | Hijo(a) | **Requerimos información adicional** | "Informe del médico pediatra en el que se especifique el cuadro clínico asociado y la presencia o ausencia de complicaciones o secuelas neurológicas, respiratorias y oftalmológicas. El informe también debe incluir la evaluación actual del crecimiento y desarrollo, los tratamientos recibidos, que recibe actualmente o que está por recibir, el plan de seguimiento clínico y el estado actual del solicitante en relación con su antecedente de nacimiento prematuro." |
> | SAENZ NEGRETE, JOSE | Contratante | Aprobado | (mismo texto que ANA PAOLA) |
>
> La tabla muestra 5 registros. Botón **"Cerrar"** visible en la parte inferior. Se observa una flecha roja apuntando a un área vacía al lado del botón Cerrar — indica que falta el botón de carga de documentos (el problema reportado).

---

## Clasificación y Prioridad

- **Tipo de ticket:** Incidente
- **Servicio de negocio:** -
- **Categoría:** Application
- **Subcategoría:** Other
- **Impacto:** - **Urgencia:** -

---

## Solución paso a paso

**I.** Cuando se requiere información adicional, se debe solicitar el documento por cada integrante. El agente, desde el Dashboard, accede al dictamen de la solicitud correspondiente y debería tener habilitada la opción para cargar los archivos solicitados por el área de emisión.

**II.** La habilitación de la carga de documentos lo realiza el analista del área de emisión, en el sistema de BeAware.

**a.** Desde el sistema de BeAware, dar clic en el botón "Ver detalle" de cada asegurado.

> **[IMAGEN - Sistema BeAware: pantalla de análisis de solicitud con botón "Ver detalle"]**
> Ventana "Solicitud AXA" en Microsoft Edge. URL interna de BeAware. Pantalla "Póliza Nueva". Contratante: GUERRERO FLORES, PAMELA | Folio: GMMI-A-18606. Aviso en naranja: "Caso requiere análisis por firma manual, documentos". Botones de acción: **"Solicitud de Información Adicional"**, **"Enviar Resultado"**, **"Emitir"**, **"Rechazar"**.
>
> Tabla con columnas: Nombre del cliente, Parentesco, Hallazgo, Resultado, Analista Seleccionador, Dictaminador médico, Compliance, y botón **"VER DETALLE"** (azul) por fila. Dos filas: RODARTE RODRIGUEZ, RAYMUNDO ALONSO (Titular / R.Laboral / Aprobado) y RODARTE RODRIGUEZ, RAYMUNDO ALONSO (Titular / IMC / Aprobado).

**b.** Es necesario agregar el documento a solicitar, en el enlace de "Ver documentos adjuntos" en la parte inferior del apartado "Información general".

> **[IMAGEN - BeAware: pantalla "INTERNA" con detalle del asegurado y enlace "VER DOCUMENTOS ADJUNTOS"]**
> Ventana "INTERNA" en Microsoft Edge. Folio: GMMI-A-18606. Panel izquierdo (Analista Seleccionador): nombre del asegurado RODARTE RODRIGUEZ, RAYMUNDO ALONSO resaltado en amarillo; secciones: Dictamen defnitivo, Observaciones generales, (Analista seleccionador), Observaciones generales, (Dictaminador médico), Resultados agentes compliance, Dictamen definitivo VP, Dictamen previo al área de decisiones (IMC: 24.22 Aprobado / Riesgo laboral: Básico/a (Aprobado)), botones **"AGREGAR HALLAZGO"**, **"MODIFICAR ENDOSO EXCLUSIÓN"**, **"FICHAR LA EXTRAPRIMA"**; secciones: Antecedentes de otras pólizas, Antecedentes de solicitudes ingresadas previamente, botón **"IR A LA CONSULTA DE HISTÓRICO"**, Consulta GV, Requerimiento de información adicional.
>
> Panel derecho (Información general): lista de datos a consultar (Consulta de ocupación o deporte/hobbies, Botánico, Consulta Nacionalidad, México, Consulta País de nacimiento, México, Consulta tabla de IMC: 29.22, Consulta de antecedentes de pólizas, Consulta de antecedentes de solicitudes, Consulta cuestionario médico (matriz de padecimientos), Consulta tabla de hábitos, Antigüedad, Artículo 492, Continuidad Bienvenida). Enlace resaltado con flecha roja: **"VER DOCUMENTOS ADJUNTOS"** (en texto azul/subrayado).

**c.** Hacer clic en el botón "Agregar documento".

> **[IMAGEN - Modal "DOCUMENTOS ADJUNTOS" con lista de documentos y botón "Agregar Documento"]**
> Modal con tabla de columnas: Parentesco, Documento, Estado del Documento. Tres registros:
> - Contratante | Identificación oficial vigente | Recibido | Botón "Ver Documento"
> - Contratante | Comprobante de domicilio | Recibido | Botón "Ver Documento"
> - Contratante | Firma manual | Recibido, por analizar | Botón "Ver Documento"
>
> Pie: "Mostrando de 1 a 3 registros de 3 registros en total". Flecha roja apuntando al botón **"Agregar Documento"** (blanco con borde) en la esquina inferior derecha. Botón **"Cerrar"** (rojo) a la izquierda.

**a.** Seleccionar una opción de la lista del campo "Cliente". También se debe elegir una opción de la lista desplegable del campo "Documento".

> **[IMAGEN - Modal "Agrega Documento" con campos Cliente y Documento desplegados]**
> Modal "Agrega Documento". Campo **"Cliente*"**: valor seleccionado en amarillo: **RODARTE RODRIGUEZ, RAYMUNDO ALONSO** (con ∨). Campo **"Documento*"**: valor seleccionado en amarillo: **CURP** (con ∨). La lista desplegable del campo Documento está abierta y muestra las opciones disponibles (scroll vertical):
> 2 copias últimos recibos nómin, A.P, Acta constitutiva, Acta constitutiva socio empres, Acta de defunción, Acta de nacimiento, Acta o demanda divorcio, Alcohol y drogas, Alfa-feto proteína, Antígeno carcinoembrionario, Antígeno prostático, Baja del IMSS, Biometría hemática, **CURP** (resaltado en azul/seleccionado), Carta asegurabilidad < 45 días, Carta separación asegurado Ins, Certificado cobertura de GMM, Colesterol, Colesterol LDL, Colonoscopia (y más, con barra de desplazamiento). Botón **"Cerrar"** (rojo) visible.

**b.** Al finalizar, hacer clic en el botón "Guardar información"

> **[IMAGEN - Modal "Agrega Documento" con campos llenos y flecha apuntando a "Guardar Información"]**
> Modal "Agrega Documento" con Cliente: **RODARTE RODRIGUEZ, RAYMUNDO ALONSO** y Documento: **CURP** seleccionados. Flecha roja apuntando al botón **"Guardar Información"** (blanco). Botón "Cerrar" (rojo) a la izquierda.

**c.** Al guardar el documento solicitado, se mostrará el nombre del documento que se requiere, con la opción de "Carga", sólo basta con cerrar la pantalla.

> **[IMAGEN - Modal "DOCUMENTOS ADJUNTOS" actualizado con nueva fila "CURP - Pendiente - Carga"]**
> El modal de documentos adjuntos ahora muestra 4 registros:
> - Contratante | Identificación oficial vigente | Recibido | "Ver Document" (botón recortado)
> - Contratante | Comprobante de domicilio | Recibido | "Ver Document"
> - Contratante | Firma manual | Recibido, por analizar | "Ver Document"
> - **Titular | CURP | Pendiente | Botón "Carga" (azul)**
>
> La fila nueva "CURP / Pendiente / Carga" confirma que el documento fue agregado correctamente. Pie: "Mostrando de 1 a 4 registros de 4 registros en total". Flecha roja apunta al botón "Carga". Botones: "Cerrar" (rojo) y "Agregar Documento".

---

**III.** Al regresar a la pantalla de "Detalle de solicitud", se debe agregar la información adicional, por lo que se da clic en "+Solicitar información adicional".

> **[IMAGEN - BeAware: pantalla "Detalle de Solicitud" con botón "+SOLICITAR INFORMACIÓN ADICIONAL"]**
> Ventana "INTERNA" en Edge, Folio: GMMI-A-18606. Panel izquierdo con el detalle del asegurado RODARTE RODRIGUEZ, RAYMUNDO ALONSO. Panel derecho (Información general) muestra el enlace **"VER DOCUMENTOS ADJUNTOS"** y en la parte superior derecha el botón **"+SOLICITAR INFORMACIÓN ADICIONAL"** (azul). En la sección de Hallazgos se ve: RODARTE RODRIGUEZ, RAYNAUNDO ALONSO — con flecha roja indicando dónde hacer clic.

---

**IV.** Se debe seleccionar el "Motivo", "Submotivo" y hacer clic en el botón "Guardar Información".

> **[IMAGEN - Modal "Solicitar información adicional" con Motivo y Submotivo seleccionados]**
> Modal titulado **"Solicitar información adicional"**. Campos:
> - **Motivo***: "Solicitud Firmada" (resaltado en amarillo, con ∨).
> - **Submotivo***: "La firma no coincide con la del documento de identificación" (resaltado en amarillo, con ∨).
> - "Por favor revisar la leyenda de notificación y añade el detalle requerido:*"
>   Campo de texto con contenido: "Le solicitamos ingresar nuevamente la solicitud debidamente firmada, ya que la firma plasmada en la solicitud no coincide con la del documento de identificación."
> - Flecha roja apuntando al botón **"Guardar Información"** (blanco/gris).

**V.** Al guardar la información, mostrará el mensaje "Se actualiza la información correctamente", con esto confirmamos la solicitud de información adicional.

> **[IMAGEN - Mensaje de confirmación "Se actualiza la información correctamente"]**
> Modal simple con ícono de información (ⓘ circular gris), texto: **"Se actualiza la información correctamente"** y botón **"OK"**.

**VI.** Regresar a la pantalla del detalle de folios de solicitud y hacer clic en el botón "Enviar resultado".

> **[IMAGEN - BeAware: pantalla "Solicitud AXA" con botón "Enviar Resultado" resaltado]**
> Ventana "Solicitud AXA" en Edge. Contratante: GUERRERO FLORES, PAMELA | Folio: GMMI-A-18606. Aviso en naranja: texto de análisis. Botones de acción: **"Solicitud de Información Adicional"**, **"Enviar Resultado"** (azul, señalado con flecha roja), **"Emitir"**, **"Rechazar"**. Tabla con los dos registros de RODARTE RODRIGUEZ, RAYMUNDO ALONSO (Titular / R.Laboral / Aprobado y Titular / IMC / Aprobado) con botones "VER DETALLE".

**VII.** Mostrará un mensaje con la leyenda "La notificación fue enviada".

> **[IMAGEN - Mensaje de confirmación "La notificación fue enviada"]**
> Modal simple con ícono ⓘ gris, texto: **"La notificación fue enviada"** y botón **"OK"**.

---

**VIII.** Con las acciones anteriores, el usuario puede validar desde el Dashboard consultando el dictamen correspondiente.

> **[IMAGEN - Dashboard con solicitud en estatus "Solicitud con información adicional" y dictamen actualizado]**
> Dashboard en Chrome. Agente: Moncada RINCON, Brenda. Fechas: 27/02/2026 — 02/03/2026. Tabla de trámites:
> | Folio | Titular | Fecha Registro | Inicio Vigencia | Estatus | SLA |
> |---|---|---|---|---|---|
> | GMMI-A-18251 | PUENTES OLVERA, PATRICIA | 02/03/2026 | — | **Solicitud con información adicional** | 16/03/2026 |
> | GMMI-A-18241 | NEVAREZ RIOS, MARISELA | 27/02/2026 | 27/03/2026 | Emitida | — |
>
> Debajo, la pantalla del dictamen correspondiente (Póliza Nueva, Contratante: MORALES HERNANDEZ, ROCIO NALLELI, Folio: GMMI-A-18251). Texto: "La solicitud fue turnada al análisis de selección de riesgos." Tabla:
> | Nombre del cliente | Parentesco | Resultado | Observaciones/Requerimos Información adicional |
> |---|---|---|---|
> | PUENTES OLVERA, PATRICIA | Titular | **Reg.Análisis** | — |
> | BURGOS ALVAREZ, MARISELA | Otros | **Reg.Análisis** | — |
> | MORALES HERNANDEZ, ROCIO NALLELI | Contratante | **Reg.Análisis** | "Le solicitamos ingresar nuevamente la solicitud detallamente requisitada y firmada, completando la información correspondiente al apartado de Aviso de Privacidad" |
>
> Botones al pie: **"Cargar documentos"** (azul, señalado con flecha roja) y **"Cerrar"**.

**IX.** Visualiza la opción "Cargar documentos".

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

Se levanta ticket de incidencia y se asigna al grupo de soporte: **-**

---

## Información ampliada

N/A
