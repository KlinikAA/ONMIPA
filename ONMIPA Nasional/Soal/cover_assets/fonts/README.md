Plus Jakarta Sans for the editable ONMIPA cover
==============================================

Source: https://github.com/google/fonts/tree/main/ofl/plusjakartasans
Upstream: https://github.com/tokotype/PlusJakartaSans
License: SIL Open Font License 1.1; see OFL.txt.

`cnjakarta-sb.ttf` and `cnjakarta-sbi.ttf` are static weight-600 instances
of PlusJakartaSans[wght].ttf and PlusJakartaSans-Italic[wght].ttf, respectively.
They were instantiated with fontTools. Legacy kern tables derived from the
GPOS kerning were added for compatibility with ttf2tfm; outlines were not
redrawn. Instance names were set to SemiBold / SemiBold Italic.

`cnjakarta-t1.enc` uses the standard TeX T1 (Cork) character ordering.
The TFM files were generated with MiKTeX ttf2tfm and pltotf, preserving
kerning and TeX punctuation ligatures. The package loads them locally and
registers PDF font mappings only for this compilation. No system font
installation or global MiKTeX font-map update is required.
