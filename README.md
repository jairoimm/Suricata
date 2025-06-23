# Proyecto Suricata

![Logo Suricata](assets/img/logo.png)

Este proyecto es una landing page responsiva para "Suricata", una empresa ficticia de productos alimenticios. El sitio web muestra una variedad de productos organizados en secciones, destacando información clave como descripciones y precios.

## Tabla de Contenidos

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Características](#características)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación y Uso](#instalación-y-uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Secciones del Sitio](#secciones-del-sitio)
- [Créditos](#créditos)
- [Licencia](#licencia)

## Descripción del Proyecto

"Suricata" es una página web estática diseñada para presentar y vender diversos productos alimenticios como colaciones, desayunos, bebidas, verduras, dulces y empanadas. La página está construida con un enfoque en la responsividad y una interfaz de usuario limpia, utilizando Bootstrap para un diseño adaptable.

## Características

* **Diseño Responsivo:** Adaptable a diferentes tamaños de pantalla (móviles, tabletas, escritorios) gracias a Bootstrap.
* **Navegación Intuitiva:** Barra de navegación superior con enlaces a las secciones principales.
* **Catálogo de Productos:** Presentación clara de los productos con imágenes, descripciones, precios y botones de acción ("ver más", "comprar").
* **Iconos de Medios de Pago:** Sección en el footer mostrando los métodos de pago aceptados (Visa, MasterCard, Amex, Diners Club, PayPal, Discover) utilizando Font Awesome.
* **Estilo Moderno:** Uso de fuentes de Google Fonts (Open Sans, Raleway) y colores distintivos.

## Tecnologías Utilizadas

* **HTML5:** Estructura del contenido de la página.
* **CSS3:** Estilos personalizados (`assets/css/style.css`) para el diseño y la presentación.
* **Bootstrap 5.3.3:** Framework CSS para el diseño responsivo, componentes de navegación y tarjetas.
* **Font Awesome 6.5.2:** Librería de iconos utilizada para los logos de las tarjetas de crédito.
* **Google Fonts:** Fuentes "Open Sans" y "Raleway" para la tipografía.

## Instalación y Uso

Para visualizar este proyecto localmente, sigue los siguientes pasos:

1.  **Clona el repositorio** (si el proyecto está en Git) o **descarga los archivos** del proyecto.
    ```bash
    git clone <URL_DEL_REPOSITORIO>
    ```
2.  **Abre el archivo `index.html`** en tu navegador web preferido. No se requiere ningún servidor web adicional, ya que es una aplicación puramente de frontend.

## Estructura del Proyecto

├── assets/
│   ├── css/
│   │   └── style.css       # Archivo de estilos CSS personalizados
│   └── img/
│       ├── logo.png        # Logo principal de Suricata
│       ├── logo-footer.png # Logo para el pie de página
│       ├── bebidas.jpg
│       ├── colaciones.jpg
│       ├── desayunos.jpg
│       ├── dulces.jpg
│       ├── empanadas.jpg
│       └── verduras.jpg
└── index.html              # Archivo principal HTML

## Secciones del Sitio

* **Header (`#cabeza`):** Contiene el logotipo de Suricata y una barra de navegación responsiva.
* **Sección de Productos 1 (`#sectprod1`):** Muestra "Nuestros Productos" con tarjetas para Colaciones, Desayunos y Bebidas.
* **Sección de Productos 2 (`#sectprod2`):** Muestra "Más Productos" con tarjetas para Verduras, Dulces y Empanadas.
* **Footer de Medios de Pago (`#foot1`):** Visible solo en pantallas grandes, muestra los logos de las tarjetas de crédito aceptadas.
* **Footer Principal (`#foot2`):** Contiene el logo de Suricata en el pie de página.

## Créditos

* Diseño y desarrollo: Jairo Muñoz Muñoz
* Iconos: [Font Awesome](https://fontawesome.com/)
* Framework CSS: [Bootstrap](https://getbootstrap.com/)
* Fuentes: [Google Fonts](https://fonts.google.com/)
