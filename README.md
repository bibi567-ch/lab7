# Laboratorio 7 – HTML y CSS
Taller de Programación

## Prerrequisitos
- Cuenta en GitHub[](https://github.com/)
- Visual Studio Code instalado[](https://code.visualstudio.com/)
- Navegador Web

## Objetivo del laboratorio
- Crear páginas web básicas usando HTML y CSS.
- Hacer uso de los tags HTML básicos de texto, listas, enlaces, tablas, etc.
- Utilizar CSS para cambiar el estilo de los elementos HTML.
- Comprender el uso de selectores CSS.

## Parte I: Configuración del repositorio
Se creó este repositorio local en VS Code y se subió a GitHub. Se trabaja en la rama 'lab7-html-css' para este laboratorio.

## Parte II: HTML Básico
### 2. Archivo index.html
Se creó la estructura básica de HTML con explicaciones de etiquetas.

**¿Para qué sirven las siguientes etiquetas?**
- **DOCTYPE:** Declara el tipo de documento y la versión de HTML (ej. HTML5). Indica al navegador cómo interpretar el archivo.
- **html:** Etiqueta raíz que envuelve todo el documento HTML.
- **head:** Contiene metadatos como título, enlaces a CSS, etc. No se muestra en la página.
- **meta:** Proporciona metadatos como charset (codificación de caracteres) o viewport para móviles.
- **title:** Define el título de la página, que aparece en la pestaña del navegador.
- **body:** Contiene el contenido visible de la página.

Se abrió en el navegador y se vio la estructura básica.

**d. Cambio de lang a "es":** Al agregar `lang="es"` en <html>, el navegador interpreta el idioma como español, lo que afecta la corrección ortográfica, accesibilidad y SEO. No cambia visualmente la página, pero es buena práctica para internacionalización.

**e. Agregar tags en head:** Se agregaron <meta charset="UTF-8"> y <meta name="viewport" content="width=device-width, initial-scale=1.0">. Esto asegura que los caracteres especiales (como acentos) se muestren correctamente y que la página sea responsive en móviles. Sin ellos, podría haber problemas de codificación o zoom.

### 3. Archivo formulario.html
Se creó un formulario básico con inputs para nombre, email, etc.

### 4. Archivo tabla.html
Se creó una tabla simple con filas y columnas.

## Parte III: CSS
### 5. Archivos login.html y login-styles.css
Se creó un formulario de login con estilos CSS básicos (colores, centrado).

### 6. Tarea: card.html y card-styles.css
Se recreó una tarjeta (card) similar a las imágenes proporcionadas, con imagen, texto y estilos.

## Instrucciones de uso
- Clona el repo: `git clone [URL]`
- Abre en VS Code y usa Live Server para ver los HTML.