# Portafolio de Valentina Osorio Arenas
 
## Por qué esta estética
 
El diseño busca reflejar mi personalidad sin restarle seriedad al contenido técnico. Se eligió una estética **girly retro 2000s con toques 8-bit**, llevada a una versión más vibrante. Esto inspirado por la tendencia Cyberdeck, por estas razones:
 
- **Público y tono**: es un portafolio personal, no corporativo. La estética Y2K (colores saturados, degradados holográficos, botones "glossy") comunica cercanía y estilo propio sin sacrificar legibilidad.
- **Contraste entre pixel y contenido**: la tipografía `Press Start 2P` se usa solo en títulos y elementos de acento (nav, botones, contador), mientras que el cuerpo de texto usa `Baloo 2`, una fuente redondeada y legible. Así el 8-bit queda como firma visual, no como obstáculo para leer el contenido real.
- **Paleta vibrante controlada**: se trabajó con 4 colores base (rosa `#ff4fa3`, morado `#9b4de3`, turquesa `#22c7c2` y dorado `#ffcb3d`) sobre un fondo claro. Se evitó saturar todo el layout: el degradado fuerte solo aparece en el header y el footer, mientras que el resto de la página usa tonos suaves de esos mismos colores para no cansar la vista.
- **Formas y bordes**: bordes gruesos, esquinas redondeadas y sombras "duras" (offset, sin difuminado) imitan los botones y ventanas de interfaces de finales de los 2000s, reforzando el guiño retro sin caer en un diseño plano genérico.
- **Modo oscuro coherente**: la paleta oscura no es solo "invertir colores"; se ajustaron los tonos para mantener el mismo carácter vibrante pero sin quemar la vista en pantallas oscuras.
## Por qué estas funcionalidades
 
Las tres funcionalidades de JavaScript se eligieron porque son elementos característicos de las páginas personales de esa época, adaptados con buenas prácticas actuales:
 
1. **Botón de modo oscuro / claro (☀ / ☾)**
   Da control al visitante sobre su experiencia de lectura y demuestra manejo de manipulación del DOM y variables CSS. La preferencia se guarda en `localStorage` para que se mantenga si la persona vuelve a entrar.
2. **Mensaje sorpresa al hacer clic**
   Es un guiño directo a los "easter eggs" y mensajes de bienvenida típicos de los sitios personales de los 2000s. También sirve como ejemplo simple de manejo de eventos (`click`) y de mostrar/ocultar contenido dinámicamente.
3. **Contador de visitas**
   Es probablemente el elemento más icónico de esa era web: casi todo blog o página personal de los 2000s tenía un "hit counter". Aquí se recreó con estética de pantalla LCD y se implementó con `localStorage` para que el número persista entre visitas, mostrando manejo básico de almacenamiento en el navegador.