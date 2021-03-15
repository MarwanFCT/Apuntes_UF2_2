# Apuntes de Entornos de desarrollo UF2_2

### INDICE DEL TEMARIO

 - [**INTRODUCCIÓN**](https://github.com/MarwanFCT/Apuntes_UF2_2/blob/main/README.md#introducci%C3%B3n)
 - [**OPTIMIZACIÓN**](https://github.com/MarwanFCT/Apuntes_UF2_2/blob/main/README.md#optimizaci%C3%B3n)
 - [**DOCUMENTACIÓN**](https://github.com/MarwanFCT/Apuntes_UF2_2/blob/main/README.md#documentaci%C3%B3n)


#### INTRODUCCIÓN

**En esta unidad aprenderemos a:**
- Ser capaces de trabajar de forma habitual con sistemas de control de versiones.
- Identificar patrones de refactorización más usuales.
- Revisar el código fuente usando analizadores de código.
- Documentación del código fuente al programar.

#### OPTIMIZACIÓN

##### HEDIONDEZ DEL CÓDIGO
Se le llama hediondez del código cuando hay algo en el mismo que no tiene muy buena pinta en cuanto a la eficiencia o uso.
Puede llegar a indicar deficiencias en el codigo que puedan resultar en un problema más profundo.
No se identifican como bugs o errores ya que no impiden que se ejecute el código correctamente.
Pueden llegar a provocar errores o fallos en el desarrollo, ralentizandolo mucho.
Se suele solucionar con una buena refactorización el código.

##### ANÁLISIS DE CÓDIGO

 *Hay dos tipos de análisis de código:*
 
 **Análisis dinámico** Unit Tests
-Se realiza mediante unit tests del código. (con jUnit por ejemplo)
 
 **Análisis estático** Lint
 *El análisis estático se puede realizar de dos formas:*
 
-Mediante analizadores estáticos (linters)

-Mediante sitios web para inspección de código (Continuous Inspection)

#### REFACTORIZACIÓN
Es el proceso de realizar una reestructuración en pequeños pasos. Pudiendo así hacerlo: 

-Más eficiente.

-Menos redundante.

-Más funcional.

-Más Facil de interpretar.

Hay varias técnicas diferentes que se utilizan en la refactorización como por ejemplo:

-Renombrado de variables a nombres funcionales y entendibles.

-Pasar código duplicado a funciones.

-Eliminación de código no utilizado.

-Eliminación de código redundante.

#### DOCUMENTACIÓN

##### TIPOS DE DOCUMENTACIÓN
 
###### Existen los siguientes tipos de documentación:

-**Documentación de código** Documentación que deja plasmado la explicación de la función de cada línea de código de manera clara y detallada para que cualquier otro programador pueda entenderlo.

-**Documentación técnica** Documentación que deja en constancia la explicación del proyecto o programa en sí, sin ahondar en temas de programación complejos ni la funcionalidad del mismo.

-**Documentación de usuario** Documentación que deja plasmado las instrucciones o pautas que debe seguir el usuario para utilizar el programa y aclaraciones varias sobre el mismo que pueden ser de utilidad para el usuario final.

###### FORMATOS DE DOCUMENTACIÓN

-**HTML** (Ej: Javadoc)

-**Markdown** (Ej: Github)

-**reStructuredText** (Ej: Sphinx)

-**asciiDoc**





