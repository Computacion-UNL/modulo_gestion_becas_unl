<h1 align="center">MÓDULO DE GESTIÓN DE BECAS</h1>
<p align="center"> UNIVERSIDAD NACIONAL DE LOJA</p>
<p align="center"><img src="https://pbs.twimg.com/profile_images/1225522326487347211/FaNm0ISf_400x400.jpg" width="200" height="200"/></p> 

## Tabla de contenidos:
---
- [Tabla de contenidos:](#tabla-de-contenidos)
- [Autor](#autor)
- [Descripción y contexto](#descripción-y-contexto)
- [Guía de usuario](#guía-de-usuario)
- [Guía de implementación](#guía-de-implementación)
  - [Dependencias](#dependencias)
- [Información adicional](#información-adicional)

## Autor
---
El presente Trabajo de Titulación fue desarrollado por:
-   Jackson Andrews Guzmán Tituana - jackson.guzman@unl.edu.ec
<br/><br/>

Con la dirección del:
-   Ing. Pablo Fernando Ordoñez Ordoñez - pfordonez@unl.edu.ec

## Descripción y contexto
---
El repositorio contiene una copia del Trabajo de Titulación <b>"Módulo para el seguimiento y control de becas de la Unidad de Bienestar Universitario"</b> el cuál contiene en su Anexo 1 la descripción de todo el desarrollo que se llevó a cabo para la ejecución del proyecto.
Recursos adicionales como diagramas BPMN de los procesos que se llevan a cabo en la Gestión de Becas. Diagramas de componentes que detallan la arquitectura del MGB.
<br/><br/>
El Módulo de Gestión de Becas (MGB) implementado en el sistema SIAAF, forma parte integral del proyecto de Titulación mencionado y complementa el proceso de postulación de becas que se lleva a cabo a través del Módulo de Gestión de Trámites (MGT), mediante el seguiento y control de becas de la Unidad de Bienestar Universitario.
<br/><br/>
Las funcionalidades con las que cuenta el módulo de sofware son:<br/>
-   Administración de la información de postulantes en la Etapa de Revisión
-   Administración de la información de postulantes en la Etapa de Selección
-   Automatización de las notificaciones de postulación de estudiantes vía correo electrónico
-   Administración de la información de becas en la Etapa de Adjudicación
-   Gestión de registros de pago en la Etapa de Concesión
-   Tablero de estadísticas generales durante el seguimiento y control de becas 
-   Generación de reportes en formato xls de cada una de las Etapas
-   Filtrado y paginación de datos en cada Etapa
<br/><br/>

El módulo implementado en los servidores de la Universidad Nacional de Loja (UNL) forma parte del Sistema de Información Académico Administrativo Financiero (SIAAF) en el cual se encuentra embebido, por ello el código fuente se encuentra presente en el repositorio del proyecto SIAAF del software de control de versiones GitLab de la UNL.

## Guía de usuario
---
Para acceder al código fuente solicitar acceso a la Dirección de Telecomunicaciones e Información (DTI): direccion.dti@unl.edu.ec
<br/><br/>
Para acceder al manual de usuario del módulo de software ingrese al siguiente enlace: https://drive.google.com/file/d/1ZRrB-HpoS4Vygfsw1ztw6VSXocv4eiOL/view
<br/><br/>

 	
## Guía de implementación
---
Para poder implementar el módulo se recomienda acceder al siguiente enlace: https://drive.google.com/file/d/1ylsQh2zn3y8yTKJNXuA7qV5YXIwm9mql/view guía referente a la implementación del módulo en el Sistema SIAAF.
<br/><br/>
Las Tecnologías y Herramientas utilizadas fueron:
-   Sistema Operativo Linux o derivados
-   Lenguaje de Programación Pyhton versión 3.5+
-   Gestor de Base de Datos PostgreSQL versión 10
-   Framework Django versión 3.2
-   Entorno de Desarrollo VsCode

### Dependencias
Para instalar las dependencias y herramientas necesarias para la ejecución del módulo lea el archivo README.md del sistema SIAAF una vez haya solicitado acceso al código fuente.

## Información adicional
---
Para conocer más de Django ingrese a: https://www.djangoproject.com/
<br/><br/>
Para acceder a la documentación de desarrollo de Django ingrese a: https://docs.djangoproject.com/en/3.2/