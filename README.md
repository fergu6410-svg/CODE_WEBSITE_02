# La Máquina de Turing — Página Web Histórica

> Una página web profesional e interactiva sobre la historia de la Máquina de Turing, con animaciones avanzadas, efectos visuales y contenido educativo completo.

---

## Vista Previa

```
┌─────────────────────────────────────────────────┐
│  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░  │
│                                                  │
│   Historia de la Computación · 1936 — Presente  │
│                                                  │
│   La Máquina                                     │
│   de Turing                                      │
│                                       1936       │
│                                                  │
└─────────────────────────────────────────────────┘
```

---

## Características

### Animaciones
- **Preloader** con contador numérico animado 0→100 y barra de progreso con glow
- **Entrada de palabras** en el título con animación de resorte física por palabra
- **Zoom progresivo por sección** — cada sección escala al entrar en viewport
- **Parallax multi-velocidad** en el hero y banda de cita
- **Barra de progreso** de lectura en la parte superior de la pantalla

### Interacciones
- **Cursor personalizado** con anillo de seguimiento suavizado y expansión en links
- **Tilt 3D magnético** en el título del hero (responde al mouse con perspectiva)
- **Portrait con glitch** y corrección de perspectiva 3D en hover
- **Scramble de glifos matemáticos** en las cards de legado (∞, NP, AI → caracteres aleatorios)
- **Citas** que se deslizan horizontalmente al hacer hover
- **Filas de tabla** que avanzan con padding al hacer hover

### Efectos Continuos
- **Canvas de partículas** flotantes en el hero (60 partículas animadas)
- **Grilla de fondo animada** que se desplaza infinitamente
- **Diagrama de Máquina de Turing** interactivo con cabezal pulsante y estados cambiantes
- **Grilla de bits** que parpadea aleatoriamente en tiempo real
- **Ticker horizontal** de términos computacionales
- **Cinta de Turing** animada con cabezal indicador

### Contenido
- **Counters animados** que cuentan desde 0 hasta su valor real al entrar en vista
- **Cronología completa** 1912–2021 con animaciones de entrada por scroll
- **Tabla de transición** funcional de la máquina
- **6 cards de legado** con efecto de glitch matemático
- **Sección de Turing-completitud** con grilla de bits interactiva

---

## Estructura del Proyecto

```
turing-machine/
│
├── index.html          # Página principal (archivo único, sin dependencias)
└── README.md           # Este archivo
```

> El proyecto es un **archivo HTML autocontenido**. No requiere bundler, servidor ni dependencias npm. Solo abre `index.html` en un navegador moderno.

---

## Uso

### Opción 1 — Abrir directamente
```bash
# Clona el repositorio
git clone https://github.com/tu-usuario/maquina-de-turing.git

# Abre en el navegador
open turing-machine/index.html
# o en Windows:
start turing-machine/index.html
```

### Opción 2 — Servidor local (recomendado)
```bash
# Con Python
python3 -m http.server 8080

# Con Node.js
npx serve .

# Con VS Code
# Instala la extensión "Live Server" y haz clic en "Go Live"
```

### Opción 3 — GitHub Pages
1. Sube el repositorio a GitHub
2. Ve a **Settings → Pages**
3. Selecciona la rama `main` y carpeta raíz `/`
4. Tu página estará disponible en `https://tu-usuario.github.io/maquina-de-turing`

---

## Tecnologías

| Tecnología | Uso |
|------------|-----|
| **HTML5** | Estructura semántica |
| **CSS3** | Animaciones, Grid, Custom Properties, `@keyframes` |
| **Vanilla JavaScript** | Interactividad, Canvas API, IntersectionObserver |
| **Canvas API** | Sistema de partículas del hero |
| **Google Fonts** | Playfair Display · DM Mono · DM Sans |

> **Sin frameworks. Sin dependencias. Sin bundler.** Solo un archivo HTML de ~500 líneas.

---

## Contenido Cubierto

1. **§ 01 — Origen** — Vida y contexto histórico de Alan Turing
2. **§ 02 — Funcionamiento** — Diagrama interactivo con cinta, cabezal y tabla de transición
3. **§ 03 — Cronología** — 1912 a 2021, de Cambridge a Bletchley Park al billete de £50
4. **§ 04 — Legado** — Tesis Church-Turing, Complejidad, IA, von Neumann, λ-cálculo
5. **§ 05 — Universalidad** — Qué es la Turing-completitud y qué sistemas la cumplen

---

## Paleta de Colores

```css
--tape:         #1a1a2e   /* Fondo oscuro principal    */
--paper:        #f5f0e8   /* Fondo crema claro         */
--amber:        #c8841a   /* Color de acento principal */
--amber-light:  #e8a832   /* Acento suave              */
--ink:          #0d0d0d   /* Texto principal           */
```

---

## Compatibilidad

| Navegador | Soporte |
|-----------|---------|
| Chrome 90+ | Completo |
| Firefox 88+ | Completo |
| Safari 14+ | Completo |
| Edge 90+ | Completo |
| IE 11 | No soportado |

---

## Licencia

Este proyecto está bajo la licencia **MIT**. Puedes usarlo, modificarlo y distribuirlo libremente con atribución.

---

## Referencias

- Turing, A.M. (1936). *On Computable Numbers, with an Application to the Entscheidungsproblem*. Proceedings of the London Mathematical Society.
- Turing, A.M. (1950). *Computing Machinery and Intelligence*. Mind, 59(236), 433–460.
- Hodges, A. (1983). *Alan Turing: The Enigma*. Burnett Books.
- Sipser, M. (2012). *Introduction to the Theory of Computation* (3rd ed.). Cengage Learning.

---

<div align="center">

**"Solo podemos ver poco del futuro, pero lo suficiente para darnos cuenta de que hay mucho por hacer."**

*— Alan Turing, 1950*

</div>
