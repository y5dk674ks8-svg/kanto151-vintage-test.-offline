# Scanner test build 22

Source repository: `y5dk674ks8-svg/kanto151-vintage`
Source branch: `offline-scanner`
Source commit: `856b343e7adf294ae71b363746826914c3b824c4`
Changes:
- Broader top-title OCR crops and conservative fuzzy Pokémon-name matching.
- Recover card numbers when OCR reads the slash as digit `1` (for example `67/130` as `671130`).
- Require an unambiguous reconstructed number; ambiguous readings remain for manual confirmation.
