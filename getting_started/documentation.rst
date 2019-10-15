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
   un punto de vista del negocio ni se encarga de precisar este procesos 
   de este tipo o internos de la empresa (a menos que se dé una petición 
   específica o una excepción). Las reuniones del proyecto, las cuales tendrán
   lugar una dos veces por semana, se centrarán en las necesidades del negocio
   (SPoc) y definirán cómo el consultor implementará esas necesidades en Odoo.

-  **Entrenar al entrenador como filosofía**:
   El consultor Odoo provee entrenamiento funcional al SPoC para que este pueda
   pasar su conocimiento a sus colaboradores. Para que este acercamiento sea 
   exitoso, será necesario que el SPoC mejore sus habilidades mediante autoaprendizaje
   con la ayuda de la `Documentación Odoo <http://www.odoo.com/documentation/user/13.0/index.html>`__, 
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
   
-  **División en fases de proyect**:
   Favorecer una implementación en varias fases coherentes entre sí permitiendo
   las entregas regulares en entornos de producción y una asimilación continua por parte de 
   los usuarios finales con respecto a Odoo ha demostrado su efectividad con el paso
   del tiempo. Esta aproximación también ayuda a indentificar huecos y aplicar acciones
   correctivas en las fases tempranas.
   
-  **Adaptar características estandarizadas como prioridad**:
   Odoo ofrece un gran entorno para implementar mejoras tanto ligeras - personalizaciones - 
   como importantes - desarrollos. De todas formas, adoptar una solución estándar será
   lo preferido en tanto en cuanto se desse optimizar los tiempos de de entrega del proyecto
   y provver al usuario con una estabilidad de larga duración, así como una escalabilidad
   fluida de su nueva herramienta. Idealmente, una implementación será desplegada después de
   una experimentación del estándar en producción.


.. image:: media/basic_quickstart01.png
    :align: center

3. Administrar expectativas
========================
El huecho entre la realidad de una implementación y las expectativas de esta es un factor crucial.
Tres aspectos importantes deben ser considerados desde el inicio del proyecto:

-  **Alinearse con la aproximación del proyecto**:
   Tanto una división clara de los roles y responsabilidades como
   una descripción de los modos de operación - validación, resolución 
   de problemas, etc. - son aspectos cruciales al éxito de una 
   implementación Odoo. Luego, se aconseja encarecidamente tomar el tiempo
   necesario al inicio del proyecto para tomar conciencia y  de estos temas
   y regularmente compbrobar si están correctamente definidos.
   
-  **Concentrarse en el éxito del proyecto, no la solución ideal**:
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
   Esta técnica separa claramente las responsabilidades entre el SPoC, el responsable de
   explicar el QUÉ, el POR QUÉ y el QUIÉN, y el consultor, el cual proveerá una respuesta
   al CÓMO.

.. image:: media/basic_quickstart02.png
    :align: center

- `La prubea de concepot <https://es.wikipedia.org/wiki/Prueba_de_concepto>`__ 
  Una versión simplificada, un prototipo del acuerdo que se llega, en líneas 
  generales, de los cambios esperados.
  
- **El boceto**: Teniendo la misma idea que la prueba de concepot, el boceto
  se alineará con los cambios relacionados a la interfaz.

Se añadirá completa transparencia de las posibilidades y limitaciones 
del software y/o su entorno a las herramientas anteriormente mencionadas,
en tanto que se busque que los stakeholders del proyecto tengan una idea 
clara de qué esperar y qué se consigue en el proyecto. Asimismo evitaremos
basar nuestro trabajo en hipótesis sin verificar sus veracidades de antemano.

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
-  Las sesiones de entrenamiento en las soluciones estandarizadas o 
   personalizadas serán organizadas.

5. Personalización y desarrollo
=================================
Odoo es un software conocido por su flexibilidad y su importante capacidad
de evolución. Sin embargo, una gran cantidad de desarrollo contradice 
al hecho de tener una implementación rápida y sostenible. Por ello, se
recomienda:

-  **Desarrollar solo si hay una buena razón**:
   La decisión de desarrollar siempre tiene que tomarse cuando el ratio
   coste-beneficio es positivo (ahorrar tiempo diario, etc.). Por ejemplo,
   será preferible realizar un desarrollo considerable en tanto en cuanto
   se reduzca el tiempo de una operación recurrente, diaria antes que una
   que se realiza una vez por trimestre. Está popularmente aceptado que
   la solución, cuanto más se acerque a lo estandarizado, más ligero y 
   fluido será el proceso de migración, así como un menor coste de mantenimiento
   para ambas partes.
    Además, la experiencia muestra que el 60% de las peticiones iniciales 
   de desarrollo son descartadas después de unas semanas de uso del estándar
   Odoo (ver "Adaptar características estandarizadas como prioridad").
    

-  **Reemplazar sin replicar**:
   Contextualicemos que existe una buena razón para hacer un cambio 
   en el software. Cuando se hace la implementación es EL momento 
   adecuado para aceptar o incluso sugerir un cambio tanto 
   en términos de cómo el software se usará como en términos 
   de procesos de negocio de la compañía.
   
6. Testing and Validation principles
====================================

Whether developments are made or not in the implementation, it is
crucial to test and validate the correspondence of the solution with the
operational needs of the company.

-  **Role distribution**:
   In this context, the Consultant will be responsible for delivering a
   solution corresponding to the defined specifications; the SPoC will
   have to test and validate that the solution delivered meets the
   requirements of the operational reality.

-  **Change management**:
   When a change needs to be made to the solution, the noted gap is
   caused by:
   
   -  A difference between the specification and the delivered solution - This is a correction for which the Consultant is responsible
   
      **or**
   
   -  A difference between the specification and the imperatives of
      operational reality - This is a change that is the responsibility of SPoC.

7. Data Imports
===============

Importing the history of transactional data is an important issue and
must be answered appropriately to allow the project running smoothly.
Indeed, this task can be time-consuming and, if its priority is not well
defined, prevent production from happening in time. To do this as soon
as possible, it will be decided :

-  **Not to import anything**:
   It often happens that after reflection, importing data history is
   not considered necessary, these data being, moreover, kept outside
   Odoo and consolidated for later reporting.

-  **To import a limited amount of data before going into production**:
   When the data history relates to information being processed
   (purchase orders, invoices, open projects, for example), the need to
   have this information available from the first day of use in
   production is real. In this case, the import will be made before the
   production launch.

-  **To import after production launch**:
   When the data history needs to be integrated with Odoo mainly for
   reporting purposes, it is clear that these can be integrated into
   the software retrospectively. In this case, the production launch of
   the solution will precede the required imports.

8. Support
==========

When your project is put in production, our support teams take care of your
questions or technical issues.

See :ref:`support-expectations`.
