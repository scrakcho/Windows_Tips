# Debloat Win11

## Fuente Origen

[Win11Debloat](https://github.com/Raphire/Win11Debloat) es un script de PowerShell de código abierto para Windows 10 y Windows 11. Permite quitar aplicaciones preinstaladas y ajustar opciones de privacidad y del sistema. Las opciones disponibles pueden variar entre versiones; revisa la documentación y las selecciones antes de aplicar cambios.

## Pasos

1. Haz clic derecho en el botón **Inicio** y selecciona **Terminal (Administrador)** o **Windows PowerShell (Administrador)**.
2. Usa el siguiente comando:

   ```powershell
   & ([scriptblock]::Create((irm "https://debloat.raphi.re/")))
   ```

3. Sigue las opciones que muestre la herramienta. Según la versión, puedes elegir una configuración **predeterminada** o personalizar qué aplicaciones y ajustes aplicar. Lee cada opción antes de confirmarla; quitar componentes o cambiar funciones puede afectar tu uso de Windows.
4. Cuando termine, reinicia el ordenador si la herramienta lo solicita o si los cambios lo requieren.
