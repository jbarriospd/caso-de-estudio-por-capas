# CASO DE ESTUDIO

- Juan Esteban Marin Duarte
- Cristian David Nieto Montero
- Jose Barrios

En este repositorio presentamos la estructura de carpetas que se deberian realizar en una arquitectura por capas en un projecto Java con Spring boot, agregando un ejemplo para el Caso (Clientes).

```md
.
└── Caso-de-estudio
    ├── mvnw
    ├── mvnw.cmd
    ├── pom.xml
    └── src
        ├── main
        │   ├── java
        │   │   └── co
        │   │       └── edu
        │   │           └── poli
        │   │               └── caso
        │   │                   ├── CaseApplication.java
        │   │                   ├── ServletInitializer.java
        │   │                   ├── controllers
        │   │                   │   └── ClientesController.java
        │   │                   ├── dto
        │   │                   │   └── ClientesDTO.java
        │   │                   ├── entidades
        │   │                   │   └── Clientes.java
        │   │                   ├── repositorios
        │   │                   │   └── ClientesRepository.java
        │   │                   ├── servicios
        │   │                   │   ├── Clientes.java
        │   │                   │   └── impl
        │   │                   │       └── ClientesServiceImpl.java
        │   │                   └── vistas
        │   │                       └── ClientesVista.java
        │   └── resources
        │       └── application.properties
        └── test
            └── java
                └── co
                    └── edu
                        └── caso
                            └── estudiantes
                                └── CaseApplicationTests.java
 ```
