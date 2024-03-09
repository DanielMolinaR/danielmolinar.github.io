+++
title = 'CRM para clínica de fisioterapia'
date = 2021-05-15T17:20:16+01:00
draft = false
+++

El proyecto que desarrollé consiste en un [CRM](https://es.wikipedia.org/wiki/Gesti%C3%B3n_de_Relaciones_con_el_Cliente) (Customer Relationship Management) para una clínica de fisioterapia. La motivación detrás de este proyecto fue crear una herramienta que simplificara la gestión de usuarios, citas y ejercicios programados, optimizando así la eficiencia y la calidad del servicio proporcionado por la clínica.

La aplicación se diseñó para ser utilizada por tres tipos diferentes de usuarios: **pacientes, empleados y administradores**. Cada uno de estos roles tiene diferentes niveles de acceso y privilegios en la plataforma. Los administradores tienen acceso total a todas las funcionalidades de la aplicación, incluyendo la gestión de usuarios, citas y ejercicios. Los empleados tienen acceso limitado y solo pueden gestionar las citas y los pacientes asignados a ellos. Los pacientes tienen la capacidad de gestionar sus propias citas, ejercicios y cuentas personales.

Para garantizar la seguridad de la información, se implementaron medidas como la autenticación mediante credenciales y la **gestión de la sesión** del usuario a través del uso de **tokens de acceso y refresco** como se indica en el protocolo [OAuth2.0](https://oauth.net/2/). Además, durante el proceso de registro, se envía un correo de confirmación al usuario para verificar su identidad y asegurar que solo los usuarios autorizados puedan acceder a la plataforma.

El desarrollo de la aplicación se dividió en dos partes principales: el frontend y el backend. Para el [frontend](https://github.com/DanielMolinaR/front-fisioterapia), se utilizó **Vuetify**, un framework de componentes basado en **Vue.js**, que proporcionó una **interfaz de usuario intuitiva y adaptable a dispositivos móviles y de escritorio**. En cuanto al [backend](https://github.com/DanielMolinaR/API-REST), se optó por utilizar **Go** como lenguaje de programación debido a su rendimiento y eficiencia. La comunicación entre el frontend y el backend se realiza a través de una **API RESTful**, que se encarga de manejar las solicitudes y respuestas entre ambas partes.

La base de datos utilizada para almacenar la información de la aplicación es **PostgreSQL**, que ofrece robustez y seguridad en el manejo de datos. Además, se integró **KeyCloak** para la gestión de cuentas de usuario y la generación de tokens de acceso y tokens de refresco, siguiendo el protocolo **OAuth 2.0** para garantizar la seguridad en la autenticación y autorización de usuarios.

Además, la aplicación se implementó como una **aplicación web progresiva (PWA)**, lo que permite a los usuarios instalarla en sus dispositivos móviles desde el navegador web. Esto proporciona una experiencia similar a la de una aplicación nativa, con funcionalidades adicionales como acceso offline y notificaciones push.

Durante el desarrollo del proyecto, se enfrentaron diversos desafíos técnicos, como la implementación de la lógica de negocio y la integración de diferentes tecnologías. Sin embargo, gracias a un enfoque meticuloso y a la resolución efectiva de problemas, se logró superar estos obstáculos y completar con éxito el proyecto.

En resumen, este proyecto no solo demostró mis habilidades técnicas en el desarrollo de aplicaciones web complejas, sino que también me brindó la oportunidad de aprender y crecer como desarrollador. Estoy orgulloso del resultado final y del camino emprendido.