---
layout: default
title: Despliegue y Alojamiento
---

---

**[< Volver a Herramientas](../herramientas-utiles.html)**

**[< Volver al Inicio](../)**

---

# Despliegue y Alojamiento

Ya terminamos nuestro proyecto, ¿ahora dónde lo subimos para que el mundo (o el profesor) lo vea? Esta es la etapa de despliegue.

El tipo de alojamiento que elijamos dependerá de nuestro proyecto: no es lo mismo subir un sitio de HTML y CSS que un backend complejo con una base de datos. Aquí vemos las opciones principales.

---

## VPS (Virtual Private Servers)

Un VPS es la opción de **control total**. Es como rentar una computadora virtual (generalmente con Linux) en la nube. Nosotros somos responsables de instalar y configurar todo: el servidor web (como Nginx o Apache), la base de datos, la seguridad, las actualizaciones, etc.

### DigitalOcean
Es uno de los VPS más populares entre desarrolladores por su simplicidad y su excelente documentación. Sus "Droplets" (así llaman a los VPS) se crean en segundos.

* **Cómo nos sirve:** Para proyectos serios de backend (Node, Python, Java), bases de datos, o cualquier aplicación que necesite un entorno personalizado y control total.
* **Beneficio:** El **GitHub Student Developer Pack nos da $200 USD de crédito** por un año.
* **Enlace:** [https://www.digitalocean.com](https://www.digitalocean.com)

### Linode
Es un competidor muy fuerte de DigitalOcean, ahora propiedad de Akamai. Es conocido por tener una excelente relación precio/rendimiento.

* **Cómo nos sirve:** Exactamente igual que DigitalOcean. Es una gran alternativa si queremos probar otro proveedor o si buscamos planes de cómputo más específicos.
* **Beneficio:** Suelen tener créditos de prueba para nuevos usuarios.
* **Enlace:** [https://www.linode.com](https://www.linode.com)

### Vultr
Otra alternativa muy popular, conocida por sus precios competitivos y por tener ubicaciones de servidores en muchísimas partes del mundo.

* **Cómo nos sirve:** Ideal si buscamos el mejor precio o si necesitamos que nuestro servidor esté físicamente cerca de nuestros usuarios en una región específica.
* **Beneficio:** Tienen planes muy económicos para empezar.
* **Enlace:** [https://www.vultr.com](https://www.vultr.com)

---

## PaaS (Platform as a Service)

Esta es la **ruta fácil**. En una "Plataforma como Servicio", nosotros no gestionamos el servidor. Solo subimos nuestro código (usualmente con un `git push`) y la plataforma se encarga de compilarlo, ejecutarlo, escalarlo y mantenerlo.

### Heroku
Es el PaaS clásico que popularizó este modelo. Es famoso por ser increíblemente fácil de usar para desplegar aplicaciones de Node.js, Ruby, Python, etc.

* **Cómo nos sirve:** Es perfecto para desplegar nuestros primeros proyectos de backend o APIs sin tener que pelearnos con la configuración de un VPS.
* **Beneficio:** El **GitHub Student Pack nos da créditos** (anteriormente "Dyno-hours") para nuestros proyectos.
* **Enlace:** [https://www.heroku.com](https://www.heroku.com)

### Railway
Es el "sucesor espiritual" de Heroku. Es una plataforma moderna que ha ganado muchísima popularidad por su simplicidad.

* **Cómo nos sirve:** Es aún más fácil. Detecta el código en nuestro repositorio, lo despliega e incluso puede provisionar bases de datos (como PostgreSQL o Redis) con un clic.
* **Beneficio:** Tiene una capa gratuita muy generosa para proyectos pequeños.
* **Enlace:** [https://railway.app](https://railway.app)

---

## Hosting estático y Jamstack

Esta es la opción para nuestros proyectos de **frontend** (HTML/CSS, React, Vue, Svelte) y sitios estáticos (como este mismo). Son increíblemente rápidos, escalables y, por lo general, tienen capas gratuitas muy generosas.

### Vercel
Es la plataforma de los creadores de Next.js (uno de los frameworks de React más populares). Está 100% optimizada para el desarrollo frontend moderno.

* **Cómo nos sirve:** Conectamos nuestro repositorio de GitHub y cada vez que hacemos `git push`, Vercel lo despliega automáticamente. Nos da URLs de prueba por cada Pull Request.
* **Beneficio:** Su plan "Hobby" (gratuito) es súper generoso y perfecto para proyectos personales.
* **Enlace:** [https://vercel.com](https://vercel.com)

### Netlify
El competidor directo de Vercel y los pioneros del término "Jamstack".

* **Cómo nos sirve:** Funciona idéntico a Vercel. Es excelente para sitios estáticos y también maneja "serverless functions" (backend simple) de forma muy intuitiva.
* **Beneficio:** También tiene un plan gratuito muy generoso.
* **Enlace:** [https://www.netlify.com](https://www.netlify.com)

### Github Pages
El hosting estático integrado directamente en GitHub. Es lo que estamos usando para este sitio.

* **Cómo nos sirve:** Es perfecto para sitios de documentación, portafolios personales o páginas de proyectos. Se activa con un clic desde la configuración del repositorio.
* **Beneficio:** Totalmente gratuito.
* **Enlace:** [https://pages.github.com](https://pages.github.com)

### Neocities
Esta es una mención un poco diferente. Es el "Geocities" moderno, enfocado en la web creativa e independiente.

* **Cómo nos sirve:** Si solo queremos subir un `index.html` y algunos archivos CSS a la "antigua usanza" (arrastrando y soltando), sin Git. Es genial para experimentar.
* **Beneficio:** Gratuito para sitios simples.
* **Enlace:** [https://neocities.org](https://neocities.org)

---

**[< Volver a Herramientas](../herramientas-utiles.html)**

**[< Volver al Inicio](../)**