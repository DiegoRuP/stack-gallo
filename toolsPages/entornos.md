---
layout: default
title: Entornos de Desarrollo
---

---

**[< Volver a Herramientas](../herramientas-utiles.html)**

**[< Volver al Inicio](../)**

---

# Entornos de Desarrollo

Estas son las herramientas que usamos todos los días para escribir, probar y guardar nuestro código. Configurar un buen entorno de desarrollo es clave para ser más productivos y no frustrarnos en el proceso.

Aquí cubrimos desde el editor donde escribimos, hasta el sistema que usamos para guardar nuestros cambios y colaborar.

---

## Editores de código e IDEs

Esta es nuestra herramienta principal. Un "Editor de Código" (como VS Code) es ligero y lo personalizamos con extensiones. Un "IDE" (Entorno de Desarrollo Integrado, como JetBrains) es más pesado pero ya trae todo incluido (debugger, compilador, etc.).

### VS Code (Visual Studio Code)
Es el estándar de la industria. Es un editor de código ligero pero increíblemente potente, desarrollado por Microsoft.

* **Cómo nos sirve:** Su fortaleza son las extensiones. Podemos adaptarlo para cualquier lenguaje (Python, Web, C++, Java, R). Tiene una terminal integrada, un debugger excelente y se integra perfecto con Git.
* **Beneficio:** Es 100% gratuito y de código abierto.
* **Enlace:** [https://code.visualstudio.com/](https://code.visualstudio.com/)

### Cursor
Es un "fork" (una versión modificada) de VS Code, diseñado para ser nativo de IA.

* **Cómo nos sirve:** Es básicamente VS Code con esteroides de IA. Nos permite chatear con toda nuestra base de código, generar código de forma más avanzada y "preguntarle" cosas a nuestros archivos. Es como tener Copilot integrado en el editor.
* **Beneficio:** Tiene una capa gratuita generosa.
* **Enlace:** [https://cursor.sh/](https://cursor.sh/)

### Windsurf
Es otro editor de código nuevo, también enfocado 100% en el desarrollo asistido por IA.

* **Cómo nos sirve:** Similar a Cursor, está diseñado desde cero para ayudarnos a entender y escribir código complejo usando IA. Es una de las herramientas de nueva generación que vale la pena probar.
* **Beneficio:** (Generalmente tienen planes gratuitos o de prueba).
* **Enlace:** [https://windsurf.dev/](https://windsurf.dev/)

### JetBrains
No es un solo IDE, es la *compañía* que hace los IDEs más potentes y especializados del mercado.

* **Cómo nos sirve:** Usamos el IDE específico para nuestro lenguaje: `IntelliJ IDEA` (para Java/Kotlin), `PyCharm` (para Python), `WebStorm` (para JavaScript/TypeScript), `CLion` (para C/C++), etc. Son pesados, pero su análisis de código, refactorización y autocompletado son inigualables.
* **Beneficio:** ¡Son **totalmente gratis para estudiantes**! Solo necesitamos verificar nuestro correo institucional.
* **Enlace:** [https://www.jetbrains.com/community/education/](https://www.jetbrains.com/community/education/)

### Neovim / Vim
Es un editor de código legendario que funciona 100% dentro de la terminal. Neovim es un *fork* moderno de Vim.

* **Cómo nos sirve:** Tiene una curva de aprendizaje alta, pero una vez que dominamos sus comandos (keybindings), podemos editar código a una velocidad increíble sin tocar el mouse. Es esencial para cuando nos conectamos por SSH a un servidor.
* **Beneficio:** Gratuitos, de código abierto y extremadamente rápidos.
* **Enlace:** [https://neovim.io/](https://neovim.io/)

---

## Control de versiones

Es el sistema que usamos para guardar "fotos" (snapshots o commits) de nuestro proyecto. Si algo se rompe, podemos "viajar en el tiempo" a una versión que sí funcionaba. Es la base de la colaboración.

### Git
Es el *sistema* de control de versiones. Es la herramienta de línea de comandos (`git commit`, `git push`, `git pull`).

* **Cómo nos sirve:** Es el motor que corre por debajo. Es fundamental aprender sus comandos básicos, ya que todas las plataformas (GitHub, GitLab) se basan en él.
* **Beneficio:** Gratuito, de código abierto y el estándar mundial.
* **Enlace:** [https://git-scm.com/](https://git-scm.com/)

### Github
Es la *plataforma social* o servicio en la nube donde alojamos nuestros repositorios de Git.

* **Cómo nos sirve:** Aquí es donde creamos Pull Requests, revisamos el código de nuestros compañeros, gestionamos proyectos y alojamos nuestra documentación (¡como este sitio!). Es nuestro portafolio profesional.
* **Beneficio:** Gratis para repositorios públicos y privados. (Y nos da el Student Pack).
* **Enlace:** [https://github.com/](https://github.com/)

### Gitlab
Es la competencia directa de GitHub. Es una plataforma "todo en uno".

* **Cómo nos sirve:** Ofrece todo lo de GitHub, pero su gran diferenciador es su CI/CD (Integración Continua / Despliegue Continuo) integrado, que muchos consideran más potente y flexible.
* **Beneficio:** Tiene una capa gratuita muy generosa.
* **Enlace:** [https://gitlab.com/](https://gitlab.com/)

---

## Terminales

Aunque los IDEs son visuales, la terminal sigue siendo la herramienta más rápida. Estas son versiones modernas que mejoran la terminal que viene con nuestro sistema operativo.

### Warp
Es una terminal moderna escrita en Rust. Es increíblemente rápida y reimagina cómo interactuamos con los comandos.

* **Cómo nos sirve:** Trata los comandos y sus salidas como "bloques" que podemos copiar y editar. Tiene autocompletado con IA integrado y menús para los comandos más comunes (como Git).
* **Beneficio:** Gratuita.
* **Enlace:** [https://www.warp.dev/](https://www.warp.dev/)

### Termius
Es un cliente SSH multiplataforma, más que solo una terminal.

* **Cómo nos sirve:** Su fortaleza es si gestionamos varios servidores (como nuestros VPS de DigitalOcean). Sincroniza nuestros hosts, claves SSH y configuraciones entre todos nuestros dispositivos (PC, laptop, celular).
* **Beneficio:** Tiene un plan gratuito. (El plan Pro está en el GitHub Student Pack).
* **Enlace:** [https://termius.com/](https://termius.com/)

---

## Clientes gráficos para Git

Los comandos de Git son potentes, pero a veces queremos *ver* el historial de ramas. Estas herramientas (GUIs) nos ayudan.

### GitKraken
Es uno de los clientes Git más potentes y visuales.

* **Cómo nos sirve:** Nos da una vista gráfica muy clara del árbol de ramas. Podemos hacer "drag and drop" para mergear, resolver conflictos de forma visual y entender qué está pasando en el proyecto.
* **Beneficio:** **Gratis para estudiantes** a través del GitHub Student Pack.
* **Enlace:** [https://www.gitkraken.com/](https://www.gitkraken.com/)

### SourceTree
Es el cliente Git gratuito de Atlassian (la misma compañía de Trello y Jira).

* **Cómo nos sirve:** Es una alternativa muy sólida y un poco más simple que GitKraken. Funciona muy bien, especialmente si en un futuro usamos Bitbucket (el "GitHub" de Atlassian).
* **Beneficio:** Gratuito (para Windows y Mac).
* **Enlace:** [https://www.sourcetreeapp.com/](https://www.sourcetreeapp.com/)

---

**[< Volver a Herramientas](../herramientas-utiles.html)**

**[< Volver al Inicio](../)**