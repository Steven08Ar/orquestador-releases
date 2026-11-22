# Orquestador — descargas

Aquí se publican los **instaladores de la app nativa del Orquestador** (Windows, macOS y Linux). Este repositorio no contiene código: solo las versiones descargables y sus avisos de licencia.

> Todavía no hay versiones publicadas. La primera aparecerá en **[Releases](../../releases)** cuando esté lista la versión definitiva.

## Descargar

Entra en **[Releases](../../releases/latest)** y elige el archivo de tu sistema:

| Sistema | Archivo | Notas |
| --- | --- | --- |
| Windows 10 / 11 (64 bits) | `Orquestador-Setup-<versión>.exe` | Instalador. Se instala solo para tu usuario, sin permisos de administrador. |
| Windows (portable) | `Orquestador-<versión>-windows.zip` | Sin instalar: descomprime y abre `orquestador.exe`. |
| macOS | `Orquestador-<versión>.dmg` | Próximamente. |
| Linux | `Orquestador-<versión>-x86_64.AppImage` | Próximamente. |

### Aviso de Windows (SmartScreen)

Las versiones aún no están firmadas digitalmente, así que Windows puede mostrar «Windows protegió su PC».
Pulsa **«Más información»** y después **«Ejecutar de todas formas»**.

## Requisitos

- Un Orquestador (hub) al que conectarte: la app te pide su dirección al iniciar sesión.
- Windows 10/11 de 64 bits · macOS 14 o superior · Linux de 64 bits con un entorno gráfico reciente.

## Actualizaciones

La app se entera sola de las versiones nuevas publicadas aquí:

- **Automático:** comprueba al abrir y después cada pocas horas. Si hay una versión posterior, muestra un aviso.
- **Manual:** en **Ajustes → Actualizaciones** hay un botón para comprobarlo cuando quieras.
- **Instalar:** en Windows, el aviso trae **«Descargar e instalar»**: descarga el instalador, **verifica su huella SHA-256** y solo entonces lo ejecuta; la app se cierra y se vuelve a abrir ya actualizada. En macOS y Linux el aviso abre la página de descarga.
- Solo avisa si la versión nueva trae el archivo de **tu** sistema.
- Solo consulta públicamente la última release; **no envía ningún dato tuyo**.

## Licencias

- La aplicación se distribuye bajo la licencia **MIT** (archivo [`LICENSE`](LICENSE)).
- Usa **Qt 6**, bajo **LGPL v3**, enlazado de forma dinámica. Detalles, cómo sustituir las bibliotecas de Qt y dónde obtener su código fuente en [`AVISO-QT.txt`](AVISO-QT.txt) y [`LGPL-3.0.txt`](LGPL-3.0.txt).
- Los avisos completos de terceros también vienen dentro de cada instalador, en la carpeta `licencias`, y en [`AVISOS-DE-TERCEROS.md`](AVISOS-DE-TERCEROS.md).
