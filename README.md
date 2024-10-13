# Portafolio de Proyectos Web

Este proyecto tiene como objetivo principal mostrar un conjunto de proyectos de desarrollo web con una estructura interactiva y visualmente atractiva.

## Tabla de Contenidos

1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [Tecnologías Utilizadas](#tecnologías-utilizadas)
3. [Desafíos y Soluciones](#desafíos-y-soluciones)
4. [Instalación](#instalación)
5. [Uso](#uso)
6. [Créditos](#créditos)
7. [Licencia](#licencia)
8. [Badges](#badges)
9. [Cómo Contribuir](#cómo-contribuir)
10. [Pruebas](#pruebas)

## Descripción del Proyecto

Este proyecto es un portafolio interactivo que muestra varios proyectos web utilizando tecnologías HTML, CSS y frameworks adicionales. Los usuarios pueden visualizar proyectos individuales, acceder a descripciones detalladas y ver imágenes relevantes de cada proyecto.

- **Objetivo del proyecto**: Presentar de manera profesional y visualmente atractiva mis habilidades y proyectos en desarrollo web.
- **Funciones principales**: Cada proyecto tiene un modal que se abre al hacer clic, mostrando más detalles e imágenes del proyecto. Además, los proyectos tienen un efecto hover interactivo.
- **Futuras funcionalidades**: Posible integración de un formulario de contacto completo y soporte para múltiples idiomas.

## Tecnologías Utilizadas

Este proyecto fue desarrollado utilizando las siguientes tecnologías:

- **HTML5**: Estructura semántica del contenido.
- **CSS3**: Estilos visuales, animaciones y diseño responsivo.
- **Grid y Flexbox**: Para el diseño de los layouts responsivos.
- **Frameworks**: Font Awesome para iconos.

## Desafíos y Soluciones

- **Desafío 1**: Crear modales para mostrar proyectos de manera interactiva sin utilizar JavaScript.
  - **Solución**: Utilización de pseudoclases `:target` y enlaces anclados en HTML para abrir y cerrar los modales, garantizando compatibilidad sin scripts.
  
- **Desafío 2**: Asegurar la visualización correcta de imágenes en pantallas de diferentes tamaños.
  - **Solución**: Aplicación de media queries y `object-fit` en las imágenes de la galería.

## Instalación

Sigue los siguientes pasos para instalar y ejecutar el proyecto en tu máquina local:

1. Clona este repositorio:
   git clone https://github.com/tu_usuario/portafolio_proyectos_web.git
Navega al directorio del proyecto:


2. Navega al directorio del proyecto:
    cd portafolio_proyectos_web

3. No hay dependencias adicionales requeridas.


## Uso
Una vez clonado el repositorio, simplemente abre el archivo index.html en tu navegador. No es necesario configurar ningún entorno adicional.

Para ver los diferentes proyectos, haz clic en "Proyectos" en el menú de navegación.

## Estructura del Proyecto
El proyecto sigue una estructura básica de carpetas:

bash
Copiar código
/assets
   /images         # Imágenes usadas en el proyecto
   /systemsimg     # Imágenes de los proyectos
/css
   /header.css     # Estilos del header y menú de navegación
   /projects.css   # Estilos específicos para los proyectos
/paginas
   /contact.html   # Página de contacto
index.html         # Página principal

## Créditos
Este proyecto fue desarrollado por Martin Rivas.


## Licencia
Este proyecto está licenciado bajo la MIT License.



## Cómo Contribuir
Si deseas contribuir a este proyecto, por favor sigue estos pasos:

1. Realiza un fork del repositorio.
2. Crea una rama para tu nueva característica (git checkout -b feature/nueva-caracteristica).
3. Realiza tus cambios y haz un commit (git commit -am 'Añadir nueva característica').
4. Sube tus cambios a tu rama (git push origin feature/nueva-caracteristica).
5. Abre un Pull Request.


## Pruebas
Aún no se han implementado pruebas formales para el proyecto, pero sería recomendable escribir tests unitarios para futuras actualizaciones. Puedes hacerlo utilizando frameworks como Jest para JavaScript (en caso de agregar funcionalidades con JavaScript).
