## Curso Git desde cero
Sistema de control de versiones para el mantenimiento eficiente y confiable de archivos

### Zonas de Git
1. Directorio de trabajo
2. Area de preparacion
3. Directorio Git

### Flujo de trabajo basico en Git
1. Modificas una serie de archivos en tu directorio de trabajo.
2. Preparas los archivos, añadiendolos a tu area de preparacion.
3. Confirmas los cambios, lo que toma los archivos tal y como estan en el area de preparacion y almacena esa copia instantanea de manera permanente en tu directorio Git.

### Configurando Git por primera vez
´´´
git config --global user.name "nombre de ususario"
git config --global user.email <<email>
git config --global core.editor nano
git config --list
´´´