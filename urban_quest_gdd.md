
# Urban Quest - Game Design Document (GDD)

## 1. General Overview

**Name:** Urban Quest**Genre:** 2D Pixel-Art RPG**Platform:** PC**Engine:** Godot 4.3**Art Style:** Modern 16-bit Pixel Art (assets: LimeZu)**Core Mechanics:** Combat by turns, exploration, inventory management, and missions.

Urban Quest es un RPG ambientado en una ciudad moderna donde el jugador explora, completa misiones y lucha contra enemigos en un sistema de combate por turnos. El juego combina la nostalgia del pixel art con un contexto contemporáneo lleno de narrativa y exploración libre.

---

## 2. Story & Setting

### **Premisa**

El protagonista, un joven que acaba de llegar a una ciudad caótica y vibrante, se ve envuelto en una serie de eventos inesperados que ponen a prueba sus habilidades y decisiones. Con el tiempo, descubrirá que no todo es lo que parece en esta ciudad, y deberá resolver conflictos urbanos y derrotar enemigos que amenazan su camino.

### **Setting**

- **Ubicación:** Ciudad contemporánea con elementos modernos (cafeterías, parques, centros comerciales, calles, y callejones).
- **Estilo:** Ambientes urbanos detallados en pixel art (día/noche).
- **Atmosfera:** Moderna, juvenil y desenfadada con algunos toques de misterio.

### **Objetivo Principal**

Resolver los misterios de la ciudad mientras se completan misiones principales y secundarias, ganando experiencia y objetos para fortalecer al personaje.

### **Personaje Principal**

- **Nombre (editable):** Alex (por defecto).
- **Edad:** Joven adulto (20-25 años).
- **Estilo:** Casual, moderno, ropa urbana.
- **Armas/Habilidades:** Objetos cotidianos (palos, gadgets) y habilidades especiales aprendidas con experiencia.

---

## 3. Core Gameplay

### **3.1 Exploración**

- Movimiento libre en mapas 2D urbanos.
- Interacción con NPCs, objetos, y zonas clave (botón de acción).
- Exploración de diferentes entornos:
  - Calles principales.
  - Callejones oscuros.
  - Edificios: tiendas, apartamentos, estaciones de metro.
- **Recompensas:** Objetos, dinero, pistas para la historia.

### **3.2 Sistema de Combate**

- **Tipo:** Combate por turnos.
- **Estructura:**
  - Turno del jugador: Elegir entre atacar, usar habilidad, usar objeto o huir.
  - Turno del enemigo: Realiza una acción (ataque o habilidad).
- **Acciones:**
  - **Ataque:** Daño básico al enemigo.
  - **Habilidad:** Acciones especiales (por ejemplo, "Patada fuerte" que inflige más daño pero consume energía).
  - **Objeto:** Usar pociones o gadgets del inventario.
- **Progresión del Combate:**
  - Los enemigos serán más fuertes a medida que se avanza en la historia.
  - Derrotar enemigos otorga experiencia y objetos.

### **3.3 Inventario**

- Sistema básico con capacidad limitada.
- **Tipos de objetos:**
  - **Consumibles:** Pociones, comida para recuperar vida o energía.
  - **Equipables:** Armas y gadgets que mejoran el daño o defensa.
  - **Misceláneos:** Llaves, objetos de misiones, y coleccionables.
- **Obtención:**
  - Compra en tiendas.
  - Drops tras combates.
  - Exploración y recompensas de misiones.

---

## 4. Missions

### **Tipos de Misiones**

1. **Misiones Principales:**

   - Impulsan la narrativa central del juego.
   - Ejemplo: "Encuentra al contacto en el callejón".

2. **Misiones Secundarias:**

   - Pequeños encargos opcionales.
   - Ejemplo: "Ayuda al vendedor a recuperar su mercancía robada".

3. **Eventos Aleatorios:**

   - Interacciones menores durante la exploración.
   - Ejemplo: Un NPC perdido que necesita ayuda.

---

## 5. Progression System

### **Experiencia y Niveles**

- Ganar experiencia al completar misiones y derrotar enemigos.
- Al subir de nivel, el jugador puede:
  - Aumentar atributos: Vida, energía, ataque, defensa.
  - Desbloquear nuevas habilidades.

### **Dinero**

- Recompensas de misiones y combate.
- Usado para comprar objetos, equipo, y mejoras en tiendas.

---

## 6. Visuals & Assets

### **Pixel Art Style**

- **Escenarios:** Modernos y urbanos (usando LimeZu assets).
- **Personajes:** Sprites 16-bit detallados.
- **Efectos:** Partículas simples para ataques y eventos especiales (impactos, explosiones pequeñas).

### **UI (User Interface)**

- HUD con información de:
  - Vida.
  - Energía.
  - Dinero.
- Menú de inventario y combate sencillo y claro.

---

## 7. Audio

- **Música:** Chiptune moderna y relajada para exploración.
- **Efectos de sonido:**
  - Pasos, ataques, interacciones.
  - Notificaciones de misiones o diálogos.

---

## 8. Tasks and Milestones

### **Primera Tarea (Programación)**

1. Implementar movimiento básico del jugador.
   - Movimiento en 4 direcciones (arriba, abajo, izquierda, derecha).
   - Colisiones con el entorno.
   - Prueba en un mapa vacío.

**Próximo entregable**: Prototipo de movimiento.

---

Con esto, tenemos una base sólida para **Urban Quest**. Estoy listo para escuchar tu feedback y ajustar cualquier cosa. ¡Vamos allá! 🚀
