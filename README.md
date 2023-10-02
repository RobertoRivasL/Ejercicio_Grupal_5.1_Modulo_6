<table><tr><th colspan="4" valign="top">Módulo</th><th colspan="3" valign="top">Nivel de Dificultad</th></tr>
<tr><td colspan="4" valign="top">Desarrollo de aplicaciones JEE conSpring Framework</td><td colspan="3" valign="top">Medio</td></tr>
<tr><td colspan="4" valign="top">Tema: JDBC Template</td><td colspan="3" valign="top">JDBC Template</td></tr>
<tr><td colspan="7" valign="top">Intención del aprendizaje o aprendizaje esperado:</td></tr>
<tr><td colspan="7" valign="top"><p></p><p>- Codificar un servicio Spring que accesa información en una base de datos utilizando JdbcTemplate.</p></td></tr>
<tr><td colspan="7" valign="top">Planteamiento del Problema:</td></tr>
<tr><td colspan="7" valign="top"><p></p><p>Una empresa de asesorías en prevención de riesgos necesita contar con un sistema de información que le permita administrar los principales procesos que se llevan a cabo en ella día a día.</p><p></p><p>Hasta el momento se han definido las siguientes funcionalidades en el sistema:</p></td></tr>
<tr><td colspan="1" rowspan="11" valign="top"></td><td colspan="1" valign="top"><b>ID</b></td><td colspan="1" valign="top"><b>Nombre</b></td><td colspan="2" valign="top"><b>Detalle</b></td><td colspan="1" valign="top"><b>Actor(es)</b></td><td colspan="1" rowspan="11" valign="top"></td></tr>
<tr><td colspan="1" valign="top">1</td><td colspan="1" valign="top"><b>Inicio</b></td><td colspan="2" valign="top"><p>Página  de  inicio  del  portal  con</p><p>información relevante del proyecto</p><p>que se está realizando.</p></td><td colspan="1" valign="top"><p>Cliente	/</p><p>Administrativo	/</p><p>Profesional</p></td></tr>
<tr><td colspan="1" valign="top">2</td><td colspan="1" valign="top"><b>Contacto</b></td><td colspan="2" valign="top"><p>Formulario de contacto para realizar</p><p>consultas.</p></td><td colspan="1" valign="top">Cliente</td></tr>
<tr><td colspan="1" valign="top">3</td><td colspan="1" valign="top"><b>Crear Capacitación</b></td><td colspan="2" valign="top"><p>Formulario	para	crear	una</p><p>capacitación en el sistema.</p></td><td colspan="1" valign="top">Cliente</td></tr>
<tr><td colspan="1" valign="top">4</td><td colspan="1" valign="top"><b>Listar Capacitaciones</b></td><td colspan="2" valign="top">Listado de capacitaciones registradas.</td><td colspan="1" valign="top">Cliente</td></tr>
<tr><td colspan="1" valign="top">5</td><td colspan="1" valign="top"><b>Listado de Usuarios</b></td><td colspan="2" valign="top"><p>Listado con los usuarios existentes en</p><p>plataforma.</p></td><td colspan="1" valign="top">Administrativo</td></tr>
<tr><td colspan="1" valign="top">6</td><td colspan="1" valign="top"><b>Crear Usuario</b></td><td colspan="2" valign="top"><p>Formulario que permitirá crear un</p><p>usuario en sistema.</p></td><td colspan="1" valign="top">Administrativo</td></tr>
<tr><td colspan="1" valign="top">7</td><td colspan="1" valign="top"><b>Editar Cliente</b></td><td colspan="2" valign="top"><p>Formulario que permite modificar los</p><p>datos de un usuario de tipo cliente.</p></td><td colspan="1" valign="top">Administrativo</td></tr>
<tr><td colspan="1" valign="top">8</td><td colspan="1" valign="top"><b>Editar Administrativo</b></td><td colspan="2" valign="top"><p>Formulario que permite modificar los</p><p>datos	de	un	usuario	de	tipo</p><p>administrativo.</p></td><td colspan="1" valign="top">Administrativo</td></tr>
<tr><td colspan="1" valign="top">9</td><td colspan="1" valign="top"><b>Editar Profesional</b></td><td colspan="2" valign="top"><p>Formulario que permite modificar los</p><p>datos	de	un	usuario	de	tipo profesional.</p></td><td colspan="1" valign="top">Administrativo</td></tr>
<tr><td colspan="1" valign="top">10</td><td colspan="1" valign="top"><b>Listado Visitas</b></td><td colspan="2" valign="top"><p>Lista de todas las visitas realizadas a</p><p>cada uno de los clientes. Además,</p></td><td colspan="1" valign="top">Profesional</td></tr>
<tr><td colspan="7" valign="top"></td></tr>
</table>

|    |                            | posee un formulario que permite agregar nuevas visitas a sistema.                                                                                                                                        |                                                           |
|:---|:---------------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:----------------------------------------------------------|
| 11 | **Responder checklist**    | Listado de chequeos de una visita.                                                                                                                                                                       | Profesional                                               |
| 12 | **Listado Pago**           | Lista de todos los pagos realizados por los clientes.                                                                                                                                                    | Administrativo                                            |
| 13 | **Crear Pago**             | Permitirá agregar un pago al sistema.                                                                                                                                                                    | Administrativo                                            |
| 14 | **Listado Asesorías**      | Lista con las asesorías realizadas hasta el momento.                                                                                                                                                     | Profesional                                               |
| 15 | **Crear Asesorías**        | Contiene un formulario para agregar una nueva asesoría.                                                                                                                                                  | Profesional                                               |
| 16 | **Reportes**               | Despliega reportes específicos.                                                                                                                                                                          | Profesional                                               |
| 17 | **Administrar Asistentes** | <p>Administración de asistentes a una</p><p>capacitación; incluye listarlos, poder agregar asistentes y eliminarlos.</p>                                                                                 | Cliente                                                   |
| 18 | **Login**                  | <p>Contendrá un acceso a un usuario al</p><p>portal a través de un RUT de usuario y una clave.</p>                                                                                                       | <p>Cliente	/</p><p>Administrativo	/</p><p>Profesional</p> |
| 19 | **Gestionar accidentes**   | <p>Listado con todos los accidentes registrados en plataforma. Además, permite editarlos, agregar uno nuevo y eliminarlos.  En  esta  sección  cada</p><p>cliente administra sus propios accidentes.</p> | Cliente                                                   |
| 20 | **Administrar chequeos**   | <p>Permite	mostrar	los	distintos chequeos realizados a cada cliente en</p><p>una visita a terreno, y permite agregar uno nuevo, y cambiar su estado.</p>                                                 | Administrativo                                            |

En el ejercicio del día anterior, se creó un proyecto Spring MVC, con tres controladores, los que abarcan

los siguientes casos de uso:

- Inicio
- Contacto
- Crear Capacitación
- Listar Capacitación

Como parte de este ejercicio se pide realizar lo siguiente:

1. Agregue las funcionalidades necesarias para el caso de uso Crear Capacitación. Recuerde que en

` `este caso se deben rescatar los datos desde un formulario, e insertarlos en la tabla correspondiente.

1. Desarrolle el caso de uso Contacto. Para ello, debe generar una rutina tal que tome los datos desde

` `el formulario respectivo, y los despliegue a través de la consola de comandos del sistema.

1. Finalmente, desarrolle el caso de uso Listar Usuarios. Este caso de uso debe tomar los datos

` `existentes en la tabla que registra los usuarios, y desplegarlos por pantalla.

El entregable debe ser un proyecto Java Web comprimido en un archivo ZIP o RAR.

| **Nota 1:** En este caso sí es necesario que la plataforma se conecte a la base de datos. Recuerde usar los conceptos asociados a JDBC Template para estos efectos.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| El Datos de apoyo al planteamiento                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| <p></p><p>**Ejecución**: Grupal (equipo de no más 4 personas)</p><p></p><p>**Componentes para evaluar**: Se deberá entregar un archivo comprimido con el proyecto.</p>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Preguntas guía:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| Recursos Bibliográficos:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| <p></p><p>**Spring MVC: Configuración**</p><p><https://www.javatutoriales.com/2015/12/spring-mvc-parte-1-configuracion.html></p><p></p><p>**Introducción a MVC en Spring**</p><p><http://www.jtech.ua.es/j2ee/publico/spring-2012-13/sesion03-apuntes.html></p><p></p><p>**Crear un proyecto MVC con Spring Tool Suite (STS)**</p><p><https://www.youtube.com/watch?v=eMG9qi061D8></p><p></p><p>**Spring MVC - Cómo incluir archivos CSS o JS en una página JSP**</p><p><https://mkyong.com/spring-mvc/spring-mvc-how-to-include-js-or-css-files-in-a-jsp-page/></p><p></p><p>**Log con log4j**</p><p><https://www.es.w3ki.com/spring/logging_with_log4j.html></p><p></p><p>**Spring Crud con JDBC Template y Oracle**</p><p><https://www.javainterviewpoint.com/spring-crud-example-jdbctemplate/></p> |


![Static Badge](https://img.shields.io/badge/Ejercicio%20Grupal%205.1%20-%20Modulo%206%20-%20blue?labelColor=abcdef&cacheSeconds=3200)


![GitHub last commit](https://img.shields.io/badge/Integrantes%20%3A%20-%20%237E7E73?cacheSeconds=7200
) ![GitHub code size in bytes](https://img.shields.io/badge/Bastian%20Mariangel%20-%20%2350CAC0?cacheSeconds=7200
)
![GitHub last commit](https://img.shields.io/badge/Ivan%20Mieres%20-%20%23D8DA31?cacheSeconds=7200
)
![GitHub last commit](https://img.shields.io/badge/Patricio%20Bonnin%20-%20%23E87215?cacheSeconds=7200
)
![GitHub last commit](https://img.shields.io/badge/Roberto%20Rivas%20-%20%23F70910?cacheSeconds=7200
)


![image](https://github.com/RobertoRivasL/Ejercicio_Grupal_5.1_Modulo_6/assets/131497718/bed278ea-0456-4be9-a6cd-87c4b33b0458)
![image](https://github.com/RobertoRivasL/Ejercicio_Grupal_5.1_Modulo_6/assets/131497718/b3ddf97d-1524-48b3-9230-cc2db5e7c4d0)
![image](https://github.com/RobertoRivasL/Ejercicio_Grupal_5.1_Modulo_6/assets/131497718/dff77f78-318c-440b-94ca-f69cba822a80)
![image](https://github.com/RobertoRivasL/Ejercicio_Grupal_5.1_Modulo_6/assets/131497718/13dc8e1e-ced1-4ab3-8a02-1efd2b5d3384)
![image](https://github.com/RobertoRivasL/Ejercicio_Grupal_5.1_Modulo_6/assets/131497718/15fc0b6f-64eb-4d44-adcc-cf0b158f4a87)
![image](https://github.com/RobertoRivasL/Ejercicio_Grupal_5.1_Modulo_6/assets/131497718/04d50de1-9755-47e7-aac7-fd73d181dee1)
![image](https://github.com/RobertoRivasL/Ejercicio_Grupal_5.1_Modulo_6/assets/131497718/3e6a1f8c-c6d2-426c-8590-1d04f6943eff)
![image](https://github.com/RobertoRivasL/Ejercicio_Grupal_5.1_Modulo_6/assets/131497718/74a8a852-5fff-47d3-816f-e6173d4aad8b)
![image](https://github.com/RobertoRivasL/Ejercicio_Grupal_5.1_Modulo_6/assets/131497718/96d88a1d-3cd9-4c53-94b8-286d1d3009ea)
![image](https://github.com/RobertoRivasL/Ejercicio_Grupal_5.1_Modulo_6/assets/131497718/c23a8ba0-b287-43ca-a08d-3817347a7c6a)










