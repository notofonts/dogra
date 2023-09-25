## FontBakery report

fontbakery version: 0.9.2

<details><summary><b>[9] NotoSerifDogra-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, tifinagh, cherokee, coptic
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, old-permic, math, tifinagh, malayalam, coptic, tai-le, syriac
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
 * U+030C COMBINING CARON: try adding one of: cherokee, tai-le
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition

Or you can add the above codepoints to one of the subsets supported by the font: `dogra`, `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Avagraha.dogra

	- Eight.dogra

	- Five.dogra

	- Four.dogra

	- Nine.dogra

	- One.dogra

	- Seven.dogra

	- Six.dogra

	- Three.dogra

	- Two.dogra

	- Zero.dogra

	- vowelL.dogra

	- vowelLl.dogra

	- vowelR.dogra

	- vowelRr.dogra
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 310:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

	* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

	* five (U+0035): X=395.5,Y=624.0 (should be at cap-height 625?)

	* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* P (U+0050): X=422.0,Y=625.5 (should be at cap-height 625?)

	* V (U+0056): X=192.0,Y=624.0 (should be at cap-height 625?)

	* V (U+0056): X=520.0,Y=623.0 (should be at cap-height 625?)

	* W (U+0057): X=201.0,Y=624.0 (should be at cap-height 625?)

	* W (U+0057): X=883.0,Y=623.0 (should be at cap-height 625?)

	* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

	* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

	* cent (U+00A2): X=411.0,Y=626.0 (should be at cap-height 625?)

	* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

	* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=83.0,Y=624.0 (should be at cap-height 625?)

	* atilde (U+00E3): X=409.0,Y=623.0 (should be at cap-height 625?)

	* aring (U+00E5): X=195.0,Y=624.0 (should be at cap-height 625?)

	* aring (U+00E5): X=365.0,Y=624.0 (should be at cap-height 625?)

	* ntilde (U+00F1): X=458.0,Y=623.0 (should be at cap-height 625?)

	* otilde (U+00F5): X=416.0,Y=623.0 (should be at cap-height 625?)

	* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

	* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

	* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

	* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

	* uni0122 (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

	* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

	* uring (U+016F): X=219.0,Y=624.0 (should be at cap-height 625?)

	* uring (U+016F): X=389.0,Y=624.0 (should be at cap-height 625?)

	* Wcircumflex (U+0174): X=201.0,Y=624.0 (should be at cap-height 625?)

	* Wcircumflex (U+0174): X=883.0,Y=623.0 (should be at cap-height 625?)

	* ring (U+02DA): X=81.0,Y=624.0 (should be at cap-height 625?)

	* ring (U+02DA): X=251.0,Y=624.0 (should be at cap-height 625?)

	* tilde (U+02DC): X=349.0,Y=623.0 (should be at cap-height 625?)

	* tildecomb (U+0303): X=-187.0,Y=623.0 (should be at cap-height 625?)

	* uni030A (U+030A): X=-85.0,Y=624.0 (should be at cap-height 625?)

	* uni030A (U+030A): X=85.0,Y=624.0 (should be at cap-height 625?)

	* Wgrave (U+1E80): X=201.0,Y=624.0 (should be at cap-height 625?)

	* Wgrave (U+1E80): X=883.0,Y=623.0 (should be at cap-height 625?)

	* Wacute (U+1E82): X=201.0,Y=624.0 (should be at cap-height 625?)

	* Wacute (U+1E82): X=883.0,Y=623.0 (should be at cap-height 625?)

	* Wdieresis (U+1E84): X=201.0,Y=624.0 (should be at cap-height 625?)

	* Wdieresis (U+1E84): X=883.0,Y=623.0 (should be at cap-height 625?)

	* quoteright (U+2019): X=194.0,Y=627.0 (should be at cap-height 625?)

	* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

	* quotedblright (U+201D): X=394.0,Y=627.0 (should be at cap-height 625?)

	* quotedblright (U+201D): X=194.0,Y=627.0 (should be at cap-height 625?)

	* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

	* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?)

	* trademark (U+2122): X=56.0,Y=623.0 (should be at cap-height 625?)

	* trademark (U+2122): X=27.0,Y=623.0 (should be at cap-height 625?)

	* trademark (U+2122): X=325.0,Y=623.0 (should be at cap-height 625?)

	* trademark (U+2122): X=296.0,Y=623.0 (should be at cap-height 625?)

	* Ka.dogra (U+1180A): X=515.0,Y=-2.0 (should be at baseline 0?)

	* Dha.dogra (U+1181C): X=93.5,Y=624.0 (should be at cap-height 625?)

	* Dha.dogra (U+1181C): X=227.5,Y=623.0 (should be at cap-height 625?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* Ba.dogra (U+11820): L<<326.0,385.0>--<242.0,353.0>> -> L<<242.0,353.0>--<239.0,352.0>>

	* Rra.dogra (U+1182B): L<<311.0,70.0>--<293.0,67.0>> -> L<<293.0,67.0>--<235.0,60.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Aghem (Latn, 38,843 speakers), Navajo (Latn, 166,319 speakers), Igbo (Latn, 27,823,640 speakers), Belarusian (Cyrl, 10,064,517 speakers), Basaa (Latn, 332,940 speakers), Ukrainian (Cyrl, 29,273,587 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 1 | 8 | 118 | 7 | 115 | 0 |
| 0% | 0% | 3% | 47% | 3% | 46% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
