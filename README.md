# SchooldaysGUIA

Descargas de SchooldaysGUIA para Minecraft Java 1.21.1 con Fabric.

## Instalación

1. Abrí [la última versión](https://github.com/zlAquiles/SchooldaysGUIA-Releases/releases/latest) y descargá el archivo JAR de **Assets**.
2. Cerrá Minecraft y guardá el JAR en la carpeta mods del perfil de Fabric 1.21.1. Si ya había una versión de SchooldaysGUIA, reemplazala.
3. Entrá a SchoolDays Roleplay y usá /guia.

## Actualizador de Windows

Descargá Actualizar-SchooldaysGUIA.ps1 desde la última release. Con Minecraft cerrado, ejecutalo en PowerShell y pasale la carpeta mods del perfil:

```powershell
& "C:\ruta\Actualizar-SchooldaysGUIA.ps1" -Repository "zlAquiles/SchooldaysGUIA-Releases" -ModsDirectory "C:\ruta\del\perfil\mods"
```

El actualizador verifica el archivo SHA-256 y conserva la versión anterior como respaldo. Si querés abrir el launcher al terminar, agregá -Launcher seguido de la ruta de su ejecutable.
