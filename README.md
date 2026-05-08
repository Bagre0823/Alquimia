# Alquimia
Landig de licores artesanales
Descripción
Somos un emprendimiento familiar dedicado a la elaboración de licores frutales artesanales, como el lemoncello, a partir de una receta tradicional.
Nuestros productos se realizan de forma casera, con ingredientes naturales y mucho cuidado en cada paso.
________________________________________
Nuestra idea
Buscamos que cada persona que pruebe nuestros licores pueda disfrutar de un sabor auténtico, pensado para compartir y disfrutar en buenos momentos.

Proceso de desarrollo (Paso a paso)
1. Estructura inicial (HTML)
Se comenzó armando la estructura base del sitio con HTML:
•	Definición del header con logo, título y navegación.
•	Creación de secciones principales:
o	Introducción
o	Productos (cards)
o	Recursos (contenido educativo)
o	Footer
•	Uso de etiquetas semánticas como <header>, <section> y <footer> para mejorar la organización.
También se integraron recursos externos:
•	Bootstrap para el menú responsive.
•	Google Fonts para tipografías.
•	Font Awesome para íconos.
________________________________________
2. Estilos iniciales (CSS)
Se trabajó con un archivo CSS externo para separar estructura de diseño.
Se aplicaron:
•	Reset básico (* { margin:0; padding:0; })
•	Estilos generales para body, h2, p
•	Definición de tipografías personalizadas (@font-face)
________________________________________
3. Header y navegación
Primero se intentó un menú tradicional con listas (ul), pero luego se optó por:
•	Implementar Bootstrap Navbar
•	Agregar menú hamburguesa para dispositivos móviles
•	Lograr un diseño más adaptable sin reinventar la rueda
________________________________________
4. Uso de Flexbox 
Acá estuvo uno de los mayores aprendizajes.
•	Se utilizó display: flex en varios contenedores:
o	Header
o	Cards de productos
•	Se aplicaron propiedades como:
o	justify-content
o	align-items
o	flex-wrap
Esto permitió resolver problemas de alineación que en la primera versión del proyecto no se podían manejar bien.
________________________________________
5. Sección de productos
Se crearon tarjetas reutilizables con:
•	Imagen
•	Título
•	Descripción
•	Botón
Mejoras aplicadas:
•	Uso de flex-direction: column
•	flex-grow para empujar el botón hacia abajo
•	Estilos consistentes para todas las cards
________________________________________
6. Manejo de medidas y unidades
Se trabajaron distintos tipos de unidades:
•	Absolutas (px)
•	Relativas (rem, %)
•	Responsive (vw, clamp())
Esto permitió entender mejor cómo se adapta el contenido a distintos dispositivos.
________________________________________
7. Responsive Design 
Se implementaron media queries:
@media (max-width: 768px)
Cambios importantes:
•	Ocultar imagen derecha del header
•	Ajustar tamaños de texto
•	Cambiar cards a formato vertical
•	Mejorar la legibilidad en pantallas chicas
________________________________________
8. Imágenes
•	Se intentó trabajar con Photoshop, pero no siempre se lograron los resultados esperados.
•	Se recurrió a inteligencia artificial para generar o mejorar imágenes.
•	Esto ayudó a mantener una estética más uniforme.
________________________________________
9. Investigación y aprendizaje
Durante todo el desarrollo se investigó constantemente:
•	Uso intensivo de W3Schools
•	Búsqueda de ejemplos reales
•	Pruebas de código
•	Ajustes iterativos
También se exploraron:
•	Menús desplegables
•	Navbar responsive
•	Diseño adaptable
________________________________________
10. Iteraciones del código
El proyecto no salió perfecto desde el inicio:
•	El código se modificó varias veces
•	Se probaron distintas soluciones
•	Se descartaron enfoques iniciales
Esto fue clave para mejorar el resultado final.
________________________________________
Tecnologías utilizadas
•	HTML5
•	CSS3
•	Bootstrap 5
•	Google Fonts
•	Font Awesome
________________________________________
Conclusión
Un proyecto simple, pero muy útil para consolidar bases.
Flexbox fue un antes y un después en la forma de encarar el layout.
Y como siempre: prueba, error… y aprendizaje constante.
