# Sistema de Gestión de Torneos eSports

## Autor
Sandra Marcos García
Perfil de GitHub: https://github.com/smarcos90


## Descripción del Proyecto
Link al repositorio del Proyecto: https://github.com/smarcos90/torneo-esports-uml.git

Diseño y desarrollo de un sistema de gestión de torneos de eSports, aplicando Programación
Orientada a Objetos (POO) y utilizando diagramas UML para modelar su estructura y funcionalidad.


## Diagramas UML
### Diagrama de casos de uso
![Diagrama de casos de uso](diagrams/casos-uso.png)


### Diagrama de Clases
![Diagrama de clases](diagrams/clases.png)


## Estructura del Proyecto
torneo-esports-uml/  
├── src/  
│ ├── es/empresa/torneo/  
│ │ ├── modelo/  
│ │ ├── control/  
│ │ ├── vista/  
│ │ ├── Main.java  
├── diagrams/  
│ ├── casos-uso.png  
│ ├── clases.png  
├── README.md  
├── .gitignore


## Instalación y ejecución
1. Clonar el repositorio:
`git clone https://github.com/smarcos90/torneo-esports-uml.git`

2. Compilar y ejecutar el proyecto:
`cd src javac es/empresa/torneo/Main.java java es.empresa.torneo.Main`


## Justificación del diseño
### Casos de uso
El administrador tiene completo control del sistema, pudiendo realizar las tareas de registro y consulta del listado de equipos y jugadores. 
Al añadir un equipo obliga (include) a registrar jugadores dentro del equipo. Sin embargo, la consultar el listado de equipos no es obligatorio la consulta de jugadores (extends).

### Diagrama de clases



## Conclusiones