## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[7] NotoSansCoptic-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02B9 MODIFIER LETTER PRIME: not included in any glyphset definition
 * U+02C7 CARON: try adding one of: canadian-aboriginal, tifinagh, yi
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+0605 ARABIC NUMBER MARK ABOVE: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `coptic`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are any segments inordinately short? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_short_segments">com.google.fonts/check/outline_short_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have segments which seem very short:

	* two (U+0032) contains a short segment L<<159.0,84.0>--<159.0,80.0>>

	* at (U+0040) contains a short segment B<<613.0,293.0>-<612.0,275.0>-<612.0,267.5>>

	* at (U+0040) contains a short segment B<<612.0,267.5>-<612.0,260.0>-<612.0,257.0>>

	* M (U+004D) contains a short segment L<<177.0,626.0>--<173.0,626.0>>

	* M (U+004D) contains a short segment L<<450.0,129.0>--<454.0,129.0>>

	* N (U+004E) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* N (U+004E) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* Q (U+0051) contains a short segment B<<416.0,-9.0>-<410.0,-9.0>-<403.5,-9.5>>

	* Q (U+0051) contains a short segment B<<403.5,-9.5>-<397.0,-10.0>-<391.0,-10.0>>

	* W (U+0057) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* a (U+0061) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* d (U+0064) contains a short segment L<<446.0,72.0>--<442.0,72.0>>

	* m (U+006D) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* n (U+006E) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* p (U+0070) contains a short segment L<<169.0,463.0>--<173.0,463.0>>

	* r (U+0072) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* u (U+0075) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Ntilde (U+00D1) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Ntilde (U+00D1) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* germandbls (U+00DF) contains a short segment B<<382.0,412.0>-<382.0,399.0>-<388.5,388.0>>

	* agrave (U+00E0) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aacute (U+00E1) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* acircumflex (U+00E2) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* atilde (U+00E3) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* adieresis (U+00E4) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aring (U+00E5) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* ntilde (U+00F1) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* ugrave (U+00F9) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uacute (U+00FA) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* ucircumflex (U+00FB) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* udieresis (U+00FC) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* amacron (U+0101) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* abreve (U+0103) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* aogonek (U+0105) contains a short segment L<<399.0,76.0>--<395.0,76.0>>

	* dcaron (U+010F) contains a short segment L<<446.0,72.0>--<442.0,72.0>>

	* dcroat (U+0111) contains a short segment L<<445.0,72.0>--<441.0,72.0>>

	* Nacute (U+0143) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Nacute (U+0143) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* nacute (U+0144) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* uni0145 (U+0145) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* uni0145 (U+0145) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* uni0146 (U+0146) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* Ncaron (U+0147) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Ncaron (U+0147) contains a short segment L<<582.0,123.0>--<586.0,123.0>>

	* ncaron (U+0148) contains a short segment L<<169.0,463.0>--<174.0,463.0>>

	* Eng (U+014A) contains a short segment L<<176.0,593.0>--<172.0,593.0>>

	* Eng (U+014A) contains a short segment L<<582.0,142.0>--<586.0,142.0>>

	* eng (U+014B) contains a short segment L<<170.0,463.0>--<175.0,463.0>>

	* racute (U+0155) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* uni0157 (U+0157) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* rcaron (U+0159) contains a short segment L<<167.0,438.0>--<171.0,438.0>>

	* umacron (U+016B) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* ubreve (U+016D) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uring (U+016F) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* uhungarumlaut (U+0171) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Uogonek (U+0172) contains a short segment B<<539.5,-158.5>-<551.0,-156.0>-<559.0,-155.0>>

	* uogonek (U+0173) contains a short segment L<<448.0,71.0>--<444.0,71.0>>

	* Wcircumflex (U+0174) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* uni03EA (U+03EA) contains a short segment L<<190.0,714.0>--<210.0,714.0>>

	* uni1DCD (U+1DCD) contains a short segment L<<-420.0,606.0>--<-420.0,616.0>>

	* Wgrave (U+1E80) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Wacute (U+1E82) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Wdieresis (U+1E84) contains a short segment B<<468.0,577.5>-<463.0,600.0>-<461.0,609.0>>

	* Euro (U+20AC) contains a short segment B<<184.0,390.0>-<183.0,380.0>-<183.0,371.0>>

	* Euro (U+20AC) contains a short segment B<<183.0,371.0>-<183.0,362.0>-<183.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<183.0,352.0>-<183.0,343.0>-<183.0,332.5>>

	* Euro (U+20AC) contains a short segment B<<183.0,332.5>-<183.0,322.0>-<184.0,311.0>>

	* Euro (U+20AC) contains a short segment B<<95.0,311.0>-<94.0,323.0>-<94.0,331.0>>

	* Euro (U+20AC) contains a short segment B<<94.0,331.0>-<94.0,339.0>-<94.0,352.0>>

	* Euro (U+20AC) contains a short segment B<<94.0,352.0>-<94.0,363.0>-<94.5,373.5>>

	* Euro (U+20AC) contains a short segment B<<94.5,373.5>-<95.0,384.0>-<95.0,390.0>>

	* trademark (U+2122) contains a short segment L<<386.0,633.0>--<382.0,633.0>>

	* uni2C8B (U+2C8B) contains a short segment B<<221.5,-175.5>-<215.0,-175.0>-<210.0,-174.0>>

	* uni2C8B (U+2C8B) contains a short segment B<<210.0,-98.0>-<218.0,-99.0>-<223.0,-99.5>>

	* uni2C8B (U+2C8B) contains a short segment B<<223.0,-99.5>-<228.0,-100.0>-<237.0,-100.0>>

	* uni2C96 (U+2C96) contains a short segment B<<131.5,642.5>-<122.0,640.0>-<115.0,637.0>>

	* uni2C96 (U+2C96) contains a short segment B<<554.0,62.0>-<562.0,62.0>-<570.5,64.0>>

	* uni2C96 (U+2C96) contains a short segment B<<570.5,64.0>-<579.0,66.0>-<584.0,67.0>>

	* uni2C9A (U+2C9A) contains a short segment L<<567.0,123.0>--<571.0,123.0>>

	* uni2C9A (U+2C9A) contains a short segment L<<183.0,593.0>--<179.0,593.0>>

	* uni2C9C (U+2C9C) contains a short segment L<<229.0,437.0>--<229.0,434.0>>

	* uni2C9C (U+2C9C) contains a short segment L<<390.0,641.0>--<390.0,643.0>>

	* uni2C9D (U+2C9D) contains a short segment L<<197.0,335.0>--<197.0,332.0>>

	* uni2CF2 (U+2CF2) contains a short segment B<<227.0,837.0>-<232.0,838.0>-<241.0,838.5>>

	* uni2CF2 (U+2CF2) contains a short segment B<<241.0,838.5>-<250.0,839.0>-<263.0,839.0>>

	* uni2CF3 (U+2CF3) contains a short segment B<<209.0,760.0>-<214.0,761.0>-<225.5,761.5>>

	* u102F7 (U+102F7) contains a short segment B<<198.5,-69.5>-<193.0,-78.0>-<193.0,-81.0>>

	* u102FB (U+102FB) contains a short segment B<<132.0,80.0>-<132.0,74.0>-<142.0,72.0>> [code: found-short-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̅ į̆ į̇ į̈ į̊ į̋ į̑ į̒ į̿ į̣̀ į̣́ į̣̂ į̣̃ į̣̄ į̣̅ į̣̆ į̣̇ į̣̈ į̣̊ į̣̋

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers), Igbo (Latn, 27,823,640 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Aghem (Latn, 38,843 speakers), Belarusian (Cyrl, 10,064,517 speakers), Navajo (Latn, 166,319 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 6 | 119 | 7 | 116 | 0 |
| 0% | 0% | 2% | 48% | 3% | 47% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
