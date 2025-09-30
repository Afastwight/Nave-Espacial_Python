# Nave Espacial – Python Biblioteca (Pygame)

Arcade **2D Shooter** en **Python + Pygame**.  
Controla tu nave, esquiva meteoros, dispara láseres, acumula **puntos**, administra tu **escudo** y disfruta de **explosiones** con sonido y música de fondo.


## ✨ Características
- Movimiento lateral suave (← →) y disparo con **espacio**.
- **Meteoros** con tamaños/velocidades aleatorias.
- **Colisiones**: bala–meteoro (explosión + score) y meteoro–jugador (daño al escudo).
- **Barra de escudo** y **marcador** en pantalla.
- **Pantalla de inicio** (“Press Key” para comenzar).
- **Música de fondo** en loop + efectos (láser y explosión).
- Organización con `pygame.sprite.Group` y clases (`Player`, `Meteor`, `Bullet`, `Explosion`).

## 🧱 Requisitos
- **Python 3.8+** (recomendado 3.10+)
- **Pygame** 2.x
```bash
pip install pygame


