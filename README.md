# Tutorial: Como crear tu blog
> Resultado final siguiendo los articulos publicados.
 
[[_TOC_]]
 
## Requisitos  (Prerequisitos)
- Identificar que requisitos hacen falta para su instalación, pruebas y desarrollo
 
## Instalación / Despliegue
Lista los pasos para realizar el despliegue o la instalación si fuera necesaria.
 
## Estructura
La estructura de carpetas del poryecto
~~~
├───cmd
|   └───server.go
├───internal
├───pkg
├───static
├───templates
├───main.go
└───README.md
 
~~~
 
## Proyectos de AAP
-----------------
Listado de enlaces a los proyectos de tower en caso de existir
 
### Jobtemplate de AAP
-----------------
Listado de enlaces a los jobtemplates/workflow de tower en caso de existir
 
### Variables necesarias para lanzar las plantillas
-----------------
Identificación de las variables para lanzar las plantillas (las encuestas o los extravars)
```
VARIABLE    (valores ejemplor)  Descripción
VARIABLE    (valores ejemplor)  Descripción
```
 
## Playbooks | Código
Descripción del proyectos. Qué hace y como lo hace
 
### Entrada especifica de un playbook / script
 
#### Tareas
1. Tarea 1
    Descripción
1. Tarea 1
    Descripción
1. ...
1. Tarea N
    Descripción
 
#### Variables
Distinguir entre variables externas, generales y de tarea.
Variables externas, introducidas por extra_vars o encuestas:
  - VARIABLE_1: breve explicación
  - ...
  - VARIABLE_N: breve explicación
Variables generales. Definidas en <path_del_fichero>
  - variable_1: breve explicación
  - ...
  - variable_N: breve explicación
Variables por tarea:
  - Tarea 1:
    - variable_1: breve explicación
    - ...
    - variable_N: breve explicación
  - ...
  - Tarea N:
    - variable_1: breve explicación
    - ...
    - variable_N: breve explicación
 
## Roles
Listado de roles y link a sus README
- [rol](/roles/rol/README.md)
 
## Ejemplos de ejecución
-----------------
Tower:
- Enlace a una ejecución realizadaa en tower
 
Línea de comando
```bash
comando para ejecutar
```
 
## Enlace de interes
-----------------
- Documentación de referencia usada durante el desarrollo del proyecto