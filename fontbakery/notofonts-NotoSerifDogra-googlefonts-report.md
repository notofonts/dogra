## FontBakery report

fontbakery version: 0.12.10





## Check results



<details><summary>[10] NotoSerifDogra-Regular.ttf</summary>
<div>
<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file.</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file.</p>
 [code: missing-description]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check if each glyph has the recommended amount of contours. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.</p>
<p>The following glyphs do not have the recommended number of contours:</p>
<pre><code>- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: uogonek	Contours detected: 2	Expected: 1

- Glyph name: Uogonek	Contours detected: 2	Expected: 1

- Glyph name: aogonek	Contours detected: 3	Expected: 2

- Glyph name: uogonek	Contours detected: 2	Expected: 1
</code></pre>
 [code: contour-count]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 559 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 579:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.glyphset.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- Avagraha.dogra

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
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSerifDogra/googlefonts/ttf does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, math, coptic, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: todhri, tai-le, math, syriac, hebrew, old-permic, coptic, duployan, malayalam, canadian-aboriginal, tifinagh</li>
<li>U+030A COMBINING RING ABOVE: try adding one of: syriac, duployan</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: try adding math</li>
<li>U+0327 COMBINING CEDILLA: try adding math</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>dogra</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Dutch (Latn, 31,709,104 speakers), Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Mundani (Latn, 34,000 speakers), Mango (Latn, 77,000 speakers), Zapotec (Latn, 490,000 speakers), Makaa (Latn, 221,000 speakers), Fur (Latn, 1,230,163 speakers), Vute (Latn, 21,000 speakers), Teke-Ebo (Latn, 260,000 speakers), Nzakara (Latn, 50,000 speakers), Southern Kisi (Latn, 360,000 speakers), Lugbara (Latn, 2,200,000 speakers), Koonzime (Latn, 40,000 speakers), Aghem (Latn, 38,843 speakers), Cicipu (Latn, 44,000 speakers), Mfumte (Latn, 79,000 speakers), Nateni (Latn, 100,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Dan (Latn, 1,099,244 speakers), Sar (Latn, 500,000 speakers), Ejagham (Latn, 120,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Heiltsuk (Latn, 300 speakers), Bafut (Latn, 158,146 speakers), Gulay (Latn, 250,478 speakers), Ngbaka (Latn, 1,020,000 speakers), Kom (Latn, 360,685 speakers), Dii (Latn, 71,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Ekpeye (Latn, 226,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Avokaya (Latn, 100,000 speakers), Navajo (Latn, 166,319 speakers), Yala (Latn, 200,000 speakers), South Central Banda (Latn, 244,000 speakers), Kaska (Latn, 125 speakers), Ebira (Latn, 2,200,000 speakers), Igbo (Latn, 27,823,640 speakers), Ma’di (Latn, 584,000 speakers), Basaa (Latn, 332,940 speakers), Han (Latn, 6 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Are there any misaligned on-curve points? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have on-curve points which have potentially incorrect y coordinates:</p>
<pre><code>* Ka.dogra (U+1180A): X=515.0,Y=-2.0 (should be at baseline 0?)

* Dha.dogra (U+1181C): X=93.5,Y=624.0 (should be at cap-height 625?)

* Dha.dogra (U+1181C): X=227.5,Y=623.0 (should be at cap-height 625?)

* vowelAi.old2.dogra: X=422.0,Y=0.5 (should be at baseline 0?)

* Nga.old2.dogra: X=337.5,Y=626.0 (should be at cap-height 625?)

* Nga.old2.dogra: X=425.5,Y=626.0 (should be at cap-height 625?)

* matraAuAnusvara.old.dogra: X=-178.0,Y=1129.5 (should be at ascender 1130?)

* matraAuAnusvara.old.dogra: X=-242.5,Y=1129.0 (should be at ascender 1130?)

* matraAuAnusvara.old.dogra: X=-347.5,Y=1128.5 (should be at ascender 1130?)

* NuktamatraUu.old.dogra: X=-117.0,Y=-363.0 (should be at descender -364?)

* Two.dogra: X=356.0,Y=-2.0 (should be at baseline 0?)

* Two.dogra: X=136.0,Y=623.0 (should be at cap-height 625?)

* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

* Gbreve (U+011E): X=519.0,Y=1.5 (should be at baseline 0?)

* uni0122 (U+0122): X=519.0,Y=1.5 (should be at baseline 0?)

* Gdotaccent (U+0120): X=519.0,Y=1.5 (should be at baseline 0?)

* P (U+0050): X=422.0,Y=625.5 (should be at cap-height 625?)

* V (U+0056): X=192.0,Y=624.0 (should be at cap-height 625?)

* V (U+0056): X=520.0,Y=623.0 (should be at cap-height 625?)

* W (U+0057): X=201.0,Y=624.0 (should be at cap-height 625?)

* W (U+0057): X=883.0,Y=623.0 (should be at cap-height 625?)

* Wacute (U+1E82): X=201.0,Y=624.0 (should be at cap-height 625?)

* Wacute (U+1E82): X=883.0,Y=623.0 (should be at cap-height 625?)

* Wcircumflex (U+0174): X=201.0,Y=624.0 (should be at cap-height 625?)

* Wcircumflex (U+0174): X=883.0,Y=623.0 (should be at cap-height 625?)

* Wdieresis (U+1E84): X=201.0,Y=624.0 (should be at cap-height 625?)

* Wdieresis (U+1E84): X=883.0,Y=623.0 (should be at cap-height 625?)

* Wgrave (U+1E80): X=201.0,Y=624.0 (should be at cap-height 625?)

* Wgrave (U+1E80): X=883.0,Y=623.0 (should be at cap-height 625?)

* aring (U+00E5): X=195.0,Y=624.0 (should be at cap-height 625?)

* aring (U+00E5): X=365.0,Y=624.0 (should be at cap-height 625?)

* atilde (U+00E3): X=409.0,Y=623.0 (should be at cap-height 625?)

* cent (U+00A2): X=411.0,Y=626.0 (should be at cap-height 625?)

* comma (U+002C): X=114.0,Y=1.0 (should be at baseline 0?)

* five (U+0035): X=395.5,Y=624.0 (should be at cap-height 625?)

* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?)

* gbreve (U+011F): X=161.0,Y=-0.5 (should be at baseline 0?)

* uni0123 (U+0123): X=161.0,Y=-0.5 (should be at baseline 0?)

* gdotaccent (U+0121): X=161.0,Y=-0.5 (should be at baseline 0?)

* nine (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

* ntilde (U+00F1): X=458.0,Y=623.0 (should be at cap-height 625?)

* ordfeminine (U+00AA): X=83.0,Y=624.0 (should be at cap-height 625?)

* otilde (U+00F5): X=416.0,Y=623.0 (should be at cap-height 625?)

* q (U+0071): X=412.5,Y=0.5 (should be at baseline 0?)

* quotedblbase (U+201E): X=314.0,Y=1.0 (should be at baseline 0?)

* quotedblbase (U+201E): X=114.0,Y=1.0 (should be at baseline 0?)

* quotedblright (U+201D): X=394.0,Y=627.0 (should be at cap-height 625?)

* quotedblright (U+201D): X=194.0,Y=627.0 (should be at cap-height 625?)

* quoteright (U+2019): X=194.0,Y=627.0 (should be at cap-height 625?)

* quotesinglbase (U+201A): X=114.0,Y=1.0 (should be at baseline 0?)

* ring (U+02DA): X=81.0,Y=624.0 (should be at cap-height 625?)

* ring (U+02DA): X=251.0,Y=624.0 (should be at cap-height 625?)

* uni030A (U+030A): X=-85.0,Y=624.0 (should be at cap-height 625?)

* uni030A (U+030A): X=85.0,Y=624.0 (should be at cap-height 625?)

* section (U+00A7): X=101.0,Y=2.0 (should be at baseline 0?)

* semicolon (U+003B): X=132.0,Y=1.0 (should be at baseline 0?)

* sterling (U+00A3): X=77.0,Y=1.0 (should be at baseline 0?)

* three (U+0033): X=334.5,Y=1.0 (should be at baseline 0?)

* tilde (U+02DC): X=349.0,Y=623.0 (should be at cap-height 625?)

* tildecomb (U+0303): X=-187.0,Y=623.0 (should be at cap-height 625?)

* trademark (U+2122): X=56.0,Y=623.0 (should be at cap-height 625?)

* trademark (U+2122): X=27.0,Y=623.0 (should be at cap-height 625?)

* trademark (U+2122): X=325.0,Y=623.0 (should be at cap-height 625?)

* trademark (U+2122): X=296.0,Y=623.0 (should be at cap-height 625?)

* uring (U+016F): X=219.0,Y=624.0 (should be at cap-height 625?)

* uring (U+016F): X=389.0,Y=624.0 (should be at cap-height 625?)
</code></pre>
 [code: found-misalignments]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Do any segments have colinear vectors? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/outline.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs have colinear vectors:</p>
<pre><code>* Ba.dogra (U+11820): L&lt;&lt;326.0,385.0&gt;--&lt;242.0,353.0&gt;&gt; -&gt; L&lt;&lt;242.0,353.0&gt;--&lt;239.0,352.0&gt;&gt;

* Rra.dogra (U+1182B): L&lt;&lt;311.0,70.0&gt;--&lt;293.0,67.0&gt;&gt; -&gt; L&lt;&lt;293.0,67.0&gt;--&lt;235.0,60.0&gt;&gt;

* Tha.old1.dogra: L&lt;&lt;194.0,417.0&gt;--&lt;193.0,409.0&gt;&gt; -&gt; L&lt;&lt;193.0,409.0&gt;--&lt;184.0,358.0&gt;&gt;

* VaMatraR.dogra: L&lt;&lt;434.0,224.0&gt;--&lt;381.0,198.0&gt;&gt; -&gt; L&lt;&lt;381.0,198.0&gt;--&lt;364.0,190.0&gt;&gt;
</code></pre>
 [code: found-colinear-vectors]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 1 | 9 | 116 | 6 | 119 | 0 | 
| 0% | 0% | 0% | 4% | 46% | 2% | 47% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
