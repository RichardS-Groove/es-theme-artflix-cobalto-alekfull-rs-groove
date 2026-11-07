# Historial de versiones · Changelog

Todas las mejoras del tema, de la más nueva a la más vieja. Las versiones siguen el formato `MAYOR.MENOR.ARREGLO`:

- **MAYOR**: cambios grandes de diseño.
- **MENOR**: mejoras nuevas (por ejemplo, una vista o una opción más).
- **ARREGLO**: correcciones chicas.

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
