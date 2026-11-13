# 🔍 OBS Zoom to Mouse (Desplazamiento Horizontal Inteligente)

![OBS Studio](https://img.shields.io/badge/OBS%20Studio-28.0%2B-302E31?style=for-the-badge&logo=obsstudio&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-5.1-2C2D72?style=for-the-badge&logo=lua&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Un script en **Lua** para **OBS Studio** que extiende la funcionalidad clásica de *Zoom to Mouse*, permitiendo hacer seguimiento suave del cursor y **desplazamiento horizontal/vertical libre** para visualizar el 100% del contenido de una fuente, sin importar las diferencias entre la relación de aspecto de tu captura y el tamaño de tu lienzo (canvas).

---

## ✨ Características Principales

* **Exploración Total sin Límites de Lienzo:** Ideal para mostrar capturas de dispositivos móviles (9:16), monitores ultrawide (21:9) o ventanas de alta resolución dentro de un lienzo estándar (16:9) sin cortar información en los bordes.
* **Desplazamiento Suave (*Smooth Panning*):** Movimiento interpolado que sigue el cursor de forma natural y profesional, evitando saltos bruscos para el espectador.
* **Zoom Dinámico Configurable:** Control total sobre el factor de ampliación, la velocidad de transición y el margen de seguridad en los bordes.
* **Atajos de Teclado (*Hotkeys*):** Activa o desactiva el zoom y el seguimiento en tiempo real mediante teclas rápidas configurables en OBS.
* **Ligero y Nativo:** Escrito íntegramente en Lua utilizando la API nativa de OBS Studio; no requiere dependencias externas ni consumo extra de CPU/GPU.

---

## 🎥 Video Tutorial de Instalación y Configuración

Mira este video paso a paso para aprender a instalar el script, vincular tu fuente de captura y configurar tus atajos de teclado en menos de 3 minutos:

[![Tutorial de Instalación OBS Zoom to Mouse](https://img.youtube.com/vi/ID_DE_TU_VIDEO/maxresdefault.jpg)](https://www.youtube.com/watch?v=ID_DE_TU_VIDEO)

> 💡 **Nota para el autor:** Reemplaza `ID_DE_TU_VIDEO` en el enlace de arriba con el identificador de tu video en YouTube (por ejemplo, si tu enlace es `https://youtu.be/dQw4w9WgXcQ`, el ID es `dQw4w9WgXcQ`).

---

## 🚀 Instalación Paso a Paso

### 1. Descargar el Script
Clona este repositorio o descarga directamente el archivo `.lua`:
```bash
git clone [https://github.com/TU_USUARIO/obs-zoom-to-mouse-desplasamiento-horizontal-.git](https://github.com/TU_USUARIO/obs-zoom-to-mouse-desplasamiento-horizontal-.git)
