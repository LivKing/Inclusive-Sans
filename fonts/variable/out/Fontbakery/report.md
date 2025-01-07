## FontBakery report

fontbakery version: 0.13.0a6





## Check results



<details><summary>[24] InclusiveSans-Italic[wght].ttf</summary>
<div>
<details>
    <summary>💥 <b>ERROR</b> Check if the axes match between the font and the Google Fonts version. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.axes_match.html#"></a></summary>
    <div>







* 💥 **ERROR** <p>Failed with KeyError: 'fvar'</p>
<pre><code>  File &quot;/Users/marichalemma/Google/env/lib/python3.12/site-packages/fontbakery/checkrunner.py&quot;, line 213, in _run_check
    subresults = list(subresults)
                 ^^^^^^^^^^^^^^^^
  File &quot;/Users/marichalemma/Google/env/lib/python3.12/site-packages/fontbakery/checks/vendorspecific/googlefonts/axes_match.py&quot;, line 15, in check_axes_match
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
    <summary>🔥 <b>FAIL</b> Checking OS/2 fsSelection value. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.fsselection.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>OS/2 fsSelection REGULAR bit should be unset.</p>
 [code: bad-REGULAR]



* 🔥 **FAIL** <p>OS/2 fsSelection ITALIC bit should be set.</p>
 [code: bad-ITALIC]





</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking post.italicAngle value. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.italic_angle.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font is italic, so post.italicAngle should be non-zero.</p>
 [code: zero-italic]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Checking head.macStyle value. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/opentype.mac_style.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>head macStyle ITALIC bit should be set.</p>
 [code: bad-ITALIC]





</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Font contains '.notdef' as its first glyph? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/mandatory_glyphs.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The '.notdef' glyph should contain a drawing, but it is blank.</p>
 [code: notdef-is-blank]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check name table IDs 1, 2, 16, 17 to conform to Italic style. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/name.italic_names.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Name ID 1 (Family Name) must not contain 'Italic'.</p>
 [code: bad-familyname]



* 🔥 **FAIL** <p>Name ID 2 (Subfamily Name) does not conform to specs. Only R/I/B/BI are allowed.
Got: 'Regular'.</p>
 [code: bad-subfamilyname]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Space and non-breaking space have the same width? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/whitespace_widths.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Space and non-breaking space have differing width: The space glyph named space is 200 font units wide, non-breaking space named (uni00A0) is 600 font units wide, and both should be positive and the same. GlyphsApp has &quot;Sidebearing arithmetic&quot; (<a href="https://glyphsapp.com/tutorials/spacing">https://glyphsapp.com/tutorials/spacing</a>) which allows you to set the non-breaking space width to always equal the space width.</p>
 [code: different-widths]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check font names are correct <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.font_names.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Font names are incorrect:</p>
<table>
<thead>
<tr>
<th align="left">nameID</th>
<th align="left">current</th>
<th align="left">expected</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Family Name</td>
<td align="left"><strong>Inclusive Sans Italic</strong></td>
<td align="left"><strong>Inclusive Sans</strong></td>
</tr>
<tr>
<td align="left">Subfamily Name</td>
<td align="left"><strong>Regular</strong></td>
<td align="left"><strong>Italic</strong></td>
</tr>
<tr>
<td align="left">Full Name</td>
<td align="left">Inclusive Sans Italic</td>
<td align="left">Inclusive Sans Italic</td>
</tr>
<tr>
<td align="left">Postscript Name</td>
<td align="left">InclusiveSans-Italic</td>
<td align="left">InclusiveSans-Italic</td>
</tr>
<tr>
<td align="left">Typographic Family Name</td>
<td align="left"><strong>Inclusive Sans</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
<tr>
<td align="left">Typographic Subfamily Name</td>
<td align="left"><strong>Italic</strong></td>
<td align="left"><strong>N/A</strong></td>
</tr>
</tbody>
</table>
 [code: bad-names]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/alt_caron.html#"></a></summary>
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
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/mandatory_avar_table.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table. Most variable fonts should include an avar table to correctly define axes progression rates.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/math_signs_width.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 573 among a set of 3 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 614:
plus, equal</p>
<p>Width = 552:
greater, less</p>
<p>Width = 556:
multiply</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.article.images.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at . does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.metadata.unreachable_subsetting.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, coptic, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, old-permic, canadian-aboriginal, malayalam, tifinagh, math, syriac, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
18 more.</li>
</ul>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.utils.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.utils.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̉ į̊ į̋ į̒ į̛̀ į̛́ į̛̂ į̛̃ į̛̄ į̛̆ į̛̇ į̛̈ į̛̉ į̛̊ į̛̋ į̛̌ į̛̒</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ijo, Southeast (Latn, 2,471,000 speakers), Mundani (Latn, 34,000 speakers), Gulay (Latn, 250,478 speakers), Makaa (Latn, 221,000 speakers), Nateni (Latn, 100,000 speakers), Lugbara (Latn, 2,200,000 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Nzakara (Latn, 50,000 speakers), Ebira (Latn, 2,200,000 speakers), Dan (Latn, 1,099,244 speakers), Ma’di (Latn, 584,000 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Bafut (Latn, 158,146 speakers), Kom (Latn, 360,685 speakers), South Central Banda (Latn, 244,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Mango (Latn, 77,000 speakers), Dii (Latn, 71,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Sar (Latn, 500,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Fur (Latn, 1,230,163 speakers), Navajo (Latn, 166,319 speakers), Zapotec (Latn, 490,000 speakers), Yala (Latn, 200,000 speakers), Ejagham (Latn, 120,000 speakers), Southern Kisi (Latn, 360,000 speakers), Mfumte (Latn, 79,000 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.meta.script_lang_tags.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.vendor_id.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> List all superfamily filepaths <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/superfamily.list.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>.</p>
 [code: family-path]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> EPAR table present in font? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/epar.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>EPAR table not present in font. To learn more see <a href="https://github.com/fonttools/fontbakery/issues/818">https://github.com/fonttools/fontbakery/issues/818</a></p>
 [code: lacks-EPAR]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/hinting_impact.html#"></a></summary>
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
<td align="right">91.8kb</td>
</tr>
<tr>
<td align="left">Hinted Size</td>
<td align="right">91.8kb</td>
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
    <summary>ℹ️ <b>INFO</b> Font contains all required tables? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/required_tables.html#"></a></summary>
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
    <summary>ℹ️ <b>INFO</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.description.has_article.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>This font doesn't have an ARTICLE.en_us.html file.</p>
 [code: missing-article]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.gasp.html#"></a></summary>
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
    <summary>ℹ️ <b>INFO</b> Font has old ttfautohint applied? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.old_ttfautohint.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>Could not detect which version of ttfautohint was used in this font. It is typically specified as a comment in the font version entries of the 'name' table. Such font version strings are currently: ['Version 2.002']</p>
 [code: version-not-detected]



</div>
</details>
</div>
</details>

<details><summary>[19] InclusiveSans[wght].ttf</summary>
<div>
<details>
    <summary>💥 <b>ERROR</b> Check if the axes match between the font and the Google Fonts version. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.axes_match.html#"></a></summary>
    <div>







* 💥 **ERROR** <p>Failed with KeyError: 'fvar'</p>
<pre><code>  File &quot;/Users/marichalemma/Google/env/lib/python3.12/site-packages/fontbakery/checkrunner.py&quot;, line 213, in _run_check
    subresults = list(subresults)
                 ^^^^^^^^^^^^^^^^
  File &quot;/Users/marichalemma/Google/env/lib/python3.12/site-packages/fontbakery/checks/vendorspecific/googlefonts/axes_match.py&quot;, line 15, in check_axes_match
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
    <summary>🔥 <b>FAIL</b> Font contains '.notdef' as its first glyph? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/mandatory_glyphs.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The '.notdef' glyph should contain a drawing, but it is blank.</p>
 [code: notdef-is-blank]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Space and non-breaking space have the same width? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/whitespace_widths.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>Space and non-breaking space have differing width: The space glyph named space is 200 font units wide, non-breaking space named (uni00A0) is 600 font units wide, and both should be positive and the same. GlyphsApp has &quot;Sidebearing arithmetic&quot; (<a href="https://glyphsapp.com/tutorials/spacing">https://glyphsapp.com/tutorials/spacing</a>) which allows you to set the non-breaking space width to always equal the space width.</p>
 [code: different-widths]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check accent of Lcaron, dcaron, lcaron, tcaron <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/alt_caron.html#"></a></summary>
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
    <summary>⚠️ <b>WARN</b> Ensure variable fonts include an avar table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/mandatory_avar_table.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This variable font does not have an avar table. Most variable fonts should include an avar table to correctly define axes progression rates.</p>
 [code: missing-avar]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/math_signs_width.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 573 among a set of 3 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 614:
plus, equal</p>
<p>Width = 552:
greater, less</p>
<p>Width = 556:
multiply</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Validate size, and resolution of article images, and ensure article page has minimum length and includes visual assets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.article.images.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at . does not have an article.</p>
 [code: lacks-article]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check for codepoints not covered by METADATA subsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.metadata.unreachable_subsetting.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following codepoints supported by the font are not covered by
any subsets defined in the font's metadata file, and will never
be served. You can solve this by either manually adding additional
subset declarations to METADATA.pb, or by editing the glyphset
definitions.</p>
<ul>
<li>U+02C7 CARON: try adding one of: yi, canadian-aboriginal, tifinagh</li>
<li>U+02D8 BREVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02D9 DOT ABOVE: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DB OGONEK: try adding one of: yi, canadian-aboriginal</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: math, cherokee, coptic, tifinagh</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: tai-le, old-permic, canadian-aboriginal, malayalam, tifinagh, math, syriac, coptic</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage
18 more.</li>
</ul>
<p>Use -F or --full-lists to disable shortening of long lists.</p>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>latin</code>, <code>latin-ext</code>, <code>vietnamese</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.utils.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>No dotted circle glyph present</p>
 [code: missing-dotted-circle]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.utils.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌ ị̀ ị́ ị̂ ị̃ ị̄</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̉ į̊ į̋ į̒ į̛̀ į̛́ į̛̂ į̛̃ į̛̄ į̛̆ į̛̇ į̛̈ į̛̉ į̛̊ į̛̋ į̛̌ į̛̒</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers), Dutch (Latn, 31,709,104 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Ijo, Southeast (Latn, 2,471,000 speakers), Mundani (Latn, 34,000 speakers), Gulay (Latn, 250,478 speakers), Makaa (Latn, 221,000 speakers), Nateni (Latn, 100,000 speakers), Lugbara (Latn, 2,200,000 speakers), Igbo (Latn, 27,823,640 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Vute (Latn, 21,000 speakers), Nzakara (Latn, 50,000 speakers), Ebira (Latn, 2,200,000 speakers), Dan (Latn, 1,099,244 speakers), Ma’di (Latn, 584,000 speakers), Koonzime (Latn, 40,000 speakers), Avokaya (Latn, 100,000 speakers), Cicipu (Latn, 44,000 speakers), Bafut (Latn, 158,146 speakers), Kom (Latn, 360,685 speakers), South Central Banda (Latn, 244,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Ekpeye (Latn, 226,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Mango (Latn, 77,000 speakers), Dii (Latn, 71,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Sar (Latn, 500,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Fur (Latn, 1,230,163 speakers), Navajo (Latn, 166,319 speakers), Zapotec (Latn, 490,000 speakers), Yala (Latn, 200,000 speakers), Ejagham (Latn, 120,000 speakers), Southern Kisi (Latn, 360,000 speakers), Mfumte (Latn, 79,000 speakers), Aghem (Latn, 38,843 speakers), Basaa (Latn, 332,940 speakers).</p>
 [code: soft-dotted]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.meta.script_lang_tags.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Checking OS/2 achVendID. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.vendor_id.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at <a href="https://www.microsoft.com/typography/links/vendorlist.aspx">https://www.microsoft.com/typography/links/vendorlist.aspx</a></p>
 [code: unknown]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> List all superfamily filepaths <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/superfamily.list.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>.</p>
 [code: family-path]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> EPAR table present in font? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/epar.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>EPAR table not present in font. To learn more see <a href="https://github.com/fonttools/fontbakery/issues/818">https://github.com/fonttools/fontbakery/issues/818</a></p>
 [code: lacks-EPAR]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Show hinting filesize impact. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/hinting_impact.html#"></a></summary>
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
<td align="right">89.1kb</td>
</tr>
<tr>
<td align="left">Hinted Size</td>
<td align="right">89.1kb</td>
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
    <summary>ℹ️ <b>INFO</b> Font contains all required tables? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/required_tables.html#"></a></summary>
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
    <summary>ℹ️ <b>INFO</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.description.has_article.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>This font doesn't have an ARTICLE.en_us.html file.</p>
 [code: missing-article]



</div>
</details>

<details>
    <summary>ℹ️ <b>INFO</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.gasp.html#"></a></summary>
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
    <summary>ℹ️ <b>INFO</b> Font has old ttfautohint applied? <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.old_ttfautohint.html#"></a></summary>
    <div>







* ℹ️ **INFO** <p>Could not detect which version of ttfautohint was used in this font. It is typically specified as a comment in the font version entries of the 'name' table. Such font version strings are currently: ['Version 2.002']</p>
 [code: version-not-detected]



</div>
</details>
</div>
</details>

<details><summary>[1] Family checks</summary>
<div>
<details>
    <summary>ℹ️ <b>INFO</b> Check axis ordering on the STAT table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/vendorspecific.googlefonts.STAT.axis_order.html#"></a></summary>
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
| 2 | 0 | 9 | 18 | 175 | 15 | 250 | 0 | 
| 0% | 0% | 2% | 4% | 37% | 3% | 53% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* PASS
* DEBUG
