# 🐉 Interactive SVG Dragon Animation

Una impresionante animación interactiva y cinemática de un dragón desarrollada completamente con **HTML5, SVG nativo y JavaScript (Vanilla JS)**. El proyecto es una recreación y modernización (port) de un clásico efecto visual de la era de Flash, actualizado para la web moderna.

La estructura del dragón sigue dinámicamente el movimiento del cursor(mouse) mediante cálculos de trigonometría y física de seguimiento inversa (Inverse Kinematics), adaptando su escala y rotación de forma fluida.

## 🚀 Características

* **Gráficos Vectoriales Puros:** El cuerpo, la cabeza y las aletas están construidos utilizando elementos `<svg>` y gradientes dinámicos, lo que garantiza una nitidez absoluta en cualquier resolución.
* **Interactividad Fluida:** El dragón persigue de forma inteligente el cursor (`pointermove`) con un efecto de amortiguación (easing).
* **Movimiento Autónomo:** Si el usuario no interactúa, el dragón cuenta con un patrón de nado/vuelo automático basado en funciones trigonométricas sinusoidales.
* **Estructura Jerárquica:** El código segmenta dinámicamente los componentes de la criatura (Cabeza, Aletas y Espinas) a lo largo de 40 nodos interconectados.

## 🛠️ Tecnologías Utilizadas

* **HTML5** (Estructura semántica y contenedores)
* **CSS3** (Estilizado responsive a pantalla completa)
* **SVG** (`<defs>`, `<linearGradient>`, `<path>`, `<use>`)
* **JavaScript Moderno** (Estructura de renderizado con `requestAnimationFrame` y manipulación del DOM)
* **jQuery** (Cargado en el entorno base)

## 📜 Créditos
Basado originalmente en el arte e idea del clásico de Flash: **Dragon** por *GifHaas* en DeviantArt.
