
# Lista de Comprobación

## Momento 1: Al Llegar

1. Control de entorno y aislamiento de personas: Alejar a sospechosos, usuarios y testigos tanto de los equipos informáticos como de cualquier dispositivo de comunicación que pudiera interactuar con ellos para evitar manipulación o destrucción remota de datos «ENFSI §8.2».

2. Identificación y toma de datos de testigos presentes: Documentar quiénes estaban en el lugar, qué actividad realizaban en los sistemas, qué anomalías o incidencias observaron y cómo reaccionaron ante el evento «RFC 3227 §3.2».

3. Coordinación de disciplinas forenses concurrentes: Si se requiere recogida de huellas dactilares o ADN, coordinar la intervención con los otros especialistas para fijar una secuencia que respete la naturaleza destructiva de cada técnica antes de manipular teclados, ratones o cables «ENFSI §8.2, §9.1».

4. Reconocimiento perimetral de dispositivos visibles y ocultos: Inspeccionar minuciosamente el espacio físico (despachos, mobiliario, cajones) identificando servidores, equipos de sobremesa, portátiles, almacenamiento en red y dispositivos portátiles como móviles, PDA, cámaras o grabadoras «NIST SP 800-86 §3.1.1».

5. Búsqueda de soportes extraíbles y puertos de conexión: Localizar memorias USB, tarjetas flash/memoria, discos ópticos (CD/DVD), cintas magnéticas o discos externos conectados o almacenados en las inmediaciones «NIST SP 800-86 §3.1.1».

6. Búsqueda de indicios físicos y credenciales manuscritas: Rastrear pósits, anotaciones, cuadernos, diagramas técnicos o listados impresos que puedan contener contraseñas, topologías o claves de descifrado «ENFSI §9.2».

7. Aislamiento electromagnético preventivo: Introducir teléfonos móviles y equipos con enlace inalámbrico en bolsas o jaulas de Faraday para bloquear radiofrecuencia (RF) e infrarrojos, evitando borrados o bloqueos remotos «ENFSI §8.2, §9.1».

8. Gestión de alimentación y comprobación de baterías: Evaluar el estado de carga en dispositivos que funcionan con batería; asegurar alimentación continua protegida o priorizar su análisis para evitar la pérdida total de datos por apagado súbito «NIST SP 800-86 §3.1», «ENFSI §8.2, §9.2».

## Momento 2: Antes de tocar nada

9. Fijación fotográfica contemporánea y croquis de la escena: Fotografiar el entorno, el cableado y el contenido íntegro visible en las pantallas (ventanas activas, errores, sesiones abiertas), elaborando un croquis detallado con la ubicación de cada elemento «RFC 3227 §3.2», «ENFSI §8.2».

10. Diagnóstico del estado operativo: Determinar si el equipo está encendido, suspendido o apagado. No apagar un equipo encendido antes de evaluar los datos volátiles ni fiarse de los procesos de apagado estándar, que pueden ejecutar scripts maliciosos de borrado «RFC 3227 §2.2», «ENFSI §9.2».

11. Detección de volúmenes cifrados en caliente: Comprobar si existen contenedores, particiones o discos cifrados montados y abiertos en memoria RAM antes de alterar el suministro eléctrico o la conectividad «ENFSI §9.1, §9.2».

12. Evaluación de interruptores de hombre muerto: Valorar el riesgo de que la simple desconexión física del cable de red dispare rutinas automáticas programadas para borrar evidencias al perder la red «RFC 3227 §2.2», «ENFSI §9.1».

13. Levantamiento de la topología y conectividad física: Identificar y documentar la configuración física, conexiones cableadas, routers, conmutadores, interfaces de red y periféricos antes de desconectar o mover nada «RFC 3227 §2.1», «ENFSI §9.2».

14. Medición del desfase horario: Registrar la discrepancia exacta entre el reloj interno de cada sistema analizado y UTC, anotando la zona horaria utilizada para correlaciones futuras «RFC 3227 §3.2».

## Momento 3: Al decidir qué se adquiere y en qué orden

15. Delimitación de sistemas y alcance probatorio: Responder a ¿Dónde está la evidencia?, listando los equipos involucrados y determinando qué información es relevante y admisible legalmente; ante la duda, recopilar de más «RFC 3227 §3.2».

16. Ponderación por la Tríada de Priorización: Jerarquizar la recogida evaluando conjuntamente tres factores: el valor probable para la investigación, la volatilidad de la fuente y la cantidad de esfuerzo requerido en tiempo, coste y autorizaciones «NIST SP 800-86 §3.1.2».

17. Priorizar recolección frente a análisis: Ante la disyuntiva entre recolectar datos o analizarlos in situ, proceder siempre a la recogida y aseguramiento primero y posponer el análisis pericial «RFC 3227 §2».

18. Recogida ordenada de datos volátiles por volatilidad: En sistemas encendidos, proceder estrictamente de lo más volátil a lo menos volátil: registros/caché de CPU, tablas de rutas, caché ARP, tabla de procesos, estadísticas del kernel, memoria RAM y sistemas de archivos temporales «RFC 3227 §2.1».

19. Despliegue de herramientas de solo lectura y minimización del impacto: Ejecutar herramientas forenses preparadas en medios de solo lectura sin confiar en los binarios del sistema comprometido, evitando comandos que alteren las marcas temporales de acceso a archivos «RFC 3227 §2.2, §3.2».

20. Identificación de fuentes lógicas corporativas y de red: Rastrear evidencias que no residen en el equipo local: registros de routers, cortafuegos, servidores proxy, servidores DHCP, registros de aplicaciones corporativas (correo, bases de datos) y tráfico de red «NIST SP 800-86 §3.1.1».

21. Identificación de fuentes alternas y externas: Si una fuente primaria no está accesible o exige trámites dilatados (como requerimientos judiciales a un ISP), identificar y recopilar datos en fuentes alternas internas con información equivalente o equipos de teletrabajadores «NIST SP 800-86 §3.1.1».

22. Aislamiento controlado y eliminación de vías de modificación: Aislar el sistema de posibles influencias externas para preservar la evidencia sin destruir datos en el proceso «RFC 3227 §2, §3.2», «NIST SP 800-86 §3.1.3».

23. Embalaje, precintado y apertura de cadena de custodia: Asignar a cada paquete sellado un identificador único, registrando descripción detallada, números de serie, ubicación exacta del hallazgo, responsable de la recogida y fecha/hora precisa «RFC 3227 §3.2», «ENFSI §8.2».
