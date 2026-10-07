---
layout: default
title: "05 · THE GAME KNOWS"
nav_order: 5
permalink: /05-juego/
---

# 05 — THE GAME KNOWS

**Survival horror · shooter · sigilo · inteligencia artificial adaptativa**

Un videojuego de terror inspirado en las mecánicas de supervivencia de los clásicos del género, con una idea original: **ECHO, un monstruo que aprende de tus hábitos**. Explora un hospital abandonado, recoge tres fusibles, administra tu munición y escapa.

## Juega directamente aquí

<div style="width:100%;max-width:1100px;margin:1.2rem auto 1.5rem">
  <iframe
    src="{{ '/assets/game/index.html' | relative_url }}"
    title="THE GAME KNOWS — videojuego de terror jugable"
    allow="fullscreen; pointer-lock; autoplay"
    allowfullscreen
    loading="eager"
    style="display:block;width:100%;height:min(76vh,720px);min-height:500px;border:1px solid #577b83;border-radius:10px;background:#071016;"
  ></iframe>
  <p style="text-align:center;margin:12px 0">
    <a class="btn btn-primary" href="{{ '/assets/game/index.html' | relative_url }}" target="_blank" rel="noopener noreferrer">Jugar en pantalla completa ↗</a>
  </p>
</div>

> **Consejo:** en computadora, haz clic sobre el videojuego para controlar la cámara con el ratón. Presiona **Esc** para recuperar el cursor o pausar.

## Controles

| Tecla | Acción |
|:---|:---|
| **W A S D** | Moverse |
| **Ratón** | Girar cámara en tercera persona |
| **Clic izquierdo** | Disparar |
| **Shift** | Correr (genera ruido) |
| **Ctrl** | Caminar agachado |
| **E** | Interactuar, recoger objetos o esconderse |
| **R** | Recargar |
| **Q** | Usar botiquín |
| **Esc** | Pausar |

## Cómo funciona la IA

ECHO utiliza un sistema de **IA adaptativa basada en reglas**, no una red neuronal externa. Reacciona a tus disparos y ruidos, recuerda las zonas recorridas y reconoce un escondite después de usarlo varias veces. Cuantos más impactos recibe, menos tiempo permanece aturdido.

### Objetivo de la partida

1. Localiza los **tres fusibles** verdes del hospital.
2. Recoge munición y botiquines.
3. Evita al monstruo: escóndete cuando no sea seguro combatir.
4. Activa la **salida roja** después de recuperar los tres fusibles.

**Autor:** Leonardo García Contreras  
**Tecnologías:** HTML5, JavaScript, Canvas 2D (raycasting de apariencia 3D), GitHub Pages.  
**Estado:** prototipo web jugable; versión experimental, distinta del proyecto editable en Godot.

> La versión del navegador utiliza un motor de raycasting ligero para ofrecer apariencia tridimensional sin instalaciones ni bibliotecas externas. No es una exportación del proyecto Godot; se desarrolló como alternativa web autónoma.
