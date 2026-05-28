# EC_Error en Firma Autógrafa Digital FAD

> **Clasificación:** Internal

---

## Descripción

El usuario se comunica a mesa notificando sobre un error en el proceso de la Firma Autógrafa Digital (FAD).

---

## Clasificación y Prioridad

- **Tipo de ticket:** Incidente
- **Servicio de negocio:** -
- **Categoría:** Application
- **Subcategoría:** Performance
- **Impacto:** - **Urgencia:** -

---

## Solución paso a paso

**I.** Explicar al usuario que, el servicio de la FAD no permite enviar las notificaciones correspondientes cuando el correo del agente y del contratante es el mismo.

**II.** Validar que se capturaron los datos correctos del agente y el contratante para realizar la FAD.

**a.** Datos requeridos:
- **Correo electrónico del agente**
  - El correo del agente debe ser diferente al del contratante.
- **Correo electrónico del contratante**
  - El correo del contratante debe ser diferente al del agente.
- **Teléfono del agente**
  - Debe ser correcto a 10 dígitos.
- **Teléfono del contratante**
  - Debe ser correcto a 10 dígitos.

**III.** Retomar la solicitud desde el Dashboard.

---

## Flujo para crear una nueva solicitud con Firma FAD

**I.** Acceder a la herramienta mediante OneAccount capturando correo electrónico y contraseña.

> **[IMAGEN - Pantalla de inicio de sesión "OneAccount" (Página 2)]**
> Pantalla de inicio de sesión con fondo blanco. Elementos visuales:
> - Ícono circular azul con un candado blanco en el centro, encima del cual aparece el nombre **"OneAccount"** en texto azul/morado oscuro y negrita.
> - Título en negro: **"Acceder"** (tipografía grande).
> - Etiqueta: **"Tu correo"** con un campo de texto rectangular vacío debajo.
> - Botón rectangular de fondo azul oscuro/navy con texto blanco en mayúsculas: **"ACCEDER"**.
> - Selector de idioma: botón con texto **"Español ∨"** (desplegable) alineado a la izquierda, y enlace de texto azul **"Contáctanos"** alineado a la derecha.
> - Pie de página: logotipo AXA (letras blancas sobre fondo negro/oscuro en forma de escudo) seguido del texto gris **"© 2026 AXA Todos los derechos reservados"**.

**II.** Hacer clic en "Ir al DashBoard"

> **[IMAGEN - Plataforma VisualTIME con menú principal y tooltip "Ir al Dashboard" (Página 3, parte superior)]**
> Pantalla de la plataforma VisualTIME después de iniciar sesión. Estructura general:
>
> **Panel lateral izquierdo** (fondo azul oscuro/navy): logotipo AXA (blanco sobre negro), nombre de usuario: **"Jose Resendiz / User-"**, y menú de navegación con opciones en texto blanco:
> - 🏠 Home
> - 📊 Cotizador
> - 📋 New Tab
> - 📋 New Tab
> - 📝 Tareas
>
> **Panel principal** (fondo blanco/gris claro), dividido en cuatro secciones (widgets):
> - **Clientes** (íconos de edición y vista): submenús: Base de datos de clientes, Transacciones (con flechas expandibles), Consultas, Procesos Batch y reportes.
> - **Pólizas** (íconos de edición): submenús: Tratamiento de pólizas, Transacciones de cartera, Carga masiva, Consultas de Pólizas, Procesos batch y reportes, Transacciones fiscales.
> - **Procesos masivos**: submenús: Estado de procesos batch, Procesos diarios, Parámetros de procesos batch. Ícono de configuración (⚙) en la esquina superior derecha del widget.
> - **IrABeAware**: enlace "Ir a BeAware".
> - **Ir al Dashboard**: enlace **"Ir al Dashboard"** con un tooltip verde emergente que dice **"Presionar para ir al Dashboard"**.
> - **Ir a Endoso**: enlace "Ir a Endoso".
>
> Pie de página: "@2018 InMotion GIT. Todos los derechos reservados · Política de privacidad · Términos de servicio". Botón "+ Nueva página" en esquina inferior derecha.

**III.** Visualizar el Dashboard y el nombre del agente en sesión, en caso de ser promotor, hacer clic en el campo "Agente" para desplegar la lista de opciones.

> **[IMAGEN - Dashboard "Trámites" con campo Agente desplegable (Página 3, parte inferior)]**
> Pantalla del Dashboard de la plataforma AXA. Encabezado: logotipo AXA + título **"Trámites"** (texto blanco sobre fondo azul oscuro). Esquina superior derecha: "Bienvenido: 90614-Resendiz Garcia, Jose Gabriel".
>
> Sección **"Seguimiento de trámites"**:
> - Botones: **"NUEVA COTIZACIÓN"** (azul) y **"SOLICITAR ENDOSO"** (blanco con borde azul).
> - Filtros: radio buttons TODAS (•), NUEVO NEGOCIO, ENDOSO/MANTENIMIENTO, RENOVACIÓN.
> - Campo **"Agente*"**: menú desplegable con flecha (∨), actualmente vacío/sin seleccionar.
> - Campo "Buscar por Nro. de Folio".
> - Fechas: Inicio 18/03/2026 — Fin 25/03/2026, con íconos de calendario. Botón "Consultar" (azul).
> - La tabla de trámites se muestra vacía (sin registros visibles aún).

**IV.** Seleccionamos el requerido que en este caso es: Resendiz Garcia Jose Gabriel.

> **[IMAGEN - Lista desplegable de agentes en el Dashboard (Página 4, parte superior)]**
> Vista del Dashboard con el menú desplegable del campo "Agente" abierto. La lista muestra nombres de agentes en texto negro sobre fondo blanco, con barra de desplazamiento vertical a la derecha. Agentes visibles en la lista:
> - Flores Espitia, Marlen
> - BALLESTEROS REYES, DAVID
> - Luis Gonzalez, Rubén Antonio
> - Garcia Urbi, Alejandro Ismael
> - Loza Fortanel, Alan Daniel
> - Vega Diaz, America Valeria
> - Millian Garcia, Brenda Itzel
> - Garcia Jimenez, Hector Leopoldo
> - **Seg** [inicio de un separador o grupo — texto truncado]
> - Alanis Albor, Karina
> - Serrano Castro, Tania Jaquelín
> - Lopez Vega, Luis Alfredo
>
> En la esquina superior derecha se mantiene: "Bienvenido: 90614-Resendiz Garcia, Jose Gabriel". Botones NUEVA COTIZACIÓN y SOLICITAR ENDOSO visibles. Fechas: 18/03/2026 — 25/03/2026. Botón "Consultar".

> **[IMAGEN - Lista desplegable de agentes con "Resendiz Garcia, Jose Gabriel" seleccionado (Página 4, parte inferior)]**
> Continuación de la lista desplegable de agentes, haciendo scroll hacia abajo. Agentes visibles:
> - Garcia Jimenez, Hector Leopoldo
> - Alanis Albor, Karina
> - Serrano Castro, Tania Jaquelin
> - Lopez Vega, Luis Alfredo
> - ADAN FERNANDO GONZALEZ OLIVARES
> - MARIA FERNANDA GUTIERREZ ROBLES
> - PEDROZA RAMIREZ, FERNANDO
> - BLASCO MANTEROLA, JORGE
> - **Seg** [separador/grupo]
> - Moncada RINCON, Brenda
> - SALGADO ROMERO, Victor Manuel
> - **Resendiz Garcia, Jose Gabriel** (resaltado en verde/amarillo como opción seleccionada)
>
> Debajo del menú desplegable aparece el campo con el valor seleccionado: "Resendiz Garcia, Jose Gabriel" y un tooltip/etiqueta verde: **"Lista de agentes"**. Campo "Buscar por Nro. de Folio" visible. Fechas: 18/03/2026 — 25/03/2026. Botón "Consultar".

**V.** Hacemos clic en el botón "NUEVA COTIZACION".

> **[IMAGEN - Dashboard con agente "Resendiz Garcia, Jose Gabriel" seleccionado en campo Agente (Página 5, parte superior)]**
> Dashboard con el filtro de agente ya establecido:
> - Filtros: TODAS (•), Agente: **Resendiz Garcia, Jose Gabriel** (seleccionado en el campo con flecha ∨).
> - Campo "Buscar por Nro. de Folio" vacío.
> - Fechas: Inicio 18/03/2026 — Fin 25/03/2026. Botón "Consultar".
> - La tabla de trámites se muestra vacía.
> - Botones en esquina superior: **"NUEVA COTIZACIÓN"** (azul) y **"SOLICITAR ENDOSO"**.

**VI.** En la siguiente pantalla, en caso de ser Promotor, seleccionamos nuevamente el nombre del agente.

> **[IMAGEN - Pantalla "Cotizador - Producto Flex Plus" / Paso 1: Registro de datos, con campo Agente desplegado (Página 5, parte inferior)]**
> Pantalla del cotizador con barra de progreso de 4 pasos en la parte superior:
> - **① Registro de datos** (activo, subrayado azul)
> - ② Propuesta
> - ③ Resumen
> - ④ Solicitud
>
> Encabezado: AXA logo, "Bienvenido: 90614-Resendiz Garcia, Jose Gabriel".
>
> Sección **"¿Con qué agente quieres cotizar?"**:
> - Campo "Agente*": menú desplegable abierto mostrando lista de agentes:
>   - 9031 - RAMIREZ PACHECO, MARCELINA
>   - 9035 - RIOS ACEVES, MARTIN
>   - 422 - ROSALES TORRES, AMERICA
>   - **317 - Resendiz Garcia, Jose Gabriel** (resaltado en verde)
>   - 9042 - SALGADO ROMERO, Victor Manuel
>   - 309 - Serrano Castro, Tania Jaquelin
> - "Tipo de negocio*": menú desplegable con valor "Nuevo negocio".
> - Campos: Desde* (vacío con calendario), Hasta* (25/03/2027 con calendario negro).
> - "Género*": menú desplegable. "Edad*": campo numérico con valor 0. "Fecha de nacimiento": campo con calendario. "Código postal*": campo vacío.
> - Casilla: "☐ Reconocimiento de antigüedad".
> - Enlace: "+ Agregar otro tipo de antigüedad".

**VII.** Ingresar los datos:
- Plan
- CURP
- Código postal

**VIII.** En caso de ser necesario, ingresar más datos como antigüedad y agregar integrantes adicionales.

> **[IMAGEN - Cotizador Paso 1: Registro de datos con agente seleccionado y datos del titular (Página 6, parte superior)]**
> Pantalla del cotizador con el agente ya seleccionado. Sección **"¿Con qué agente quieres cotizar?"**:
> - Agente*: "317 - Resendiz Garcia, Jose Gabriel" (con flecha ∨).
> - Texto: "Usted está cotizando con el agente:"  **Resendiz Garcia, Jose Gabriel**
> - Tipo de negocio: Nuevo negocio (∨). Vigencia póliza - Desde: 25/03/2026 — Hasta: 25/03/2027.
>
> Sección **"¿Quién es el solicitante titular?"**:
> - CURP*: campo resaltado en amarillo con valor ingresado (parcialmente visible).
> - Género*: "Femenino" (∨). Edad*: 45.
> - Fecha de nacimiento: 28/07/1980 con ícono de calendario negro.
> - Código postal*: campo con valor "1345**" (parcialmente visible) y nombre de ciudad "Tláhuac".
> - Casilla: "☐ Reconocimiento de antigüedad".
> - Enlace: "+ Agregar otro tipo de antigüedad".
> - Texto informativo gris: "Recuerda que la prima puede variar de acuerdo a los años de antigüedad reconocidos completos al momento de la emisión de la póliza."

> **[IMAGEN - Cotizador: sección "Integrantes adicionales" con botón Continuar (Página 6, parte inferior)]**
> Continuación del formulario con:
> - **CURP**: ROLA800728MPL0R004
> - Género: Femenino (∨). Edad: 45.
> - Fecha de nacimiento: 28/07/1980.
> - Código postal*: 10450 — Ciudad: Tláhuac.
> - Casilla: "☐ Reconocimiento de antigüedad".
> - Enlace: "+ Agregar otro tipo de antigüedad".
> - Texto en gris: "Recuerda que la prima puede variar de acuerdo a los años de antigüedad reconocidos completos al momento de la emisión de la póliza."
>
> Sección **"Integrantes adicionales"** con tabla de columnas: Parentesco, Género, Edad, C.P., Fecha de Rec. Ant. La tabla muestra: *"No se encontraron registros"*. Botón central azul: **"👤+ Agregar"**.
>
> Botones en la parte inferior: **"Cancelar"** (blanco) y **"Continuar"** (verde/azul).

**IX.** Hacer clic en el botón "Continuar".

> **[IMAGEN - Cotizador: Paso 1 con datos del titular listos y tabla de integrantes vacía (Página 7, parte superior)]**
> Misma pantalla del cotizador mostrando la sección de integrantes adicionales con tabla vacía ("No se encontraron registros") y el botón **"Continuar"** visible y activo (verde). CURP visible: ROLA800728MPL0R004. Género: Femenino. Edad: 45. CP: 13450. Ciudad: Tláhuac. Botones: "Cancelar" y "Continuar".

**X.** Visualizar la pantalla del Cotizador en donde podemos observar los datos del agente.

> **[IMAGEN - Cotizador Paso 2: Propuesta con datos del agente y titular (Página 7, parte inferior)]**
> Pantalla del cotizador en el **Paso 2: Propuesta**. Barra de progreso:
> - ① Registro de datos
> - **② Propuesta** (activo, subrayado)
> - ③ Resumen
> - ④ Solicitud
>
> Encabezado: AXA logo, "Bienvenido: 90614-Resendiz Garcia, Jose Gabriel".
>
> **Banner informativo azul/verde** con texto (letra blanca): "Usted está trabajando con el agente: 317-Resendiz Garcia, Jose Gabriel / Fecha de la cotización: 25/03/2026 (válida por 15 días) / Número de cotización: GMMI-A-18368 / Los montos están expresados en moneda nacional".
>
> Sección **"Titular"** (encabezado de tabla en azul/verde): columnas: Nombre(s), Parentesco, Género, Edad, Código postal, Fecha de Rec. Ant, y ícono de edición (✏). Fila: RODRIGUEZ LORENZO, ADELA | Titular | Femenino | 45 | 12450 | — (con ícono de lápiz).
>
> Sección **"Integrantes adicionales"** (encabezado azul/verde): columnas: #, Nombre(s), Parentesco, Género, Edad, Código postal, Fecha de Rec. Ant. Tabla vacía: "No se encontraron registros".
>
> Tres columnas de propuestas al pie: **☐ PAQUETE BASE**, **☐ PROPUESTA 2**, **☐ PROPUESTA 3**, cada una con datos de pago (Pago total anual, Primer pago, Pago subsecuente — valores no visibles por estar ocultos con ∨). Paquete Base muestra: $45,780.03.

**XI.** Ingresar las coberturas solicitadas por el cliente, así como la frecuencia de pago y las condiciones contratadas, posteriormente hacer clic en el botón "Continuar".

---

**XII.** Visualizar la pantalla "Resumen" donde podemos corroborar los datos capturados anteriormente.

> **[IMAGEN - Cotizador Paso 2: vista inferior con IVA, propuestas y coberturas (Página 8, parte superior)]**
> Parte inferior del cotizador en el Paso 2 (Propuesta). Sección de coberturas (parcialmente visible):
> - **Integral**: ● (incluido) — $0.00
> - **Plan Dental Integral**: ● — $1,675.04
> - **Serv. de Asistencia en viaje**: ● — $140.94
>
> Sección **"Paquetes"**:
> - **Selección de IVA**: "IVA Informativo. Se aplicará el correspondiente al código postal del contratante." Casilla IVA, valor **8%**.
> - Botón **"COMPARATIVO"** (azul oscuro).
> - Columnas: **✓ PAQUETE BASE**, **☐ PROPUESTA 2**, **☐ PROPUESTA 3**.
>
> Paquete Base:
> - Primer pago: $25,938.12 | Pago subsecuente: $32,992.12 | Pago total anual: **$47,930.24**
> - Botones: "Descargar ↓", "Seleccionar 🖻", "Mostrar más".
> Propuesta 2 y 3: campos de pago vacíos, botones "Descargar ↓", "Seleccionar 🖻", "Mostrar más".
>
> Nota al pie: "El IVA incluido en esta cotización se calculó de acuerdo con lo seleccionado..."
> Botones: **"Salir"**, **"Regresar"** (izquierda), **"Continuar"** (derecha, azul) con tooltip: "Presione para continuar con la cotización".

> **[IMAGEN - Cotizador Paso 3: Resumen con datos del agente, titular e integrantes (Página 8, parte inferior)]**
> Pantalla del cotizador en el **Paso 3: Resumen**. Barra de progreso con el paso 3 activo (subrayado).
>
> **Banner informativo** azul/verde: "Usted está trabajando con el agente: 317-Resendiz Garcia, Jose Gabriel / Fecha de la cotización: 25/03/2026 (válida por 15 días) / Número de cotización: GMMI-A-18368".
>
> Sección **"RESUMEN"** (encabezado azul/verde, tabla con fondo claro):
> - Número de agente: **317**
> - Nombre de agente: **Resendiz Garcia, Jose Gabriel**
> - Correo electrónico: **jresendiz021@gmail.com**
> - Fecha de cotización: 25/03/2026
> - Inicio de vigencia: 25/03/2026
> - Fin de vigencia: 25/03/2027
> - Código postal: 13450
> - Folio: GMMI-A-18568
>
> Sección **"TITULAR"** (encabezado azul/verde): columnas: Nombre cliente, Parentesco, Género, Edad, Código postal, Fecha de Rec. Ant. Fila: RODRIGUEZ LORENZO, ADELF | Titular | Femenino | 45 | 13450 | —
>
> Sección **"INTEGRANTES"**: columnas: #, Nombre cliente, Parentesco, Género, Edad, Código postal, Fecha de Rec. Ant. Tabla: "No se encontraron registros".
>
> Sección **"Condiciones contratadas"** (encabezado azul/verde): (contenido parcialmente cortado en el borde inferior).

**XIII.** Hacer clic en el botón "Solicitar".

> **[IMAGEN - Cotizador Paso 3: Resumen inferior con coberturas, primas y botón "Solicitar" (Página 9, parte superior)]**
> Parte inferior del Resumen del cotizador. Secciones visibles:
>
> **Sección de coberturas** (tabla):
> - Titular: — | Gastos: (vacío)
>
> **Sección "COBERTURAS"**:
> - Medicamentos Fuera del Hospital: casilla ☐ — $7,400.94
> - Proctólogos: ☐ — $1,981.82
> - Deducible Cero por Accidente: ☐ — $960.74
> - Emergencia Médica por Complicaciones de Gastos Médicos Mayores no Cubiertas: ☐ — $633.12
> - Emergencia Médica en el Extranjero: ☐ — $1,006.38
>
> **Sección "PRIMAS POR ASEGURADO"**:
> - # | Titular | RODRIGUEZ LORENZO, ADELA — $27,589.68
>
> **Sección "RESUMEN COTIZACIÓN"**:
> - Frecuencia de pago: Semestral
> - Primer pago: $25,938.12
> - Pago Subsecuente: $32,992.12
> - Pago total anual: $47,930.34
> - Prima base: $25,820.78
> - Coberturas adicionales: $11,768.92
> - Descuento familiar: $0.00
> - Prima neta: $37,589.70
> - Recargo por pago fraccionado: $1,879.48
> - Derecho de póliza: $1,850.00
> - I.V.A.: $6,611.06
>
> Botones: **"Salir"** (izquierda), **"Regresar"** (centro), **"Solicitar"** (derecha, azul).

**XIV.** Visualizar la pantalla "Solicitud de póliza – Producto Flex Plus" y hacer clic en "DATOS DEL AGENTE".

> **[IMAGEN - Pantalla "Solicitud de póliza - Producto Flex Plus" con secciones colapsadas (Página 9, parte inferior)]**
> Pantalla de la solicitud. Encabezado: AXA logo, "Bienvenido: 90614-Resendiz Garcia, Jose Gabriel". Folio: **GMMI-A-18563** (esquina superior derecha).
>
> Título en azul: **"Solicitud de póliza - Producto Flex Plus"**
>
> Lista de secciones en acordeón (todas colapsadas con flecha ∨):
> - **INFORMACIÓN DE PÓLIZA** — ∨
> - **DATOS DEL AGENTE** — ∨
> - **DATOS DEL ASEGURADO TITULAR** — ∨
> - **DATOS DEL CONTRATANTE** — ∨
> - **DATOS ASEGURADOS ADICIONALES** — ∨
>
> (El resto de la pantalla está cortada en la parte inferior.)

**XV.** Validar el correo del agente. El correo electrónico del agente es diferente al del contratante.
- **Correo electrónico del agente:** jresendiz021@gmail.com

**XVI.** Ingresar el correo electrónico del contratante y el teléfono móvil. El correo electrónico del contratante es diferente al del agente:
- **Correo electrónico del contratante:** JoseGabriel.Resendiz.Consultor@axa.com.mx

> **[IMAGEN - Sección "DATOS DEL AGENTE" expandida con correo del agente visible (Página 10, parte superior)]**
> Pantalla de la solicitud con la sección **"DATOS DEL AGENTE"** expandida (la primera imagen muestra la sección completa). Contenido:
>
> **"Información general"** (encabezado azul/verde oscuro).
>
> **"DATOS DEL AGENTE"** (encabezado azul/verde con ∨):
> - Subsección "Entrevista con el cliente (exclusivo para agentes de seguros)":
>   Texto legal: "Yo, agente de seguros, bajo protesta de decir verdad, hago constar que los datos contenidos en este formato fueron recabados del proponente y/o de su apoderado legal por medio de una entrevista personal de conformidad con el artículo 492 de la Ley de las Instituciones de Seguros y de Fianzas y sus Disposiciones, o aquellas que lleguen a sustituirla, así como la Política de Identificación y Conocimiento de los Clientes de AXA Seguros, S.A de C.V., manifestando que he cotejado los originales contra las copias que se anexan a este formulario."
>
> - Número de agente: **317**
>
> - Tabla de datos del agente:
>   | Nombre(s) | Apellido paterno | Apellido materno | Nombre completo del agente |
>   |---|---|---|---|
>   | Jose Gabriel | Resendiz | Garcia | Resendiz Garcia, Jose Gabriel |
>
>   | Comisión % | Cesión de comisión % | — | % Participación comisión* |
>   |---|---|---|---|
>   | % | 0 | % Apellido paterno | 0 | % | 100 |
>
> - Texto en azul: "En caso de elegir la opción de firmar mediante Firma Autógrafa Digital (FAD), la solicitud de firma se enviará a estos datos de contacto, así como las notificaciones asociadas a este trámite."
> - Teléfono de contacto*: **5540762786** | Correo electrónico*: **jresendiz021@gmail.com** (resaltado en amarillo/verde) | Correo electrónico adicional solo para notificaciones: (vacío)
> - Enlace: "+ Agregar agente" con ícono de suma (🔵 cuadrado azul a la derecha).
>
> - **"DATOS DEL ASEGURADO TITULAR"** (colapsado con ∨).
>
> **Segunda imagen de la página 10:** Vista completa de la solicitud mostrando todas las secciones colapsadas con el Folio: **GMMI-A-18522**:
> - INFORMACIÓN DE PÓLIZA ∨
> - DATOS DEL AGENTE ∨
> - DATOS DEL ASEGURADO TITULAR ∨
> - DATOS DEL CONTRATANTE ∨
> - DATOS ASEGURADOS ADICIONALES ∨
> - FORMAS DE PAGO (Carta autorización) ∨
> - NOTA IMPORTANTE ∨
> - ARTÍCULO 492 ∨
> - AVISO DE PRIVACIDAD ∨

**XVII.** Para completar el proceso, ingresar los datos solicitados en cada una de las siguiente secciones:
- DATOS DE ASEGURADOS ADICIONALES
- FORMAS DE PAGO
- NOTA IMPORTANTE
- ARTÍCULO 492
- AVISO DE PRIVACIDAD
- ENTREVISTA
- CARGA DE DOCUMENTOS
- FIRMA

> **[IMAGEN - Sección "DATOS DEL CONTRATANTE" con campos llenados (Página 11, parte superior)]**
> Vista de la sección **"DATOS DEL CONTRATANTE"** expandida. Contenido del formulario:
>
> - "¿El asegurado es el mismo contratante?" — Opción seleccionada: **● Sí** ○ No
>
> **Datos Fiscales:**
> - Tipo de persona: ● Persona Física ○ Persona Moral
> - RFC*: campo con valor parcialmente visible "|"
> - CURP*: **RDLA800728MPL0R004**
> - FIE.: (campo vacío)
> - País de nacimiento*: México (∨). Nacionalidad*: México (∨). Estado civil: (∨). Edad: **37**. Fecha de nacimiento*: **14/09/1988** (con ícono de calendario negro).
> - Género: **Femenino** (∨).
> - Nombre(s)*: **EDNA JAZMIN**. Apellido paterno*: **QUIROZ**. (Apellido materno vacío)
> - Apellido materno: **ESPINOZA**. Ocupación*: Abogado (∨). Nombre ocupación*: (vacío). Actividad laboral/Giro mercantil*: Acaparadores de agua y recolectores de leña (∨).
> - Régimen Fiscal*: 605 - Sueldos y Salarios e Ingresos Asimilados i… (∨). Uso de CFDI*: 007 Primas por seguros (∨). Requiere: ☐ Factura.
> - **Teléfono Móvil***: **4444444444**. Teléfono Particular: (vacío).
> - **Correo electrónico***: **joseGabriel.Resendiz.Consultor@axa.com.mx** (resaltado en amarillo/verde → campo con correo diferente al del agente)
>
> **Domicilio:**
> - Código postal*: **7600**. Ciudad: **Gustavo A. Madero**. Municipio/Delegación: **Gustavo A. Madero**.
> - Colonia: (∨). Nombre de colonia: (vacío). Calle: **ea**. Número exterior: **4**.
> - Otras. Número interior. ☐ Beneficio 'no fronteras'.
>
> **"DATOS ASEGURADOS ADICIONALES"** (sección siguiente, colapsada, ∨).

> **[IMAGEN - Vista completa de secciones de la solicitud con acordeones (Página 11, parte inferior)]**
> Vista de la pantalla de la solicitud mostrando la estructura de secciones en acordeón. Parte superior muestra el domicilio del contratante (Colonia ∨, Nombre de colonia vacío, Calle, Número exterior, Otras, Número interior, ☐ Beneficio no fronteras).
>
> Secciones siguientes listadas (todas con flecha ∨, colapsadas):
> - **DATOS ASEGURADOS ADICIONALES** (fondo azul/verde con ∨)
> - **FORMAS DE PAGO (Carta autorización)** (fondo azul/verde con ∨)
> - **NOTA IMPORTANTE** (fondo azul/verde con ∨)
> - **ARTÍCULO 492** (fondo azul/verde con ∨)
> - **AVISO DE PRIVACIDAD** (fondo azul/verde con ∨)
> - **Entrevista** (fondo azul/turquesa con flecha ∧, expandida)
> - **Carga de documentos** (fondo azul/turquesa con flecha ∨)
> - **CARGA DE DOCUMENTOS** (fondo azul/verde con ∨)
> - **FIRMA** (fondo azul/verde con ∨)
>
> Botones al pie: **"CANCELAR"** (blanco) y **"ENVIAR"** (azul).

---

**XVIII.** En el apartado "FIRMA" seleccionamos si desea Firma Autógrafa Digital FAD o Firma Autógrafa Manual.

> **[IMAGEN - Sección "CARGA DE DOCUMENTOS" con Documentos requeridos y sección FIRMA sin selección (Página 12, parte superior)]**
> Pantalla de la solicitud mostrando la sección de carga de documentos y firma:
>
> **Sección "CARGA DE DOCUMENTOS"** (encabezado azul/verde con ∨):
> - Subsección **"Documentos requeridos"** (texto en azul): "Se requiere adjuntar los siguientes documentos:".
>   Tabla con columnas: Número, Parentesco, Documento, Fecha solicitud, Estado del Documento.
>   - 1 | Contratante | Identificación oficial vigente | 25/03/2026 | Pendiente | Botón "Cargar"
>   - 1 | Contratante | Comprobante de domicilio | 25/03/2026 | Pendiente | Botón "Cargar"
>
> **Sección "SOLICITUD DIGITAL"** (con flecha ∨):
> - "¿Quieres descargar la solicitud digital?"
> - Botón azul: **"↓ Descargar solicitud"**
>
> **Sección "FIRMA"**:
> - "¿Cómo quieres firmar la solicitud?"
> - Botón verde/azul: **"Firma Autógrafa Digital (FAD)"** (seleccionado/resaltado)
> - Botón blanco: **"Firma Autógrafa Manual"**
>
> Botones: **"CANCELAR"** y **"ENVIAR"** (azul).

**XIX.** Validar que no se dejó algún registro sin contestar como este ejemplo:
- "Se requiere el registro de 'DATOS DEL ASEGURADO TITULAR') de la solicitud"

> **[IMAGEN - Alerta de validación "Se encontraron las siguientes observaciones en la propuesta" (Página 12, parte inferior)]**
> Pantalla de la solicitud con un **banner de alerta** (fondo azul oscuro/navy, texto blanco) en la parte superior del área de contenido:
> - Texto: **"Se encontraron las siguientes observaciones en la propuesta"**
> - Subtexto: "Para continuar con el proceso:"
> - **"Se requiere el registro de 'DATOS DEL ASEGURADO TITULAR') de la solicitud"**
> - Enlace: "Aceptar" (texto azul/subrayado)
>
> Debajo del banner, la tabla de Documentos requeridos muestra:
> - 1 | Contratante | Identificación oficial vigente | 25/03/2026 | **Recibido, por analizar** | Botón "Cargar"
> - 1 | Contratante | Comprobante de domicilio | 25/03/2026 | **Recibido, por analizar** | Botón "Cargar"
>
> Sección SOLICITUD DIGITAL con botón "Descargar solicitud". Sección FIRMA con dos opciones de radio: "○ Firma Autógrafa Digital (FAD)" y "○ Firma Autógrafa Manual" (ninguna seleccionada en este estado de error). Botones: "CANCELAR" y **"ENVIAR"** (azul, desactivado visualmente).

**XX.** Validar que se selecciona Firma Autógrafa Digital (FAD).

**XXI.** Si los documentos no están cargados, no se podrá seleccionar el tipo de firma.

**XXII.** Hacer clic en botón "ENVIAR".

> **[IMAGEN - Pantalla con documentos en estado "Recibido, por analizar" y Firma FAD seleccionada (Página 13, parte superior)]**
> Dos vistas de la pantalla de la solicitud apiladas verticalmente:
>
> **Vista superior (antes de enviar):**
> - Tabla de Documentos requeridos:
>   - 1 | Contratante | Identificación oficial vigente | 25/03/2026 | **Recibido, por analizar** | Botón "Cargar"
>   - 1 | Contratante | Comprobante de domicilio | 25/03/2026 | **Recibido, por analizar** | Botón "Cargar"
> - SOLICITUD DIGITAL con botón "Descargar solicitud".
> - FIRMA: "¿Cómo quieres firmar la solicitud?" — **● Firma Autógrafa Digital (FAD)** (seleccionada, punto verde) — ○ Firma Autógrafa Manual.
> - Botones: "CANCELAR" y **"ENVIAR"** (azul).
>
> **Vista inferior (con FAD seleccionada y lista para enviar):**
> - Tabla de documentos igual: Recibido, por analizar.
> - SOLICITUD DIGITAL con botón "↓ Descargar solicitud".
> - FIRMA: **● Firma Autógrafa Digital (FAD)** (punto verde/seleccionado) — ○ Firma Autógrafa Manual.
> - Botones: "CANCELAR" y **"ENVIAR"** (azul) — en esta vista el botón ENVIAR tiene un pequeño ícono de carga/procesamiento (🔄 circular).

---

**XXIII.** Visualizar el mensaje **"Se ha enviado correctamente la solicitud para firma a través de FAD."**

> **[IMAGEN - Modal de confirmación "Firma digital" con mensaje de éxito FAD (Página 14, parte superior)]**
> La pantalla de la solicitud muestra un **cuadro modal** emergente centrado titulado **"Firma digital"** (encabezado azul/verde):
> - Ícono circular con símbolo de información (ⓘ) en el centro.
> - Texto en negro: **"Se ha enviado correctamente la solicitud para firma a través de FAD."**
> - Texto en gris: "Si deseas información en la solicitud, puedes hacerlo en cualquier momento antes de firmar el documento."
> - Botón azul: **"OK"**
>
> Al fondo (detrás del modal) se ve la pantalla de la solicitud con:
> - Documentos requeridos: Recibido, por analizar.
> - SOLICITUD DIGITAL con botón "Descargar solicitud".
> - FIRMA: **● Firma Autógrafa Digital (FAD)** seleccionada. ○ Firma Autógrafa Manual.
> - Botón "ENVIAR" (azul) y "CANCELAR".

**XXIV.** Consultar el Dashboard. En caso de que mande algún error, regresar al Dashboard y consultar la solicitud.
- Imprimir
- Cancelar
- Modificar solicitud

> **[IMAGEN - Dashboard con solicitud en estatus "Solicitud pendiente de Firma" y menú de acciones (Página 15, parte superior)]**
> Dashboard de la plataforma AXA. Encabezado: AXA logo + "Trámites". Sección "Seguimiento de trámites" con filtros: TODAS (•), Agente: Resendiz Garcia, Jose Gabriel (∨). Fechas: 18/03/2026 — 25/03/2026. Botón "Consultar".
>
> Tabla de registros:
> | Trámite | Folio | Intermediario | Póliza | Nº Endoso | Titular | Fecha Registro | Inicio Vigencia | Estatus | SLA | Acción |
> |---|---|---|---|---|---|---|---|---|---|---|
> | Nuevo Negocio | GMMI-A-18568 | Resendiz Garcia, Jose Gabriel | — | — | RODRIGUEZ LORENZO, ADELA | 25/03/2026 | — | **Solicitud pendiente de Firma** | — | [Menú] |
> | Nuevo Negocio | GMMI-A-18564 | Resendiz Garcia, Jose Gabriel | — | — | RODRIGUEZ LORENZO, ADELA | 25/03/2026 | — | Solicitud en registro | — | — |
> | Nuevo Negocio | GMMI-A-18556 | Resendiz Garcia, Jose Gabriel | — | — | RODRIGUEZ LORENZO, ADELA | 25/03/2026 | — | Solicitud en registro | — | — |
> | Nuevo Negocio | GMMI-A-18524 | Resendiz Garcia, Jose Gabriel | — | — | QUIROZ ESPINOZA, EDNA JAZMIN | 20/03/2026 | — | Solicitud en registro | — | — |
> | Nuevo Negocio | GMMI-A-18522 | Resendiz Garcia, Jose Gabriel | — | — | QUIROZ ESPINOZA, EDNA JAZMIN | 19/03/2026 | — | Solicitud en registro | — | — |
>
> En la fila de GMMI-A-18568 hay un menú desplegable emergente con tres opciones:
> - **"Imprimir"** (azul)
> - **"Cancelar"** (rojo)
> - **"Modificar solicitud"** (azul/verde, destacado)
>
> Pie: "Mostrando de 1 a 5 registros de 5 registros en total".

**XXV.** Dar clic en Modificar Solicitud mandará este mensaje: Existe un proceso de solicitud para Firma Autógrafa Digital (FAD) en curso, el cual será cancelado al continuar con la modificación de la solicitud.

> **[IMAGEN - Modal "Modificación de solicitud pendiente de firma" con pregunta de confirmación (Página 15, parte inferior)]**
> Dashboard con un **cuadro modal** emergente centrado titulado **"Modificación de solicitud pendiente de firma"** (encabezado azul/verde):
> - Ícono circular de información (ⓘ).
> - Texto: "Existe un proceso de solicitud para Firma Autógrafa Digital (FAD) en curso, el cual será cancelado al continuar con la modificación de la solicitud."
> - Texto: **"¿Deseas continuar?"**
> - Botón blanco: **"NO DESEO REGRESAR AL DASHBOARD"**
> - Texto azul con subrayado: "Presione para continuar con la modificación de la solicitud"
>
> Al fondo del modal se ve la tabla del Dashboard con los mismos 5 registros.

**XXVI.** Hacer clic en el botón "Si deseo modificar la solicitud" para continuar con la solicitud.

> **[IMAGEN - Pantalla de la solicitud con sección FIRMA seleccionada y botón ENVIAR activo (Página 16, parte superior)]**
> Pantalla de la solicitud de póliza (en modo de modificación). Sección visible:
>
> - **Documentos requeridos** (tabla):
>   - 1 | Contratante | Identificación oficial vigente | 19/03/2026 | Recibido, por analizar | Botón "Cargar"
>   - 1 | Contratante | Comprobante de domicilio | 19/03/2026 | Recibido, por analizar | Botón "Cargar"
>
> - **SOLICITUD DIGITAL**: "¿Quieres descargar la solicitud digital?" + Botón "↓ Descargar solicitud".
> - **FIRMA**: "¿Cómo quieres firmar la solicitud?" — **● Firma Autógrafa Digital (FAD)** (seleccionada, punto verde/azul resaltado) — ○ Firma Autógrafa Manual.
> - Botones: **"CANCELAR"** y **"ENVIAR 🔄"** (azul con ícono de procesamiento circular en la segunda imagen).

**XXVII.** Podemos realizar las modificaciones y asegurar que los datos ingresados son correctos.

> **[IMAGEN - Dos vistas de la pantalla con FIRMA FAD seleccionada y botón ENVIAR (Página 16, parte inferior)]**
> Dos capturas de pantalla muy similares mostrando la misma interfaz de la solicitud:
>
> **Vista 1:**
> - Tabla de documentos: Recibido, por analizar (× 2).
> - Botón "↓ Descargar solicitud".
> - FIRMA: **● Firma Autógrafa Digital (FAD)** (verde/resaltado) — ○ Firma Autógrafa Manual.
> - Botones: "CANCELAR" + "ENVIAR 🔄" (azul, con ícono de carga circular).
>
> **Vista 2 (igual a Vista 1):** Misma estructura e información, confirmando que la modificación es posible con FAD seleccionada.

---

## Flujo de una solicitud con el mismo correo electrónico para el agente y titular

**I.** En caso de haber ingresado el mismo correo electrónico para el agente y para el contratante al realizar la consulta del Dashboard.

**II.** Datos del agente.

> **[IMAGEN - Sección "DATOS DEL AGENTE" con correo jresendiz021@gmail.com (Página 17, parte superior)]**
> Pantalla de la solicitud "Solicitud de póliza - Producto Flex Plus" (encabezado parcialmente visible). Sección **"DATOS DEL AGENTE"** expandida:
>
> - Texto legal de entrevista con el cliente (mismo texto que antes).
> - Número de agente: **317**.
> - Tabla del agente: José Gabriel | Resendiz | Garcia | **Resendiz Garcia, Jose Gabriel**
> - Comisión: % 0 | Cesión: % Apellido paterno 0 | Participación: % 100
> - Teléfono de contacto*: **5540762786**
> - **Correo electrónico***: **jresendiz021@gmail.com** (resaltado en amarillo/verde — **mismo correo que el contratante en este escenario de error**)
> - Correo electrónico adicional solo para notificaciones: (vacío).
> - "+ Agregar agente" (🔵).
>
> - **"DATOS DEL ASEGURADO TITULAR"** (colapsado ∨).

**III.** Datos del contratante.

> **[IMAGEN - Sección "DATOS DEL CONTRATANTE" con mismo correo del agente (Página 17, parte inferior)]**
> Secciones de la solicitud visibles:
>
> - **"DATOS DEL ASEGURADO TITULAR"** (colapsado ∨).
> - **"DATOS DEL CONTRATANTE"** (colapsado ∨).
>
> Sección **"DATOS DEL CONTRATANTE"** expandida con formulario:
> - "¿El asegurado es el mismo contratante?" — **● Sí** ○ No.
> - Datos Fiscales: Persona Física.
> - RFC: campo con "|" (cursor vacío).
> - CURP: **RDLA800728MPLDR004**.
> - País: México. Nacionalidad: México. Estado civil. Edad: **45**. Fecha de nacimiento: **28/07/1980**.
> - Género: Femenino. Nombre(s)*: **EDNA JAZMIN**. Apellido paterno: **QUIROZ**. Apellido materno: **RODRIGUEZ**. Ocupación: (∨). Nombre ocupación: (vacío). Actividad laboral/Giro mercantil: (∨).
> - Régimen Fiscal: (∨). Uso de CFDI: (∨). Requiere: ☐ Factura.
> - **Teléfono Móvil***: (vacío). Teléfono Particular: (vacío).
> - **Correo electrónico***: **jresendiz021@gmail.com** (resaltado en amarillo/verde — **¡MISMO correo que el agente! Este es el escenario de error**).
>
> Domicilio: Código postal: (CDMX implied). Ciudad: Tláhuac. Colonia. Nombre de colonia. Calle. Número exterior.

**IV.** Seleccionar Firma Autógrafa Digital (FAD).

> **[IMAGEN - Sección FIRMA con FAD seleccionada y pantalla lista para enviar (Página 18, parte superior)]**
> La sección final de la solicitud mostrando:
>
> - **CARGA DE DOCUMENTOS** (encabezado con ∨):
>   - Documentos requeridos: Identificación oficial vigente (25/03/2026 / Recibido, por analizar / Cargar) + Comprobante de domicilio (25/03/2026 / Recibido, por analizar / Cargar).
> - **SOLICITUD DIGITAL** (∨): "¿Quieres descargar la solicitud digital?" + Botón "↓ Descargar solicitud".
> - **FIRMA**: "¿Cómo quieres firmar la solicitud?" — **● Firma Autógrafa Digital (FAD)** (resaltada/seleccionada en verde) — ○ Firma Autógrafa Manual.
> - Botones: **"CANCELAR"** + **"ENVIAR"** (azul).

**V.** En el Dashboard hacer clic en el botón "Modificar solicitud" en la solicitud correspondiente.

> **[IMAGEN - Dashboard con menú de acciones en solicitud (Imprimir / Cancelar / Modificar solicitud) (Página 18, parte inferior)]**
> Dashboard de la plataforma AXA mostrando el listado de trámites del agente "Resendiz Garcia, Jose Gabriel". Tabla con 5 registros:
>
> | Folio | Titular | Fecha Registro | Estatus |
> |---|---|---|---|
> | GMMI-A-18568 | RODRIGUEZ LORENZO, ADELA | 25/03/2026 | **Solicitud pendiente de Firma** |
> | GMMI-A-18564 | RODRIGUEZ LORENZO, ADELA | 25/03/2026 | Solicitud en registro |
> | GMMI-A-18556 | RODRIGUEZ LORENZO, ADELA | 25/03/2026 | Solicitud en registro |
> | GMMI-A-18524 | QUIROZ ESPINOZA, EDNA JAZMIN | 20/03/2026 | Solicitud en registro |
> | GMMI-A-18522 | QUIROZ ESPINOZA, EDNA JAZMIN | 19/03/2026 | Solicitud en registro |
>
> En la fila GMMI-A-18568 se despliega un menú emergente con:
> - **"Imprimir"** (azul)
> - **"Cancelar"** (rojo)
> - **"Modificar solicitud"** (azul/verde, señalado/resaltado)

**VI.** Hacer clic en el botón "Si deseo modificar la solicitud".

**VII.** Muestra el mensaje de error: **"No se pudo cancelar la firma: Requisición no cancelada. No se encontró el documento solicitado ..."** lo cual es correcto ya que **el sistema no permite esta acción debido a que se capturó el mismo correo electrónico para el agente y el titular.**

> **[IMAGEN - Modal "Modificación de solicitud pendiente de firma" y mensaje de error en Microsoft Edge (Página 19)]**
>
> La imagen contiene dos secciones:
>
> **Sección superior — Modal de confirmación:**
> Dashboard con modal centrado: **"Modificación de solicitud pendiente de firma"** (encabezado verde/azul):
> - Ícono ⓘ.
> - Texto: "Existe un proceso de solicitud para Firma Autógrafa Digital (FAD) en curso, el cual será cancelado al continuar con la modificación de la solicitud."
> - "¿Deseas continuar?"
> - Botón blanco: **"NO DESEO REGRESAR AL DASHBOARD"**
> - Texto con subrayado azul: "Presione para continuar con la modificación de la solicitud"
>
> **Sección inferior — Pantalla de error en Microsoft Edge:**
> Ventana de Microsoft Edge. Barra de título: "Mis trámites - Trabajo. Microsoft Edge". URL: `https://uat-int-axasalud.visualtime.cl/fasi/dli/forms/DASHAXA001Popup.html`. Encabezado: AXA logo + "Trámites". "Bienvenido: 90614-Resendiz Garcia, Jose Gabriel".
>
> Sobre la tabla del Dashboard, aparece un **cuadro modal de error** (fondo blanco, borde gris) con:
> - Ícono de información (ⓘ) azul circular.
> - Texto en gris: **"No se pudo cancelar la firma: Requisición no cancelada. No se encontró el documento solicitado ..."**
> - Botón: **"OK"** (azul).
>
> La tabla de fondo muestra los 5 registros del agente con estatus:
> - GMMI-A-18568: Solicitud pendiente de Firma (25/03/2026)
> - GMMI-A-18564: Solicitud en registro (25/03/2026)
> - GMMI-A-18556: Solicitud en registro (25/03/2026)
> - GMMI-A-18524: Solicitud en registro (20/03/2026)
> - GMMI-A-18522: Solicitud en registro (19/03/2026)
>
> En la barra de tareas de Windows (parte inferior de la pantalla) se ven íconos de aplicaciones y la hora: **03:15 p.m. 25/03/2026**.

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
