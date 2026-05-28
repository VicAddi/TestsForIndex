# EC_Problemas de acceso_1

> **Clasificación:** Internal

---

## Descripción

El usuario se comunica con la Mesa de Atención para reportar un error al acceder a la herramienta, de acuerdo con los casos descritos en la sección "Solución paso a paso" de este documento.

---

## Clasificación y Prioridad

- **Tipo de ticket:** Incidente
- **Servicio de negocio:** -
- **Categoría:** Application
- **Subcategoría:** Performance
- **Impacto:** - **Urgencia:** -

---

## Solución paso a paso

**I. Primer caso:** Se está trabajando y muestra el mensaje "Su usuario no está autorizado a acceder a esta operación". Error que indica que la sesión expiró y debemos acceder nuevamente a VisualTIME.

> **[IMAGEN - VisualTIME con modal de error de sesión expirada]**
> Plataforma VisualTIME (usuario: Abad Hernandez, Administrator). Modal emergente con ícono ⓘ y el mensaje: **"Su usuario no está autorizado a acceder a esta operación."** Subtexto: "Haz clic en 'OK' para refrescar la página." Botón **"OK"** (azul, resaltado con recuadro rojo).

**a.** Hacer clic en el botón "Ok" en la ventana emergente que muestra el mensaje de error.

**b.** Hacer clic nuevamente en el ícono "Desconectar" para cerrar sesión.

> **[IMAGEN - VisualTIME con ícono "Desconectar" señalado en la barra superior]**
> Pantalla de VisualTIME con la sesión aún activa (Abad Hernandez, Administrator). En la barra superior derecha se muestra un tooltip emergente **"Desconectar"** señalando el ícono de salida (→|) ubicado en la esquina superior derecha, resaltado con un recuadro rojo.

**c.** Hacer clic nuevamente en el ícono "Desconectar" para cerrar sesión.

> **[IMAGEN - VisualTIME con sesión cerrada y menú reducido]**
> Pantalla de VisualTIME después del primer clic en Desconectar: el panel lateral izquierdo solo muestra las opciones **"Inicio"** y **"Nueva página"**, sin nombre de usuario. El ícono de desconexión (→|) en la esquina superior derecha está resaltado con recuadro rojo, indicando que se debe hacer clic nuevamente para cerrar sesión completamente.

**a.** Acceder nuevamente a VisualTIME mediante OneAccount capturando correo electrónico y contraseña correspondiente.

> **[IMAGEN - Pantalla de inicio de sesión OneAccount]**
> Pantalla de login de **OneAccount** (ícono de escudo azul con candado). Campo "Tu correo" vacío, botón **"ACCEDER"** (azul oscuro). Selector de idioma "Español ∨" y enlace "Contáctanos". Pie: "© 2026 AXA Todos los derechos reservados".

---

**II. Segundo caso:** Al acceder a la herramienta muestra el mensaje "Su usuario no tiene acceso", o bien sí ingresan, pero no pueden ver el Dashboard.

**a.** Favor de completar la sección "Datos mínimos de este documento".

---

**III. Tercer caso:** Error en el acceso al sistema.

**a.** Favor de completar la sección "Datos mínimos de este documento".

---

**IV. Cuarto caso:** Error 500 o mensaje X al ingresar.

**a.** Favor de completar la sección "Datos mínimos de este documento".

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
