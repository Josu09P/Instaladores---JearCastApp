
# 🎵 JearCastApp v1.0.0 - Guía de Instalación

> 📆 Publicado el: **21 de julio de 2025**  
> 🧑‍💻 Desarrollado por: **Josue Elias Algarate Rubio**

JearCastApp es una aplicación de escritorio moderna para escuchar música desde YouTube en Linux, construida con **Electron**, **Vue**, y tecnologías web modernas. Esta guía te mostrará cómo instalarla en tu sistema Linux preferido.

---

## 📦 Paquetes disponibles

| Formato       | Archivo generado                              | Distribución compatible          |
| ------------- | --------------------------------------------- | -------------------------------- |
| `.deb`        | `jearcastapp_electrone_1.0.0_amd64.deb`        | Debian, Ubuntu, Linux Mint, etc |
| `.pacman`     | `jearcastapp_electrone-1.0.0.pacman`           | Arch, Manjaro, EndeavourOS, etc |
| `.AppImage`   | `JearCast Player-1.0.0.AppImage`               | Todas las distribuciones Linux  |

---

## ⚠️ Requisitos importantes

- Tener **Chromium** o un navegador basado en Chromium instalado.  
  > Electron usa Chromium internamente. Algunas distros necesitan este requisito para evitar errores con el sandbox.

### En Debian/Ubuntu:

```bash
sudo apt install chromium
```

### En Arch Linux:

```bash
sudo pacman -S chromium
```

---

## 🐧 Instalación en diferentes distribuciones

### 📥 Debian / Ubuntu / Linux Mint (.deb)

```bash
sudo dpkg -i jearcastapp_electrone_1.0.0_amd64.deb
sudo apt-get install -f  # Solo si hay errores de dependencias
```

---

### 📥 Arch Linux / Manjaro / CachyOS / EndeavourOS (.pacman)

```bash
sudo pacman -U jearcastapp_electrone-1.0.0.pacman
```

---

### 📥 Todas las distros Linux (AppImage)

1. Asigna permisos de ejecución:

```bash
chmod +x 'JearCast Player-1.0.0.AppImage'
```

2. Ejecuta la aplicación:

```bash
./JearCast\ Player-1.0.0.AppImage
```

#### ✅ Recomendación: Instalar **AppImageLauncher**

AppImageLauncher permite que las AppImages se integren como apps nativas en el sistema.

- Página oficial: [https://github.com/TheAssassin/AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher)

##### En Debian/Ubuntu:

```bash
sudo apt install appimagelauncher
```

##### En Arch Linux (usando Yay):

```bash
yay -S appimagelauncher
```

---

## 🙏 Agradecimientos

Gracias a toda la comunidad de **Linux** por su apoyo y sugerencias.  
Esta aplicación nació como una necesidad personal, pero con el tiempo se transformó en un proyecto pensado para todos los que usan Linux y disfrutan de una experiencia moderna, libre y accesible para reproducir su música favorita.

---

## 📫 Contacto y soporte
- Email: josuealgarate24@gmail.com
---

_Disfruta la música como se debe: con estilo y en tu sistema operativo favorito._ 🎶🐧
