# Debloat Win11

## Método 1: Win11Debloat (recomendado)

[Win11Debloat](https://github.com/Raphire/Win11Debloat) es un script de PowerShell de código abierto para Windows 10 y Windows 11. Permite quitar aplicaciones preinstaladas y ajustar opciones de privacidad y del sistema. Las opciones disponibles pueden variar entre versiones; revisa la documentación y las selecciones antes de aplicar cambios.

## Pasos

1. Haz clic derecho en el botón **Inicio** y selecciona **Terminal (Administrador)** o **Windows PowerShell (Administrador)**.
2. Para consultar el comando e instrucciones oficiales, visita el [repositorio de Win11Debloat](https://github.com/Raphire/Win11Debloat). El comando de inicio publicado por el proyecto es:

   ```powershell
   & ([scriptblock]::Create((irm "https://debloat.raphi.re/")))
   ```

   Este comando descarga y ejecuta un script remoto. Antes de ejecutarlo, revisa el contenido y las instrucciones en la fuente oficial. No uses el enlace incompleto `https://githubusercontent.com` que aparecía en el borrador.

3. Sigue las opciones que muestre la herramienta. Según la versión, puedes elegir una configuración predeterminada o personalizar qué aplicaciones y ajustes aplicar. Lee cada opción antes de confirmarla; quitar componentes o cambiar funciones puede afectar tu uso de Windows.
4. Cuando termine, reinicia el ordenador si la herramienta lo solicita o si los cambios lo requieren.

## Recomendaciones

- Crea un punto de restauración y guarda tus archivos importantes antes de modificar el sistema.
- Descarga el proyecto solo desde su [repositorio oficial](https://github.com/Raphire/Win11Debloat) y consulta allí la documentación actualizada.
- No se proporcionó el enlace del video mencionado; añádelo aquí cuando esté disponible.
