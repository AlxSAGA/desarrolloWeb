
# Formulario de Contacto con Estilo Degradado

![Preview](preview_labes.png)

Este proyecto implementa un formulario de contacto moderno con un diseño atractivo que utiliza un degradado de rojo intenso a negro, perfecto para sitios web con estilo audaz y contemporáneo.

## Características principales

- 🌈 Fondo degradado impactante (#ee0029 a #000)
- 🏷️ Etiquetas claras para cada campo del formulario
- ✉️ Validación integrada de email
- 📝 Área de texto con tamaño fijo optimizado
- 💾 Botón de envío con estilo minimalista
- ✨ Efectos de sombra y transparencia elegantes
- 📱 Diseño completamente responsive

## Uso

1. Clona el repositorio o descarga los archivos
2. Abre `index.html` en tu navegador web
3. Completa los campos:
   - Nombre de usuario
   - Correo electrónico
   - Comentarios o mensaje
4. Haz clic en el botón de envío

## Personalización

Puedes modificar fácilmente estos aspectos del diseño:

### Gradiente y colores (en style.css)
```css
body {
  background: linear-gradient(#ee0029, #000); /* Cambia los colores del degradado */
  color: #fff; /* Color del texto principal */
}

form {
  background-color: #0008; /* Color de fondo del formulario (con transparencia) */
  box-shadow: 0 0 35px 0 #0009; /* Sombra del formulario */
}
```

### Dimensiones y espaciado
```css
form {
  max-width: 50%; /* Ancho máximo del formulario */
  padding: 50px; /* Espaciado interno */
}

textarea {
  min-height: 200px; /* Altura mínima del área de texto */
}
```

### Tipografía
```css
h1 {
  text-transform: uppercase; /* Transformación de texto */
  letter-spacing: 5px; /* Espaciado entre letras */
}

.form-label {
  font-size: 20px; /* Tamaño de las etiquetas */
}
```

## Tecnologías utilizadas

- HTML5
- CSS3 (Gradientes, Sombras, Propiedades Responsive)
- Diseño Mobile-First

Este formulario es ideal para páginas de contacto, secciones de soporte al cliente, o cualquier interfaz que requiera recopilar información de usuarios con un diseño impactante y profesional.