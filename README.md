# Biblioteca de Componentes UI con CSS Avanzado

Esta biblioteca contiene una colección de componentes de interfaz de usuario (UI) reutilizables, diseñados con **CSS avanzado**. El objetivo es facilitar el desarrollo de interfaces modulares, responsivas, accesibles y visualmente coherentes para sitios y aplicaciones web modernas.

## Características

- Componentes listos para usar
- Diseño modular y escalable
- CSS moderno (variables, grid, flexbox, animaciones)
- Adaptado a dispositivos móviles (responsive)
- Fácil integración en cualquier proyecto HTML/CSS

---

## Componentes Incluidos

- **Botones**: primario, secundario, deshabilitado, con efectos `:hover` y `:focus`.
- **Tarjetas**: con imagen, título, descripción y acción.
- **Formularios**: inputs, select, checkbox, textarea con validación visual.
- **Navbar**: menú responsivo con hamburguesa para móviles.
- **Modal**: ventana emergente con fondo opaco y animación.
- **Tooltip**: mensaje contextual al pasar el cursor.
- **Alertas**: mensajes de éxito, advertencia y error.
- **Acordeón**: secciones expandibles con transiciones suaves.

---

## Técnicas de CSS Avanzado Utilizadas

- `--Variables CSS` para definir colores, tipografías y espaciados.
- `Flexbox` y `Grid` para layouts flexibles.
- `Pseudo-clases` y `pseudo-elementos`: `:hover`, `:focus`, `::before`, etc.
- `Transiciones` y `animaciones` suaves para mejorar la UX.
- `Media Queries` para responsividad.
- Clases utilitarias y convención BEM para organización de estilos.

---

## Estructura del Proyecto

```
📦 ui-library/
├── 📁 components/
│   └── button.html
├── 📁 styles/
│   └── style.css
├── 📁 demo/
│   └── index.html
├── README.md
```

---

## Cómo Usar

1. Clona el repositorio o descarga los archivos.
2. En tu archivo HTML, enlaza el archivo CSS:

```html
<link rel="stylesheet" href="styles/style.css">
```

3. Usa los componentes en tu HTML. Por ejemplo, un botón:

```html
<button class="btn btn--primary">Enviar</button>
```

O una tarjeta:

```html
<div class="card">
  <img src="img/ejemplo.jpg" alt="Imagen">
  <h3 class="card__title">Título</h3>
  <p class="card__text">Descripción del contenido.</p>
  <button class="btn btn--secondary">Leer más</button>
</div>
```

---

## Capturas de Pantalla

> Puedes ver todas las capturas de pantalla en la carpeta `/demo` o en el PDF entregado.

- Modal abierto
- Navbar en versión móvil
- Tooltip visible
- Acordeón desplegado
- Formulario completo

---

## Referencias

- [CSS Variables - MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)
- [CSS Flexbox Guide - CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS Grid Guide - CSS Tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)
- [Media Queries - W3Schools](https://www.w3schools.com/css/css_rwd_mediaqueries.asp)

---

## Autor y Datos Académicos

**Estudiante:** Candy Fernanda Rengifo Rengifo  
**Profesor:** Enrique Macías Arias, Mtr.  
**Carrera:** Ingeniería en Tecnología de la Información  
**Universidad:** Universidad Técnica de Manabí  
**Fecha de entrega:** 10 de julio de 2025  
**Semestre:** Quinto

---

## Enlace al Proyecto

https://github.com/CandyRengifoRengifo/ui-components-css.git


---

## Licencia

Este proyecto puede ser usado con fines educativos o personales.  
