# 🚀 LuminaKraft Launcher - Releases

[![Latest Release](https://img.shields.io/github/v/release/luminakraft/luminakraft-launcher-releases?style=for-the-badge&logo=github&color=blue)](https://github.com/luminakraft/luminakraft-launcher-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/luminakraft/luminakraft-launcher-releases/total?style=for-the-badge&logo=download&color=green)](https://github.com/luminakraft/luminakraft-launcher-releases/releases)
[![Windows](https://img.shields.io/badge/Windows-10%2B-blue?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/luminakraft/luminakraft-launcher-releases/releases/latest)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

> **Un lanzador de modpacks personalizado para Minecraft, desarrollado específicamente para la comunidad de LuminaKraft Studios.**

## 📋 Descripción

**LuminaKraft Launcher** es un lanzador moderno y eficiente para modpacks de Minecraft, construido con tecnología de vanguardia (Tauri, React, TypeScript y Rust) y potenciado por la biblioteca Lyceris. Ofrece una experiencia completa de gestión de modpacks con actualizaciones automáticas, soporte offline y una interfaz intuitiva.

### ✨ Características Principales

- 🎮 **Gestión Completa de Modpacks**: Instalación automática y gestión de instancias aisladas
- 🔄 **Actualizaciones Automáticas**: Sistema completamente automático con un solo clic
- ⚡ **Gestión Automática de Java**: Descarga e instala automáticamente la versión correcta de Java
- 🎯 **Modo Offline**: Compatible con usuarios premium y no premium
- 🖥️ **Interfaz Moderna**: Diseño intuitivo con tema oscuro y componentes responsivos
- 🛠️ **Múltiples Modloaders**: Soporte para Forge, Fabric, Quilt y NeoForge
- 📊 **Descargas Optimizadas**: Descargas paralelas 3-5x más rápidas con verificación de integridad

---

## 💾 Descarga e Instalación

### 📥 Descarga para Windows

**👉 [Descargar Última Versión](https://github.com/luminakraft/luminakraft-launcher-releases/releases/latest)**

#### Opciones de Instalación:

| Tipo | Descripción | Recomendado Para |
|------|-------------|------------------|
| **`.msi`** | Instalador completo con registro en sistema | ✅ **Usuarios generales** |
| **`.exe`** | Ejecutable portable autocontenido | 💻 Usuarios avanzados |

### 🔧 Pasos de Instalación

#### Para archivo `.msi` (Recomendado):
1. **Descarga** el archivo `.msi` desde la [página de releases](https://github.com/luminakraft/luminakraft-launcher-releases/releases/latest)
2. **Ejecuta** el archivo descargado como administrador
3. **Sigue** el asistente de instalación
4. **Busca** "LuminaKraft Launcher" en el menú de inicio

#### Para archivo `.exe` (Portable):
1. **Descarga** el archivo `.exe` desde la [página de releases](https://github.com/luminakraft/luminakraft-launcher-releases/releases/latest)
2. **Crea** una carpeta dedicada (ej: `C:\LuminaKraftLauncher\`)
3. **Mueve** el archivo `.exe` a esa carpeta
4. **Ejecuta** el archivo directamente

---

## ⚙️ Requisitos del Sistema

### Requisitos Mínimos:
- **Sistema Operativo**: Windows 10 (build 1903) o superior
- **RAM**: 4 GB (mínimo), 8 GB recomendado
- **Espacio en Disco**: 2 GB libres (más espacio para modpacks)
- **Conexión a Internet**: Requerida para descargas y actualizaciones

### Requisitos Automáticos:
- ☑️ **Java**: Se instala automáticamente (no requiere instalación manual)
- ☑️ **Actualizaciones**: Sistema automático integrado
- ☑️ **Dependencias**: Todas las librerías necesarias están incluidas

---

## 🔄 Sistema de Actualizaciones Automáticas

### ✨ Características de las Actualizaciones:

- **🔍 Detección Automática**: Verifica nuevas versiones al iniciar la aplicación
- **📱 Notificaciones Elegantes**: Interfaz moderna para gestionar actualizaciones
- **⚡ Un Clic para Actualizar**: Descarga, instala y reinicia automáticamente
- **🔒 Seguridad**: Descargas verificadas directamente desde GitHub
- **📝 Notas de Versión**: Muestra qué hay de nuevo en cada actualización

### 🔄 Proceso de Actualización:
1. El launcher verifica automáticamente al iniciar
2. Te notifica si hay una nueva versión disponible
3. Un clic descarga e instala la actualización
4. El launcher se reinicia automáticamente con la nueva versión

---

## 📸 Capturas de Pantalla

<!-- Screenshots will be added here -->
*📋 Las capturas de pantalla se agregarán en futuras actualizaciones del README.*

### Vista Previa de Características:
- 🎮 Pantalla principal con lista de modpacks
- ⚙️ Panel de configuración avanzada
- 📊 Monitor de descargas en tiempo real
- 🔄 Sistema de actualizaciones integrado

---

## ❓ Preguntas Frecuentes (FAQ)

### 🔧 Instalación y Configuración

**Q: ¿Necesito instalar Java por separado?**  
A: No, LuminaKraft Launcher utiliza la biblioteca Lyceris que descarga e instala automáticamente la versión correcta de Java para cada modpack.

**Q: ¿Funciona sin cuenta premium de Minecraft?**  
A: Sí, el launcher tiene soporte completo para modo offline y usuarios sin cuenta premium.

**Q: ¿Dónde se instalan los modpacks?**  
A: En `%APPDATA%\LuminaKraftLauncher\instances\` - cada modpack en su propia carpeta aislada.

### 🚫 Problemas Comunes

**Q: "La aplicación no se abre" o "Error al iniciar"**  
A: 
1. Ejecuta como administrador
2. Verifica que Windows Defender no esté bloqueando el archivo
3. Descarga nuevamente desde el enlace oficial

**Q: "Error de descarga de modpack"**  
A: 
1. Verifica tu conexión a internet
2. El sistema reintentará automáticamente las descargas fallidas
3. Lyceris incluye verificación de integridad automática

**Q: "Problemas de memoria/RAM"**  
A: 
1. Ajusta la RAM asignada en Configuración
2. El launcher optimiza automáticamente la configuración JVM
3. Recomendamos mínimo 4GB de RAM total en el sistema

### 🔄 Actualizaciones

**Q: ¿Cómo actualizo el launcher?**  
A: Las actualizaciones son completamente automáticas. El launcher te notificará cuando haya una nueva versión y se actualizará con un clic.

**Q: ¿Perderé mis modpacks al actualizar?**  
A: No, todas tus instancias, configuraciones y partidas guardadas se mantienen intactas durante las actualizaciones.

---

## 🔗 Enlaces Oficiales

### 🌐 Sitios Web y Comunidad
- **🏠 [Sitio Web Oficial](https://luminakraft.com)** - Página principal de LuminaKraft Studios
- **💬 [Discord Oficial](https://discord.gg/luminakraft)** - Comunidad, soporte y noticias
- **📺 [YouTube](https://youtube.com/@luminakraft)** - Tutoriales y contenido oficial
- **🐦 [Twitter](https://twitter.com/luminakraft)** - Actualizaciones y anuncios

### 🛠️ Soporte Técnico
- **🐛 [Reportar Problemas](https://github.com/luminakraft/luminakraft-launcher-releases/issues)** - Issues de GitHub
- **📖 [Documentación](https://docs.luminakraft.com)** - Guías detalladas
- **❓ [Centro de Ayuda](https://help.luminakraft.com)** - Base de conocimientos

---

## ⚠️ Información Importante

### 🔒 Código Fuente
> **Nota**: Este repositorio contiene únicamente las **releases públicas** del LuminaKraft Launcher. El código fuente es **privado** y está desarrollado por LuminaKraft Studios. Las releases aquí publicadas son completamente **gratuitas** y **seguras** para uso público.

### 🛡️ Seguridad
- ✅ Todas las releases están firmadas digitalmente
- ✅ Verificación automática de integridad de archivos
- ✅ Sin telemetría invasiva ni recolección de datos personales
- ✅ Código malware-free verificado por Windows Defender

### 📋 Licencia
Este software se distribuye bajo la **Licencia MIT**. Ver [LICENSE](LICENSE) para más detalles.

---

## 🎯 Próximas Características

### 🔮 En Desarrollo:
- 🌍 **Soporte Multiplataforma**: Versiones para macOS y Linux
- 🎨 **Temas Personalizables**: Más opciones de personalización de interfaz
- 📊 **Estadísticas Avanzadas**: Métricas de tiempo de juego y rendimiento
- 🔧 **Configuración Cloud**: Sincronización de configuraciones entre dispositivos

---

## 👥 Comunidad y Contribuciones

### 🤝 Únete a Nuestra Comunidad
- **Discord**: Más de 1,000 miembros activos
- **Eventos**: Torneos y eventos regulares de la comunidad
- **Soporte**: Ayuda de la comunidad y staff oficial 24/7

### 📝 Reportar Problemas
Si encuentras algún problema:
1. **Busca** en [issues existentes](https://github.com/luminakraft/luminakraft-launcher-releases/issues)
2. **Crea** un nuevo issue con detalles específicos
3. **Incluye** tu versión de Windows y detalles del error

---

## 📊 Estadísticas del Proyecto

![GitHub Release Date](https://img.shields.io/github/release-date/luminakraft/luminakraft-launcher-releases?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/luminakraft/luminakraft-launcher-releases?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/luminakraft/luminakraft-launcher-releases?style=flat-square)

---

<div align="center">

## 💖 Desarrollado con ❤️ por LuminaKraft Studios

**¿Te gusta el proyecto? ¡Dale una ⭐ y compártelo con tus amigos!**

[⚡ Descargar Ahora](https://github.com/luminakraft/luminakraft-launcher-releases/releases/latest) • [💬 Discord](https://discord.gg/luminakraft) • [🌐 Sitio Web](https://luminakraft.com)

</div>

---

*Última actualización del README: Enero 2024* 