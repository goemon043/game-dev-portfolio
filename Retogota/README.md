# 💧 Reto Gota

<div align="center">
  <img src="assets/screenshot.png" alt="Captura de Reto Gota" width="80%">
  <br>
  <em>¡Cada gota cuenta! Ayuda a Gustavo a no desperdiciar agua.</em>
</div>

---

## 📖 Descripción
**Reto Gota** es un juego de precisión y timing (ritmo) con un fuerte mensaje educativo sobre el cuidado del agua. El jugador acompaña a Gustavo en 8 situaciones cotidianas donde debe detener el flujo de agua en el momento exacto para alcanzar la cantidad necesaria, ni una gota más.

### 🎯 Objetivo del Jugador
Completar los 8 niveles deteniendo el llenado del recipiente exactamente cuando el contador llegue a los litros objetivo, maximizando la precisión para obtener 3 estrellas en cada nivel.

### 🎮 Mecánica Principal
- El agua sube automáticamente a diferentes velocidades según la situación.
- El jugador debe observar la barra de progreso y hacer clic (o tocar en móvil) en el momento preciso.
- El juego evalúa la precisión: si te pasas o no llegas, pierdes el nivel o obtienes menos estrellas.
- Incluye efectos visuales de gotas cayendo, salpicaduras y partículas de celebración.

## 🏷️ Género
`Timing` | `Precision` | `Educativo` | `Casual`

## 🎮 Controles
- **MOUSE CLICK** o **TOUCH (Móvil)**: Detener el flujo de agua.
- **Botones en pantalla**: Navegación por menús (Jugar, Mapa de niveles, Reintentar).

## 📊 Mapa de Niveles

| Nivel | Escenario | Objetivo | Velocidad | Consejo de Gustavo |
|:---:|:---|:---:|:---:|:---|
| **1** | 🥛 El vaso | 1 L | 🟢 Muy lenta | Detén el grifo apenas tengas lo necesario. |
| **2** | 🚿 La ducha | 35 L | 🟡 Media | Una ducha más corta ahorra mucha agua. |
| **3** | 🔧 La fuga | 15 L | 🟡 Media | Detectar y reparar fugas es clave. |
| **4** | 👕 La lavadora | 50 L | 🔴 Rápida | Una carga bien organizada evita usar agua de más. |
| **5** | 🍽️ La cocina | 12 L | 🟢 Lenta | Cierra el grifo mientras no lo uses. |
| **6** | 🌱 Regar la planta | 5 L | 🟢 Lenta | La planta no necesita que dejemos correr el agua. |
| **7** | 🚲 Lavar la bici | 15 L | 🟡 Media | No mantengas la manguera abierta mientras limpias. |
| **8** | 💧 Gran desafío | 60 L | 🔥 Extrema | ¡Controla cada gota! Ya aprendiste a ahorrar. |

## ⭐ Sistema de Puntuación y Precisión

El juego evalúa qué tan cerca estuviste del objetivo (`target`):

| Precisión | Estrellas | Puntos | Mensaje |
|-----------|:---:|:---:|:---|
| **98% - 100%** (Diferencia ≤ 2%) | ⭐⭐⭐ | +100 | 🎉 ¡PERFECTO! |
| **92% - 97%** (Diferencia ≤ 8%) | ⭐⭐ | +70 | 😃 ¡MUY BIEN! |
| **70% - 115%** | ⭐ | +35 | 👍 ¡LO LOGRASTE! |
| **< 70%** | ☆ | +10 | 💧 ¡FALTÓ AGUA! |
| **> 115%** | ❌ | 0 | 😱 ¡TE PASASTE! (Game Over del nivel) |

*Nota: El progreso (estrellas y puntos) se guarda automáticamente en el `localStorage` del navegador.*

## 💻 Tecnologías Utilizadas
- **HTML5** - Estructura semántica y contenedores del juego.
- **CSS3** - Diseño responsive, animaciones complejas (`@keyframes` para gotas, salpicaduras, partículas y flotación), gradientes y sombras.
- **JavaScript (Vanilla)** - Lógica de temporizadores (`setInterval`), cálculo de precisión en tiempo real, manipulación del DOM y persistencia de datos (`localStorage`).
- **Pixel Art** - Sprites del personaje y fondos generados con asistencia de IA y adaptados manualmente.

### 🤖 Uso de IA
- Generación de conceptos base para los sprites del personaje (Gustavo) y fondos de escenarios.
- Optimización de funciones de cálculo de precisión y generación de partículas visuales.
- Asistencia en la estructuración de la lógica de estados del juego (menú, juego, resultado).

## 🧠 Aprendizajes y Mejoras

### ✅ Qué aprendí
- Implementación de mecánicas de **timing preciso** con evaluación de márgenes de error.
- Uso de **`localStorage`** para crear un sistema de progreso persistente (niveles desbloqueados, estrellas, puntos).
- Creación de **sistemas de partículas** con JavaScript puro y animaciones CSS para feedback visual (celebración al ganar).
- Diseño de interfaces **responsive** que funcionan tanto en escritorio como en dispositivos móviles (touch events).
- Gestión de múltiples estados de UI (pantalla de inicio, mapa de niveles, consejos, gameplay, resultados).

### 🔧 Aspectos a mejorar
- **Audio:** Implementar la Web Audio API para agregar efectos de sonido (agua corriendo, gotas, clic, celebración) y música ambiental.
- **Gameplay:** Agregar un modo "Contrarreloj" o desafíos aleatorios una vez completados los 8 niveles.
- **Visual:** Transiciones más suaves (fade in/out) entre el mapa de niveles y el gameplay.
- **Accesibilidad:** Opción para aumentar el tamaño de la zona segura (safe zone) para jugadores con dificultades motoras.

## 🌍 Impacto Educativo
Cada nivel incluye un **"Consejo de Gustavo"** y un mensaje post-nivel que refuerza hábitos reales de ahorro de agua:
- Cerrar el grifo al lavarse los dientes o enjabonarse.
- Detectar fugas invisibles en el hogar.
- Usar la cantidad justa de agua para regar o limpiar.
- La importancia de cada litro en el contexto global del cuidado del planeta.

---
[⬅ Volver al Portafolio Principal](../README.md)
