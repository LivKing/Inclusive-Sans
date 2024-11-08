## FontBakery report

fontbakery version: 0.13.0a3





## Check results



<details><summary>[19] InclusiveSans-Italic[wght].ttf</summary>
<div>
<details>
    <summary>💥 <b>ERROR</b> Check if the axes match between the font and the Google Fonts version. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.varfont.html#"></a></summary>
    <div>







* 💥 **ERROR** <p>Failed with KeyError: 'fvar'</p>
<pre><code>  File &quot;/Users/marichalemma/Google/env/lib/python3.12/site-packages/fontbakery/checkrunner.py&quot;, line 213, in _run_check
    subresults = list(subresults)
                 ^^^^^^^^^^^^^^^^
  File &quot;/Users/marichalemma/Google/env/lib/python3.12/site-packages/fontbakery/checks/vendorspecific/googlefonts/varfont.py&quot;, line 18, in check_axes_match
    a.axisTag: (a.minValue, a.maxValue) for a in remote_style[&quot;fvar&quot;].axes
                                                 ~~~~~~~~~~~~^^^^^^^^
  File &quot;/Users/marichalemma/Google/env/lib/python3.12/site-packages/fontTools/ttLib/ttFont.py&quot;, line 461, in __getitem__
    table = self._readTable(tag)
            ^^^^^^^^^^^^^^^^^^^^
  File &quot;/Users/marichalemma/Google/env/lib/python3.12/site-packages/fontTools/ttLib/ttFont.py&quot;, line 468, in _readTable
    data = self.reader[tag]
           ~~~~~~~~~~~^^^^^
  File &quot;/Users/marichalemma/Google/env/lib/python3.12/site-packages/fontTools/ttLib/sfnt.py&quot;, line 109, in __getitem__
    entry = self.tables[Tag(tag)]
            ~~~~~~~~~~~^^^^^^^^^^

</code></pre>
 [code: failed-check]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Font contains '.notdef' as its first glyph? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The '.notdef' glyph should contain a drawing, but it is blank.</p>
 [code: notdef-is-blank]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/some_other_checks.html#"></a></summary>
    <div>









* ⚠️ **WARN** <p>dcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>tcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/some_other_checks.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 start point differs in glyph 'M' between location wght=400 and location wght=300

- Contour 0 in glyph 'M': becomes underweight between wght=400 and wght=300.

- Contour 0 start point differs in glyph 'M' between location wght=300 and location wght=700

- Contour 0 in glyph 'M': becomes underweight between wght=300 and wght=700.

- Contour 0 start point differs in glyph 'plusminus' between location wght=300 and location wght=700

- Contour 0 in glyph 'plusminus': becomes underweight between wght=300 and wght=700.

- Contour 0 start point differs in glyph 'uni0312' between location wght=400 and location wght=300

- Contour 0 in glyph 'uni0312': becomes underweight between wght=400 and wght=300.

- Contour 0 start point differs in glyph 'uni0312' between location wght=300 and location wght=700

- Contour 0 in glyph 'uni0312': becomes underweight between wght=300 and wght=700.

- 165 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table. Most variable fonts should include an avar table to correctly define axes progression rates.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/some_other_checks.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 573 among a set of 3 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 614:
equal, plus</p>
<p>Width = 552:
less, greater</p>
<p>Width = 556:
multiply</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at . does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, old-permic, coptic, syriac, tifinagh, tai-le, math, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
18 more.</li>
</ul>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̉ į̊ į̋ į̒ į̛̀ į̛́ į̛̂ į̛̃ į̛̄ į̛̆ į̛̇ į̛̈ į̛̉ į̛̊ į̛̋ į̛̌ į̛̒</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Kom (Latn, 360,685 speakers), Ekpeye (Latn, 226,000 speakers), Ejagham (Latn, 120,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Mango (Latn, 77,000 speakers), Southern Kisi (Latn, 360,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Fur (Latn, 1,230,163 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Dan (Latn, 1,099,244 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Basaa (Latn, 332,940 speakers), Ngbaka (Latn, 1,020,000 speakers), Lugbara (Latn, 2,200,000 speakers), Avokaya (Latn, 100,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Navajo (Latn, 166,319 speakers), Makaa (Latn, 221,000 speakers), Igbo (Latn, 27,823,640 speakers), Koonzime (Latn, 40,000 speakers), Zapotec (Latn, 490,000 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Aghem (Latn, 38,843 speakers), South Central Banda (Latn, 244,000 speakers), Gulay (Latn, 250,478 speakers), Bafut (Latn, 158,146 speakers), Ma’di (Latn, 584,000 speakers), Vute (Latn, 21,000 speakers), Mundani (Latn, 34,000 speakers), Cicipu (Latn, 44,000 speakers), Yala (Latn, 200,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> List all superfamily filepaths <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/superfamily.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>.</p>
 [code: family-path]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/hinting.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>Hinting filesize impact:</p>
<table>
<thead>
<tr>
<th align="left"></th>
<th align="right">InclusiveSans-Italic[wght].ttf</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Dehinted Size</td>
<td align="right">89.4kb</td>
</tr>
<tr>
<td align="left">Hinted Size</td>
<td align="right">89.4kb</td>
</tr>
<tr>
<td align="left">Increase</td>
<td align="right">24 bytes</td>
</tr>
<tr>
<td align="left">Change</td>
<td align="right">0.0 %</td>
</tr>
</tbody>
</table>
 [code: size-impact]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Font contains all required tables? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/tables.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>This font contains the following optional tables:</p>
<pre><code>- loca

- prep

- GPOS

- GSUB

- gasp
</code></pre>
 [code: optional-tables]





</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.description.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>This font doesn't have an ARTICLE.en_us.html file.</p>
 [code: missing-article]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> EPAR table present in font? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.license.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>EPAR table not present in font. To learn more see <a href="https://github.com/fonttools/fontbakery/issues/818">https://github.com/fonttools/fontbakery/issues/818</a></p>
 [code: lacks-EPAR]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.hinting.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>These are the ppm ranges declared on the gasp table:</p>
<p>PPM &lt;= 65535:
flag = 0x0F
- Use grid-fitting
- Use grayscale rendering
- Use gridfitting with ClearType symmetric smoothing
- Use smoothing along multiple axes with ClearType®</p>
 [code: ranges]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Font has old ttfautohint applied? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.hinting.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>Could not detect which version of ttfautohint was used in this font. It is typically specified as a comment in the font version entries of the 'name' table. Such font version strings are currently: ['Version 2.000']</p>
 [code: version-not-detected]



</div>
</details>
</div>
</details>

<details><summary>[19] InclusiveSans[wght].ttf</summary>
<div>
<details>
    <summary>💥 <b>ERROR</b> Check if the axes match between the font and the Google Fonts version. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.varfont.html#"></a></summary>
    <div>







* 💥 **ERROR** <p>Failed with KeyError: 'fvar'</p>
<pre><code>  File &quot;/Users/marichalemma/Google/env/lib/python3.12/site-packages/fontbakery/checkrunner.py&quot;, line 213, in _run_check
    subresults = list(subresults)
                 ^^^^^^^^^^^^^^^^
  File &quot;/Users/marichalemma/Google/env/lib/python3.12/site-packages/fontbakery/checks/vendorspecific/googlefonts/varfont.py&quot;, line 18, in check_axes_match
    a.axisTag: (a.minValue, a.maxValue) for a in remote_style[&quot;fvar&quot;].axes
                                                 ~~~~~~~~~~~~^^^^^^^^
  File &quot;/Users/marichalemma/Google/env/lib/python3.12/site-packages/fontTools/ttLib/ttFont.py&quot;, line 461, in __getitem__
    table = self._readTable(tag)
            ^^^^^^^^^^^^^^^^^^^^
  File &quot;/Users/marichalemma/Google/env/lib/python3.12/site-packages/fontTools/ttLib/ttFont.py&quot;, line 468, in _readTable
    data = self.reader[tag]
           ~~~~~~~~~~~^^^^^
  File &quot;/Users/marichalemma/Google/env/lib/python3.12/site-packages/fontTools/ttLib/sfnt.py&quot;, line 109, in __getitem__
    entry = self.tables[Tag(tag)]
            ~~~~~~~~~~~^^^^^^^^^^

</code></pre>
 [code: failed-check]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Font contains '.notdef' as its first glyph? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The '.notdef' glyph should contain a drawing, but it is blank.</p>
 [code: notdef-is-blank]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/some_other_checks.html#"></a></summary>
    <div>









* ⚠️ **WARN** <p>dcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>lcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



* ⚠️ **WARN** <p>tcaron is decomposed and therefore could not be checked. Please check manually.</p>
 [code: decomposed-outline]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/some_other_checks.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 0 start point differs in glyph 'M' between location wght=400 and location wght=300

- Contour 0 in glyph 'M': becomes underweight between wght=400 and wght=300.

- Contour 0 start point differs in glyph 'M' between location wght=300 and location wght=700

- Contour 0 in glyph 'M': becomes underweight between wght=300 and wght=700.

- Contour 0 start point differs in glyph 'plusminus' between location wght=300 and location wght=700

- Contour 0 in glyph 'plusminus': becomes underweight between wght=300 and wght=700.

- Contour 0 start point differs in glyph 'uni0312' between location wght=400 and location wght=300

- Contour 0 in glyph 'uni0312': becomes underweight between wght=400 and wght=300.

- Contour 0 start point differs in glyph 'uni0312' between location wght=300 and location wght=700

- Contour 0 in glyph 'uni0312': becomes underweight between wght=300 and wght=700.

- 165 more.
</code></pre>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/varfont.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table. Most variable fonts should include an avar table to correctly define axes progression rates.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/some_other_checks.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 573 among a set of 3 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 614:
equal, plus</p>
<p>Width = 552:
less, greater</p>
<p>Width = 556:
multiply</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at . does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.subsets.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, coptic, tifinagh, cherokee</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, old-permic, coptic, syriac, tifinagh, tai-le, math, malayalam</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
18 more.</li>
</ul>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̉ į̊ į̋ į̒ į̛̀ į̛́ į̛̂ į̛̃ į̛̄ į̛̆ į̛̇ į̛̈ į̛̉ į̛̊ į̛̋ į̛̌ į̛̒</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Kom (Latn, 360,685 speakers), Ekpeye (Latn, 226,000 speakers), Ejagham (Latn, 120,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Mango (Latn, 77,000 speakers), Southern Kisi (Latn, 360,000 speakers), Nateni (Latn, 100,000 speakers), Sar (Latn, 500,000 speakers), Dii (Latn, 71,000 speakers), Fur (Latn, 1,230,163 speakers), Ebira (Latn, 2,200,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Dan (Latn, 1,099,244 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Basaa (Latn, 332,940 speakers), Ngbaka (Latn, 1,020,000 speakers), Lugbara (Latn, 2,200,000 speakers), Avokaya (Latn, 100,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Navajo (Latn, 166,319 speakers), Makaa (Latn, 221,000 speakers), Igbo (Latn, 27,823,640 speakers), Koonzime (Latn, 40,000 speakers), Zapotec (Latn, 490,000 speakers), Mfumte (Latn, 79,000 speakers), Nzakara (Latn, 50,000 speakers), Aghem (Latn, 38,843 speakers), South Central Banda (Latn, 244,000 speakers), Gulay (Latn, 250,478 speakers), Bafut (Latn, 158,146 speakers), Ma’di (Latn, 584,000 speakers), Vute (Latn, 21,000 speakers), Mundani (Latn, 34,000 speakers), Cicipu (Latn, 44,000 speakers), Yala (Latn, 200,000 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.os2.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> List all superfamily filepaths <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/superfamily.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>.</p>
 [code: family-path]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/hinting.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>Hinting filesize impact:</p>
<table>
<thead>
<tr>
<th align="left"></th>
<th align="right">InclusiveSans[wght].ttf</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Dehinted Size</td>
<td align="right">87.0kb</td>
</tr>
<tr>
<td align="left">Hinted Size</td>
<td align="right">87.0kb</td>
</tr>
<tr>
<td align="left">Increase</td>
<td align="right">24 bytes</td>
</tr>
<tr>
<td align="left">Change</td>
<td align="right">0.0 %</td>
</tr>
</tbody>
</table>
 [code: size-impact]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Font contains all required tables? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/tables.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>This font contains the following optional tables:</p>
<pre><code>- loca

- prep

- GPOS

- GSUB

- gasp
</code></pre>
 [code: optional-tables]





</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.description.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>This font doesn't have an ARTICLE.en_us.html file.</p>
 [code: missing-article]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> EPAR table present in font? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.license.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>EPAR table not present in font. To learn more see <a href="https://github.com/fonttools/fontbakery/issues/818">https://github.com/fonttools/fontbakery/issues/818</a></p>
 [code: lacks-EPAR]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.hinting.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>These are the ppm ranges declared on the gasp table:</p>
<p>PPM &lt;= 65535:
flag = 0x0F
- Use grid-fitting
- Use grayscale rendering
- Use gridfitting with ClearType symmetric smoothing
- Use smoothing along multiple axes with ClearType®</p>
 [code: ranges]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Font has old ttfautohint applied? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.hinting.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>Could not detect which version of ttfautohint was used in this font. It is typically specified as a comment in the font version entries of the 'name' table. Such font version strings are currently: ['Version 2.000']</p>
 [code: version-not-detected]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>ℹ️ <b>INFO</b> Check axis ordering on the STAT table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.stat.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>None of the fonts lack a STAT table.</p>
<pre><code>And these are the most common STAT axis orderings:
('wght-ital', 2)
</code></pre>
 [code: summary]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 2 | 0 | 2 | 20 | 189 | 15 | 260 | 0 | 
| 0% | 0% | 0% | 4% | 39% | 3% | 53% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* PASS
* DEBUG
