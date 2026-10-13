<div align="center">

<img src="assets/banner.svg" width="100%" alt="Cristian Gutiérrez · Ingeniero de Sistemas"/>

<br>

Soy **Ingeniero de Sistemas**. Construyo productos digitales completos: interfaz, lógica de negocio y base de datos, con criterios de **UX/UI**.

<br>

<a href="https://github.com/cristianagutierrezalc"><img src="https://img.shields.io/badge/GitHub-111827?style=flat-square&logo=github&logoColor=white&label=Github"/></a>&nbsp;<a href="mailto:cristianagutierrez@unicesar.edu.co"><img src="https://img.shields.io/badge/Correo-111827?style=flat-square&logo=gmail&logoColor=38BDF8&label=Correo"/></a>&nbsp;<a href="https://www.instagram.com/Andressdev.ofic/"><img src="https://img.shields.io/badge/Instagram-111827?style=flat-square&logo=instagram&logoColor=E1306C&label=Andressdev.ofic"/></a>

</div>

<br>

---

## Sobre mí

Me interesa convertir necesidades reales en productos digitales que funcionen de verdad: claros para el usuario y Sostenibles en el tiempo. Trabajo con **desarrollo de escritorio y web, backend, bases de datos y diseño de interfaces**, normalmente cubro un proyecto completo, de la interfaz a la consulta SQL.

<table>
<tr>
<td valign="top" width="50%">

### Lo que construyo

* Aplicaciones de escritorio y web
* Interfaces y diseño de producto
* Frontend y backend
* Integración de servicios
* Herramientas internas con base de datos
* Sistemas multi-sede

</td>
<td valign="top" width="50%">

### En lo que me enfoco

* Experiencia de usuario
* Arquitectura de aplicaciones
* Modelado de datos y RLS
* Seguridad y control de acceso
* Soluciones que escalar con el tiempo
* Calidad: pruebas y documentación

</td>
</tr>
</table>

---

## Tecnologías

<div align="center">

<img src="https://skillicons.dev/icons?i=java,python,js,ts,react,postgres,supabase,html,css,fastapi,flask,firebase,maven,git&perline=7" alt="Tecnologías"/>

<br><br>

<img src="https://img.shields.io/badge/Java-17-111827?style=flat-square&logo=openjdk&logoColor=ED8B00&label=Java"/>
<img src="https://img.shields.io/badge/JavaFX-21-111827?style=flat-square&logo=java&logoColor=ED8B00&label=JavaFX"/>
<img src="https://img.shields.io/badge/Maven-111827?style=flat-square&logo=apachemaven&logoColor=C71A36&label=Maven"/>
<img src="https://img.shields.io/badge/PostgreSQL-111827?style=flat-square&logo=postgresql&logoColor=4169E1&label=PostgreSQL"/>
<img src="https://img.shields.io/badge/Supabase-111827?style=flat-square&logo=supabase&logoColor=3FCF8E&label=Supabase"/>
<img src="https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=3776AB&label=Python"/>
<img src="https://img.shields.io/badge/FastAPI-111827?style=flat-square&logo=fastapi&logoColor=009688&label=FastAPI"/>
<img src="https://img.shields.io/badge/Node.js-111827?style=flat-square&logo=nodedotjs&logoColor=5FA04E&label=Node.js"/>
<img src="https://img.shields.io/badge/React-111827?style=flat-square&logo=react&logoColor=61DAFB&label=React"/>
<img src="https://img.shields.io/badge/PL%2FpgSQL-111827?style=flat-square&logo=postgresql&logoColor=336791&label=PL%2FpgSQL"/>

</div>

---

## Proyectos

### 01 · GastroConnect

**Sistema de gestión de restaurantes multi-sede** · JavaFX + PostgreSQL

<img src="assets/pedidos-web.png" width="100%" alt="GastroConnect · Order Hub"/>

*Centro de pedidos web: aceptar, preparar y despachar los pedidos de todas las sedes en tiempo real.*

<table>
<tr>
<td align="center" width="50%" valign="top">

**Cupones y promociones**

<img src="assets/cupones.png" width="100%" alt="Módulo de cupones"/>

Descuento, compra mínima y usos por cliente, respetados en el total del pedido.

</td>
<td align="center" width="50%" valign="top">

**Acceso y seguridad**

<img src="assets/inicio-sesion.png" width="100%" alt="Inicio de sesión"/>

Inicio de sesión con roles, credenciales cifradas y sesión por sede.

</td>
</tr>
</table>

**Qué cubre hoy**

<table>
<tr>
<td valign="top" width="50%">

**APLICACIÓN DE ESCRITORIO**

* Java 17 + JavaFX 21, modular, con Maven
* Interfaz en FXML y CSS, rediseñada desde Figma
* Módulos: catálogo, inventario, pedidos, sedes,
  cupones, facturación y API por sede
* Empaquetado con `jpackage`: instalador de Windows
  que no requiere Java instalado
* Tema claro y oscuro

</td>
<td valign="top" width="50%">

**BASE DE DATOS**

* PostgreSQL en Supabase: 21 tablas, 10 vistas
  y una vista materializada de ventas diarias
* Aislamiento por tenant y por sede con RLS
* La lógica de cálculo vive en la base: totales,
  folios correlativos, descuento de stock y cupones
* 39 funciones de negocio y 74 políticas RLS
* 168 pruebas end-to-end sobre la base real

</td>
</tr>
</table>

**Stack:** Java · JavaFX · Maven · PostgreSQL · Supabase · RLS · PL/pgSQL

---

### 02 · Menú digital · Fuego & Carbón

**Publicado** · [Repositorio](https://github.com/cristianagutierrezalc/pagdemodev) · [API](https://github.com/cristianagutierrezalc/backend-fuego-carbon)

Menú digital para restaurante con frontend y API separados. El backend en FastAPI quedó como **única fuente de verdad**: antes el frontend mantenía su propia copia del catálogo y se desincronizaba.

**Stack:** Python · FastAPI · HTML · CSS · JavaScript

---

### 03 · Web Cotizador Dev

**Publicado** · [Repositorio](https://github.com/cristianagutierrezalc/Web-Cotizador-Dev)

Herramienta web para que una agencia o un desarrollador comparta un enlace con sus clientes y ellos mismos calculen una estimación de inversión, en pesos colombianos.

**Stack:** HTML · CSS · JavaScript

---

### 04 · Sistema PITA

**Proyecto académico** · [Repositorio](https://github.com/cristianagutierrezalc/Pita-Project)

Programa Integrado de Transacciones Académicas, taller de Estructura de Datos. Lógica de cálculo de nómina, matrículas y promedios, con interfaz gráfica en Tkinter y persistencia en archivos.

**Stack:** Python · Tkinter · Estructuras de datos

---

### 05 · Otros proyectos

<table>
<tr>
<td valign="top" width="50%">

**[Doce papelitos](https://github.com/cristianagutierrezalc/Pagina-De-Amor)**

Página personal en HTML, CSS y JavaScript.

</td>
<td valign="top" width="50%">

**[Cachetona](https://github.com/cristianagutierrezalc/programa-para-volver)**

Aplicación Flask con interfaz web y registro de interacciones.

</td>
</tr>
<tr>
<td valign="top" width="50%">

**[demopage](https://github.com/cristianagutierrezalc/demopage)**

Versión inicial del menú digital con API y frontend.

</td>
<td valign="top" width="50%">

**[Este perfil](https://github.com/cristianagutierrezalc/cristianagutierrezalc)**

Repositorios públicos y privados del proyecto.

</td>
</tr>
</table>

---

## Formación

Mi formación principal es la **Ingeniería de Sistemas**, y mantengo un proceso constante de actualización en áreas relacionadas con tecnología y desarrollo de software.

<table>
<tr>
<td valign="top" width="50%">

**CIBERSEGURIDAD**

* Fundamentos de Ciberseguridad

</td>
<td valign="top" width="50%">

**BASES DE DATOS**

* Database Foundations
* Data Programming with SQL
* Data Programming with PL/SQL

</td>
</tr>
</table>

El objetivo es complementar el desarrollo de software con conocimientos sólidos en **datos, seguridad y arquitectura tecnológica**.

---

## Cómo trabajo

Entender el problema antes de escribir código. Ese es el orden en el que avanza cada proyecto:

<table>
<tr>
<td align="center">Idea</td>
<td align="center">→</td>
<td align="center">Análisis</td>
<td align="center">→</td>
<td align="center">Requerimientos</td>
</tr>
<tr>
<td align="center">UX / UI</td>
<td align="center">→</td>
<td align="center">Arquitectura</td>
<td align="center">→</td>
<td align="center">Desarrollo</td>
</tr>
<tr>
<td align="center">Pruebas</td>
<td align="center">→</td>
<td align="center">Documentación</td>
<td align="center">→</td>
<td align="center">Mejora</td>
</tr>
</table>

La prioridad es construir soluciones que no solo funcionen, sino que sean **claras, mantenibles y preparadas para evolucionar**.

<table>
<tr>
<td align="center" width="25%">

### Claridad

Código y estructuras fáciles de comprender.

</td>
<td align="center" width="25%">

### Escalabilidad

Soluciones preparadas para crecer.

</td>
<td align="center" width="25%">

### Experiencia

Interfaces pensadas desde el usuario.

</td>
<td align="center" width="25%">

### Evolución

Mejora continua de cada solución.

</td>
</tr>
</table>

---

## Actividad en GitHub

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=cristianagutierrezalc&show_icons=true&hide_border=true&bg_color=0F172A&title_color=38BDF8&icon_color=0EA5E9&text_color=CBD5E1&include_all_commits=true&count_private=true" alt="Estadísticas de GitHub"/>

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=cristianagutierrezalc&layout=compact&hide_border=true&bg_color=0F172A&title_color=38BDF8&text_color=CBD5E1&langs_count=8" alt="Lenguajes más usados"/>

<br>

<img src="https://streak-stats.demolab.com?user=cristianagutierrezalc&hide_border=true&background=0F172A&ring=38BDF8&fire=0EA5E9&currStreakLabel=38BDF8&sideLabels=CBD5E1&dates=64748B" alt="Racha de contribuciones"/>

</div>

---

## Conectemos

Si quieres conocer mis proyectos, colaborar en una solución digital o hablar sobre desarrollo de software:

<div align="center">

<a href="mailto:cristianagutierrez@unicesar.edu.co"><img src="https://img.shields.io/badge/cristianagutierrez%40unicesar.edu.co-111827?style=flat-square&logo=gmail&logoColor=38BDF8&label=Correo"/></a>&nbsp;<a href="https://www.instagram.com/Andressdev.ofic/"><img src="https://img.shields.io/badge/@Andressdev.ofic-111827?style=flat-square&logo=instagram&logoColor=E1306C&label=Instagram"/></a>&nbsp;<a href="https://github.com/cristianagutierrezalc"><img src="https://img.shields.io/badge/cristianagutierrezalc-111827?style=flat-square&logo=github&logoColor=white&label=Github"/></a>

</div>

<br>

<img src="assets/onda.svg" width="100%" alt="Ingeniería · Desarrollo · Datos · Diseño"/>