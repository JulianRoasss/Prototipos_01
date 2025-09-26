# Especificacion de requisitos de software

Proyecto: Plataforma para la gamificacion a traves del uso de rutas alternativas para la ciudad de Bogotá

# Ficha del documento

| Fecha | version | Autor | Verificado | Observaciones |
|-------|---------|-------|------------|---------------|
|       |         |       |            |               |
## Contenido
## 1 Introduccion
TODO:Redactar un parrafo donde se de una introduccion al contenido de este documento
### 1.1 Proposito
En este documento se define las especificaciones funcionales y no funcionales para el desarrollo de un sistema recomendador web que permite orientar a los clientes durante la compra de su equipo de computo.Este sera utilizado como guia para clientes y desarrolladores
### 1.2 Alcance
### 1.3 Personal involucrado
| Nombre                  | Harold Pava                                      |
|-------------------------|--------------------------------------------------|
| Rol                     | Desarrollador                                    |
| Categoria Profesional   | Ingeniero Sistemas                               |
| Responsabilidad         | Diseñar, desarrollar, implementar bases de datos |
| Informacion de contacto | hapava@ucompensar.edu.co                         |
### Ddefiniciones, Acronimos y abreviaturas
| Nombre  | Descripción                                          |
|---------|------------------------------------------------------|
| Usuario | Persona que usará el sistema para gestionar procesos |
| ERS     | Especificación de Requisitos Software                |
| RF      | Requerimiento Funcional                              |
| RNF     | Requerimiento No Funcional                           |
### 1.5 Referencias

### 1.6 Resumen
## 2 Descripcion general
### 2.1 Perspectiva del producto
```mermaid
graph
  subgraph "usuarios"
      U_CONDUCTOR[Conductor]
  end
 
  subgraph "Sistemas externos"
     AUTH["Autenticacion Microsoft"]
  end
 
subgraph "Sistemas externos"
     APP["Plataforma de rutas alternativas"]
  end
 
  U_CONDUCTOR --> |Inicia Sesion| AUTH
  U_CONDUCTOR --> |Busca rutas alternas y recolecta puntos| APP
 
 
```

