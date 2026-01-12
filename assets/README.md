# M3AE5 ABP5

---
## Gonzalo Román Reyes

## Ruta del repositorio:https://github.com/GRomanD3v/VerdeModa

## Nombre de la rama: feat/bootstrap-integration (el ejercicio se encuentra en está rama para compararlo con el anterior proyecto)
---

## Descripción General del Proyecto
Este proyecto es una interfaz web responsiva para "VerdeModa". Ha sido construida principalmente con Bootstrap 5 para la estructura y sus componentes, y SASS para una gestión modular y personalizada de los estilos.

### Problemas para instalar bootstrap y @popperjs/core
Necesitaba permisos de administrador y ejecuté el comando :
sudo chown -R 501:20 "/Users/estemac/.npm"
Luego de introducir mi contraseña pude instalar sin problemas bootstrap y @popperjs/core

###  Tecnologías Utilizadas

* HTML5: Estructura del contenido.
* SASS (SCSS): Preprocesador CSS para estilos modulares y personalización.
* Bootstrap 5: Framework CSS para diseño responsivo y componentes pre-construidos.
* npm: Gestor de paquetes para la instalación de dependencias.


### En header remplpacé por etiqueta nav:

* Usé el componente navbar de Bootstrap.
* Muestro el logo como navbar-brand.
* Agregué el botón colapsable (hamburguesa) para móviles.
* Alinea los links a la derecha (justify-content-end).

### integré bootstrap en navbar y navbar-collapse para el menú y nav-brand para el logo. También bootstrap para todo el main que contiene las cards del sitio. Además de dale estilos a _main.scss para cumplir con los requisitos del contenedor principal.

### Footer: Diseño simple implementado con clases de utilidad de Bootstrap.


### Responsividad:  El diseño es completamente responsivo, adaptándose a diferentes tamaños de pantalla gracias al enfoque mobile-first de Bootstrap 5 y el uso de sus clases de rejilla.
