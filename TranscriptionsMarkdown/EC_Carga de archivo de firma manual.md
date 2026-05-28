# EC_Carga de archivo de firma manual

> **Clasificación:** Internal

---

## Descripción

El usuario se comunica con la Mesa de Atención para reportar un error al realizar la carga del archivo de Firma Manual Autógrafa.

---

## Clasificación y Prioridad

- **Tipo de ticket:** Incidente
- **Servicio de negocio:** -
- **Categoría:** Application
- **Subcategoría:** Performance
- **Impacto:** - **Urgencia:** -

---

## Solución paso a paso

**I.** Preguntar al usuario si el archivo que cargó previamente cumple con los requisitos de formato.

**a.** Los requisitos de formato vienen especificados en el cuadro "Carga de documentos".

> **[IMAGEN - Cuadro "Carga de documentos" (Página 1)]**
> Se muestra un cuadro modal/panel titulado **"Carga de documentos"** con fondo de encabezado azul oscuro. El cuadro contiene:
>
> - **Sección "Instrucciones"** con el siguiente texto:
>   - "Para agregar imágenes, haga click sobre el botón '+'. Hecho eso, aparece una ventana que le permitirá seleccionar la(s) imagen(es) deseada(s)."
>   - "Dentro de la ventana de selección y haciendo uso del botón 'Examinar', ubique la(s) imagen(es) que desea asociar al reporte/caso."
>   - "Terminada la selección de la(s) imagen(es), presione el botón 'Subir archivos', esto carga la(s) imagen(es). Presione la 'X' que se encuentra en la parte inferior derecha para cerrar la ventana de carga."
>   - "Puede repetir el proceso tantas veces como lo considere necesario."
>
> - **Barra de acciones** con tres botones: **"+ Agregar"** (azul), **"↺ Refrescar"** (blanco con borde) y **"🗑 Borrar"** (rojo).
>
> - **Tabla** con columnas: casilla de selección, **"Nombre"**, **"Descripción"**, **"Descargar"**. La tabla muestra el mensaje: *"No se encontraron registros"*.
>
> - **Nota en recuadro amarillo/beige** en la parte inferior:
>   - "** Solo se admiten archivos tipo: pdf, jpg, jpeg, bmp. No se admiten correos desde outlook (.msg), ni documentos (doc, docx, xls, xlsx, ppt, pptx)."
>   - "Nota: Para evitar errores, procura renombrar los archivos con nombres cortos y sin caracteres intermedios o especiales ($,/(#%&, etc.)"
>
> - **Dos botones** en la parte inferior: **"Cancelar"** (gris/blanco) y **"Continuar"** (azul oscuro).

**b.** Si el usuario indica que el archivo que cargó previamente cumple con los requisitos de formato entonces continúa con el punto II.

---

**II.** Desde el Dashboard, retomar la solicitud haciendo clic en la opción "Continuar".

**a.** Visualizar la pantalla "Solicitud de póliza – Producto Flex Plus".

> **[IMAGEN - Dashboard "Seguimiento de trámites" y pantalla "Solicitud de póliza – Producto Flex Plus" (Página 2)]**
>
> La imagen contiene dos secciones apiladas verticalmente:
>
> **Sección superior — Dashboard "Seguimiento de trámites":**
> Interfaz de la plataforma AXA. En la esquina superior derecha hay dos botones: **"NUEVA COTIZACIÓN"** y **"SOLICITAR ENDOSO"**. Debajo hay un panel de filtros:
> - Radio buttons: **TODAS** (seleccionado, punto azul), NUEVO NEGOCIO, ENDOSO / MANTENIMIENTO, RENOVACIÓN.
> - Campo "Agente": **Alvarado, Alberto** con menú desplegable.
> - Campos de fecha: "Fecha Inicio: 19/03/2026" y "Fecha Fin: 26/03/2026" con íconos de calendario y botón **"Consultar"** (azul).
>
> Tabla de resultados con columnas: **Trámite, Folio, Intermediario, Póliza, Nº Endoso, Titular, Fecha Registro, Inicio Vigencia, Estatus, SLA, Acción**. La tabla muestra múltiples registros de "Nuevo Negocio" con folios del tipo GMMI-A-18XXX, todos con intermediario "Alvarado, Alberto", fechas de registro 23/03/2026 o 20/03/2026, y estatus variados ("En cotización", "Solicitud en análisis", "Solicitud en registro"). En la fila del folio **GMMI-A-18557** (Titular: HERNANDEZ DURAN, ABAD) aparece un menú desplegable emergente con tres opciones resaltadas: **"Continuar"** (en azul/verde), **"Imprimir"** y **"Cancelar"** (en rojo). Pie de tabla: "Mostrando de 11 a 20 registros de 32 registros en total | 10 registros por página | < 1 2 3 4 >".
>
> **Sección inferior — Pantalla "Solicitud de póliza – Producto Flex Plus":**
> Encabezado con logotipo de **AXA** (letras blancas sobre fondo negro) en la esquina superior izquierda. En la esquina superior derecha: "Bienvenido: 90756-Hernandez Duran, Abad" y debajo "Folio: GMMI-A-18557".
> Título en azul: **"Solicitud de póliza - Producto Flex Plus"**.
> Tres secciones en acordeón con fondo verde azulado:
> 1. **"Información general"** — con flecha apuntando hacia abajo (colapsado).
> 2. **"Entrevista"** — con flecha apuntando hacia arriba (expandido/activo).
> 3. **"Carga de documentos"** — recuadrada con borde rojo (resaltada como indicación visual), con flecha apuntando hacia arriba. Esta sección está marcada específicamente como el paso a seguir.
>
> En la parte inferior de la pantalla dos botones: **"CANCELAR"** (borde gris) y **"ENVIAR"** (azul).

---

**III.** Hacer clic en la flecha de la sección "carga de documentos".

**IV.** Hacer clic en botón "Agregar"

> **[IMAGEN - Sección "Instrucciones firma manual" con botón "Agregar" (Página 2, parte inferior)]**
> Se muestra el panel expandido de la sección **"Instrucciones firma manual"** dentro de la solicitud. Contiene:
> - Texto de instrucción en color gris oscuro: "Descarga, imprime y entrega al solicitante para recabar sus firmas. Una vez recabadas las firmas, escanea, carga y envía la solicitud para ser revisada. AXA validará la información y notificaremos si la solicitud es aceptada, rechazada o si es necesario adjuntar información adicional."
> - Barra de acciones: **"+ Agregar"** (azul), **"↺ Refrescar"** (blanco) y **"🗑 Borrar"** (rojo).
> - Tabla con columnas: casilla de selección, **"Nombre"**, **"Descripción"**, **"Descargar"**. Muestra: *"No se encontraron registros"*.
> - Botón **"Aceptar carga"** (azul, en la parte inferior izquierda).

---

**a.** Hacer clic en el botón "Examinar"

> **[IMAGEN - Ventana modal "Agregar" con área de carga de archivo (Página 3, parte superior)]**
> Ventana modal titulada **"Agregar"** con encabezado azul oscuro. Contiene tres campos:
> - **"Descripción"**: campo de texto vacío.
> - **"Fecha de expiración"**: campo de texto vacío con ícono de calendario (negro) a la derecha.
> - **"Archivo"**: área de carga representada por un rectángulo con borde discontinuo gris. En el centro del área aparece el texto **"Arrastre y suelte aquí los archivos …"**. Debajo del área aparece el texto "Seleccionar archivos..." y un botón azul con ícono de carpeta: **"Examinar …"**.
> - En la esquina inferior derecha: botón **"× Cerrar"** (gris).

**i.** Seleccione el archivo a cargar que cumpla con las especificaciones de formato. Posteriormente hacer clic en "Abrir".

> **[IMAGEN - Explorador de archivos de Windows — Ventana "Abrir" (Página 3, parte inferior)]**
> Ventana del explorador de archivos de Windows titulada **"Abrir"** (barra superior con × para cerrar en la esquina derecha). La barra de navegación superior muestra la ruta: **Este equipo > Alethia, AXA > 01.WinDevice > Imágenes**. Hay botones de navegación (←, →, ↑), un campo de búsqueda con lupa a la derecha ("Buscar en Imágenes"), y botones "Organizar ▼" y "Nueva carpeta".
>
> El panel izquierdo (árbol de carpetas) muestra: Inicio, Galería, Alethia AXA (con subentradas), Documentos, Descargas, **Imágenes** (resaltada en azul), Música, Vídeos, Screenpresso, CP013, Carga de documentos.
>
> El panel derecho (contenido de la carpeta "Imágenes") muestra una lista de archivos PNG con sus detalles:
> | Nombre | Fecha | Tipo | Tamaño |
> |---|---|---|---|
> | firma | 18/07/2025 02:46 p.m. | Archivo PNG | 219 KB |
> | Fila57 | 26/06/2025 01:00 p.m. | Archivo PNG | 145 KB |
> | Fila10 | 26/06/2025 12:54 p.m. | Archivo PNG | 47 KB |
> | cp contratante | 04/06/2025 05:57 p.m. | Archivo PNG | 101 KB |
> | contraseña incorrecta | 04/06/2025 05:57 p.m. | Archivo PNG | 31 KB |
> | Está mal el orden | 02/06/2025 12:39 p.m. | Archivo PNG | 41 KB |
> | Titular en dashboard, p… | 30/05/2025 12:47 p.m. | Archivo PNG | 90 KB |
> | Titular en dashboard | 30/05/2025 12:45 p.m. | Archivo PNG | 68 KB |
> | parentesco | 29/05/2025 11:22 a.m. | Archivo PNG | 87 KB |
> | hora fecha de nacimiento | 29/05/2025 10:17 a.m. | Archivo PNG | 46 KB |
> | Botón Enviar | 04/04/2025 01:21 p.m. | Archivo PNG | 134 KB |
> | Ocupación Empleado | 04/04/2025 01:19 p.m. | Archivo PNG | 139 KB |
>
> En la parte inferior: campo "Nombre:" (vacío), menú "Todos los archivos", y botones **"Abrir"** (azul) y **"Cancelar"** (blanco).

---

**b.** Hacer clic en "Subir archivo"

> **[IMAGEN - Ventana modal "Agregar" con archivo cargado lista para subir (Página 4, parte superior)]**
> La misma ventana modal **"Agregar"** ahora muestra el archivo seleccionado en el área de carga:
> - **"Descripción"**: campo vacío.
> - **"Fecha de expiración"**: campo vacío con ícono de calendario azul.
> - **"Archivo"**: el área de carga ahora muestra una vista previa en miniatura de la imagen seleccionada. La miniatura muestra una imagen publicitaria de AXA con fondo azul/morado y la frase **"Juntos para su tranquilidad"** junto a dos personas (una persona al fondo y una pareja mirando un documento). Debajo de la miniatura aparece el nombre del archivo: **"firma.png (218.66 KB)"** y dos íconos (un círculo naranja/rojo a la izquierda y un círculo con signo + a la derecha).
> - Debajo del área, aparece el nombre del archivo seleccionado: **"firma.png"** precedido por un ícono de documento azul.
> - Barra de acciones con tres botones: **"🗑 Quitar"** (ícono de papelera), **"⊕ Subir archivo"** (botón azul resaltado, con ícono de flecha hacia arriba) y **"📁 Examinar …"** (botón con ícono de carpeta).
> - Botón **"× Cerrar"** en esquina inferior derecha.

---

**V.** Dar clic en "Aceptar carga"

> **[IMAGEN - Panel "Instrucciones firma manual" con archivo firma.png en tabla (Página 4, parte inferior)]**
> El panel de **"Instrucciones firma manual"** ahora muestra el archivo cargado en la tabla:
> - Texto de instrucción (igual que antes): "Descarga, imprime y entrega al solicitante para recabar sus firmas..."
> - Barra de acciones: **"+ Agregar"**, **"↺ Refrescar"**, **"🗑 Borrar"** (rojo).
> - Tabla con una fila registrada:
>   - Casilla de selección vacía
>   - **Nombre**: "firma.png" (con un ícono de menú/opciones a la derecha representado por "~")
>   - **Descripción**: (vacía, con "~")
>   - **Descargar**: ícono de flecha hacia abajo (▲ invertida, para descargar)
> - Pie de tabla: "Mostrando de 1 a 1 registros de 1 registros en total".
> - Botón **"Aceptar carga"** (azul/morado) en la parte inferior izquierda, rodeado con borde rojo como indicación visual de que debe presionarse.

**a.** Verificar que se haya recibo correctamente el documento de Firma manual en el cuadro Documentos requeridos, Firma manual con estatus "Recibido" y concluye este procedimiento.

> **[IMAGEN - Cuadro "Carga de documentos" con tabla "Documentos requeridos" (Página 5, parte superior)]**
> Panel expandido titulado **"Carga de documentos"** (encabezado azul oscuro con flecha hacia arriba indicando que está expandido). Dentro hay una subsección **"CARGA DE DOCUMENTOS"** con flecha hacia abajo.
>
> Subtítulo: **"Documentos requeridos"** (en azul) seguido del texto: "Se requiere adjuntar los siguientes documentos:".
>
> Tabla con columnas: **Número, Parentesco, Documento, Fecha solicitud, Estado del Documento** (y columna de acción). Tres filas:
> | Número | Parentesco | Documento | Fecha solicitud | Estado del Documento | |
> |---|---|---|---|---|---|
> | 1 | Contratante | Identificación oficial vigente | 26/03/2026 | Recibido | Botón "Cargar" |
> | 1 | Contratante | Comprobante de domicilio | 26/03/2026 | Recibido, por analizar | Botón "Cargar" |
> | 1 | Contratante | **Firma manual** | 26/03/2026 | **Recibido** (etiqueta en fondo amarillo/dorado) | Botón "Cargar" |
>
> La fila de **"Firma manual"** está enmarcada con un borde rojo como indicación visual de que es el documento que se acaba de cargar exitosamente con estatus **"Recibido"**.

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
