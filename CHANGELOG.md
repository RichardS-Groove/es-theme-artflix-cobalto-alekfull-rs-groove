# Historial de versiones · Changelog

Todas las mejoras del tema, de la más nueva a la más vieja. Las versiones siguen el formato `MAYOR.MENOR.ARREGLO`:

- **MAYOR**: cambios grandes de diseño.
- **MENOR**: mejoras nuevas (por ejemplo, una vista o una opción más).
- **ARREGLO**: correcciones chicas.

---

## [1.1.0] — 2026-11-08

### Nuevo · New

- **Android TV** (sistema `android`, para el proyecto
  [Android TV RS Groove](https://github.com/RichardS-Groove/batocera-android-tv-rs-groove)):
  - Logo **«android tv»** con el robot verde (`assets/logos/android.png`): el «android» original con «tv» dibujado
    con el mismo trazo, la misma altura y el mismo borde blanco. El robot de Android es de Google (CC BY 3.0).
  - Textos sutiles (`android/custom.xml`): título «Android TV» y autor «Richard Campos»; año y desarrollador ocultos.
- **Firma «by RS Groove»** chiquita, en el violeta de «COBALTO» y con letra de marcador, a la derecha del logo
  ARTFLIX COBALTO, en las dos capas que lo traen dibujado: `assets/overr.png` (listas de juegos) y
  `assets/cobaltoverlay.png` (menú de sistemas). El logo y los créditos de Fagner (AlekFull) y Galisteo siguen igual.

### Notas · Notes

- El fondo de Android (`assets/arts/android.jpg`) sigue siendo el de ARTFLIX-Cobalto. Si querés uno propio, cambiá
  esa imagen (y las de `720/` y `540/`) por una de 1920×1080.
- Varios archivos de `assets/` pueden estar enlazados (hardlink) con ARTFLIX-Cobalto si los dos temas están
  instalados: para cambiarlos, reemplazá el archivo (copiar a uno nuevo y renombrar), no lo escribas encima.

---

## [1.0.0] — 2026-11-07

Primera versión. Basada en **ARTFLIX-Cobalto** `9cad3de` (Fagner / AlekFull · Galisteo).

### Cambios respecto de ARTFLIX-Cobalto · Changes from ARTFLIX-Cobalto

- **Nueva lista de juegos** (vistas `basic` y `detailed`), inspirada en ALEKFULL NX y redibujada al estilo Artflix:
  - Fondo: arte del sistema (`assets/arts`) + capa violeta de Artflix (`assets/overr.png`) + degradados nuevos
    (`_inc/rs-groove/degrade-izq.png`, `degrade-der.png`) para que el texto se lea con cualquier fondo.
  - Logo del sistema arriba a la izquierda y la lista **debajo**, sin superponerse.
  - Letra *Circular Std*; selección violeta `#5e026d → #1c0640` (los colores del menú de Artflix).
  - Detalle del juego: video o imagen, nombre (*Circular Std Black*), género en rojo `#e0343d`, desarrollador, año,
    estrellas de Artflix y descripción sobre un panel de vidrio oscuro (`_inc/rs-groove/blanco.png` teñido).
- **Vista por defecto**: `detailed` (antes «CoinOps Details»).
- **Quitadas las vistas extra** (CoinOps, NFlix, Pegasus OS, Banner, Fanart, Tiles…) para que la lista nueva sea la
  experiencia principal. La grilla (`grid`) original de Artflix-Cobalto se mantiene.
- Encabezado de créditos en `theme.xml`; README, licencia y este historial nuevos. README original en
  `docs/README-ARTFLIX-COBALTO.md`.
- Aviso automático semanal (`.github/workflows/upstream-check.yml`) cuando ARTFLIX-Cobalto publica cambios.

### Sin cambios · Unchanged

- Pantalla de sistemas, arte, logos, música, sonidos, menús y opciones de Artflix-Cobalto.

[1.0.0]: https://github.com/RichardS-Groove/es-theme-artflix-cobalto-alekfull-rs-groove/releases/tag/v1.0.0
