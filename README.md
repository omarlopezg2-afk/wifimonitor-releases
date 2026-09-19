# WiFi Monitor — descargas para Linux y macOS

Este repositorio contiene **solo los archivos descargables**. El código fuente es privado.

## Descargas

Ve a la pestaña **[Releases](https://github.com/omarlopezg2-afk/wifimonitor-releases/releases)** y elige la última versión.

| Plataforma | Archivo | Cómo se instala |
|---|---|---|
| 🐧 Linux (Ubuntu/Debian) | `WiFiMonitor_*_amd64.deb` | `sudo apt install ./WiFiMonitor_*.deb` (o doble clic). Queda en el menú de aplicaciones. |
| 🐧 Linux (universal) | `WiFiMonitor-*-x86_64.AppImage` | `chmod +x WiFiMonitor*.AppImage && ./WiFiMonitor*.AppImage` |
| 🍎 macOS (Apple Silicon) | `WiFiMonitor-*-macOS-arm64.dmg` | Abrir el `.dmg` y arrastrar a Aplicaciones. |

**🪟 Windows**: no se distribuye por aquí. La versión oficial está en la [Microsoft Store](https://apps.microsoft.com/store/detail/9P51J5MN0DGM).

## Notas

- Estas builds de Linux y macOS son **completas y gratuitas**. La versión con la parte de pago (Intrusos, Historial de 7 días y Alertas) es la de la Microsoft Store, donde la app es gratis y el desbloqueo se paga una sola vez.
- **macOS**: si Gatekeeper bloquea la app al abrirla, ve a Ajustes → Privacidad y seguridad → *Abrir igualmente*. Solo Apple Silicon (M1 o superior); el soporte para Mac Intel está discontinuado.
- Los archivos se publican automáticamente desde el pipeline de compilación, en la misma versión que se manda a la Store.
