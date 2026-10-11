
# Plan de Identificación y Preservación

## 1. Las fuentes de evidencia

### A. Mesa de Marta

- Memoria RAM y almacenamiento interno del portátil Dell

- Disco duro externo de 2TB

- Móvil de la empresa

(No se comenta nada así que no lo tendré en cuenta, pero podría haber en la mesa ciertas notas escritas o cosas similares con información relevante)

### B. En otras manos y puestos compartidos

- Pendrive en el cajón de la mesa de Javier

- Testimonio de Javier sobre las conductas extrañas de la compañera

- Pantalla de sobremesa compartido de la entrada con una sesión abierta de Outlook

- Impresora multifunción con el historial de trabajos

### C. Infraestructura local

- Servidor de ficheros del cuartito con documentación de proyectos

- Dispositivo NAS con copias de seguridad de los últimos 14 días

- Cortafuegos con registro de conexiones

### D. En la nube y en el edificio

- OneDrive corporativo sincronizado

- Repositorios de las claves gestionado por Bahía Sistemas

- Cámara domo gestionada por la administración de la comunidad

### E. Paradero desconocido

- Pendrive que no funciona de Marta

## 2. La prioridad

1. Memoria RAM del portátil: Si el portátil se apaga, se agota su batería o se reinicia, la memoria volátil se destruye inmediatamente. Se perderían los procesos activos y las conexiones de red.

2. Móvil corporativo: Al estar encendido y con conexión, es vulnerable a borrados de memoria y bloqueos remotos.

3. Logs del cortafuegos: El soporte técnico indicó que los registros de conexiones <<aguantan una semana o así>>. Al ser lunes 20 y el presunto incidente fué el jueves 14, los registros están a punto de ser sobreescritos.

4. Historial de la impresora multifunción: El historial de trabajos se va actualizando, lo que puede borrar evidencias.

5. Copias de seguridad del NAS: Sólo se conservan las copias de seguridad de los últimos 14 días.

6. Memoria sólida del resto de dispositivos: Cosas como el disco duro externo, la memoria interna del portátil o el pendrive de Javier conservan la información de forma persistente.

## 3. Las medidas inmediatas

- Portátil Dell: Mantenerlo conectado a la corriente para que no se apague, fotografiar la pantalla bloqueada, volcar la memoria RAM a un dispositivo USB y aislarlo de la red tras la captura volátil. Entones clonar el disco.

- Móvil corporativo: Requerir la entrega a Elena, desconectarlo inmediatamente de Wi-Fi y bluetooth y mantenerlo conectado a la corriente para que no se apague.

- Disco duro externo de 2TB: Mantenerlo conectado al dock mientras se realiza la captura de la memoria RAM del portátil. Desconectar de forma controlada, fotografiar el número de serie y realizar imágen bit a bit.

- Cortafuegos, NAS y OneDrive corporativo: Llamar a Bahía Sistemas y pedir el registro de datos de red y sesiones VPN, que bloquee temporalmente las copias de seguridad para no perder los datos del día del incidente y los datos de la cuenta de mgarcia.

- Pendrive de Javier: Solicitar la entrega del mismo, asegurarlo, fotografiar la marca, modelo y número de serie del mismo y cumplimentar el acta de custodia.

- Pantalla de sobremesa compartido: Fotografiar la pantalla con la sesión abierta de Outlook web, documentar la cuenta visible, preservar el historial y prohibir su uso mientras se realiza la investigación.

- Impresora multifunción: Hacer un volcado de los últimos trabajos de impresión.

- Cámara domo del edificio: Realizar una petición de la grabación del pasillo del día del incidente.

## 4. Los límites

- El móvil personal de Marta: 

    - No se puede tocar porque infringiría en el derecho fundamental de privacidad. Nadie puede puede registrarlo o incautarlo sin orden judicial o consentimiento libre, expreso y por escrito.

    - En su lugar miraría si hay registros para comprobar si el dispostivo se conectó a la red wi-Fi del estudio, correos cruzados con cuentas externas o trasnferencias hacia la plataforma en la nube. Si se detectan indicios, se hará una petición judicial del móvil.

- La grabación de la cámara domo: 

    - No se puede tocar directamente porque no pertenece a la compañía, así que ellos no pueden darte permiso para acceder a esas grabaciones.

    - En su lugar hay que realizar una petición formal a la comunidad para que extraigan los archivos.

- Explorar el portátil antes de clonar:

    - Podría alterar los metadatos relevantes para la investigación.

    - En su lugar habría que hacer primero un volcado de memoria.

## 5. De dónde sale cada decisión

| Decisión adoptada | Punto de la lista | Norma y apartado de origen |
| ----------------- | ----------------- | -------------------------- |
| Apartar a Marta de los equipos | Punto 1 | ENFSI §8.2 |
| No registrar el teléfono personal | Punto 21 | NIST SP 800-86 §3.1.1 |
| Búsqueda del pendrive en el cajón de Javier | Puntos 4 y 5 | NIST SP 800-86 §3.1.1 |
| Fotografiar pantalla bloqueada  | Puntos 9 y 13 | RFC 3227 §2.1, §3.2<br>ENFSI §8.2, §9.2 |
| Prohibición de apagar el portátil Dell | Punto 10 | RFC 3227 §2.2<br>ENFSI §9.2 |
| Volcado previo de la memoria RAM | Puntos 11, 15 y 18 | RFC 3227 §2.1<br>ENFSI §9.1 |
| Uso de herramientas de solo lectura desde USB propio | Punto 19 | RFC 3227 §2.2, §3.2 |
| Preservación inmediata de logs del cortafuegos | Puntos 16 y 20 | NIST SP 800-86 §3.1.2<br>RFC 3227 §2.1 |
| Congelación del NAS y solicitud del CCTV | Puntos 20 y 21 | NIST SP 800-86 §3.1.1 |
| Cadena de custodia del pendrive y soportes | Punto 23 | RFC 3227 §4.1<br>ENFSI §8.2 |
