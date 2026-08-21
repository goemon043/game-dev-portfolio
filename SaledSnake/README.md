# 🥗 SaledSnake

<div align="center">
  <img src="assets/screenshot.png" alt="Captura de SaledSnake" width="80%">
  <br>
  <em>¡La serpiente saludable que enseña a comer bien!</em>
</div>

---

## 📖 Descripción
**SaledSnake** es una versión educativa del clásico juego Snake donde controlas una serpiente que debe alimentarse exclusivamente de comida saludable para crecer y llegar a 35 puntos. 

### 🎯 Objetivo del Jugador
Alcanzar **35 puntos** comiendo alimentos saludables (frutas y verduras) mientras esquivas la comida chatarra que aparece como obstáculo cada 5 alimentos consumidos.

### 🎮 Mecánica Principal
- La serpiente se mueve automáticamente en la dirección que indiques
- Come alimentos saludables 🍎🍌 para ganar puntos y crecer
- **Cada 5 alimentos saludables**, aparecen **3 obstáculos de comida chatarra** 🍔🍭
- Si chocas contra la comida chatarra, las paredes o ti mismo, pierdes una vida
- Tienes **3 vidas** para llegar a la meta

## ️ Género
`Snake` | `Arcade` | `Educativo` | `Casual`

## 🎮 Controles
- **W**: Mover hacia arriba ️
- **S**: Mover hacia abajo ⬇️
- **A**: Mover hacia la izquierda ⬅️
- **D**: Mover hacia la derecha ➡️

## 📊 Sistema de Progresión

| Acción | Efecto |
|--------|--------|
| 🍎 Comer alimento saludable | +1 punto, crece la serpiente |
| 🍔 Chocar con comida chatarra | -1 vida |
| 🧱 Chocar con pared | -1 vida |
| 🐍 Chocar contigo mismo | -1 vida |
| ✅ Cada 5 alimentos | Aparecen 3 obstáculos de chatarra |
| 🏆 Llegar a 35 puntos | ¡Victoria! |

## 🎨 Elementos del Juego

### Alimentos Saludables (Objetivo)
 🍌 🍓  🍇 🥑 🍅
- Aparecen aleatoriamente en el tablero
- Dan 1 punto cada uno
- Hacen crecer a la serpiente

### Comida Chatarra (Obstáculos)
🍔 🍕 🍭  🌭 🍿
- Aparecen cada 5 alimentos saludables consumidos
- Son obstáculos fijos que debes evitar
- Si las tocas, pierdes una vida

##  Tecnologías Utilizadas
- **HTML5 Canvas** - Renderizado del juego y gráficos
- **CSS3** - Diseño responsive, animaciones y estilos
- **JavaScript (Vanilla)** - Lógica completa del juego
- **Emojis universales** - Para representar alimentos
- **Canvas API** - Dibujo de la serpiente con ojos animados

### 🤖 Uso de IA
- Generación de código base para la mecánica Snake
- Optimización del sistema de colisiones
- Asistencia en la lógica de spawn de obstáculos progresivos
- Mensajes educativos sobre nutrición

## 🧠 Aprendizajes y Mejoras

### ✅ Qué aprendí
- Implementación de la **mecánica clásica Snake** con crecimiento progresivo
- Sistema de **obstáculos dinámicos** que aparecen según el progreso
- **Detección de colisiones** múltiple (paredes, uno mismo, obstáculos)
- Gestión de **estados de juego** (menu, playing, gameover, victory)
- **Dibujo en Canvas** con formas redondeadas y emojis
- Sistema de **vidas** con reinicio de posición
- **Mensajes educativos rotativos** sin interrumpir el gameplay
- Animación de **ojos de la serpiente** según la dirección

### 🔧 Aspectos a mejorar
- **Audio:** Agregar efectos de sonido al comer (saludable vs chatarra) y música de fondo
- **Visual:** Efectos de partículas al comer, animación de "morder" de la serpiente
- **Gameplay:** Sistema de power-ups temporales (velocidad, invencibilidad)
- **Contenido:** Más niveles de dificultad, modo infinito sin meta de 35 puntos
- **UI:** Animaciones más suaves en las transiciones de pantalla
- **Mecánica:** Que la comida chatarra se mueva lentamente por el tablero

## 🌍 Impacto Educativo

El juego incluye **16 mensajes educativos rotativos** que enseñan:

### ✅ Beneficios de alimentos saludables:
- La fruta es energía natural
- Zanahorias mejoran la vista
- Naranjas tienen vitamina C
- Uvas tienen antioxidantes
- Sandía hidrata
- Aguacate tiene grasas saludables
- Tomate es rico en licopeno
- Plátano da energía
- Fresas son ricas en vitamina C

### ❌ Riesgos de comida chatarra:
- La chatarra te pone lento
- Papas fritas tienen mucha grasa
- Dulces en exceso dañan dientes
- Refrescos tienen mucha azúcar
- Pizza en exceso no es saludable
- Embutidos tienen mucho sodio
- Palomitas de microondas tienen mucha sal

## 📈 Progresión de Dificultad

La dificultad aumenta **automáticamente**:
- **Inicio:** Tablero vacío, solo comida saludable
- **Puntos 5, 10, 15...:** Aparecen 3 obstáculos de chatarra
- **Puntos 30+:** El tablero está casi lleno de obstáculos
- **Meta:** Llegar a 35 esquivando todos los obstáculos

---
[⬅ Volver al Portafolio Principal](../README.md)
