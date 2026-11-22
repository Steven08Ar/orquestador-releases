# Licencias de terceros (`apps/desktop`)

| Biblioteca | Versión | Licencia | Origen |
| --- | --- | --- | --- |
| QtKeychain | `0.18.0` | Modified BSD (3-Clause BSD) | https://github.com/frankosterfeld/qtkeychain |

## Notas de cumplimiento

- **QtKeychain**: se integra mediante CMake `FetchContent` (`BUILD_SHARED_LIBS=OFF`, `BUILD_WITH_QT6=ON`) para almacenar el token de sesión en el llavero del sistema operativo (Windows Credential Manager, macOS Keychain, Linux Secret Service/KWallet).
- El texto íntegro de su licencia se encuentra en el archivo `COPYING` del repositorio oficial de QtKeychain (`tag 0.18.0`).
