<div align="center">

# Pixel Taskbar Enabler

**Un módulo Xposed de alto rendimiento para habilitar la barra de tareas en dispositivos Pixel**

<p align="center">
  <img src="https://raw.githubusercontent.com/beymans-code/pixel-taskbar-enabler/main/PXTE%20beyman-dev.png" alt="Pixel Taskbar Enabler" width="500" />
</p>


[![Download](https://img.shields.io/github/v/release/beymans-code/pixel-taskbar-enabler?color=orange&logoColor=orange&label=Download&logo=DocuSign)](https://github.com/beymans-code/pixel-taskbar-enabler/releases/latest)
[![Total](https://img.shields.io/github/downloads/beymans-code/pixel-taskbar-enabler/total?logo=Bookmeter&label=Counts&logoColor=yellow&color=yellow)](https://github.com/beymans-code/pixel-taskbar-enabler/releases)
[![VirusTotal](https://img.shields.io/badge/VirusTotal-0/67_Clean-brightgreen?logo=virustotal)](https://www.virustotal.com/gui/file/7e51bab3b19012ea41728ba714e2daf9c62b45854359c3dea3fd7124aea6b9ae/detection)

</div>

---

### Introducción

Pixel Taskbar Enabler es un **módulo exclusivo de Xposed / LSPosed / Vector** diseñado para forzar la aparición y personalizar la barra de tareas (Taskbar) en el Pixel Launcher nativo de los dispositivos Google Pixel. Trae la experiencia de tabletas a tu dispositivo sin necesidad de modificar el DPI del sistema.

Gracias a que utiliza Xposed, los cambios se aplican en la memoria, haciéndolos no destructivos y fácilmente reversibles con solo deshabilitar el módulo y reiniciar.

> *Espero que en algún momento Google decida incorporar oficialmente estas opciones de personalización en el Pixel Launcher nativo. Mientras tanto, este proyecto seguirá vivo en la medida de lo posible, siempre y cuando a Google no le dé por convertir a Android en un sistema completamente cerrado.*

---

### Características

*   **Activación de la Taskbar:** Fuerza la aparición de la barra de tareas del Pixel Launcher en tu dispositivo móvil.
*   **Escala de Iconos y Carpetas:** Ajusta el tamaño de los iconos en la barra de tareas y el grid de aplicaciones.
*   **Cantidad de Iconos:** Controla cuántas aplicaciones quieres que se muestren simultáneamente en el dock inferior.
*   **Recientes tipo Móvil:** Obliga al sistema a mostrar la vista de "Aplicaciones Recientes" con el estilo clásico de teléfono, incluso cuando la interfaz simula estar en una tablet.

---

### Compatibilidad

Este módulo está diseñado y probado exclusivamente para el **Pixel Launcher** en firmware oficial de Google Pixel.

Compatible con **Android 17**.

> [!WARNING]
> No se garantiza su funcionamiento en ROMs personalizadas (LineageOS, Pixel Experience, etc.) ni en launchers de terceros (Nova, Lawnchair, etc.).

> [!TIP]
> Este módulo requiere una instalación de Magisk o KernelSU y un entorno de Xposed, LSPosed o Vector con Zygisk activado.

---

### 🛡️ Seguridad y Aviso de Play Protect

Dado que esta aplicación solicita permisos especiales para modificar funciones internas del sistema a través de Xposed, es muy común que **Google Play Protect** la marque como "App desconocida" o la bloquee al intentar instalarla. Esto es un falso positivo estándar para módulos root fuera de la Play Store.

✅ **Esta aplicación es 100% segura y de código abierto.**
- No recopila datos, no se conecta a internet y todo el código está disponible públicamente para su revisión.
- Puedes verificar el análisis del APK en **[VirusTotal (0 Detecciones)](https://www.virustotal.com/gui/file/7e51bab3b19012ea41728ba714e2daf9c62b45854359c3dea3fd7124aea6b9ae/detection)**.

> Si Play Protect bloquea la instalación, pulsa en **"Más detalles" (Learn more)** y luego en **"Instalar de todas formas" (Install anyway)**.

---

### Instalación

1. Descarga el último **APK** desde la página de Releases (Lanzamientos).
2. Instala el módulo en tu dispositivo.
3. Abre la aplicación **LSPosed Manager**.
4. Ve a la pestaña de "Módulos" y activa **Pixel Taskbar Enabler**.
5. Asegúrate de que **Pixel Launcher** esté marcado en la lista de aplicaciones objetivo.
6. Abre la aplicación de Pixel Taskbar Enabler, ajusta las opciones a tu gusto y presiona **Aplicar Cambios** (esto reiniciará tu launcher automáticamente).

---

### Descargas

| Canal | Fuente |
| :--- | :--- |
| **Versiones Estables** | [GitHub Releases](https://github.com/beymans-code/pixel-taskbar-enabler/releases) |

---

### Créditos y Agradecimientos

Este proyecto es posible gracias a las siguientes contribuciones de código abierto y equipos:

*   [PixelXpert / AOSPMods](https://github.com/siavash79/PixelXpert): Equipo original (@siavash79 & @ElTifo) de donde se tomó inspiración y código base.
*   [XposedBridge](https://github.com/rovo89/XposedBridge): La creación original de Xposed por @rovo89.
*   [LSPosed](https://github.com/LSPosed/LSPosed): El equipo de LSPosed por mantener el entorno vivo.
*   **Google & Android:** El sistema operativo Android y el equipo de Google.

---

### Licencia

Pixel Taskbar Enabler está licenciado bajo la [GNU General Public License v3](http://www.gnu.org/copyleft/gpl.html).
