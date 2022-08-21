# Componentes entorno BI

**Contenedores de datos**

* **Dispersión de los datos**: Los datos acostumbran a estar dispersos y existir en _**diferentes tipos de contenedores.**_
* **Contenedores de datos**: _**Almacenes de datos**_ cuyo contenido puede ser _**de diferente naturaleza**_, debido a la herramienta que genera dichos datos.
* _**Contenidos**_: _**Ficheros de texto, bases datos, etc**_. Están _**limitados por**_ el acceso correspondiente a los _**conectores de los que dispongan las herramientas de extracción**_. Aplica a:
  * _**Data sources**_: Elementos que almacenan datos en origen.
  * _**Data targets**_: Almacenes de datos de destino.
  * _**Data intermediate**_: Almacenes intermedios, que puedan ser necesarios utilizar para un tratamiento específico de los datos en un momento determinado, para el modelado de estos.&#x20;

**ETL (Extract-Transform-Load)**

* Herramientas para la _**extracción**_ del contenido desde los orígenes, _**modelado**_ (transformación) de dicha información y _**carga**_ en los contenedores de destino.
* Son _**imprescindibles**_, ya que _**los contenidos pueden estar dispersos y en diferentes formatos**_.
* Una vez _**extraída la información y filtrada**_ (excluyendo aquellas filas que no sean necesarias), se realizarán los _**cruces, cálculos y demás operaciones necesarias**_ con el objetivo _**relacionar todos los orígenes implicados**_.\
  **Tablas intermedias**: Pueden existir y tienen por objeto _**insertar información con el dato en bruto**_. _**Al finalizar el proceso de modelado pueden ser eliminadas**_, dependiendo de la temporalidad de la información que almacenen. Estos almacenes de datos _**dan lugar a los 'stages'**_, que son escenarios intermedios de carga.

**Cuadros de Mando (Dashboards)**

* Son herramientas de gestión empresarial creadas para _**medir la evolución de las actividades y los procesos que se generan en el interior de las organizaciones**_.
* Se utilizan para _**construir recursos visuales**_, que faciliten la representación del contenido analizado, para posteriormente _**agilizar y facilitar la toma de decisiones**_.
* Visualizan los datos de una manera _**amigable**_ y permiten la _**interacción**_ con el usuario, es decir, resulta _**rápido y sencillo**_ la realización de _**segmentaciones y filtrados**_, con el fin de poner el foco en determinado dato.
* Dentro del ciclo de presentación del dato, será el _**último escalón que se encuentra en el desarrollo**_.
* Es la _**capa de mayor interés para el cliente**_, es la que representa los datos requeridos por el cliente de una forma visual y amigable.

**KPIs (Key Performance Indicators)**

* Indicadores Clave de Desempeño
* Hacen referencia a una serie de _**métricas que se utilizan para sintetizar la información**_ (detallan cuáles son los objetivos de medición).
* Con ellos se _**analizarán**_ datos relacionados con la _**eficacia y productividad de las acciones que se lleven a cabo, de forma que facilite la toma de decisiones**_.
* Posibilitan _**determinar las acciones estratégicas del negocio**_, que han sido más efectivas a la hora de cumplir con los objetivos marcados en un proceso o proyecto concreto.
* _**No es**_ un recurso en forma de _**herramienta**_, es un elemento imprescindible a la hora de plantear un proyecto, que _**nos va a indicar que es lo que se tiene que medir**_.
* No solo sirven para _**detallar donde se pone el foco de medición**_, sino que también sirven para que _**los desarrollos estén en constante evolución con la finalidad de mejorar**_ los datos representados y, por tanto, de su _**análisis**_.
