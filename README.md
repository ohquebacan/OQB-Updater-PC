# OQB Updater para Mac y PC

Prepara y mantiene la microSD de tu Nintendo Switch desde la computadora: instala el pack HATS y apps, prueba si una tarjeta es falsa, formatea en FAT32, copia partidas y migra todo a otra tarjeta.

## Descarga

Baja la última versión en [Releases](https://github.com/ohquebacan/OQB-Updater-PC/releases/latest).

| Sistema | Archivo |
|---|---|
| **Mac** (Apple Silicon e Intel) | `OQB-Updater-Mac.dmg` |
| **Windows**, con instalador | `OQB-Updater-PC-setup.exe` |
| **Windows**, portátil | `OQB-Updater-PC.exe` |

La app avisa cuando hay una versión nueva y se actualiza desde ella misma. La versión portátil, al actualizar, pasa a la versión con instalador.

## Abrirla en Mac

La app todavía no está firmada por Apple, así que macOS la bloquea la primera vez.

1. Abre el `.dmg` y arrastra **OQB Updater Mac** a Aplicaciones.
2. Abre **Terminal**, pega esta línea y pulsa Enter:

   ```bash
   xattr -dr com.apple.quarantine "/Applications/OQB Updater Mac.app"
   ```

3. Abre la app como cualquier otra.

Si aparece un error de permisos, agrega `sudo` al inicio de la línea. Te pedirá la contraseña de tu Mac; al escribirla no se ve nada. También puedes intentar abrirla e ir a **Ajustes del Sistema › Privacidad y seguridad › Abrir igualmente**.

## Abrirla en Windows

Windows puede mostrar un aviso porque la app no está firmada: pulsa **Más información** y luego **Ejecutar de todas formas**. Las operaciones con la tarjeta piden permiso de administrador.

## Antes de usarla

Haz un respaldo de lo importante: formatear, migrar y medir la capacidad de una tarjeta borran datos.

---

**OH! QUÉ BACÁN**
