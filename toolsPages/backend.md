---
layout: default
title: Bases de Datos y Backend
---

---

**[< Volver a Herramientas](../herramientas-utiles.html)**

**[< Volver al Inicio](../)**

---

# Bases de Datos y Backend

El backend es el motor que hace que todo funcione. Es la lógica que corre en el servidor y la base de datos que guarda la información (usuarios, posts, productos, etc.).

Estas herramientas nos ayudan a construir, gestionar, probar y monitorear esa parte "invisible" pero esencial de nuestros proyectos.

---

## Gestores de bases de datos

Estas son aplicaciones de escritorio (GUIs) que nos permiten conectarnos a nuestras bases de datos para ver los datos de forma visual, ejecutar consultas (queries) y administrar la estructura. Son mucho más cómodas que usar solo la terminal.

### DBeaver
Es el cliente de base de datos universal, una verdadera navaja suiza.

* **Cómo nos sirve:** Su principal ventaja es que se puede conectar a casi *cualquier* base de datos que te imagines: PostgreSQL, MySQL, SQL Server, MongoDB, etc. En lugar de aprender a usar un cliente diferente para cada materia, podemos usar DBeaver para todas.
* **Beneficio:** Es gratuito (Community Edition) y de código abierto.
* **Enlace:** [https://dbeaver.io/](https://dbeaver.io/)

### pgAdmin
Es el cliente gráfico oficial y más completo diseñado específicamente para PostgreSQL.

* **Cómo nos sirve:** Si estamos trabajando seriamente con PostgreSQL (por ejemplo, en un proyecto con Supabase o en una materia de bases de datos), pgAdmin nos da acceso a todas las funciones avanzadas, administración de roles y monitoreo específico.
* **Beneficio:** Gratuito y de código abierto.
* **Enlace:** [https://www.pgadmin.org/](https://www.pgadmin.org/)

### MongoDB Compass
Es el cliente gráfico oficial de MongoDB.

* **Cómo nos sirve:** Dado que MongoDB no es SQL (es basado en documentos JSON), una GUI es casi indispensable. Compass nos deja ver la estructura de los documentos, crear *pipelines* de agregación visualmente y optimizar nuestros queries.
* **Beneficio:** Gratuito (Community Edition).
* **Enlace:** [https://www.mongodb.com/products/compass](https://www.mongodb.com/products/compass)

---

## BaaS (Backend as a Service) y DBaaS (Database as a Service)

¿Qué pasa si no queremos (o no tenemos tiempo) de construir todo un backend desde cero? Estas plataformas nos ofrecen un backend listo para usar, o al menos una base de datos en la nube, para que solo nos preocupemos por el frontend.

### Firebase
Es la plataforma de Google. Es un BaaS súper completo.

* **Cómo nos sirve:** Es la forma más rápida de tener un backend para una app móvil o web. Nos da autenticación (login con Google, Facebook, etc.), una base de datos en tiempo real (Firestore) y almacenamiento de archivos, todo listo para consumir con un API.
* **Beneficio:** Tiene una capa gratuita ("Spark") muy generosa, perfecta para la mayoría de proyectos universitarios.
* **Enlace:** [https://firebase.google.com/](https://firebase.google.com/)

### Supabase
Se autodenominan "la alternativa de código abierto a Firebase".

* **Cómo nos sirve:** Nos da todo lo de Firebase (autenticación, base de datos en tiempo real, almacenamiento) pero con una gran ventaja: está construido sobre PostgreSQL. Esto nos permite usar el poder de una base de datos SQL que ya conocemos.
* **Beneficio:** Gratuito para proyectos pequeños y es de código abierto.
* **Enlace:** [https://supabase.com/](https://supabase.com/)

### Mongo Atlas
Es el servicio de "Base de Datos como Servicio" (DBaaS) de los creadores de MongoDB.

* **Cómo nos sirve:** Si queremos usar MongoDB en nuestro proyecto pero no queremos instalarla y administrarla en un VPS, usamos Atlas. Ellos se encargan de la seguridad, los backups y la escalabilidad.
* **Beneficio:** Tiene una capa gratuita ("cluster" M0) para siempre, ideal para aprender y para proyectos pequeños.
* **Enlace:** [https://www.mongodb.com/cloud/atlas](https://www.mongodb.com/cloud/atlas)

### Redis
Es una base de datos en memoria increíblemente rápida. No es una base de datos principal, sino una auxiliar.

* **Cómo nos sirve:** Se usa principalmente como *caché*. Si una consulta a nuestra base de datos tarda mucho, guardamos el resultado en Redis para que la próxima vez la respuesta sea instantánea. También es muy usada para manejar sesiones de usuario.
* **Beneficio:** Es un estándar en la industria para optimización de rendimiento.
* **Enlace:** [https://redis.io/](https://redis.io/)

---

## Pruebas de API

Cuando construimos un backend, creamos "endpoints" (URLs) que el frontend consumirá. Estas herramientas nos sirven para probar que esos endpoints funcionen como esperamos.

### Postman
Es la herramienta estándar de la industria para probar, documentar y compartir APIs.

* **Cómo nos sirve:** Nos permite enviar peticiones (GET, POST, PUT, DELETE) a nuestros endpoints, guardar colecciones de peticiones, crear variables de entorno (para *dev* y *prod*) y generar documentación automática.
* **Beneficio:** Tiene un plan gratuito muy completo.
* **Enlace:** [https://www.postman.com/](https://www.postman.com/)

### Insomnia
Es una alternativa más ligera y con una interfaz más limpia que Postman.

* **Cómo nos sirve:** Hace lo mismo (probar APIs), pero muchos lo prefieren por su simplicidad y su excelente integración nativa con GraphQL.
* **Beneficio:** Gratuito y de código abierto.
* **Enlace:** [https://insomnia.rest/](https://insomnia.rest/)

---

## Compartir localhost y mock de datos

Utilidades para mostrar nuestro trabajo sin desplegar y para simular APIs.

### NGROK
Es una herramienta que crea un "túnel" seguro desde nuestra computadora (localhost) a una URL pública en internet.

* **Cómo nos sirve:** Es genial para mostrarle el avance de un proyecto a un cliente o profesor sin tener que desplegarlo. También es esencial para probar *webhooks* (cuando un servicio externo necesita conectarse a nuestra app).
* **Beneficio:** Tiene un plan gratuito que es suficiente para la mayoría de los casos.
* **Enlace:** [https://ngrok.com/](https://ngrok.com/)

### Mockoon
Es una herramienta para crear servidores de "mock" (falsos) de APIs de forma muy rápida y local.

* **Cómo nos sirve:** Si el equipo de *frontend* necesita empezar a trabajar pero el *backend* aún no termina la API, podemos usar Mockoon para simular la respuesta (ej. un JSON de usuarios) y que el *frontend* pueda avanzar sin bloqueos.
* **Beneficio:** Gratuito y de código abierto.
* **Enlace:** [https://mockoon.com/](https://mockoon.com/)

---

**[< Volver a Herramientas](../herramientas-utiles.html)**

**[< Volver al Inicio](../)**