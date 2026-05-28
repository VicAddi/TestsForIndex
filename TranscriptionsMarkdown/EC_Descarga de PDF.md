# EC_Descarga de PDF

> **Clasificación:** Internal

---

## Descripción

El usuario se comunica con la Mesa de Atención para reportar un error al realizar la descarga de un documento PDF, de acuerdo con los casos descritos en la sección "Solución paso a paso" de este documento.

- Descargar PDF´s Cotización – Solicitud –Emisión
- Descargar PDF de la Carátula de la póliza

---

## Clasificación y Prioridad

- **Tipo de ticket:** Incidente
- **Servicio de negocio:** -
- **Categoría:** Application
- **Subcategoría:** Performance
- **Impacto:** - **Urgencia:** -

---

## Solución paso a paso

---

## Descargar PDF´s Cotización – Solicitud –Emisión

**I.** En caso de que se muestre el mensaje **"Server Error in '/' Application"**, favor de volver a realizar el proceso de descarga. Solo se muestra debido a una *intermitencia de seguridad* y aplica para los navegadores "Edge" y "Google Chrome"

> **[IMAGEN - Pantalla de error "Server Error in '/' Application" (Página 1)]**
> Se muestra una página de error genérica de ASP.NET en fondo blanco. El contenido es:
>
> - Título en rojo/naranja: **"Server Error in '/' Application."**
> - Subtítulo en cursiva roja: *"A potentially dangerous Request.Path value was detected from the client (&)."*
> - **Description:** "An unhandled exception occurred during the execution of the current web request. Please review the stack trace for more information about the error and where it originated in the code."
> - **Exception Details:** "System.Web.HttpException: A potentially dangerous Request.Path value was detected from the client (&)."
> - **Source Error:** Cuadro de color naranja/beige que dice: "An unhandled exception was generated during the execution of the current web request. Information regarding the origin and location of the exception can be identified using the exception stack trace below."
> - **Stack Trace:** (fondo blanco con texto en código monoespaciado):
>   ```
>   [HttpException (0x80004005): A potentially dangerous Request.Path value was detected from the client (&).]
>      System.Web.HttpRequest.ValidateInputIfRequiredByConfig() +678
>      System.Web.PipelineStepManager.ValidateHelper(HttpContext context) +52
>   ```
> - Pie de página: "**Version Information:** Microsoft .NET Framework Version:4.0.30319; ASP.NET Version:4.8.4797.0"

---

**II.** Descarga del PDF Comparativo – Regrese a la pantalla del proceso de cotización y proceda a descargar de nuevo el archivo del "Comparativo"

> **[IMAGEN - Pantalla "Cotizador Gastos Médicos Mayores - Oferta de Planes" en Chrome + panel de descargas recientes (Página 2)]**
>
> La imagen muestra dos ventanas del navegador Google Chrome apiladas verticalmente:
>
> **Ventana superior — Cotizador (popup):**
> Barra de título: "Cotizador Gastos Médicos Mayores - Oferta de Planes - Google Chrome". URL: `uat-int-axasalud.visualtime.cl/fasi/dli/forms/COTAXA004Popup.html?id=fc3d7882-3f28-436f-ab7b-17b486859d1f`
>
> Contenido del cotizador:
> - **Selección de IVA:** "IVA Informativo. Se aplicará el correspondiente al código postal del contratante." con casilla IVA y valor **8%**.
> - Botón **"COMPARATIVO"** (azul, a la izquierda).
> - Tres columnas de propuestas: **✓ PAQUETE BASE**, **✓ PROPUESTA 2**, **☐ PROPUESTA 3**.
>
> Datos de cada propuesta (resumidos):
> | Concepto | Paquete Base | Propuesta 2 | Propuesta 3 |
> |---|---|---|---|
> | Primer pago | $80,710.99 | $84,589.63 | $105,892.16 |
> | Pago total anual | **$80,710.59** | **$84,589.63** | **$105,892.16** |
> | Prima base | $46,823.15 | $46,823.15 | $51,775.10 |
> | Coberturas adicionales | $21,904.95 | $25,248.95 | $37,661.25 |
> | Descuento familiar | $0.00 | $0.00 | $0.00 |
> | Prima neta | $67,728.10 | $71,072.10 | $89,436.35 |
> | Recargo por pago fraccionado | $0.00 | $0.00 | $0.00 |
> | Derecho de póliza | $1,850.00 | $1,850.00 | $1,850.00 |
> | I.V.A. | $11,132.49 | $11,667.53 | $14,605.81 |
>
> Cada propuesta tiene botones: **"Descargar ↓"**, **"Seleccionar 🖻"**, **"Mostrar menos"**.
>
> Nota al pie: "El IVA incluido en esta cotización se calculó de acuerdo con lo seleccionado. Este monto puede variar al momento de la emisión de la póliza si el código postal del contratante no es sujeto a este beneficio o se actualizan las disposiciones fiscales."
> Botones de navegación: **"Salir"** y **"Regresar"** (izquierda), **"Continuar"** (derecha, azul).
>
> **Ventana inferior — VisualTIME con panel de descarga:**
> Barra de título: "VisualTIME" con pestaña "×" y "+". URL: `uat-int-axasalud.visualtime.cl/fasi/default.aspx`. En la esquina superior derecha aparece un panel emergente de descargas recientes con dos archivos PDF listados:
> - `79344632-289b-11f1-8f88-6472cc150000.pdf` — 23.5 KB • Listo
> - `66a6672a-289b-11f1-949a-6472cc140000.pdf` — 46.1 KB • Listo
>
> Debajo de la lista: casilla de verificación "□ No mostrar cuando finalicen las descargas" y texto: "Puedes cambiar este parámetro cuando lo desees en configuración".
>
> El panel de navegación izquierdo (barra lateral oscura) muestra: logotipo AXA, nombre "Maria Fernanda VEGA / User-", y menú con: Pólizas (con submenú: Tratamiento de pólizas, Transacciones de cartera, Carga masiva, Consultas de Pólizas, Procesos batch y reportes, Transacciones fiscales), IrABeAware, Ir al Dashboard. Botón "+ Nueva página" en la esquina inferior derecha.

---

**III.** Descarga del PDF Cotización – Regrese a la pantalla del proceso de cotización y proceda a descargar de nuevo el archivo del "Cotización" (ya sea el "Paquete Base", "Propuesta 2" y "Propuesta 3")

> **[IMAGEN - Cotizador con flecha indicando "Descargar" en Paquete Base + historial de descargas completo (Página 3)]**
>
> **Ventana superior — Cotizador (misma pantalla que antes):**
> Idéntica a la imagen anterior con las tres propuestas (PAQUETE BASE seleccionado con ✓, PROPUESTA 2 con ✓, PROPUESTA 3 sin seleccionar). Se agrega una **flecha roja** apuntando al botón **"Descargar ↓"** de la columna "PAQUETE BASE", indicando visualmente qué botón se debe presionar.
>
> **Ventana inferior — VisualTIME con historial de descargas recientes expandido:**
> Panel titulado **"Historial de descargas recientes"** con botón × para cerrar (esquina superior derecha). Lista cuatro archivos PDF:
> 1. `bb7d96a6-289b-11f1-949a-6472cc14000 0.pdf` — 45.5 KB • Listo
> 2. `92098ef6-289b-11f1-949a-6472cc140000.pdf` — 47.1 KB • Hace 1 minuto
> 3. `79344632-289b-11f1-8f88-6472cc150000.pdf` — 23.5 KB • Hace 2 minutos
> 4. `66a6672a-289b-11f1-949a-6472cc140000.pdf` — 46.1 KB • Hace 3 minutos
>
> Link: "**Historial de descargas completo** 🔲"

> **[IMAGEN - Cotizador con flecha indicando "Descargar" en Propuesta 2 + panel de una descarga reciente (Página 4)]**
>
> **Ventana superior — Cotizador:**
> Misma pantalla del cotizador. Ahora **PAQUETE BASE** aparece sin seleccionar (☐) y **PROPUESTA 2** aparece seleccionada (✓). La **flecha roja** ahora apunta al botón **"Descargar ↓"** de la columna "PROPUESTA 2".
>
> **Ventana inferior — VisualTIME con una descarga reciente:**
> Panel simplificado de descarga que muestra un solo archivo:
> - `66a6672a-289b-11f1-949a-6472cc140000.pdf` — 46.1 KB • Listo (recuadrado en rojo como indicación visual)
>
> Debajo: casilla "□ No mostrar cuando finalicen las descargas".

---

**IV.** Descarga del PDF Solicitud – Regrese a la pantalla del proceso de cotización y proceda a descargar de nuevo el archivo de la "Solicitud"

> **[IMAGEN - Cotizador con flecha indicando "Descargar" en Propuesta 3 + historial de descargas (Página 5)]**
>
> **Ventana superior — Cotizador:**
> Misma pantalla. Ahora **PROPUESTA 3** aparece seleccionada (✓ PROPUESTA 3). La **flecha roja** apunta al botón **"Descargar ↓"** de la columna "PROPUESTA 3".
>
> **Ventana inferior — VisualTIME con historial de descargas recientes:**
> Panel con tres archivos PDF:
> 1. `92098ef6-289b-11f1-949a-6472cc140000.pdf` — 47.1 KB • Listo
> 2. `79344632-289b-11f1-8f88-6472cc150000.pdf` — 23.5 KB • Hace 1 minuto
> 3. `66a6672a-289b-11f1-949a-64 [recortado]` con íconos de carpeta y lápiz — 46.1 KB • Hace 2 minutos
>
> Link: "**Historial de descargas completo** 🔲"

**a.** De esta forma concluye la actividad.

> **[IMAGEN - Pantalla "Solicitud de Seguros AXA - Documentos" con descarga exitosa (Página 6)]**
>
> La imagen muestra dos secciones:
>
> **Ventana superior — Solicitud de Seguros AXA:**
> Barra de título: "Solicitud de Seguros AXA - Documentos - Google Chrome". URL: `uat-int-axasalud.visualtime.cl/fasi/dli/forms/SOLAXA013Popup.html?id=5ca90d4b-d256-4c91-86a9-aa1db4c195af`
>
> Contenido de la página:
> - Sección **"Documentos requeridos"**: tabla con columnas Número, Parentesco, Documento, Fecha solicitud, Estado del Documento.
>   - Fila 1: 1 / Contratante / Identificación oficial vigente / 25/03/2026 / Recibido — Botón "Cargar"
>   - Fila 2: 1 / Contratante / Comprobante de domicilio / 25/03/2026 / Recibido — Botón "Cargar"
>
> - Sección **"SOLICITUD DIGITAL"** con flecha desplegable (→):
>   - Pregunta: "¿Quieres descargar la solicitud digital?"
>   - Botón azul con flecha de descarga: **"↓ Descargar solicitud"** (señalado con una flecha roja como indicación visual del botón a presionar).
>
> - Sección **"FIRMA"**:
>   - "¿Cómo quieres firmar la solicitud?"
>   - Opción seleccionada (punto azul): **"Firma Autógrafa Digital (FAD)"**
>   - Opción no seleccionada: "Firma Autógrafa Manual"
>
> Botones: **"CANCELAR"** y **"ENVIAR"** (azul).
>
> **Ventana inferior — VisualTIME con descarga completada:**
> Panel emergente de descarga en la esquina superior derecha mostrando:
> - `e0b344ba-289c-11f1-8f88-6472cc150000.pdf` — 99.7 KB • Listo (recuadrado en rojo como indicación de éxito)
>
> La barra lateral izquierda de VisualTIME muestra: AXA logo, "Maria Fernanda VEGA / User-", menú de navegación con Pólizas y submenús (Tratamiento de pólizas, Transacciones de cartera, Carga masiva, Consultas de Pólizas, Procesos batch y reportes, Transacciones fiscales), IrABeAware, Ir al Dashboard.

---

## Descargar la Carátula de la Póliza desde el Dashboard

**I.** En caso de que se muestre el mensaje **"Ha ocurrido algo inesperado"** o algún mensaje parecido de error, se puede realizar la descarga desde el navegador "Edge" o bien volver a intentar en el navegador de "Chrome" realizando primero una configuración.

> **[IMAGEN - Dashboard con mensaje de error "Ha ocurrido algo inesperado" (Página 7, parte superior)]**
> Pantalla del Dashboard de AXA (plataforma VisualTIME). Encabezado: logotipo AXA (letras blancas sobre fondo negro), título **"Trámites"**. En la esquina superior derecha: "Bienvenido: 90021-BALLESTEROS REYES, DAVID". Panel de filtros: radio buttons TODAS (seleccionado), NUEVO NEGOCIO, ENDOSO/MANTENIMIENTO, RENOVACIÓN. Campo Agente: "BALLESTEROS REYES, DAVID". Campos Fecha Fin: 21/01/2026 con botón "Consultar".
>
> Sobre la tabla de resultados aparece un **cuadro modal de error** con:
> - Ícono circular con "×" en la esquina superior derecha del modal.
> - Texto: **"Ha ocurrido algo inesperado."**
> - Subtexto: "Número de referencia: 'cc85e7d1-7e27-46cf-a8af-0ce387b6996b'"
> - Botón: **"OK"** (azul).
>
> La tabla de resultados de fondo muestra varios registros tipo "Nuevo Negocio" con folios GMMI-A-177XX, intermediario BALLESTEROS REYES, DAVID, con estatus variados (En cotización, Emitida, Solicitud en análisis, Solicitud en registro).

**a.** Acceder al navegador "Edge".

**i.** Consultar por medio del "No. de Folio" desde el Dashboard.

> **[IMAGEN - Microsoft Edge con Dashboard y búsqueda por folio GMMI-A-18588 (Página 7, parte inferior)]**
> Ventana de Microsoft Edge, título: "Mis trámites - Trabajo. Microsoft Edge". URL: `https://uat-int-axasalud.visualtime.cl/fasi/dli/forms/DASHAXA001Popup.html`
>
> Contenido: Panel "Trámites" con "Seguimiento de trámites". Filtros activos: TODAS (seleccionado), Agente: Alvarado, Alberto. Campo "Buscar por Nro. de Folio": **GMMI-A-18588** (resaltado en amarillo). Fechas: Inicio 18/03/2026 — Fin 25/03/2026. Botón "Consultar".
>
> Tabla con un único resultado:
> | Trámite | Folio | Intermediario | Póliza | Nº Endoso | Titular | Fecha Registro | Inicio Vigencia | Estatus | SLA | Acción |
> |---|---|---|---|---|---|---|---|---|---|---|
> | Nuevo Negocio | GMMI-A-18588 | Alvarado, Alberto | 3322AB00 | - | ALARCON CARLOS, MIGUEL ANGEL | 26/03/2026 | 25/03/2026 | Emitida | - | |
>
> Pie: "Mostrando de 1 a 1 registros de 1 registros en total".

**ii.** Hacer clic en el icono "…"

**1.** Hacer clic en la opción "Imprimir".

> **[IMAGEN - Microsoft Edge con menú de acción "Imprimir" / "Reproceso" y vista previa de Carátula (Página 8)]**
>
> La imagen tiene dos secciones:
>
> **Sección superior — Dashboard en Microsoft Edge con menú desplegable de acciones:**
> Misma ventana de Edge. En la fila del folio GMMI-A-18588 (Nuevo Negocio / Alvarado, Alberto / 3322AB00 / ALARCON CARLOS, MIGUEL ANGEL / 26/03/2026 / 25/03/2026 / Emitida), en la columna "Acción" aparece un menú desplegable con dos opciones resaltadas:
> - **"Imprimir"** (en negrita, señalado con flecha roja)
> - **"Reproceso"**
>
> **Sección inferior — Vista previa del documento "Salud_Caratula" en Microsoft Edge:**
> Pestaña activa: "Salud_Caratula". URL: `uat-int-axasalud.visualtime.cl/Temp/exstream_view.ashx?nBranch=34&nProduct=341018nPolicy=5120361&nCertif=0&nType_hist=1&nMoveme...`
>
> Barra de herramientas de visualización de PDF: "☰ Salud_Caratula | 1 / 3 | — 100% + | 📋 🔄 | 🔎 ↩ 🖨️" y controles de zoom. Mensaje informativo: "Este archivo tiene permisos limitados. Es posible que no tengas acceso a algunas características. Ver permisos".
>
> Vista previa del documento PDF (Carátula de póliza):
> - Cabecera: "-*- Demonstration Powered by OpenText Exstream 03/26/2026, Version 25.2.1 64-bit (DBCS) -*-" y en la esquina: "Hoja 1 de 3"
> - Logotipo AXA en la esquina superior izquierda.
> - Título al centro: "**Gastos Médicos** / **Carátula de póliza** / **Gastos Médicos Mayores Individual / Familiar**"
> - Sección **"Datos del contratante"** (tabla con fondo azul en encabezado):
>   - Nombre: PAMELA GUERRERO FLORES | CURP: GUFP960604MMCRLM07
>   - Domicilio: La Draga
>   - CDMX | Código postal: 13273 | Ciudad: Tláhuac
>   - R.F.C.: GUFP9606049B8 | Teléfono: 5581227079
> - Sección **"Datos de los Asegurados"** (tabla):
>   - MIGUEL ANGEL ALARCON CARLOS | Titular | Fecha de alta: 25/03/2026 | Antigüedad AXA Ind.: 25/03/2026 | Antigüedad Reconocida: 25/03/2026
> - Sección **"Condiciones Contratadas"**:
>   - Suma Asegurada: $96,500,000 | Póliza: 3322AB00
>   - Gama Hospitalaria: Esmeralda | Tipo de plan: **Flex Plus**
>   - (resto del documento no visible por recorte)
>
> Panel izquierdo: miniaturas de las 3 páginas del documento numeradas 1, 2, 3.

---

**II.** Reestablecer la configuración desde el navegador "Chrome".

**a.** Cerrar sesión en el navegador Chrome.

> **[IMAGEN - VisualTIME en Chrome con menú de acción "Imprimir"/"Reproceso" (Página 8, sección superior no mostrada en pág. 8 sino en pág. 9 — ver continuación)]**

**b.** Desde el menú ubicado en la parte superior derecha, en la lista desplegable, seleccionar la opción "Configuración".

> **[IMAGEN - Google Chrome: pantalla de inicio de Google con menú desplegable abierto (Página 9)]**
>
> La imagen muestra dos ventanas del navegador Google Chrome:
>
> **Ventana superior — VisualTIME en Chrome:**
> Barra de título: "VisualTIME". URL: `uat-int-axasalud.visualtime.cl/fasi/default.aspx?IrABeAwareFormId=`. Icono de descarga en la barra superior con dos flechas apuntando (→→) en esquina superior derecha.
> Interfaz de VisualTIME: panel izquierdo con AXA logo, "Maria Fernanda VEGA / User-", menú de Pólizas con submenús (Tratamiento de pólizas, Transacciones de cartera, Carga masiva, Consultas de Pólizas, Procesos batch y reportes, Transacciones fiscales), IrABeAware, Ir al Dashboard. Botón "+ Nueva página".
>
> **Ventana inferior — Nueva pestaña de Chrome con menú de configuración abierto:**
> Barra de título: "Nueva pestaña". Barra de direcciones con "G" (Google). La página muestra la pantalla de inicio de Chrome con el logotipo de **Google** (colores rojo, azul, amarillo, verde) y barra de búsqueda. Accesos directos: Acceder, VisualTIME, Secure GPT, distribuidores-c…, BeAware, Tienda virtual. Pie: "Administrado por tu organización".
>
> En la esquina superior derecha hay un **menú desplegable del navegador Chrome** abierto, con las siguientes opciones listadas:
> - 🕐 Historial >
> - ↓ Descargas (Ctrl+J)
> - ☆ Favoritos y listas >
> - ≡≡ Grupos de pestañas >
> - 🧩 Extensiones >
> - 🗑 Borrar datos de navegación… (Ctrl+Shift+Supr)
> - 🔍 Zoom — 100% + ⊞
> - 🖨 Imprimir… (Ctrl+P)
> - 🔍 Buscar esta pestaña con Google Lens
> - 🌐 Traducir…
> - 📋 Buscar y editar >
> - 🔗 Guardar y compartir >
> - ⚙ Más herramientas >
> - ❓ Ayuda >
> - **⚙ Configuración** (señalado con flecha roja →)
> - 🚪 Salir
> - 🖥 Administrado por tu organización

**i.** En la columna del lado izquierdo, seleccionar la opción "Restablecer configuración".

> **[IMAGEN - Chrome: página de Configuración (chrome://settings) (Página 10, parte superior)]**
> Ventana del navegador Chrome en la página de configuración. Barra de título: "VisualTIME" y "Configuración". URL: `Chrome chrome://settings`. Icono del navegador Chrome en la barra.
>
> Panel de configuración de Chrome:
> - Barra de búsqueda superior: "🔍 Buscar en configuración"
> - Aviso: "🖥 Tu organización administra el navegador"
> - Sección principal: "Tú y Google" con subsecciones:
>   - ⚙ Trabajo (→)
>   - Sincronización y servicios de Google (→)
>   - Importar favoritos y configuración (→)
>
> **Menú izquierdo** (columna de navegación), con las siguientes opciones con íconos:
> - ⚡ Rendimiento
> - 🎨 Diseño
> - 🔍 Motor de búsqueda
> - 🖥 Navegador predeterminado
> - ⏻ Al iniciar
> - 🌐 Idiomas
> - ↓ Descargas
> - ♿ Accesibilidad
> - 🔧 Sistema
> - **🔄 Restablecer configuración** (señalado con flecha roja →, resaltado en la lista)
> - 🔗 Extensiones 🔲
> - ⚙ Acerca de Chrome

**1.** Seleccionar la opción "Restablecer la configuración a los valores predeterminados originales"

> **[IMAGEN - Chrome: Configuración > Restablecer configuración (chrome://settings/reset) (Página 10, parte inferior)]**
> Misma ventana de configuración de Chrome. URL: `Chrome chrome://settings/reset`. La pestaña activa muestra "Configuración: Restablecer con…".
>
> La sección central ahora muestra:
> - Aviso: "🖥 Tu organización administra el navegador"
> - Sección: "Restablecer configuración"
> - Opción con flecha: **"→ Restablecer la configuración a los valores predeterminados originales"** (señalado con flecha roja → como indicación) con flecha de navegación (>) a la derecha.
>
> Menú izquierdo igual que antes, con "🔄 Restablecer configuración" ahora resaltado en azul.

---

**2.** Seleccionar la opción "Restablecer configuración".

> **[IMAGEN - Chrome: Diálogo de confirmación "¿Deseas restablecer la configuración?" (Página 11, parte superior)]**
> Misma página de configuración de Chrome (URL: `chrome://settings/resetProfileSettings?origin=userclick`). Aparece un **cuadro de diálogo modal** superpuesto con fondo semitransparente:
>
> Título: **"¿Deseas restablecer la configuración?"**
> Texto informativo: "Si realizas esta acción, sucederá lo siguiente:"
> - "• Se restablecerá parte de la configuración y los accesos directos de Chrome."
> - "• Se inhabilitarán las extensiones."
> - "• Se borrarán las cookies y otros datos temporales de sitios."
>
> Nota: "Esta acción no afectará los favoritos, el historial ni las contraseñas guardadas. Más información" (enlace azul).
>
> Casilla de verificación activa (✓): "Informa tu configuración actual para ayudarnos a mejorar Chrome".
>
> Dos botones en la parte inferior:
> - **"Cancelar"** (blanco/gris)
> - **"Restablecer configuración"** (azul, señalado con flecha roja →)

**c.** Vuelva a abrir el navegador de "Chrome" e inicie sesión.

**i.** Desde el Dashboard, consultar por medio del "No. de Folio" y hacer clic en el icono "…" en la columna "Acciones".

> **[IMAGEN - Dashboard en Google Chrome con folio GMMI-A-18588 buscado (Página 11, parte inferior)]**
> Ventana de Google Chrome. Título: "Mis trámites - Google Chrome". URL: `uat-int-axasalud.visualtime.cl/fasi/dli/forms/DASHAXA001Popup.html`. Esquina superior derecha: "Bienvenido: 90788-VEGA ROMERO, Maria Fernanda". Título de sección: "Trámites" (letras blancas sobre fondo oscuro con logo AXA). Subsección: "Seguimiento de trámites".
>
> Filtros: TODAS (•), Agente: Alvarado, Alberto (menú), Buscar Nro. de Folio: **GMMI-A-18588** (resaltado en amarillo). Fechas: Inicio 18/03/2026 — Fin 25/03/2026. Botón "Consultar" (azul).
>
> Tabla de un único resultado:
> | Trámite | Folio | Intermediario | Póliza | Nº Endoso | Titular | Fecha Registro | Inicio Vigencia | Estatus | SLA | Acción |
> |---|---|---|---|---|---|---|---|---|---|---|
> | Nuevo Negocio | GMMI-A-18588 | Alvarado, Alberto | 3322AB00 | - | ALARCON CARLOS, MIGUEL ANGEL | 26/03/2026 | 25/03/2026 | Emitida | - | |
>
> Pie: "Mostrando de 1 a 1 registros de 1 registros en total".

**ii.** Finalmente, hacer clic en la opción "Imprimir".

> **[IMAGEN - Dashboard en Chrome con menú "Imprimir"/"Reproceso" + Vista previa de Carátula en Chrome (Página 12)]**
>
> La imagen tiene dos secciones:
>
> **Sección superior — Dashboard en Chrome con menú de acciones:**
> Misma pantalla del Dashboard en Chrome. En la fila de GMMI-A-18588 (Emitida), la columna "Acción" muestra un menú desplegable con dos opciones:
> - **"Imprimir"** (señalado con flecha roja →)
> - "Reproceso"
>
> **Sección inferior — Vista previa del documento Carátula en Chrome:**
> Tres pestañas abiertas: "VisualTIME", "Salud_Caratula" (activa), y `uat-int-axasalud.visualtime.cl/fen…`. URL: `uat-int-axasalud.visualtime.cl/Temp/exstream_view.ashx?nBranch=34&nProduct=341018nPolicy=5120361&nCertif=0&nType_hist=1&nMoveme…`
>
> Barra de herramientas del visor de PDF: "☰ Salud_Caratula | 1 / 3 | — 100% + | 📄 🔄 | 🔎 ↩ ↪" y controles adicionales. Íconos en la esquina superior derecha: 🔍, 🖨, ↗, ⚙.
>
> Panel izquierdo: miniaturas de las 3 páginas del PDF numeradas 1, 2, 3 (la página 1 activa, con contenido visible de la carátula; las páginas 2 y 3 en miniatura más pequeñas).
>
> Vista principal del PDF — misma carátula de póliza:
> - Cabecera: "-*- Demonstration Powered by OpenText Exstream 03/26/2026, Version 25.2.1 64-bit (DBCS) -*-" | "Hoja 1 de 3"
> - Logotipo AXA | Título: "Gastos Médicos / Carátula de póliza / Gastos Médicos Mayores Individual / Familiar"
> - **Datos del contratante**: PAMELA GUERRERO FLORES | CURP: GUFP960604MMCRLM07 | Domicilio: La Draga | CDMX | CP: 13273 | Ciudad: Tláhuac | Teléfono: 5581227079 | R.F.C.: GUFP9606049B8
> - **Datos de los Asegurados**: MIGUEL ANGEL ALARCON CARLOS | Titular | 25/03/2026 | 25/03/2026 | 25/03/2026
> - **Condiciones Contratadas**: Suma Asegurada: $96,500,000 | Póliza: 3322AB00 | Gama Hospitalaria: Esmeralda | Tipo de plan: **Flex Plus** | (resto recortado)

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
