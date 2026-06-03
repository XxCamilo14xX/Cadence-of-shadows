# Cadence of Shadows
### Proyecto Final — Arquitectura de Videojuegos

> Prototipo funcional de un videojuego noir 2.5D ambientado en Colombia de los años 70. El jugador controla a un detective que investiga el asesinato de un candidato presidencial, combinando exploración urbana, combate cuerpo a cuerpo y recolección de pistas.

---

## 🚨 Requisitos del Sistema

| Requisito | Detalle |
|---|---|
| Sistema operativo | Windows 10 / 11 (64-bit) |
| Motor | Unreal Engine 5.3 o superior |
| Plugin obligatorio | PaperZD |

---

## 🔌 Plugins Utilizados

| Plugin | Fuente | Instalación externa requerida |
|---|---|---|
| **PaperZD** | Epic Games Store | ✅ Sí — debe instalarse antes de abrir el proyecto |

> ⚠️ **PaperZD es obligatorio.** Si no está instalado, el proyecto no compilará. Descargarlo desde Epic Games Store e instalarlo en la versión 5.3+ antes de continuar.

---

## ⚡ Cómo Abrir el Proyecto

1. Descargar e instalar **Unreal Engine 5.3+** desde el [Epic Games Launcher](https://www.unrealengine.com/)
2. Instalar el plugin **PaperZD** desde Epic Games Store en la misma versión del motor
3. Clonar este repositorio:
```bash
   git clone https://github.com/tu-usuario/cadence-of-shadows.git
```
4. Abrir la carpeta del proyecto y hacer doble clic en `MyProject.uproject`
5. Si Unreal pregunta si deseas compilar los módulos, seleccionar **Yes**
6. Una vez cargado, ejecutar desde el botón **Play** o presionar `Alt + P`

---

## 🎮 Controles

| Tecla | Acción |
|---|---|
| `W A S D` | Movimiento |
| `Shift` | Correr |
| `Espacio` | Dodge roll |
| `Clic izquierdo` | Atacar — encadenar clics = combo (máx. 3 golpes) |
| `Clic derecho` | Bloquear / Parry |
| `1` `2` `3` | Cambiar de arma |
| `E` | Interactuar / Recoger pista |
| `G` | Curación |
| `TAB` | Inventario |
| `M` | Minimapa |
| `ESC` | Menú pausa |

---

## ✅ Funcionalidades Implementadas

- Movimiento completo: caminar, correr, dodge roll
- Combate cuerpo a cuerpo con combo de hasta 3 golpes, bloqueo y parry
- Armas cuerpo a cuerpo (machete, cuchillo) y de fuego (revólver, escopeta, rifle)
- IA enemiga con Behaviour Trees y navegación NavMesh
- Inventario completo con inspección 3D de objetos
- Recolección de pistas e interacción con NPCs
- Hub urbano (Zona Norte) con vehículos NPC, semáforos y ciclo día/noche
- Sistema de clima dinámico (lluvia, niebla)
- Cámara cinemática con zonas y transiciones
- Minimapa en tiempo real
- Guardado automático por checkpoints
- Menú principal, menú pausa y pantalla de muerte

---

## ⚠️ Bugs Conocidos

- El sistema de curación (`G`) está en beta y puede presentar comportamientos inesperados
- La tienda está activa pero tiene bugs conocidos
- **Teleports:** el widget de la `E` debe estar **dentro** de la esfera de interacción para que el TP funcione. Si aparece por fuera, el teleport no se activará

---

## 👥 Equipo

| Rol | Integrante |
|---|---|
| Programación / Sistemas / Audio | Mauricio Ordoñez |
| Animaciones / Combate | Axel Prieto |
| Arte 2D / UI | Camilo Lemus |
| Modelado 3D / Escenarios | Sergio Rangel |

---

*Build Alpha — Junio 2026*
