#Diseño de Sistemas

Materiales del curso Diseño de Sistemas del TSU en Electrónica y Pruebas, en modalidad B-learning.

Este repositorio reúne las planeaciones, presentaciones, guías, formatos de evidencia y código de apoyo del curso. Su propósito es mantener los materiales organizados, conservar el historial de correcciones y facilitar la preparación de las clases.

Docente: Luis Felipe Muñoz Mendoza
Organización: ocho semanas
Plataforma de actividades, entregas y evaluación: Google Classroom

Propósito del curso

Aplicar el análisis y diseño de sistemas para desarrollar una solución de instrumentación electrónica. El trabajo integra requerimientos medibles, selección de componentes, adquisición de datos, programación, comunicación entre dispositivos y pruebas funcionales.

Proyecto del curso

Desarrollar progresivamente un sistema didáctico de monitoreo de temperatura con:

Sensor LM35 y adquisición mediante el ADC de un ESP32.

Interfaz gráfica en Python para mostrar valor, unidad y estado.

Registro de mediciones en archivos CSV.

Comunicación MQTT para supervisión en red local, utilizando la misma interfaz gráfica.

Seis requerimientos medibles y seis casos de aceptación trazables.

Documentación de resultados, incidencias, correcciones y limitaciones.

El alcance es un prototipo didáctico de baja tensión en condiciones controladas, sin actuación de potencia ni conexión a una línea productiva. Su desarrollo comienza con los requerimientos y la arquitectura y se amplía durante el curso.

Organización del repositorio

Esta es la estructura prevista. Las carpetas y sus contenidos se incorporarán conforme se revisen y carguen los materiales.

Ruta

Contenido

README.md

Presentación e índice general del curso.

programa/

Programa F1 y documentos generales.

planeaciones/

Planeaciones F3 y sus actualizaciones semanales.

formatos/

Plantillas institucionales y formatos DS-01 a DS-05.

semanas/semana-01/ a semanas/semana-08/

Presentaciones, guías, fichas y documentos de apoyo de cada semana.

codigo/

Firmware para ESP32, GUI en Python y ejemplos de comunicación.

recursos/

Diagramas, imágenes y referencias compartidas.

CAMBIOS.md

Resumen de correcciones relevantes y materiales afectados.

Dentro de cada semana, los materiales se agrupan en presencial/, virtual/ y trabajo-independiente/. Cuando corresponda, virtual/ distingue las actividades asincrónicas de las asesorías sincrónicas. Los archivos editables y sus PDF se conservan juntos.

Ruta de trabajo

Semana

Eje de trabajo

Evidencia de referencia

1

Requerimientos, alcance y arquitectura.

DS-01

2

Selección de componentes, compatibilidad y montaje.

DS-02

3

Adquisición de datos e interfaz gráfica.

Preparación de DS-03

4

Comparación y verificación de la medición.

DS-03

5

Contrato de datos e integración MQTT.

DS-04

6

Continuidad del registro, ausencia de datos y recuperación.

DS-04

7

Pruebas de aceptación e incidencias.

DS-05

8

Entrega del sistema, documentación y defensa individual.

Expediente DS-01 a DS-05

Esta tabla orienta la secuencia temática. Los tiempos, actividades, fechas y criterios de evaluación se consultan en la planeación semanal vigente y en los avisos de Classroom.

Formatos de evidencia

Formato

Finalidad

DS-01

Documentar requerimientos, arquitectura y trazabilidad.

DS-02

Justificar la selección y compatibilidad de los componentes.

DS-03

Comparar mediciones y documentar su verificación.

DS-04

Definir el contrato de datos y comprobar la integración M2M.

DS-05

Registrar pruebas de aceptación, incidencias y correcciones verificadas.

Los formatos forman parte del mismo expediente de proyecto. Su uso no crea entregas ni puntos adicionales a los establecidos en la planeación.

Consulta de materiales

Revisar la planeación vigente de la semana.

Consultar la presentación y la guía de la modalidad correspondiente.

Utilizar las plantillas y el código indicados en la actividad.

Verificar los productos solicitados y su rúbrica en Classroom.

Incorporar la retroalimentación al expediente del proyecto.

Las instrucciones de instalación y ejecución acompañarán a cada ejemplo en codigo/. El equipo, las conexiones y la configuración deben corresponder al modelo de placa y a la práctica indicada.

Actualización de materiales

Mantener nombres estables y descriptivos, por ejemplo, guia_asincronica.docx y guia_asincronica.pdf.

Conservar las versiones anteriores en el historial del repositorio.

Identificar cada cambio con un mensaje claro, por ejemplo: Ajusta instrucciones y rúbrica de la semana 2.

Actualizar conjuntamente la planeación, las diapositivas, las guías y los PDF afectados por una corrección.

Registrar en CAMBIOS.md la fecha, los archivos modificados y el motivo del ajuste.

El repositorio se destina al trabajo docente. Los materiales dirigidos al alumnado se comparten mediante Classroom según la actividad y el avance del curso.
