# Diseña tu próximo paso

**TIC II · 2.º de Bachillerato · Curso 2026–2027**

## 1. ¿De qué trata el proyecto?

Este proyecto consiste en crear una página web para consultar y comparar diferentes grados universitarios y conocer algunas de sus salidas profesionales.

La web está pensada para ayudar a estudiantes que todavía no tienen claro qué carrera elegir. Para ello, se han seleccionado tres grados relacionados con la ingeniería:

- **Ingeniería Civil**
- **Ingeniería Aeroespacial**
- **Ingeniería Mecánica**

La idea es presentar la información de una forma visual y sencilla, para que se puedan comparar las opciones sin tener que consultar varias páginas diferentes.

## 2. Estructura de la web

El proyecto está dividido en tres páginas principales:

- **`index.html` – Página de inicio:** presenta el proyecto y permite acceder al resto de apartados.
- **`pag1.html` – Opciones universitarias:** muestra los tres grados, con una pequeña descripción de cada uno.
- **`pag2.html` – Comparación:** incluye una tabla para comparar las carreras y un apartado desplegable con información adicional.
- **`pag3.html` – Salidas profesionales:** presenta tres posibles salidas profesionales de cada grado mediante carruseles de imágenes y una breve explicación.

También hay una hoja de estilos común para mantener el mismo diseño en todas las páginas.

## 3. Archivos del proyecto

La organización de los archivos es la siguiente:

```text
PROYECTO/
│
├── index.html
├── pag1.html
├── pag2.html
├── pag3.html
│
├── css/
│   └── cositas.css
│
├── img1/
│   ├── imágenes
│   ├── iconos
│   └── vídeos
│
└── README.md
```

Para abrir la web no hace falta instalar ningún programa especial. Basta con descargar o clonar el repositorio y abrir el archivo `index.html` con un navegador.

## 4. Tecnologías utilizadas

Para desarrollar la página se han utilizado:

- **HTML5:** para organizar el contenido y crear la estructura de las páginas.
- **CSS3:** para personalizar los colores, tamaños, fondos, tarjetas, textos y otros elementos visuales.
- **Bootstrap 5.3.8:** para utilizar componentes como las tarjetas, los menús, los carruseles, las tablas y el menú lateral (*Offcanvas*).
- **GitHub:** para guardar el proyecto y registrar los cambios realizados durante su desarrollo.

Bootstrap se ha añadido mediante su CDN, por lo que no ha sido necesario descargar sus archivos.

## 5. Decisiones de diseño y desarrollo

Durante la creación de la web se tomaron algunas decisiones para conseguir que las páginas tuvieran un aspecto parecido y fueran fáciles de utilizar.

**Diseño común:** se utiliza una misma hoja CSS (`cositas.css`) para mantener los mismos estilos en las diferentes páginas y evitar repetir código.

**Vídeos de fondo:** se han utilizado vídeos en algunas páginas para darles un aspecto más visual. Se colocan detrás del contenido mediante CSS, utilizando `position` y `z-index`.

**Componentes de Bootstrap:** se han aprovechado componentes ya preparados, como los carruseles y el menú lateral, para organizar mejor la información y facilitar la navegación.

## 6. Fuentes de información

Para recopilar información sobre los estudios y las universidades se han consultado las siguientes páginas:

1. [Universidade da Coruña (UDC)](https://www.udc.es/)
2. [Universidade de Vigo (UVigo)](https://www.uvigo.gal/)
3. [CIUG – Comisión Interuniversitaria de Galicia](https://ciug.gal/)
4. [Bootstrap 5.3 – Documentación oficial](https://getbootstrap.com/docs/5.3/)
5. [Ingeniería Civil – Información universitaria](https://www.udc.es/)
6. [Ingeniería Aeroespacial – Universidade de Vigo](https://www.uvigo.gal/)

Las páginas universitarias y la CIUG se han utilizado como referencia para consultar información relacionada con los estudios y el acceso a la universidad. La documentación de Bootstrap se ha utilizado para resolver dudas sobre los componentes y su funcionamiento.

## 7. Imágenes, vídeos y créditos

Las imágenes utilizadas en la web proceden de diferentes páginas y bancos de imágenes. Se han guardado en la carpeta `img1` para poder utilizarlas desde los archivos HTML.

Estas son las direcciones originales de los recursos utilizados:

| Recurso | Procedencia |
|---|---|
| Fotografía de ingeniería civil | [iStock](https://media.istockphoto.com/id/513113394/es/foto/carretera-ingeniero-de.jpg?s=612x612&w=0&k=20&c=ERPO4ZZJgQgrjwylGZJNMn7_U71xhVFmEO7MZqPJCnU=) |
| Imagen de ingeniería | [FT CDN](https://t3.ftcdn.net/jpg/05/11/87/62/360_F_511876286_v7VoBeNHNrUkTyN5DvS71xhVp99XjA7I.jpg) |
| Imagen de ingeniería de sistemas | [SII Group](https://sii-group.com/sites/default/files/2026-02/Photo_SystemEngineering_800x534px_03.jpg) |
| Imagen de mantenimiento aeronáutico | [Formación Profesional](https://www.formacioprofesional.com/sites/default/files/styles/curs_area/public/2023-08/manteniment%20aerome.jpg.webp?h=d2cf675b&itok=tPBsE8li) |
| Imagen relacionada con aeronáutica | [Fly News](https://fly-news.es/wp-content/uploads/Supplier_Annouc_Evol.jpg) |
| Imagen utilizada en la web | [Google Imágenes – miniatura original](https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcSuSSppUOE-Z7ey0f_0hEvL5h5r5ttb7gGFnzF1CFGpyKy9ryeJ) |
| Imagen utilizada en la web | [Google Imágenes – miniatura original](https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcSSGIT3oaZowAUPLiqhjG7-asfu97mbgMYMiUbkKIyHrQUDc-7C) |
| Imagen utilizada en la web | [Google Imágenes – miniatura original](https://encrypted-tbn2.gstatic.com/images?q=tbn:ANd9GcQ4PZnZ-6ljfckh7DruGb9bjb_tAjIDmWyabg87FR5RcdP86VgL) |
| Lanzamiento del transbordador espacial | [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:STS120LaunchHiRes.jpg) |
| Fotografía de topografía | [iStock](https://media.istockphoto.com/id/