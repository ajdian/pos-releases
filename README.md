# POS — Instaladores y actualizaciones

Este repositorio **solo contiene binarios** del POS: el instalador (`Pos-stable-Setup.exe`) y los paquetes de actualización que la app descarga sola. **No contiene código fuente** (el código es privado).

## Instalar
1. Abre la sección **[Releases](https://github.com/ajdian/pos-releases/releases)** y descarga `Pos-stable-Setup.exe` de la versión estable más reciente.
2. Ejecútalo con el usuario de Windows que usará la caja. No requiere permisos de administrador ni instalar .NET.
3. Mientras la app no esté firmada, Windows puede mostrar SmartScreen: **Más información → Ejecutar de todas formas** (solo con instaladores descargados de esta página).

## Actualizaciones
La app busca versiones nuevas automáticamente y las instala **al cerrarse**; nunca se reinicia sola.

Las versiones se publican automáticamente desde el repositorio privado al crear un tag `vX.Y.Z`.
