---
layout: default
title: "07 · Cubo de MDF"
nav_order: 7
permalink: /07-cubo/
---

# 07 — Cubo de MDF cortado con láser

## Introducción

En esta práctica se diseñó, cortó y ensambló un **cubo de MDF mediante corte láser**. El objetivo fue pasar de un diseño digital de piezas planas a una estructura tridimensional, considerando la precisión del corte y el ajuste entre las caras.

Las seis caras utilizan un sistema de **pestañas y ranuras** en sus bordes. Este tipo de unión permite alinear las piezas y formar el cubo sin depender únicamente de uniones externas.

## Objetivo

Construir un cubo de MDF mediante un proceso de fabricación digital que incluyera:

- Diseñar las seis caras del cubo.
- Incorporar pestañas y ranuras para el ensamble.
- Preparar el archivo para corte láser.
- Cortar las piezas en MDF.
- Revisar el ajuste entre las piezas.
- Ensamblar el cubo y comprobar su estabilidad.

## Materiales y herramientas

| Material / herramienta | Uso |
|---|---|
| MDF | Material principal de las seis caras |
| Cortadora láser | Corte preciso de los contornos |
| Archivo de diseño vectorial | Definición de caras, pestañas y ranuras |
| Computadora | Preparación y envío del diseño |
| Regla o instrumento de medición | Verificación de medidas y ajuste |
| Lija fina | Corrección ligera de bordes, si fuera necesaria |

> Las dimensiones exactas dependen del archivo utilizado durante la práctica. No se agregan medidas que no hayan sido registradas.

<style>
.media-frame{display:block;width:100%;max-width:900px;margin:18px auto;border-radius:12px;border:1px solid #d7dce1;background:#111}
.caption{text-align:center;font-size:.92rem;color:#666;margin-top:6px}
/* Conservar la proporción vertical y evitar ampliar el video de 128 px hasta 900 px */
.cube-video{width:100%;max-width:340px;height:auto;aspect-ratio:128/228;object-fit:contain;filter:contrast(1.06) saturate(1.05)}
.cube-video.cube-video-hd{max-width:520px;aspect-ratio:9/16}
/* Fotografía original de baja resolución: mostrarla sin ampliarla a todo el ancho */
.cube-parts-photo{max-width:900px;height:auto;object-fit:contain}
.cube-result-photo{max-width:820px;height:auto;object-fit:contain}
</style>

# Proceso de fabricación

## 1. Diseño de las piezas

Primero se diseñaron las **seis caras** que formarían el cubo. En los bordes se agregaron pestañas y ranuras alternadas para que cada cara pudiera unirse con las piezas adyacentes.

La parte más importante de esta etapa fue comprobar que las uniones coincidieran entre sí. Si una pestaña queda fuera de posición o una ranura tiene una medida incorrecta, el cubo puede no cerrar correctamente.

## 2. Preparación del archivo

Antes de enviar el diseño a la cortadora láser se revisó que:

- Los contornos estuvieran cerrados.
- No existieran líneas duplicadas.
- Las piezas estuvieran distribuidas dentro del área de MDF.
- Las uniones conservaran su geometría.
- El archivo estuviera listo para ser interpretado por la máquina.

## 3. Corte láser

Una vez preparado el archivo se realizó el corte de las piezas en MDF. El láser siguió los contornos del diseño y generó las seis caras con sus respectivas pestañas.

### Video del proceso de corte

<video class="media-frame cube-video" controls playsinline preload="metadata" onloadedmetadata="if(this.videoWidth>=720)this.classList.add('cube-video-hd')">
  <source src="{{ '/assets/videos/cubo-corte-fullhd.mp4' | relative_url }}" type="video/mp4">
  <source src="data:video/mp4;base64,AAAAIGZ0eXBpc29tAAACAGlzb21pc28yYXZjMW1wNDEAAAQubW9vdgAAAGxtdmhkAAAAAAAAAAAAAAAAAAAD6AAAMNQAAQAAAQAAAAAAAAAAAAAAAAEAAAAAAAAAAAAAAAAAAAABAAAAAAAAAAAAAAAAAABAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAgAAA1l0cmFrAAAAXHRraGQAAAADAAAAAAAAAAAAAAABAAAAAAAAMNQAAAAAAAAAAAAAAAAAAAAAAAEAAAAAAAAAAAAAAAAAAAABAAAAAAAAAAAAAAAAAABAAAAAAIAAAADkAAAAAAAkZWR0cwAAABxlbHN0AAAAAAAAAAEAADDUAABAAAABAAAAAALRbWRpYQAAACBtZGhkAAAAAAAAAAAAAAAAAABAAAADIAAVxwAAAAAALGhkbHIAAAAAAAAAAHZpZGUAAAAAAAAAAAAAAABWaWRlb0hhbmRsZQAAAAJ9bWluZgAAABR2bWhkAAAAAQAAAAAAAAAAAAAAJGRpbmYAAAAcZHJlZgAAAAAAAAABAAAADHVybCAAAAABAAACPXN0YmwAAADJc3RzZAAAAAAAAAABAAAAuWF2YzEAAAAAAAAAAQAAAAAAAAAAAAAAAAAAAAAAgADkAEgAAABIAAAAAAAAAAEVTGF2YzYxLjE5LjEwMSBsaWJ4MjY0AAAAAAAAAAAAAAAY//8AAAA8YXZjQwFkAAz/4QAeZ2QADKxyBEIH/nmoCAgKAAADAAIAAAMACB4oUwjAAQAHaOhDgZSyLP34+AAAAAATY29scm5jbHgAAQABAAEAAAAAFGJ0cnQAAAAAAAAIiQAAAAAAAAAYc3R0cwAAAAAAAAABAAAAGQAAIAAAAAAUc3RzcwAAAAAAAAABAAAAAQAAAJhjdHRzAAAAAAAAABEAAAABAABAAAAAAAEAAKAAAAAAAQAAQAAAAAABAAAAAAAAAAEAACAAAAAAAQAA4AAAAAABAABgAAAAAAIAAAAAAAAAAgAAIAAAAAABAAEgAAAAAAEAAIAAAAAAAwAAAAAAAAADAAAgAAAAAAEAAOAAAAAAAQAAYAAAAAACAAAAAAAAAAIAACAAAAAAHHN0c2MAAAAAAAAAAQAAAAEAAAAZAAAAAQAAAHhzdHN6AAAAAAAAAAAAAAAZAAAEKQAAAQcAAABvAAAAXgAAAD4AAACaAAAAagAAADEAAAAyAAAANwAAAEgAAAEhAAAAhgAAAG0AAABTAAAAfgAAAFQAAABCAAAAKgAAAGIAAABPAAAAKQAAAC0AAABGAAAARAAAABRzdGNvAAAAAAAAAAEAAAReAAAAYXVkdGEAAABZbWV0YQAAAAAAAAAhaGRscgAAAAAAAAAAbWRpcmFwcGwAAAAAAAAAAAAAAAAsaWxzdAAAACSpdG9vAAAAHGRhdGEAAAABAAAAAExhdmY2MS43LjEwMwAAAAhmcmVlAAANX21kYXQAAAKvBgX//6vcRem95tlIt5Ys2CDZI+7veDI2NCAtIGNvcmUgMTY0IHIzMTA4IDMxZTE5ZjkgLSBILjI2NC9NUEVHLTQgQVZDIGNvZGVjIC0gQ29weWxlZnQgMjAwMy0yMDIzIC0gaHR0cDovL3d3dy52aWRlb2xhbi5vcmcveDI2NC5odG1sIC0gb3B0aW9uczogY2FiYWM9MSByZWY9MTYgZGVibG9jaz0xOjA6MCBhbmFseXNlPTB4MzoweDEzMyBtZT11bWggc3VibWU9MTAgcHN5PTEgcHN5X3JkPTEuMDA6MC4wMCBtaXhlZF9yZWY9MSBtZV9yYW5nZT0yNCBjaHJvbWFfbWU9MSB0cmVsbGlzPTIgOHg4ZGN0PTEgY3FtPTAgZGVhZHpvbmU9MjEsMTEgZmFzdF9wc2tpcD0xIGNocm9tYV9xcF9vZmZzZXQ9LTIgdGhyZWFkcz03IGxvb2thaGVhZF90aHJlYWRzPTEgc2xpY2VkX3RocmVhZHM9MCBucj0wIGRlY2ltYXRlPTEgaW50ZXJsYWNlZD0wIGJsdXJheV9jb21wYXQ9MCBjb25zdHJhaW5lZF9pbnRyYT0wIGJmcmFtZXM9OCBiX3B5cmFtaWQ9MiBiX2FkYXB0PTIgYl9iaWFzPTAgZGlyZWN0PTMgd2VpZ2h0Yj0xIG9wZW5fZ29wPTAgd2VpZ2h0cD0yIGtleWludD0yNTAga2V5aW50X21pbj0yIHNjZW5lY3V0PTQwIGludHJhX3JlZnJlc2g9MCByY19sb29rYWhlYWQ9NjAgcmM9Y3JmIG1idHJlZT0xIGNyZj01MS4wIHFjb21wPTAuNjAgcXBtaW49MCBxcG1heD02OSBxcHN0ZXA9NCBpcF9yYXRpbz0xLjQwIGFx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" type="video/mp4">
</video>

<p class="caption">Fragmento del proceso de corte láser de las piezas del cubo.</p>

## 4. Piezas obtenidas

Después del corte se retiraron las piezas y se revisaron las pestañas y ranuras antes del ensamble.

<img class="media-frame cube-parts-photo" src="{{ '/assets/img/IMG_20260923_133608.jpg' | relative_url }}" alt="Piezas de MDF cortadas para formar el cubo" loading="lazy" decoding="async">

<p class="caption">Las seis caras de MDF después del corte láser y antes del ensamble.</p>

## 5. Ensamble del cubo

El cubo se armó haciendo coincidir las pestañas de cada pieza con las ranuras de las caras adyacentes. El ensamble se realizó de manera progresiva para evitar forzar el MDF o dañar las uniones.

Primero se formaron las paredes laterales y posteriormente se colocaron las caras restantes hasta cerrar la estructura.

# Resultado final

<img class="media-frame cube-result-photo" src="{{ '/assets/img/IMG_20260923_134042.jpg' | relative_url }}" alt="Cubo de MDF terminado y ensamblado" loading="lazy" decoding="async">

<p class="caption">Cubo de MDF ensamblado al finalizar la práctica.</p>

## Resultados y observaciones

El proceso permitió comprobar que la precisión del diseño digital afecta directamente el resultado físico. Aunque las piezas comienzan como superficies planas, las pestañas y ranuras permiten convertirlas en una estructura tridimensional.

También se observó la coloración oscura en los bordes del MDF, característica del proceso térmico del corte láser. El ajuste entre las uniones fue un punto importante porque determina qué tan firme queda la estructura.

## Problemas que pueden presentarse

Durante este tipo de fabricación pueden ocurrir algunos problemas:

- Pestañas demasiado grandes que dificultan el ensamble.
- Ranuras demasiado amplias que dejan la estructura floja.
- Líneas duplicadas que provocan que el láser pase más de una vez por una zona.
- Piezas mal acomodadas dentro del área de trabajo.
- Rotura de una pestaña al ejercer demasiada fuerza durante el ensamble.

## Conclusión

La construcción del cubo permitió aplicar un flujo completo de **fabricación digital: diseño, preparación del archivo, corte láser, revisión y ensamble**.

La práctica demostró que un objeto tridimensional puede fabricarse a partir de piezas planas siempre que las uniones estén correctamente diseñadas. El resultado final fue un cubo de MDF ensamblado mediante pestañas y ranuras, mostrando la utilidad del corte láser para producir piezas precisas y repetibles.

**Autor:** Leonardo García Contreras  
**Proceso:** diseño digital · corte láser · ensamble en MDF
