# 💰 Ahorra y Corre

<div align="center">
  <img src="assets/screenshot.png" alt="Captura de Ahorra y Corre" width="80%">
  <br>
  <em>¡Salta los microgastos, agáchate ante los recibos y alcanza tu meta financiera!</em>
</div>

---

##  Descripción
**Ahorra y Corre** es un *endless runner* (corredor infinito) con temática financiera donde el jugador debe esquivar los gastos diarios que drenan su dinero mientras recolecta monedas para alcanzar una meta de ahorro.

### 🎯 Objetivo del Jugador
Partiendo de **$300**, el jugador debe llegar a **$3000** recolectando monedas y esquivando dos tipos de obstáculos financieros. Un solo error puede costar $100, por lo que la precisión y los reflejos son clave.

### 🎮 Mecánica Principal
El juego combina dos acciones en tiempo real:
- ⬆️ **SALTAR** las **Tazas de Café ☕** (microgastos del suelo): gastos pequeños pero constantes que aparecen en el camino.
- ⬇️ **AGACHARSE** ante los **Tazas de café aereas** (gastos sorpresa): obstáculos que cuelgan del cielo y **bloquean la trayectoria del salto**, obligando al jugador a calcular si debe brincar o agacharse.
- Incluye efectos visuales de partículas, textos flotantes (+$50, -$100).

## ️ Género
`Endless Runner` | `Arcade` | `Educativo` | `Reflejos`

## 🎮 Controles
- **⬆️ FLECHA ARRIBA** o **W**: Saltar (solo en el suelo).
- **⬇️ FLECHA ABAJO** o **S**: Agacharse (reduce la altura del personaje).

## 📊 Sistema de Economía y Dificultad

| Concepto | Valor | Impacto |
|----------|:-----:|---------|
| 💵 **Dinero inicial** | $300 | Margen de error muy reducido |
| 🎯 **Meta** | $3000 | Requiere ~54 monedas perfectas |
| 💰 **Moneda recogida** | +$50 | Recompensa consistente |
|  **Chocar con Taza** | -$100 | Penalización fuerte |
| 💀 **Llegar a $0** | Game Over | Bancarrota total |

### 🚀 Progresión de Velocidad

| Frames transcurridos | Velocidad | Dificultad |
|:---:|:---:|:---|
| **0 - 500** | 7 | 🟢 Normal |
| **500 - 1000** | 7.5 | 🟡 Aumentada |
| **1000 - 1500** | 8 |  Rápida |
| **1500+** | 8.5+ | 🔥 Frenética |

## 🧠 Diseño Estratégico de Obstáculos

El juego usa **matemáticas de colisión precisas** para forzar al jugador a usar ambas mecánicas:

| Obstáculo | Posición | ¿Se puede saltar? | ¿Se puede agachar? | Solución correcta |
|-----------|----------|:-----------------:|:------------------:|:-----------------:|
| ☕ **Taza de Café** | Suelo (Y=410, H=40) | ✅ Sí | ❌ No | **SALTAR** |



## 💻 Tecnologías Utilizadas
- **HTML5 Canvas** - Renderizado del juego, partículas y textos flotantes.
- **CSS3** - Interfaz HUD, barra de progreso animada, pantallas de menú con gradientes y sombras.
- **JavaScript (Vanilla)** - Física de salto con gravedad, detección de colisiones AABB, sistema de spawn inteligente.
- **Web Audio API** - Música de fondo en loop.

### 🤖 Uso de IA
- Generación de código base para la física de plataformas y sistema de colisiones.
- Optimización del algoritmo de spawn para evitar obstáculos imposibles.
- Asistencia en el balanceo de la economía del juego (valores de recompensa/penalización).

##  Aprendizajes y Mejoras

### ✅ Qué aprendí
- Implementación de **física de salto con gravedad** (`jumpPower` + `gravity`) para sensación de peso real.
- **Detección de colisiones AABB** (Axis-Aligned Bounding Box) con padding para hitboxes justas.
- **Sistema de spawn inteligente** con distancia mínima variable para evitar situaciones imposibles.
- **Balanceo de dificultad**: economía donde un error cuesta el doble de lo que una moneda da.
- **Partículas y textos flotantes** para feedback visual inmediato (+$50, -$100).
- **Barra de progreso dinámica** que refleja el avance hacia la meta en tiempo real.
- **Efecto de temblor de cámara** al recibir daño para impacto emocional.

### 🔧 Aspectos a mejorar
- **Audio:** Agregar efectos de sonido diferenciados (salto, moneda, choque, agacharse) y música ambiental.
- **Visual:** Sprites animados del personaje corriendo (frame animation) en lugar de imagen estática.
- **Gameplay:** Power-ups temporales (imán de monedas, escudo de un choque, multiplicador x2).
- **Contenido:** Diferentes "niveles" temáticos (oficina, ciudad, supermercado) que cambien el fondo.
- **UI:** Pantalla de pausa y menú de configuración de controles.
- **Mecánica:** Modo "Diario" con meta personalizada según el ingreso del jugador.

## 🌍 Impacto Educativo

El juego enseña conceptos financieros de forma intuitiva:

| Mecánica del juego | Lección financiera real |
|-------------------|------------------------|
| ☕ Tazas de café en el suelo | Los microgastos diarios (café, snacks) drenan tu dinero silenciosamente. |
| 💸 Penalización de -$100 | Un solo gasto innecesario puede costar el equivalente a 2 monedas ahorradas. |
| 🎯 Meta de $3000 | El ahorro requiere **disciplina constante**, no suerte. |
| 🚀 Velocidad progresiva | La vida financiera se vuelve más compleja con el tiempo. |

---
[⬅ Volver al Portafolio Principal](../README.md)
