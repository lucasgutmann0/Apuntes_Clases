# 2nda Clase - Algebra Relacional
## Operaciones Basicas
### 1. Selección (SELECT)
Esta tiene la notacion σ (sigma) de predicado 
donde hay un 
#### Objetivo
seleccionar las tuplas que satisfacen el predicado dado


- **Predicado:** se trata de una expresión que incluye cualquiera de los operadores  >, <, >=, <=, ∧ (conjuncion) significa Y, V (disyuncion) y hace de un O

- **Operandos:** Atributos o constantes

ESTRUCTURA:  
**[σ] [predicado] [tabla]**
> σ sueldo >= 8000 ∧ ingreso >= 01/01/2023 (empleado)

**Nota:** a la hora de hacer un select o una selección, el resultado siempre va a ser una tabla la cual se puede modificar y/o tratar a placer propio. Pero siempre el resultado principal sera una tabla con los mismos atributos.

#### Ejemplo
![Ejemplo Select](/home/gutmanndev/Documentos/classes/5st_semester/DataBases/images/select_example.png "Ejemplo Select")

### PROYECCIÓN 
Tiene la notacion **π** (PI) donde R es una lista de atributos los cuales haran parte de la tabla resultante. 

#### Objetivos
Obtener una tabla a partir de R, eliminando los atributos no especificados, en la tabla resultante, se mostraran los atributos en el mismo orden que en la lista (los registros duplicados se eliminan)

**Ejemplo:**
ESTRUCTURA:  
**[π] [lista de atributos] [tabla]**
> π sueldo, depto (empleado)


### Unión
#### Notación
Tiene la notación R ∪ S 

#### Objetivos
Obtener una tabla que contiene las tuplas de la primera relación además de las tuplas de la segunda relación. Los renglones duplicados se eliminan.

#### Condiciones
Se debe asegurar la compatibilidad entre ambas tablas

- Tienen el mismo grado
- Los atributos tienen el mismo nombre
- El dominio del atributo i de R es el mismo que el atributo i de S)

#### Ejemplo
![Ejemplo Union](/home/gutmanndev/Documentos/classes/5st_semester/DataBases/images/union_example.png "Ejemplo Union")


### Diferencia
#### Notación
Tiene la notación R - S 

#### Objetivos
Obtener una tabla compuesta de los elementos disponibles en la tabla R que no estan en la tabla S

#### Condiciones
Se debe asegurar la compatibilidad entre ambas tablas

- Tienen el mismo grado
- Los atributos tienen el mismo nombre
- El dominio del atributo i de R es el mismo que el atributo i de S)

#### Ejemplo
![Ejemplo Diferencia](/home/gutmanndev/Documentos/classes/5st_semester/DataBases/images/difference_example.png "Ejemplo Diferencia")
### Intersección
Tiene la notación R ∩ S = R - (R - S)
#### Objetivo
Se trata de una relacion con las tuplas que están en R y en S también
#### Condiciones
Se debe asegurar la compatibilidad entre ambas tablas

- Tienen el mismo grado
- Los atributos tienen el mismo nombre
- El dominio del atributo i de R es el mismo que el atributo i de S)
#### Ejemplo
![Ejemplo Intersección](/home/gutmanndev/Documentos/classes/5st_semester/DataBases/images/intersection_example.png "Ejemplo Intersección")


## Operaciones de Productos

