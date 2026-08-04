¿Que puede hacer Git aunque GitHub no exista?

R: Al ser un sistema de control de versiones distribuido, Git puede rastrear cambios, gestionar cambios, guardar el historial completo de un proyecto y permitir la colabroacion directa entre desarrolladores localmente o mediante servidores propios sin depender de una plataforma en la nube.

¿Por qué una rama reduce el riesgo de dañar main?

R: Porque funciona como una copia de trabajo aislada: todos los cambios, experimentos o pruebas ocurren en un entorno independiente sin alterar el codigo estable de main hasta que este complemante seguro de que todo funciona correctamente y se decida fusionarlo

¿Qué diferencia existe entre guardar un archivo y crear un commit?

R: Guardar un archivo actualiza su estado en el disco, mientras que un commit registra una fotografia historica e imborrable de los cambios del proyecto

¿Por qué un pull request no es lo mismo que un merge?

R: Es una propuesta de cambio y revision, mientras que un merge es la accion tecnica de fusionar esos cambios.

¿Qué evidencia permite saber quién cambió algo y por qué?

R: La evidencia principal son el mensaje del commit(que explica el por que) y los metados de autor, fecha e identificador unicos guardados en comandos como git log o git blame (que revelan el quien


1. Crear el repositorio

 - Es el punto de partida donde se inicializa el sistema de control de versiones para el proyecto, ya sea de forma local o remota.

 - Evita el riesgo de la perdida total de trazabilidad y codigo.

2. Crear una rama

 - Crear una linea de desarrollo independiente aislada de la rama principal.

 - Evita la inestabilidad en la version de produccion.

3. Hacer commits

 - Guarda capturas historicas e imborrables del progreso a medida que se avanza en la tarea, acompañadas de mensaje explicitos.

 - Evita la perdida de avances intermedios y falta de contexto.

4. Abrir una Pull Request 

 - Proponer formalmente en la plata forma remota la integracion de los cambios de la rama secundaria hacia la rama principal.

 - Evita la integracion a ciegas. Evita que un desarrollador introduzca cambios directamente en la rama principal sin notificacion previa ni ejecucion de pruebas de integracion.

5. Revisar el codigo

 - Inspeccion del codigo por la parte de compañeros o lideres de equipo para verificar su calidad, arquitectura y seguridad.

 - Evita las fugas de errores a produccion y deuda tecnica.

6. Corregir Observaciones

 - Aplicar los ajustes necesarios solicitados durante la revision del codigo mediante nuevos commits en la misma rama.

 - Evitar integar el codigo defectuoso por descuido.

7. Fusionar

 - Integrar los cambios ya revisados y aprobados desde la rama de trabajo hacia la principal(main).

 - Evita conflitos de version y ramas divergentes.
