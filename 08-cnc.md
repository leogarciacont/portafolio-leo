---
layout: default
title: "08 · CNC"
nav_order: 8
permalink: /08-cnc/
---

# 08 — CNC: diseño y construcción de la estructura

<div class="cnc-tags"><span>Proyecto de mecatrónica</span><span>Fabricación digital</span><span>En desarrollo</span></div>

## Introducción

Este proyecto consiste en el **diseño, la fabricación y el ensamble progresivo de una estructura para una máquina CNC didáctica**. La construcción integra perfiles de aluminio, soportes, rodamientos, elementos de guiado, tornillería y componentes fabricados por impresión 3D.

El propósito es transformar diseños y piezas individuales en un sistema mecánico organizado. El trabajo permite comprobar, en condiciones reales, cómo afectan al montaje la alineación de los perfiles, las medidas, las holguras entre componentes y la posición de los puntos de apoyo. También se contempla la adaptación de un **soporte para una herramienta, como un lápiz 3D**, cuya integración se documentará conforme avance el proyecto.

> **Estado:** prototipo en construcción. Las fotografías corresponden a diferentes momentos del proceso; no constituyen evidencia de una máquina terminada ni de pruebas de mecanizado.

## Objetivo

Diseñar y ensamblar la estructura de una CNC, documentando tanto la fabricación de sus piezas como la integración de los mecanismos que permitirán realizar movimientos controlados.

### Objetivos específicos

- Revisar modelos STL y la geometría de piezas mecánicas.
- Preparar perfiles de aluminio y unirlos para formar el bastidor.
- Instalar rodamientos, soportes y componentes de transmisión.
- Integrar un carro móvil mediante ruedas de guiado.
- Preparar piezas personalizadas mediante impresión 3D.
- Registrar los ajustes y pruebas de funcionamiento conforme se realicen.

## Materiales y componentes

| Elemento | Función |
|:--|:--|
| Perfiles de aluminio | Estructura principal y travesaños |
| Escuadras, tornillos y tuercas | Unión y sujeción de perfiles |
| Rodamientos y soportes metálicos | Apoyo de elementos giratorios |
| Varilla roscada de avance | Elemento de desplazamiento lineal |
| Ruedas de guiado | Orientación y apoyo del carro móvil |
| Motor paso a paso | Accionamiento previsto del mecanismo |
| Correa dentada y poleas | Transmisión en el conjunto superior |
| Piezas diseñadas en 3D | Soportes y adaptadores del montaje |
| Impresora 3D | Fabricación de elementos personalizados |
| Equipo para cortar perfiles | Preparación de los tramos estructurales |

*Las medidas exactas, tolerancias, especificaciones del motor y material de impresión se documentarán cuando se verifiquen.*

<style>
.cnc-tags{display:flex;flex-wrap:wrap;gap:9px;margin:12px 0 24px}
.cnc-tags span{font-size:.81rem;padding:5px 11px;border:1px solid #bed0d7;border-radius:50px;background:#eef4f6;color:#46616a}
.cnc-photo{max-width:610px;width:100%;margin:18px auto 30px;text-align:center}
.cnc-photo.wide{max-width:900px}
.cnc-photo img{display:block;width:100%;height:auto;object-fit:contain;max-height:800px;background:#edf2f4;border:1px solid #d7e0e5;border-radius:12px}
.cnc-photo figcaption{font-size:.92rem;line-height:1.55;color:#53636d;margin:9px auto}
.cnc-photo .placeholder{display:none;min-height:175px;padding:30px 14px;box-sizing:border-box;background:#f4f8fa;border:1px dashed #aac0ca;border-radius:12px;color:#486473;flex-direction:column;justify-content:center;gap:8px}
.cnc-photo.missing .placeholder{display:flex}
.cnc-photo .placeholder strong{font-size:1rem}
.cnc-photo .placeholder span{font:12px monospace;overflow-wrap:anywhere}
.cnc-next{background:#f4f8fa;border-left:3px solid #7898a8;padding:15px 18px;border-radius:6px;margin:18px 0}
@media(max-width:650px){.cnc-photo img{max-height:none}.cnc-tags span{font-size:.75rem}}
</style>

# Proceso de fabricación y montaje

## 1. Diseño digital y revisión del archivo STL

La primera parte del proceso consiste en revisar la geometría de las piezas antes de incorporarlas al prototipo. Los modelos **STL** permiten inspeccionar visualmente superficies, perforaciones y rebajes, y sirven de referencia para comprender cómo una pieza podría ensamblarse con otras.

La captura muestra un modelo mecánico abierto en un visor web tridimensional. Esta evidencia corresponde a la revisión digital: visualizar una pieza no significa necesariamente que ya haya sido impresa o instalada.

<figure class="cnc-photo">
<img src="{{ '/assets/img/cnc-01-modelo-stl.jpg' | relative_url }}" alt="Modelo mecánico visualizado en un visor de archivos STL" loading="lazy" decoding="async" onerror="this.closest('figure').classList.add('missing');this.remove()">
<div class="placeholder"><strong>Fotografía pendiente de subir</strong><span>cnc-01-modelo-stl.jpg</span></div>
<figcaption>Vista de un archivo STL en un visor 3D; referencia para revisar la geometría del componente.</figcaption>
</figure>

## 2. Corte y preparación de los perfiles de aluminio

Los perfiles de aluminio constituyen el esqueleto de la máquina. Antes del ensamble se preparan los tramos que formarán la base, las columnas y los travesaños. Su longitud y la calidad de los extremos influyen en la facilidad de montaje y en la alineación final de la estructura.

En la fotografía se observa la operación de **corte de un perfil metálico en el taller**. Este paso es parte de la preparación de materiales previa a la unión mediante escuadras y tornillería.

<figure class="cnc-photo">
<img src="{{ '/assets/img/cnc-02-corte-perfiles.jpg' | relative_url }}" alt="Persona trabajando en el corte de un perfil de aluminio en el taller" loading="lazy" decoding="async" onerror="this.closest('figure').classList.add('missing');this.remove()">
<div class="placeholder"><strong>Fotografía pendiente de subir</strong><span>cnc-02-corte-perfiles.jpg</span></div>
<figcaption>Preparación de un perfil de aluminio durante la fabricación de la estructura.</figcaption>
</figure>

## 3. Construcción de la base

Una vez preparados los perfiles, comienza el armado del **bastidor principal**. Las uniones atornilladas permiten colocar las piezas en posición y ajustar su alineación antes de apretar definitivamente. El bastidor funciona como referencia para los componentes móviles.

La fotografía muestra la base en proceso de ensamble. Se aprecia una **varilla roscada de avance** con elementos de apoyo, que formará parte del mecanismo de desplazamiento. Es importante evitar que el eje trabaje desalineado respecto de la trayectoria prevista.

<figure class="cnc-photo">
<img src="{{ '/assets/img/cnc-03-estructura-base.jpg' | relative_url }}" alt="Base de perfiles de aluminio en montaje con varilla roscada y soportes" loading="lazy" decoding="async" onerror="this.closest('figure').classList.add('missing');this.remove()">
<div class="placeholder"><strong>Fotografía pendiente de subir</strong><span>cnc-03-estructura-base.jpg</span></div>
<figcaption>Vista del bastidor y de la disposición inicial del elemento de avance.</figcaption>
</figure>

## 4. Soportes mecánicos y rodamientos

Los soportes determinan la posición de los elementos que deben girar o mantenerse fijos en la máquina. En el detalle fotografiado se identifican bloques metálicos de sujeción, varios pernos con tuercas y un **rodamiento central montado en su soporte**.

Su colocación requiere atención a la rigidez de la unión y a la alineación con el eje correspondiente. Si un apoyo queda fuera de posición puede producir rozamiento o dificultar el recorrido, aspectos que deben comprobarse durante las pruebas.

<figure class="cnc-photo wide">
<img src="{{ '/assets/img/cnc-04-rodamientos-soportes.jpg' | relative_url }}" alt="Detalle de rodamiento central y bloques de aluminio atornillados a un perfil" loading="lazy" decoding="async" onerror="this.closest('figure').classList.add('missing');this.remove()">
<div class="placeholder"><strong>Fotografía pendiente de subir</strong><span>cnc-04-rodamientos-soportes.jpg</span></div>
<figcaption>Conjunto de sujeción y apoyo mecánico instalado sobre un perfil estructural.</figcaption>
</figure>

## 5. Diseño del carro y sistema de ruedas

El movimiento del carro depende tanto del accionamiento como de su correcto guiado. En el prototipo se observa una disposición de **tres ruedas alrededor de un perfil horizontal**, fijadas a una pieza de soporte que forma parte del conjunto móvil.

Esta configuración permite mantener la relación entre el carro y la guía. Durante el ajuste será necesario comprobar el contacto de las ruedas, el juego lateral y la suavidad de movimiento sin forzar los componentes.

<figure class="cnc-photo">
<img src="{{ '/assets/img/cnc-05-carro-ruedas.jpg' | relative_url }}" alt="Primer plano del carro con tres ruedas de guiado y soporte claro" loading="lazy" decoding="async" onerror="this.closest('figure').classList.add('missing');this.remove()">
<div class="placeholder"><strong>Fotografía pendiente de subir</strong><span>cnc-05-carro-ruedas.jpg</span></div>
<figcaption>Detalle del sistema de ruedas y de la pieza de soporte del carro móvil.</figcaption>
</figure>

## 6. Preparación de piezas para impresión 3D

Algunas piezas requieren una geometría adaptada a la estructura y a la posición de la tornillería. La impresión 3D permite fabricar soportes, placas y adaptadores a partir de archivos digitales, además de introducir correcciones cuando el ajuste físico lo exige.

La pantalla de la impresora **Creality** muestra un archivo cuyo nombre comienza con `01_BASE_COMPLETA_RUEDAS`. La evidencia registra la preparación o inicio de impresión; no se interpreta como una confirmación de que esa pieza se haya fabricado completamente.

<figure class="cnc-photo">
<img src="{{ '/assets/img/cnc-06-impresion-3d.jpg' | relative_url }}" alt="Pantalla de impresora Creality con archivo de base y ruedas cargado" loading="lazy" decoding="async" onerror="this.closest('figure').classList.add('missing');this.remove()">
<div class="placeholder"><strong>Fotografía pendiente de subir</strong><span>cnc-06-impresion-3d.jpg</span></div>
<figcaption>Archivo de una pieza mecánica preparado en la impresora 3D.</figcaption>
</figure>

## 7. Integración del montaje superior

La fotografía de conjunto permite apreciar un avance importante: la estructura incorpora **perfiles verticales, un travesaño, un motor paso a paso, ruedas de guiado y componentes de transmisión**. También se distingue una pieza clara en el área central del carro, destinada a la sujeción o adaptación del mecanismo.

En esta etapa se relacionan elementos trabajados por separado: el bastidor aporta rigidez, el carro define la trayectoria y el accionamiento permitirá moverlo una vez integrado y probado el control correspondiente.

<figure class="cnc-photo">
<img src="{{ '/assets/img/cnc-07-ensamble-actual.jpg' | relative_url }}" alt="Estructura CNC con motor paso a paso y carro superior de ruedas" loading="lazy" decoding="async" onerror="this.closest('figure').classList.add('missing');this.remove()">
<div class="placeholder"><strong>Fotografía pendiente de subir</strong><span>cnc-07-ensamble-actual.jpg</span></div>
<figcaption>Vista del ensamble mecánico en una de sus etapas más avanzadas.</figcaption>
</figure>

# Resultados parciales

Las imágenes documentan el avance desde un archivo digital hasta la integración de un conjunto mecánico real. Se identifican la preparación de perfiles, el bastidor, los soportes, la varilla de avance, el carro de ruedas, la preparación de piezas para impresión y la instalación de un motor.

El aprendizaje central del proceso consiste en **relacionar el diseño con los ajustes físicos**: una perforación, una distancia entre apoyos o una pequeña desalineación pueden obligar a modificar una pieza o revisar el procedimiento de ensamble.

## Verificaciones y trabajos pendientes de documentar

- **Alineación:** revisar el paralelismo entre guías y la posición de los soportes.
- **Desplazamiento:** comprobar que el carro avance sin atorarse ni presentar holgura excesiva.
- **Transmisión:** verificar acoplamientos, tensión de la correa y comportamiento del accionamiento.
- **Piezas impresas:** revisar tolerancias y corregir los modelos que lo requieran.
- **Herramienta:** documentar la adaptación del soporte para el lápiz 3D u otra herramienta.
- **Control y pruebas:** añadir evidencia de conexiones, movimientos y repetibilidad cuando esté disponible.

## Próximas actualizaciones

<div class="cnc-next"><strong>Esta documentación seguirá creciendo.</strong> Se agregarán nuevas fotografías de las piezas impresas, los ajustes del carro, el montaje de la herramienta y las pruebas de funcionamiento. Los resultados definitivos se registrarán únicamente cuando estén comprobados.</div>

## Conclusión provisional

La construcción de la CNC integra diseño tridimensional, preparación de materiales, elementos mecánicos e impresión 3D. Las fotografías permiten seguir una secuencia de trabajo y entender cómo se construye un sistema de movimiento a partir de componentes individuales.

Aunque la máquina aún se documenta como proyecto en desarrollo, el ensamble de su estructura constituye una base para continuar con el ajuste, el control y las pruebas posteriores.

**Autor:** Leonardo García Contreras  
**Área:** Mecatrónica · fabricación digital · diseño mecánico · impresión 3D  
**Estado:** proyecto en desarrollo.
