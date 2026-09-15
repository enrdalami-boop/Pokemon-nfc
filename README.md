# Pokémon NFC Player (GitHub Pages)

Plantilla para abrir una página desde una etiqueta NFC y ejecutar un emulador
de Game Boy / Game Boy Color / Game Boy Advance en el navegador.

## Importante

Este repositorio **no incluye ROMs comerciales**. Usa únicamente copias de juegos
que tengas derecho a utilizar.

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo `nfc-pokemon`.
2. Sube todos los archivos de esta carpeta a la rama `main`.
3. Ve a **Settings → Pages**.
4. En **Build and deployment → Source**, elige **GitHub Actions**.
5. Espera a que termine el workflow `Deploy GitHub Pages`.
6. La URL tendrá normalmente esta forma:

   `https://TU-USUARIO.github.io/nfc-pokemon/`

## Usar el NFC

Graba en la etiqueta NFC un registro de tipo **URL/URI** con la dirección de tu
GitHub Pages. Al acercar un teléfono compatible, se abrirá la web.

## Usar el emulador

1. Abre la web desde el NFC.
2. Pulsa **Elegir ROM**.
3. Selecciona en tu dispositivo un archivo legal `.gb`, `.gbc` o `.gba`.
4. El emulador detectará el sistema y arrancará.

## Por qué la ROM no está en GitHub

Un repositorio o una web pública que contenga una ROM comercial puede distribuir
material protegido. Esta plantilla carga el archivo localmente desde el teléfono
y no lo sube al repositorio.
