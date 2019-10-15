:banner: banners/getting_started.png

==============================================
Conceptos básicos de la metodología Quickstart
==============================================

Este documento resume los servicios de Odoo Online, nuestra metodología
de implantación Success Pack y las buenas prácticas para empezar con
nuestro producto

1. SPoC (*Single Point of Contact*) y el consultor
==========================================================
Dentro del contexto de su proyecto es altamente recomendado
designar y mantener en ambos lados (su lado y el nuestro) **una
única persona de contacto** la cual tomará las riendas y asumirá
responsabilidades con respecto a su proyecto. El consultor también
tendrá que tener **la autoridad** en términos de toma de decisiones.

- **El consultor Odoo asegura la implementación del proyecto de la A a la Z**:
  Desde el inicio al final del proyecto el consultor asegura la consistencia 
  general de la implementación en Odoo y aplica su habilidad 
  en buenas prácticas.

-  **Una sola persona que tome decisiones en la parte del cliente (SPoC)**:
   Es el responsable de la transmisión del conocimiento de negocio (coordinar 
   la intervención entre usuarios clave, si es necesario) y de la consistencia 
   de implementación desde un punto de vista de negocio (toma de decisiones,
   implementación y dirección de los eventuales cambios, etc.)

-  **Organización de las reuniones**:
   El consultor Odoo no se involucra en el proceso de toma de decisiones desde 
   un punto de vista del negocio ni se encarga de precisar procesos 
   de este tipo o internos de la empresa (a menos que se dé una petición 
   específica o una excepción). Las reuniones del proyecto, las cuales tendrán
   lugar una o dos veces por semana, se centrarán en las necesidades del negocio
   (SPoC) y definirán cómo el consultor implementará dichas necesidades en Odoo.

-  **Entrenar al entrenador como filosofía**:
   El consultor Odoo provee entrenamiento funcional al SPoC para que este pueda
   pasar su conocimiento a sus colaboradores. Para que este acercamiento sea 
   exitoso, será necesario que el SPoC mejore sus habilidades mediante técnicas de
   autoaprendizaje con la ayuda de la `Documentación Odoo <http://www.odoo.com/documentation/user/13.0/index.html>`__, 
   `La plataforma de aprendizaje electrónico <https://odoo.thinkific.com/courses/odoo-functional>`__ 
   y las funcionalidades de testeo y pruebas.

2. Alcance del proyecto
================
Para asegurarse de la implicación de todos los stakeholders será necesario definir
y establecer una evolución del alcance del proyecto tan grande como la impelementación
que el proyecto busca.

-  **Una definición clara del alcance inicial del proyecto**:    
   Una definición inicial clara se sugiere como crucial para asegurar
   que el proyecto se está desarrollando de manera correcta. En tanto en cuanto
   todos los stakeholders comparten la misma visión, la evolución de las necesidades y 
   los procesos de toma de decisiones resultantes serán más simples y claros.
   
-  **División del proyecto en fases**:
   Favorecer una implementación en varias fases coherentes entre sí, permitiendo
   las entregas regulares en entornos de producción y una asimilación continua por parte de 
   los usuarios finales con respecto a Odoo, ha demostrado su efectividad con el paso
   del tiempo. Esta aproximación también ayuda a indentificar huecos y a aplicar acciones
   correctivas en las fases tempranas.
   
-  **Adaptar características estandarizadas como prioridad**:
   Odoo ofrece un gran entorno para implementar mejoras tanto ligeras - personalizaciones - 
   como importantes - desarrollos. De todas formas, adoptar una solución estándar será
   lo preferido en tanto en cuanto se desse optimizar los tiempos de de entrega del proyecto
   y proveer al usuario con una estabilidad de larga duración, así como una escalabilidad
   fluida de su nueva herramienta. Idealmente, una implementación será desplegada después de
   una experimentación del estándar en producción.


.. image:: media/basic_quickstart01.png
    :align: center

3. Administrar expectativas
========================
El huecho entre la realidad de una implementación y las expectativas de esta es un factor crucial.
Tres aspectos importantes deben ser considerados desde el inicio del proyecto:

-  **Estar en sintonía con la idiosincrasia del proyecto**:
   Tanto una división clara de los roles y responsabilidades como
   una descripción de los modos de operación - validación, resolución 
   de problemas, etc. - son aspectos cruciales al éxito de una 
   implementación Odoo. Luego, se aconseja encarecidamente tomar el tiempo
   necesario al inicio del proyecto para tomar conciencia y  de estos temas
   y regularmente compbrobar si están correctamente definidos.
   
-  **Concentrarse en el éxito del proyecto y no la solución ideal**:
   La meta principal del SPoC y del consultor es realizar el proyecto asignado para 
   entregar la solución más efectiva que coincida con las demandas del mismo. Esta 
   meta puede, a veces, estar en conflicto con la visión del usuario final de una
   solución ideal. En este caso, el SPoC y el consultor aplicarán la regla del 80-20: 
   concentrarse en el 80% de las necesidades puestas sobre la mesa y descartar el 20% 
   de los objectivos menos aventajantes en términos de coste/beneficio (estas 
   proporciones pueden cambiar a lo largo del tiempo). Asimismo, será considerado
   aceptable el hecho de integrar manipulaciones que consuman tiempo si se detecta
   un alivio general.
   Cambios en los procesos de negocio también pueden ser propuestos en tanto en cuanto
   se busque perseguir el mismo objetivo.
   
-  **Las especificaciones son siempre EXPLÍCITAS**:   
   Los huecos entre lo esperado y lo entregado son, una gran parte del tiempo, una fuente
   de conflictos en un proyecto. Para evitar una situación así de delicada recomendamos el 
   uso de varias herramientas\* :
   
-  **Análisis GAP**: La compración entre lo requerido y el estándar de características
   propuesto por Odoo hará posible el identificar los huecos a ser rellenados por 
   desarrollos, personalizaciones o cambios en los procesos de negocio.

-  **La historia de usuario**:
   Esta técnica separa claramente las responsabilidades entre el SPoC - el responsable de
   explicar el QUÉ, el POR QUÉ y el QUIÉN - y el consultor - el cual proveerá una respuesta
   al CÓMO.

.. image:: media/basic_quickstart02.png
    :align: center

- `La prubea de concepto <https://es.wikipedia.org/wiki/Prueba_de_concepto>`__ 
  Una versión simplificada, un prototipo del acuerdo que se llega, en líneas 
  generales, de los cambios esperados.
  
- **El boceto**: Teniendo la misma idea que la prueba de concepot, el boceto
  se alineará con los cambios relacionados a la interfaz.

Se añadirá completa transparencia de las posibilidades y limitaciones 
del software y/o su entorno a las herramientas anteriormente mencionadas,
en tanto que se busque que los stakeholders del proyecto tengan una idea 
clara de qué esperar y qué se consigue en el proyecto. Asimismo evitaremos
basar nuestro trabajo en hipótesis no verificadas de antemano.

*La lista puede, por supuesto, ser complementado con otras herramientas que
adecuadamente cumplan con las necesidades de su proyecto.


4. Estrategia de comunicación
=========================
El objetivo de la metodología QuickStart es asegurar la posesión rápida
de la herramienta por parte de los usuarios finales. Una comunicación
efectiva es crucial para el éxito de esta metodología. Su optimización
se hará siguiendo estos principios:

-  **Compartir la documentación de la administración del proyecto**:
   La mejor manera de asegurar que todos los stakeholders de un proyecto
   tienen el mismo nivel de conocimiento es proveer a los mismo con 
   acceso directo a la documentación de seguimiento del proyecto 
   (Organizador del proyecto). Este documento contendrá al menos una
   lista de tareas a realizar como parte de la implementación donde
   el nivel de prioridad y el administrador son claramente definidos.

   El Organizador del proyecto es una herramienta de seguimiento
   compartida que permite tanto el seguimiento detallado de las tareas
   en progreso así como del progreso general del proyecto.

-  **Informar lo esencial**:
   Para minimizar el tiempo de documentación a lo esencial seguiremos 
   las siguientes buenas prácticas:
   
-  El tiempo de las reuniones será limitado a decisiones y validaciones

-  Los estados del proyecto solo se establecerán cuando se alcanze un hito
   considerable.
   
-  Se organizarán sesiones de entrenamiento en las soluciones estandarizadas o 
   personalizadas.

5. Personalización y desarrollo
=================================
Odoo es un software conocido por su flexibilidad y su importante capacidad
de evolución. Sin embargo, una gran cantidad de desarrollo contradice 
al hecho de tener una implementación rápida y sostenible. Por ello, se
recomienda:

-  **Desarrollar si y solo si hay una buena razón**:
   La decisión de desarrollar siempre tiene que tomarse cuando el ratio
   coste-beneficio es positivo (ahorrar tiempo diario, etc.). Por ejemplo,
   será preferible realizar un desarrollo considerable en tanto en cuanto
   se reduzca el tiempo de una operación recurrente, diaria, antes que una
   que se realiza una vez por trimestre. Está popularmente aceptado que
   la solución, cuanto más se acerque a lo estandarizado, más ligero y 
   fluido será el proceso de migración, así como un menor coste de mantenimiento
   para ambas partes.
    Además, la experiencia muestra que el 60% de las peticiones iniciales 
   de desarrollo son descartadas después de unas semanas de uso del estándar
   Odoo (ver "Adaptar características estandarizadas como prioridad").
    
-  **Reemplazar sin replicar**:
   Contextualicemos que existe una buena razón para hacer un cambio 
   en el software. El momento en el que se está haciendo hace 
   la implementación es EL momento adecuado para aceptar 
   o incluso sugerir un cambio tanto en términos de cómo 
   el software se usará como en términos de procesos de negocio 
   de la compañía.
   
6. Principios de pruebas y validación
====================================

Tanto como si los desarrollos están hechos en la implementación como si no,
es crucial probar y validar la corresondencia de dichas soluciones con las
necesidades operacionales de la compañía.

-  **Distribución de roles**:
   En este contexto el consultor será el responsable de entregar una solución
   correspondiente a las especificaciones definidas; el SPoC se encargará
   de probar y validar que la solución cumple los requerimientos de la 
   realidad operacional
   
-  **Administración de cambios**:
   Cuando un cambio se necesita traducir a una solución, el hueco detectado
   se ha generado a causa de:
   
   -  Una diferencia entre la especificación y la solución entregada. Esta es una corrección por la cual el consultor es responsable 
   
      **or**
   
   -  Una diferencia entre la especificación y los imperativos de la realidad  operacional. Esto es un cambio donde el SPoC es el responsable de su generación


7. Importaciones de datos
===============

Importar el historial de datos transaccionales es un apartado importante
que necesita ser tratado de manera apropiada para poder llevar el proyecto
de manera fluida.

Hay que aceptar, entonces, que esta tarea puede consumir una cantidad relevante
de tiempo y si su prioridad no está bien definida, puede prevenir que la producción
no ocurra a tiempo. Para hacer esto a tiempo, se tendrá que tomar una decisión
entre:

-  **No importar nada**:
   A menudo ocurre que después de una reflexión, importar el historial de datos
   no es necesario en tanto en cuanto dichos datos se mantengan fuera de Odoo
   y se consoliden para informes posteriores.

-  **Importar una cantidad limitada antes de salir a producción**:
   Cuando el historial de datos contiene información sobre datos que se estén
   procesando (órdenes de venta, facturas o proyectos, por ejemplo), la necesidad
   de tener esta información disponible desde el día 1 es real. En este caso
   la importación se hará antes de que el producto se lance a producción.

-  **Importar después de salir a producción**:
   Cuando el historial de datos necesita ser integrado con Odoo solo para la
   generación de informes, queda claro que estos datos pueden ser integrados
   en el software de manera retrospectiva. En este caso, el lanzamiento a
   producción procederá sin importación de datos previa.

8. Soporte
==========

Cuando su proyecto se ha lanzado a producción, nuestros equipos de soporte
darán auxilio a sus cuestiones o problemas técnicos.

See :ref:`support-expectations`.
