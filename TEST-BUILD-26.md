# Scanner build 26 — single-line title OCR

Source repository: `y5dk674ks8-svg/kanto151-vintage`
Source branch: `offline-scanner`
Source commit: `f79fa8dc245901732b459ce56336d58e39c1f42f`
Changes:
- The first OCR crop isolates the Pokémon name line only, excluding the Basic Pokémon label and HP value.
- A second narrow crop is used as a backup.
- Tight crops use Tesseract PSM 7 (single line); wider fallback crops use PSM 6 (text block).
- Full diagnostics remain enabled.
