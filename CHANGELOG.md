## Modifications since version 2.x

### 26.0.2

* Fix incorrect code assignment for `U+2B6E`, `U+2B6F`, `U+2B71`, `U+2B72` (#1895).
* Fix CYRILLIC CAPITAL LETTER KOMI SJE (`U+050C`) to follow serifs of `C` instead of `c` (#1896).


### 26.0.1

* Fix shape of `ij` in Aile under NWID.


### 26.0.0

* \[**Breaking**\] Add asymmetric variant to all `t` styles (#1836).
* \[**Breaking**\] Add separate variant selector for lowercase Thorn (#1854).
* \[**Breaking**\] Drop `tailed-top-left-serifed` variant of `n` as it duplicates with `tailed-motion-serifed` (#1859).
* \[**Breaking**\] Disunified the variant selector for Greek Delta and Greek Lambda, and added selectable serif variants for Lambda (#1866).
* \[**Breaking**\] Add serif variant selection for Eszet (#1881).
* \[**Breaking**\] Add a separate variant selector for lowercase Greek Chi.
* Add Characters:
  - COMBINING DOUBLED CIRCUMFLEX ACCENT (`U+1AB0`) (#1879).
  - COMBINING DOUBLE PLUS SIGN ABOVE (`U+1AC9`) (#1879).
  - COMBINING DOUBLE PLUS SIGN BELOW (`U+1ACA`) (#1879).
  - ANTICLOCKWISE GAPPED CIRCLE ARROW (`U+27F2`).
  - CLOCKWISE GAPPED CIRCLE ARROW (`U+27F3`).
  - ANTICLOCKWISE CLOSED CIRCLE ARROW (`U+2940`).
  - CLOCKWISE CLOSED CIRCLE ARROW (`U+2941`).
  - LEFTWARDS TRIANGLE-HEADED ARROW (`U+2B60`) ... DOWNWARDS TRIANGLE-HEADED ARROW TO BAR (`U+2B73`).
  - LEFTWARDS TRIANGLE-HEADED ARROW WITH DOUBLE HORIZONTAL STROKE (`U+2B7A`) ... DOWNWARDS TRIANGLE-HEADED PAIRED ARROWS (`U+2B87`).
  - LATIN CAPITAL LETTER K WITH DIAGONAL STROKE (`U+A742`).
  - LATIN SMALL LETTER K WITH DIAGONAL STROKE (`U+A743`).
  - LATIN CAPITAL LETTER K WITH STROKE AND DIAGONAL STROKE (`U+A744`).
  - LATIN SMALL LETTER K WITH STROKE AND DIAGONAL STROKE (`U+A745`).
  - LATIN CAPITAL LETTER VOLAPUK AE (`U+A79A`) ... LATIN SMALL LETTER VOLAPUK UE (`U+A79F`) (#1865).
  - CIRCLED ANTICLOCKWISE ARROW (`U+1F10E`).
  - CIRCLED HUMAN FIGURE (`U+1F16F`).
* Drop `<=` and `>=` as inequality for Verilog (#1864).
* Support variant selection for INCREMENT and NABLA (#1873).
* Add APL-specific form for `U+220A` (#1876).
* Enable `<>` ligation as diamond for C-like (#1878).
* Fix support for serifs in Rounded Schwa (#1883).
* Add script-cut corner to `U+0261` (#1887).
* Make Lowercase Schwa to respond to `c`'s serif variants (#1892).
* Fix variant selection for `cv27`, `cv33`, `cv36`, and `cv49` for `ss17` under italics.
* Make Greek Kappa respond to top-left serifed variants of `k`.
* Fix slabs for `U+019C`, `U+0257`, `U+026F`, and `U+0270`.
* Add single-storey variants support for `U+A657`.

