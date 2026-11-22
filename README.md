# Orquestador — descargas

Aquí se publican los **instaladores de la app nativa para Windows** del Orquestador. Este repositorio no contiene código: solo las versiones descargables y sus avisos de licencia.

## Descargar

1. Entra en **[Releases](../../releases/latest)**.
2. Descarga **`Orquestador-Setup-<versión>.exe`** (instalador) o **`Orquestador-<versión>-windows.zip`** (versión portable, sin instalar).
3. Instalador: ábrelo y sigue los pasos. Se instala solo para tu usuario, sin pedir permisos de administrador.
   Portable: descomprime el ZIP y abre `orquestador.exe`.

### Aviso de Windows (SmartScreen)

Las versiones aún no están firmadas digitalmente, así que Windows puede mostrar «Windows protegió su PC».
Pulsa **«Más información»** y después **«Ejecutar de todas formas»**.

## Requisitos

- Windows 10 u 11 de 64 bits.
- Un Orquestador (hub) al que conectarte: la app te pide su dirección al iniciar sesión.

## Actualizaciones

La app avisa sola cuando hay una versión nueva publicada aquí. Para saberlo solo consulta públicamente la última release; no envía datos tuyos.

## Licencias

- La aplicación se distribuye bajo la licencia **MIT** (archivo [`LICENSE`](LICENSE)).
- Usa **Qt 6**, bajo **LGPL v3**, enlazado de forma dinámica. Detalles, cómo sustituir las bibliotecas de Qt y dónde obtener su código fuente en [`AVISO-QT.txt`](AVISO-QT.txt) y [`LGPL-3.0.txt`](LGPL-3.0.txt).
- Los avisos completos de terceros también vienen dentro de cada instalador, en la carpeta `licencias`.
