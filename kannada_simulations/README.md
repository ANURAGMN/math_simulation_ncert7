# Kannada simulations (NCERT Class 7 Maths)

Kannada translations of the math simulations from the `cursor/ncert-class-7-chapter-1-e402` branch.

## File naming

All files follow: **math_chapterN_simulationM_conceptname_kn.html**

- **subjectName**: `math`
- **chapterorder**: 1, 2, 3, 4
- **simulationorder**: 1, 2, 3, …
- **conceptname**: snake_case concept (e.g. `place_value_calculator`, `expression_evaluator`)
- **kn**: Kannada language suffix

See `KANNADA_NAMING_MAP.md` for the full mapping from original filenames.

## Translation checklist (per HTML)

1. **HTML**: `lang="kn"`, `dir="ltr"`
2. **Font**: Add Noto Sans Kannada (Google Fonts) in `<head>`
3. **Title & meta**: Kannada title
4. **Body text**: All headings, labels, buttons, help text in Kannada
5. **Visuals**: Chart labels, axis labels, button text in the JS (e.g. `PV[].label`, `TXT` object) in Kannada
6. **Number words**: Use Kannada number names (ಸೊನ್ನೆ, ಒಂದು, ಹತ್ತು, ನೂರು, ಸಾವಿರ, ಲಕ್ಷ, ಕೋಟಿ) where the original has “Zero”, “One”, “Lakh”, etc.
7. **Keep**: Numbers, symbols (+, −, ×, ÷), and maths expressions as-is unless they are part of a sentence.

## Status

All **20** Kannada simulations exist. Sim1 & Sim2 have full Kannada UI; Sim3–Sim20 have lang=kn, Noto Sans Kannada, help panel titles in Kannada, numbers in English. Remaining UI can be translated in a second pass.
