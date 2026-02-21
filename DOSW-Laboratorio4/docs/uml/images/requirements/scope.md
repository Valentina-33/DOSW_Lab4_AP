# 📄 Requerimientos del Sistema

## 1. Sistema

* Nombre del sistema: Bankify 
* Objetivo: El sistema tiene como objetivo proporcionar un sistema para la gestión básica de cuentas bacnarias de los clientes. Este es usado para que los clientes puedan consultar información de sus cuentas y realizar operaciones simples. 

## 2. Problema a resolver

Bankify no cuenta con ciertos elementos esenciales para sus clientes, tales como el registro de cuentas bancarias de manera validada, consultar el saldo de estas cuentas, realizar depósitos de dinero, la generación de reportes tributarios a los clientes en PDF, y el envío de estos reportes a la DIAN en formato JSON. 


## 3. Diagrama de Contexto

### 3.1 Diagrama

En el diagrama de contexto realizado por Lucidchart identificamos actores principales tanto internos como externos, los cuales reflejan un flujo de ambas partes (Actor -> Bankify y Bankify -> Actor). 

En el diagrama también se muestran conectores puntuales sobre como estos actores aportan al sistema con acciones puntuales como gestión, consulta y envíos de información. A continuación se muestra una tabla de actores explicando a más detalle cuál es el rol que cumple dentro de Bankify. 


### 3.2 Actores


| Actor / Rol                        |          Descripción                             |
|------------------------------------|:------------------------------------------------:|
| Usuario final / Cliente            | Cliente del sistema de Bankify                   |
| Operador                           | Gestiona y operador las cuentas                  |
| Gerente Financiero                 | Genera y analiza reportes tributarios            |
| Administradores de bases de datos  | Gestión, manejo y protección de datos            |
| Supervisor                         | Gestión y atención al cliente                    |
| Bancos                             | Empresas que usan la plataforma                  |
| DIAN                               | Organización que envía los reportes tributarios  |



### 3.3 Sistemas externos


| Sistema                            |                                    Descripción                                           |
|------------------------------------|:----------------------------------------------------------------------------------------:|
| Reportes                           | Sistema que genera los reportes tributarios de cada cliente del sistema de Bankify       |
| Base de datos                      | Sistema que proporciona un espacio digital información y datos personales                |
| DIAN                               | Sistema externo gubernamental al que se envían los reportes tributarios en formato JSON  |
| Sistema de Autenticación           | Servicio encargado de validar credenciales para clientes, asesores, supervisores,gerentes|
| Sistema de Bancos Registrados      | Sistema que valida que los dos primeros dígitos del número de cuenta                     |


## 4. Alcance del sistema
   
### 4.1 Dentro del sistema

Las funciones principales que realiza Bankify actualmente son:

● Autenticación de las credenciales de clientes y operadores dentro del sistema. 

● Módulo de gestión de clientes: esto se usa para la creación y modificación de usuarios por roles y permisos autorizados.  

● Consulta de saldo de cuentas por parte del cliente. 

● Opción de realizar un depósito a una cuenta por parte del cliente propietario de la cuenta u otros usuarios. 

● Generación de reportes tributarios de declaración de renta por parte del cliente. 

● Generación de reportes tributarios de declaración de renta de todas las cuentas para la DIAN por parte del gerente financiero. 


### 4.2 Fuera del sistema

Algunas de las funciones que no realiza el sistema por el momento son:

● Registrar cuentas bancarias de manera validada. 

● Consultar el saldo de una cuenta. 

● Realizar depósitos de dinero de forma controlada. 

● Generar reportes tributarios a los clientes en formato PDF. 

● Enviar reportes a la DIAN en formato JSON. 



---
