# The Watcher – Horror (Fabric 1.21.11)

Port a Java/Fabric del addon de Bedrock "The Watcher Horror" (versión 1: núcleo del juego).

## Cómo obtener el .jar (sin instalar nada)
1. Crea una cuenta gratis en https://github.com y un repositorio nuevo (público o privado).
2. Sube TODO el contenido de esta carpeta al repositorio (botón "Add file > Upload files", arrastra los archivos y carpetas).
   - IMPORTANTE: tiene que subirse también la carpeta oculta `.github`. Si no se ve en tu explorador,
     en el repo pulsa "Add file > Create new file", escribe el nombre `.github/workflows/build.yml`
     y pega el contenido del archivo `build.yml` de esta carpeta.
3. Ve a la pestaña **Actions**. Espera ~3-5 min a que termine el trabajo "build" (check verde).
4. Abre la ejecución y descarga el artefacto **the-watcher-horror-fabric** (es un zip; dentro está el .jar).
5. Copia el .jar a `.minecraft/mods` (con Fabric Loader 0.18+ y Fabric API para 1.21.11).

Si sale una X roja, copia el error del log de "Compilar" y pásamelo.

## Comandos
`/horror help`, `/horror kit`, `/horror spawn`, `/horror clear`, `/horror sanity <0-100>`, `/horror difficulty <easy|normal|hard|nightmare>`
