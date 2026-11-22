# 🚀 Tab Weast — Docklet para RocketDock

![Platform](https://img.shields.io/badge/Plataforma-Windows%2010%20%2F%2011-0078D6?style=flat-square&logo=windows)
![RocketDock](https://img.shields.io/badge/RocketDock-v1.3.5-orange?style=flat-square)
![License](https://img.shields.io/badge/Licencia-Gratuita-brightgreen?style=flat-square)
![Author](https://img.shields.io/badge/Powered%20by-JoseICE-7d7aee?style=flat-square)

**Tab Weast** es un docklet **100% gratuito** para **RocketDock** desarrollado con arquitectura híbrida **C++ (Win32) + WebView2**, diseñado con una estética **Liquid Glass inspirada en macOS Tahoe**. Permite organizar tus aplicaciones, juegos, carpetas y accesos directos en pestañas limpias y personalizables directamente desde la barra de RocketDock.

---

## ✨ Características principales

* **Completamente gratuito:** Libre para descargar, usar y personalizar sin restricciones.
* **Organización por pestañas estilo macOS Tahoe:** Crea múltiples pestañas con íconos categóricos predefinidos (*Carpeta, Favoritos, Juegos, Aplicaciones, Trabajo, Diseño, Desarrollo, Multimedia, Navegador*).
* **Multi-instancia independiente:** Añade tantos elementos **Tab Weast** como necesites en tu barra; cada instancia guarda sus propias pestañas, configuraciones e ícono de forma aislada.
* **Personalización visual completa:**
  * **Temas:** Claro, Oscuro, Tema del Equipo (Windows) y Automático (según la hora del día).
  * **Colores de acento estilo macOS:** Paleta predefinida y selector de color personalizado.
  * **Modos de vista:** Cuadrícula, Lista, Solo Íconos y Solo Texto.
  * **Ordenamiento:** Manual, Alfabético (`A → Z`) e Inverso (`Z → A`).
* **Configuración nativa Win32:** Ventana de configuración de elemento integrada para cambiar y previsualizar el ícono `.png` del docklet en la barra sin reiniciar RocketDock.

---

## 📦 Contenido del repositorio

Al descargar o clonar este repositorio encontrarás los archivos listos para desplegar:

```text
TabWeast/
├── TabWeast.dll          # Librería compilada del docklet (x86 / Win32)
├── icon.png              # Ícono predeterminado del elemento en RocketDock
└── ui/
    └── index.html        # Interfaz gráfica Liquid Glass (HTML/CSS/JS)
