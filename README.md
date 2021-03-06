# Apuntes de Entornos de desarrollo UF2_2

### INDICE DEL TEMARIO

 - [**INTRODUCCIÓN**](https://github.com/MarwanFCT/Apuntes_UF2_2/blob/main/README.md#introducci%C3%B3n)
 - [**OPTIMIZACIÓN**](https://github.com/MarwanFCT/Apuntes_UF2_1/blob/main/README.md#pruebas)
 - [**DOCUMENTACIÓN**](https://github.com/MarwanFCT/Apuntes_UF2_1/blob/main/README.md#integraci%C3%B3n)
 - [**CONTROL DE VERSIONES**](https://github.com/MarwanFCT/Apuntes_UF2_1/blob/main/README.md#calidad)


#### INTRODUCCIÓN

En esta unidad aprenderemos a ser capaces de trabajar de forma habitual con sistemas de control de versiones
- Identificar patrones de refactorización más usuales

#### PRUEBAS

Las pruebas se pueden clasificar de varias maneras:

**Por la Forma**
- Hay pruebas dinámicas que te obligan a ejecutar la aplicación para poder realizarlas para poder medir su comportamiento.
- Hay pruebas estáticas, que al contrario de las anteriores, se pueden realizar sin ejecutar la aplicación, examinando el codigo fuente sin más.

**Por Estrategia**
- Caja Negra es una estrategia que se usa cuando lo que quieres probar es especificamente el funcionamiento correcto del programa o aplicación.
  Principalmente estudia el sistema desde fuera, se proporcionan entradas y se estudian las salidas del programa trabajando sobre la interfaz del mismo.
- Caja Blanca es una estrategia que se usa cuando deseas probar la estructura del codigo fuente y la eficiencia del mismo.
  Sobretodo examina el código fuente y la ejecución del programa.

**Por Tipo**
- Las Pruebas funcionales son las que ponen a prueba que el programa cumpla su proposito.
- Las pruebas no funcionales son las que ponen a prueba aspectos más extra, como la eficiencia, la seguridad o el rendimiento.

**Por Mecanismo**
- Existen los mecanismos manuales que significa que la prueba la realiza una persona humana revisando el codigo.
- Existen los mecanismos automáticos que significa que la prueba es realizada por un software o maquina que ejecuta el codigo revisando el resultado del mismo, con el que se esperaba obtener.

#### INTEGRACIÓN

Existen varias formas de integración:

- Integracion Big Bang: Son un tipo de prueba de integración en el que los elementos software, elementos hardware ó ambos son combinados de forma simultánea en un componente o un sistema global en lugar de hacerlo por fases.
- Integracion Descendente: Son pruebas con un enfoque incremental de pruebas de integración donde el componente en el nivel más alto en la jerarquía es probado en primer lugar, con los componentes del nivel inferior siendo simulados mediante stubs.
- Integracion Ascendente: Son pruebas que tienen un enfoque incremental para pruebas de integración donde los componentes de más bajo nivel son probados en primer lugar, posteriormente son utilizados para facilitar las pruebas de componentes de un nivel superior. 
- Integracion Continua: La integración continua es una práctica del desarrollo de software ágil en la que los ingenieros van integrando los fragmentos de código que desarrollan poco a poco en lugar de hacerlo una vez concluido todo el proyecto. Como por ejemplo Jenkins, Bamboo, TravisCI o CircleCI.

##### Cobertura Del Código

Es una unidad de medida que se usa para determinar la cantidad de código que ha sido ejecutada en el transcurso de las pruebas, como podría ser evidente, cuánto mayor sea esta unidad, mejor. La cobertura se puede realizar tanto desde el IDE como desde un servicio web adiente para esta función.

#### CALIDAD

Las pruebas conforman también de un control de Calidad, dandonos una medida que representa la calidad del producto.

En el control de Calidad se realizan dos procesos:

- Quality Assurance: Garantización de Calidad
- Quality Control: Control de Calidad

La calidad se mide por el modelo de calidad de McCall, que define 11 factores de calidad para medir la misma.
Se agrupan en 3 secciones:

- **Operación del producto**
Corrección: Mide el grado en que un programa cumple las especificaciones y consigue los objetivos del cliente.
Fiabilidad: Mide el grado en que se puede esperar que un programa cumpla sus funciones sin fallar.
Eficiencia: Mide la cantidad de recursos de nuestra PC y código empleado por un programa para cumplir su función.
Seguridad: Mide el grado en que puede controlarse el acceso al software o a los datos por personal no autorizado.
Facilidad de uso: Es el esfuerzo requerido para aprender lo que hace un programa y su funcionamiento.

- **Revisión del producto**
Mantenibilidad: Es la facilidad que se tiene para localizar y remediar errores.
Flexibilidad: Es el esfuerzo requerido para modificar un sistema operativo.
Facilidad de Prueba: Es el esfuerzo requerido para probar un programa.

- **Transición del producto**
Portabilidad: Es el esfuerzo requerido para transferir un software de un hardware o un entorno de sistemas a otro.
Reusabilidad: Es el grado en que un programa o trozos del mismo son reutilizables para otros programas.
Interoperatividad: Es el esfuerzo requerido para asociar un programa a otro.
