# 🎸 EcoSprint - Through the Fire and Flames

<div align="center">
  <img src="assets/screenshot.png" alt="Captura de EcoSprint" width="80%">
  <br>
  <em>¡Clasifica residuos al ritmo de la dificultad creciente!</em>
</div>

---

## 📖 Descripción
**EcoSprint** es un juego de ritmo y timing estilo Guitar Hero donde el jugador debe clasificar residuos que caen por 4 carriles. Cuando los residuos llegan a la **zona amarilla de clasificación**, debes presionar la tecla correspondiente al contenedor correcto antes de que se pierdan.

### 🎯 Objetivo del Jugador
Sobrevivir 10 niveles de dificultad creciente clasificando correctamente residuos orgánicos, papel, plástico y materiales peligrosos, mientras evitas que la contaminación llegue al 100%.

### 🎮 Mecánica Principal
- Los residuos caen por 4 carriles verticales
- Cuando llegan a la **línea amarilla**, presiona la tecla correcta
- **A** = 🍎 Orgánico (verde)
- **S** = 📄 Papel (azul)
- **D** = 🥤 Plástico (amarillo)
- **F** = 🔋 Peligroso (rojo)

## 🏷️ Género
`Rhythm Game` | `Timing` | `Educativo` | `Arcade`

## 🎮 Controles
- **A**: Clasificar en contenedor Orgánico (carril 1)
- **S**: Clasificar en contenedor Papel (carril 2)
- **D**: Clasificar en contenedor Plástico (carril 3)
- **F**: Clasificar en contenedor Peligroso (carril 4)
- **ESC**: Pausar el juego

## 📊 Sistema de Niveles

| Nivel | Velocidad | Frecuencia | Máx. Residuos | Dificultad |
|-------|-----------|------------|---------------|------------|
| 1-4 | Lenta-Media | 2.5s - 1.8s | 2-3 | 🟢 Fácil |
| 5-7 | Rápida | 1.0s - 0.7s | 5-6 | 🟡 Media |
| 8-10 | 🔥 EXTREMA | 0.5s - 0.3s | 7-10 | 🔥 THROUGH THE FIRE AND FLAMES |

##  Sistema de Puntuación
- ✅ **Clasificación correcta:** +10 EcoPuntos
- ❌ **Error de contenedor:** -1 vida +15% contaminación
- ⏰ **Se pasó del tiempo:** -1 vida +10% contaminación
-  **Meta por nivel:** 15 residuos reciclados
- ⭐ **Power-up ♻️:** Auto-clasificación por 5 segundos (aparece cada 40-60s)

## 💻 Tecnologías Utilizadas
- **HTML5 Canvas** - Renderizado del juego
- **CSS3** - Animaciones, gradientes y diseño responsive
- **JavaScript (Vanilla)** - Lógica del juego, física de caída, colisiones
- **Google Fonts** - Tipografía "Press Start 2P" estilo retro
- **Emojis universales** - Para representar los residuos

### 🤖 Uso de IA
- Generación de código base para el sistema de carriles y timing
- Optimización de funciones de spawn y detección de colisiones
- Asistencia en la estructura de niveles progresivos

## 🧠 Aprendizajes y Mejoras

### ✅ Qué aprendí
- Implementación de **múltiples carriles** con objetos independientes
- Sistema de **timing preciso** con zonas de activación
- **Progresión de dificultad** dinámica (10 niveles con diferentes parámetros)
- Gestión de **estados de juego** (score, vidas, contaminación, nivel)
- Sistema de **power-ups** con temporizador y auto-clasificación
- **Mensajes rotativos** educativos sin interrumpir el gameplay
- Animaciones CSS complejas (pulse, glow, fade, pop-in)

### 🔧 Aspectos a mejorar
- **Audio:** Agregar música de fondo que marque el ritmo (como Guitar Hero) y efectos de sonido al clasificar
- **Visual:** Efectos de partículas más elaborados al clasificar correctamente
- **Gameplay:** Sistema de combos y multiplicadores de puntuación
- **Contenido:** Más tipos de residuos y contenedores especiales
- **UI:** Leaderboard con localStorage para competir por el mejor puntaje
- **Accesibilidad:** Opción de cambiar las teclas y modo daltonico

## 🌍 Impacto Educativo
El juego incluye 20 mensajes educativos rotativos sobre reciclaje que enseñan:
- Tiempos de degradación de materiales
- Beneficios del reciclaje
- Procesos de compostaje
- Manejo de residuos peligrosos
- Las 3R: Reducir, Reutilizar, Reciclar

---
[⬅ Volver al Portafolio Principal](../README.md)
