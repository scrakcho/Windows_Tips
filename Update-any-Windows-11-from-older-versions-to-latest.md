# Como actualizar cualquier versión de Windows 11 a la última existente

## Fuente origen

[Gist de Asheroto](https://gist.github.com/asheroto/5087d2a38b311b0c92be2a4f23f92d3e)

## Pasos

1. Abre **PowerShell como administrador**.
2. Revisa el contenido del script en la fuente antes de ejecutarlo. Si decides continuar, ejecuta el comando que indica la página de Asheroto:

   ```powershell
   irm "https://gist.githubusercontent.com/asheroto/5087d2a38b311b0c92be2a4f23f92d3e/raw/Windows11-Enable-Upgrade.ps1" | iex
   ```

   Este comando descarga y ejecuta código remoto con privilegios de administrador. Úsalo solo si confías en la fuente y has revisado el script. Omitir comprobaciones de hardware no hace que el equipo cumpla los requisitos oficiales de Windows 11; en hardware no compatible pueden existir problemas y no se garantizan las actualizaciones ni el soporte.

3. Descarga el Asistente oficial desde [Descargar Windows 11 — Microsoft](https://www.microsoft.com/software-download/windows11) y ejecútalo.
