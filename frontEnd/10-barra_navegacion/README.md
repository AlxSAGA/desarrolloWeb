
# Barra de Navegación con Display: inline-block

![preview](nav.png)

Este proyecto demuestra la implementación de una barra de navegación utilizando las propiedades CSS `display: inline-block`, `display: block`, y `display: inline`. Es un ejemplo práctico de cómo estas propiedades afectan el diseño y comportamiento de los elementos en una interfaz de navegación.

## Características principales
- 🧩 **Implementación de display: inline-block**: Para crear elementos de navegación en línea con propiedades de bloque
- 🎨 **Diseño minimalista**: Paleta de colores azul (#209ad8) con acentos blancos
- ✨ **Efectos interactivos**: Estados hover para mejorar la experiencia de usuario
- 🧭 **Navegación intuitiva**: Elementos claramente diferenciados
- 🔘 **Botón especial**: Estilo diferenciado para el elemento de Login

## Conceptos CSS aprendidos

### Display: inline-block
```css
.nav__item {
  display: inline-block;
}
```
- Permite que los elementos `<li>` se muestren en línea (uno al lado del otro)
- Mantiene las propiedades de bloque (acepta width, height, padding, margin)

### Display: block
```css
.nav__list {
  margin: 0;
  text-align: center;
}
```
- El elemento `<ul>` es un bloque que ocupa todo el ancho disponible
- Permite centrar los elementos hijos con `text-align: center`

### Display: inline
```css
.nav__link {
  display: inline-block;
}
```
- Los enlaces se comportan como elementos en línea pero con propiedades de bloque
- Aceptan padding y mantienen el flujo en línea

## Uso
1. Clona el repositorio o descarga los archivos
2. Abre `index.html` en tu navegador web
3. Explora los diferentes estados de los elementos de navegación
4. Pasa el cursor sobre los elementos para ver los efectos hover

## Tecnologías utilizadas
- HTML5 (Estructura semántica)
- CSS3 (Display properties, Hover effects, Box model)
- Diseño centrado en la propiedad display

Este proyecto es ideal para desarrolladores que están aprendiendo sobre las propiedades de display en CSS y cómo aplicarlas para crear componentes de navegación efectivos y visualmente atractivos.