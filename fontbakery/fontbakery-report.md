## Fontbakery report

Fontbakery version: 0.8.10

<details><summary><b>[1] Family checks</b></summary><div><details><summary>⚠ <b>WARN:</b> Make sure all font files have the same version value. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/head.html#com.google.fonts/check/family/equal_font_versions">com.google.fonts/check/family/equal_font_versions</a>)</summary><div>


* ⚠ **WARN** Version info differs among font files of the same font project.
These were the version values found:
* fonts/ttf/Rubik-Regular.ttf: 2.10400390625
* fonts/ttf/Rubik-LightItalic.ttf: 2.1020050048828125
* fonts/ttf/Rubik-BlackItalic.ttf: 2.1020050048828125
* fonts/ttf/Rubik-Medium.ttf: 2.10400390625
* fonts/ttf/Rubik-MediumItalic.ttf: 2.1020050048828125
* fonts/ttf/Rubik-ExtraBoldItalic.ttf: 2.1020050048828125
* fonts/ttf/Rubik-BoldItalic.ttf: 2.1020050048828125
* fonts/ttf/Rubik-Italic.ttf: 2.1020050048828125
* fonts/ttf/Rubik-Bold.ttf: 2.10400390625
* fonts/ttf/Rubik-Black.ttf: 2.10400390625
* fonts/ttf/Rubik-Light.ttf: 2.10400390625
* fonts/ttf/Rubik-ExtraBold.ttf: 2.10400390625
* fonts/ttf/Rubik-SemiBold.ttf: 2.10400390625
* fonts/ttf/Rubik-SemiBoldItalic.ttf: 2.1020050048828125
 [code: mismatch]
</div></details><br></div></details><details><summary><b>[10] Rubik-Regular.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x04B2 (CYRILLIC CAPITAL LETTER HA WITH DESCENDER)
 

	- And 0x04B3 (CYRILLIC SMALL LETTER HA WITH DESCENDER)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* Hbar
	* Ustraitstrokecy
	* uni0462
	* uni0473
	* uni0496
	* uni049A
	* uni04A2
	* uni04E8
	* uni04E9
	* uni04F6
	* uni0524
	* uni05B8
	* uni20AE
	* uni20B4
	* uni20B9 and yen
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.BRACKET.125

	- parenleft.denominator

	- parenleft.numerator

	- parenright.denominator

	- parenright.numerator

	- uni030C.alt

	- uni20B4.BRACKET.125 

	- And yen.BRACKET.125
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0493	Contours detected: 2	Expected: 1

	- Glyph name: ustraitstrokecy	Contours detected: 2	Expected: 1

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uni0493	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0524 (U+0524): L<<529.0,90.0>--<529.0,90.0>> -> L<<529.0,90.0>--<529.0,90.0>>

	* uni05DC (U+05DC): L<<180.0,489.0>--<178.0,489.0>> -> L<<178.0,489.0>--<83.0,490.0>>

	* uni05DC (U+05DC): L<<210.0,489.0>--<180.0,489.0>> -> L<<180.0,489.0>--<178.0,489.0>>

	* uniFB3C (U+FB3C): L<<180.0,489.0>--<178.0,489.0>> -> L<<178.0,489.0>--<83.0,490.0>> 

	* And uniFB3C (U+FB3C): L<<210.0,489.0>--<180.0,489.0>> -> L<<180.0,489.0>--<178.0,489.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni0434 (U+0434): L<<168.0,80.0>--<406.0,82.0>> 

	* And uni0446 (U+0446): L<<517.0,497.0>--<516.0,80.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] Rubik-LightItalic.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x04B2 (CYRILLIC CAPITAL LETTER HA WITH DESCENDER)
 

	- And 0x04B3 (CYRILLIC SMALL LETTER HA WITH DESCENDER)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* Hbar
	* uni05B8
	* uni20AE
	* uni20B4 and yen
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.BRACKET.125

	- parenleft.denominator

	- parenleft.numerator

	- parenright.denominator

	- parenright.numerator

	- uni030C.alt

	- uni20B4.BRACKET.125 

	- And yen.BRACKET.125
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: ustraitstrokecy	Contours detected: 2	Expected: 1

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2 

	- And Glyph name: uni00AD	Contours detected: 1	Expected: 0
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft (U+0028): X=288.0,Y=698.5 (should be at cap-height 700?)

	* parenright (U+0029): X=199.0,Y=698.0 (should be at cap-height 700?)

	* one (U+0031): X=342.0,Y=699.0 (should be at cap-height 700?)

	* at (U+0040): X=645.0,Y=-1.5 (should be at baseline 0?)

	* braceright (U+007D): X=296.5,Y=699.5 (should be at cap-height 700?)

	* questiondown (U+00BF): X=197.0,Y=-2.0 (should be at baseline 0?)

	* oslash (U+00F8): X=15.0,Y=1.0 (should be at baseline 0?)

	* ccaron (U+010D): X=232.0,Y=699.0 (should be at cap-height 700?)

	* eogonek (U+0119): X=164.0,Y=-2.0 (should be at baseline 0?)

	* ecaron (U+011B): X=246.0,Y=699.0 (should be at cap-height 700?)

	* ncaron (U+0148): X=254.0,Y=699.0 (should be at cap-height 700?)

	* rcaron (U+0159): X=155.0,Y=699.0 (should be at cap-height 700?)

	* scaron (U+0161): X=200.0,Y=699.0 (should be at cap-height 700?)

	* uogonek (U+0173): X=436.0,Y=-2.0 (should be at baseline 0?)

	* zcaron (U+017E): X=200.0,Y=699.0 (should be at cap-height 700?)

	* uni01CE (U+01CE): X=228.0,Y=699.0 (should be at cap-height 700?)

	* oslashacute (U+01FF): X=15.0,Y=1.0 (should be at baseline 0?)

	* caron (U+02C7): X=35.0,Y=699.0 (should be at cap-height 700?)

	* uni030C (U+030C): X=35.0,Y=699.0 (should be at cap-height 700?)

	* uni0409 (U+0409): X=-31.0,Y=1.0 (should be at baseline 0?)

	* uni0409 (U+0409): X=-31.0,Y=1.0 (should be at baseline 0?)

	* uni041B (U+041B): X=-31.0,Y=1.0 (should be at baseline 0?)

	* uni0431 (U+0431): X=552.0,Y=702.0 (should be at cap-height 700?)

	* uni0434 (U+0434): X=282.5,Y=698.5 (should be at cap-height 700?)

	* uni0459 (U+0459): X=-7.0,Y=1.0 (should be at baseline 0?)

	* uni0474 (U+0474): X=724.5,Y=701.5 (should be at cap-height 700?)

	* uni05E2 (U+05E2): X=13.0,Y=1.0 (should be at baseline 0?)

	* uni05EA (U+05EA): X=31.0,Y=2.0 (should be at baseline 0?)

	* quoteright (U+2019): X=252.0,Y=701.5 (should be at cap-height 700?)

	* quotedblright (U+201D): X=252.0,Y=701.5 (should be at cap-height 700?)

	* quotedblright (U+201D): X=386.0,Y=701.5 (should be at cap-height 700?)

	* uni2085 (U+2085): X=80.0,Y=-1.5 (should be at baseline 0?)

	* lozenge (U+25CA): X=312.5,Y=701.5 (should be at cap-height 700?)

	* lozenge (U+25CA): X=387.5,Y=699.5 (should be at cap-height 700?)

	* uniFB2A (U+FB2A): X=718.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2B (U+FB2B): X=241.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2C (U+FB2C): X=718.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2D (U+FB2D): X=241.5,Y=699.0 (should be at cap-height 700?)

	* uniFB4A (U+FB4A): X=31.0,Y=2.0 (should be at baseline 0?) 

	* And uniFB4B (U+FB4B): X=243.5,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0524 (U+0524): L<<496.0,60.0>--<496.0,60.0>> -> L<<496.0,60.0>--<496.0,60.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0495 (U+0495): L<<185.0,462.0>--<139.0,242.0>>/L<<139.0,242.0>--<146.0,277.0>> = 0.4999504830075268 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[11] Rubik-BlackItalic.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x04B2 (CYRILLIC CAPITAL LETTER HA WITH DESCENDER)
 

	- And 0x04B3 (CYRILLIC SMALL LETTER HA WITH DESCENDER)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* Hbar
	* Ustraitstrokecy
	* hbar
	* uni00B5
	* uni040E
	* uni0423
	* uni043C
	* uni0443
	* uni044E
	* uni045E
	* uni0462
	* uni0463
	* uni046B
	* uni0473
	* uni0492
	* uni0493
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04AA
	* uni04AB
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04CB
	* uni04CC
	* uni04E8
	* uni04E9
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F6
	* uni04F7
	* uni0524
	* uni0525
	* uni05B8
	* uni05D2
	* uni05DC
	* uni05DE
	* uni05E0
	* uni05E2
	* uni05EA
	* uni20AE
	* uni20B4
	* uni20B9
	* uniFB2F
	* uniFB32
	* uniFB3C
	* uniFB3E
	* uniFB40
	* uniFB4A
	* yen
	* zero.tf.zero and zero.zero
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.BRACKET.125

	- parenleft.denominator

	- parenleft.numerator

	- parenright.denominator

	- parenright.numerator

	- uni030C.alt

	- uni20B4.BRACKET.125 

	- And yen.BRACKET.125
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: ustraitstrokecy	Contours detected: 2	Expected: 1

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2 

	- And Glyph name: uni00AD	Contours detected: 1	Expected: 0
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* quotedbl (U+0022): X=312.5,Y=700.5 (should be at cap-height 700?)

	* quotedbl (U+0022): X=567.5,Y=700.5 (should be at cap-height 700?)

	* dollar (U+0024): X=211.0,Y=-2.0 (should be at baseline 0?)

	* ampersand (U+0026): X=357.5,Y=-2.0 (should be at baseline 0?)

	* quotesingle (U+0027): X=312.5,Y=700.5 (should be at cap-height 700?)

	* b (U+0062): X=139.5,Y=702.0 (should be at cap-height 700?)

	* b (U+0062): X=362.5,Y=702.0 (should be at cap-height 700?)

	* d (U+0064): X=470.5,Y=702.0 (should be at cap-height 700?)

	* d (U+0064): X=693.5,Y=702.0 (should be at cap-height 700?)

	* h (U+0068): X=139.5,Y=702.0 (should be at cap-height 700?)

	* h (U+0068): X=372.5,Y=702.0 (should be at cap-height 700?)

	* j (U+006A): X=-16.0,Y=-1.5 (should be at baseline 0?)

	* k (U+006B): X=139.5,Y=702.0 (should be at cap-height 700?)

	* k (U+006B): X=352.5,Y=702.0 (should be at cap-height 700?)

	* l (U+006C): X=139.5,Y=702.0 (should be at cap-height 700?)

	* l (U+006C): X=356.5,Y=702.0 (should be at cap-height 700?)

	* m (U+006D): X=383.0,Y=519.0 (should be at x-height 520?)

	* t (U+0074): X=208.5,Y=702.0 (should be at cap-height 700?)

	* t (U+0074): X=421.5,Y=702.0 (should be at cap-height 700?)

	* braceleft (U+007B): X=74.5,Y=1.5 (should be at baseline 0?)

	* braceleft (U+007B): X=402.0,Y=1.0 (should be at baseline 0?)

	* braceright (U+007D): X=302.5,Y=2.0 (should be at baseline 0?)

	* braceright (U+007D): X=-26.0,Y=1.0 (should be at baseline 0?)

	* cent (U+00A2): X=348.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=380.5,Y=1.0 (should be at baseline 0?)

	* ae (U+00E6): X=280.0,Y=1.0 (should be at baseline 0?)

	* eth (U+00F0): X=640.0,Y=699.0 (should be at cap-height 700?)

	* thorn (U+00FE): X=139.5,Y=702.0 (should be at cap-height 700?)

	* thorn (U+00FE): X=362.5,Y=702.0 (should be at cap-height 700?)

	* dcaron (U+010F): X=470.5,Y=702.0 (should be at cap-height 700?)

	* dcaron (U+010F): X=693.5,Y=702.0 (should be at cap-height 700?)

	* dcroat (U+0111): X=469.5,Y=702.0 (should be at cap-height 700?)

	* dcroat (U+0111): X=692.5,Y=702.0 (should be at cap-height 700?)

	* hcircumflex (U+0125): X=139.5,Y=702.0 (should be at cap-height 700?)

	* hcircumflex (U+0125): X=372.5,Y=702.0 (should be at cap-height 700?)

	* hbar (U+0127): X=139.5,Y=702.0 (should be at cap-height 700?)

	* hbar (U+0127): X=372.5,Y=702.0 (should be at cap-height 700?)

	* IJ (U+0132): X=337.0,Y=-2.0 (should be at baseline 0?)

	* ij (U+0133): X=307.0,Y=-1.5 (should be at baseline 0?)

	* uni0137 (U+0137): X=139.5,Y=702.0 (should be at cap-height 700?)

	* uni0137 (U+0137): X=352.5,Y=702.0 (should be at cap-height 700?)

	* lacute (U+013A): X=139.5,Y=702.0 (should be at cap-height 700?)

	* lacute (U+013A): X=356.5,Y=702.0 (should be at cap-height 700?)

	* uni013C (U+013C): X=139.5,Y=702.0 (should be at cap-height 700?)

	* uni013C (U+013C): X=356.5,Y=702.0 (should be at cap-height 700?)

	* lcaron (U+013E): X=139.5,Y=702.0 (should be at cap-height 700?)

	* lcaron (U+013E): X=356.5,Y=702.0 (should be at cap-height 700?)

	* ldot (U+0140): X=139.5,Y=702.0 (should be at cap-height 700?)

	* ldot (U+0140): X=356.5,Y=702.0 (should be at cap-height 700?)

	* lslash (U+0142): X=192.5,Y=702.0 (should be at cap-height 700?)

	* lslash (U+0142): X=409.5,Y=702.0 (should be at cap-height 700?)

	* oe (U+0153): X=516.5,Y=-2.0 (should be at baseline 0?)

	* tcaron (U+0165): X=208.5,Y=702.0 (should be at cap-height 700?)

	* tcaron (U+0165): X=421.5,Y=702.0 (should be at cap-height 700?)

	* tbar (U+0167): X=210.5,Y=702.0 (should be at cap-height 700?)

	* tbar (U+0167): X=423.5,Y=702.0 (should be at cap-height 700?)

	* Uogonek (U+0172): X=222.0,Y=1.0 (should be at baseline 0?)

	* aeacute (U+01FD): X=280.0,Y=1.0 (should be at baseline 0?)

	* uni021B (U+021B): X=208.5,Y=702.0 (should be at cap-height 700?)

	* uni021B (U+021B): X=421.5,Y=702.0 (should be at cap-height 700?)

	* uni0431 (U+0431): X=288.0,Y=698.0 (should be at cap-height 700?)

	* uni0439 (U+0439): X=411.0,Y=701.0 (should be at cap-height 700?)

	* uni0444 (U+0444): X=409.0,Y=702.0 (should be at cap-height 700?)

	* uni0444 (U+0444): X=626.0,Y=702.0 (should be at cap-height 700?)

	* uni0452 (U+0452): X=165.0,Y=702.0 (should be at cap-height 700?)

	* uni0452 (U+0452): X=398.0,Y=702.0 (should be at cap-height 700?)

	* uni0458 (U+0458): X=-16.0,Y=-1.5 (should be at baseline 0?)

	* uni045B (U+045B): X=165.5,Y=702.0 (should be at cap-height 700?)

	* uni045B (U+045B): X=398.5,Y=702.0 (should be at cap-height 700?)

	* uni045E (U+045E): X=409.0,Y=701.0 (should be at cap-height 700?)

	* uni0463 (U+0463): X=160.5,Y=702.0 (should be at cap-height 700?)

	* uni0463 (U+0463): X=378.5,Y=702.0 (should be at cap-height 700?)

	* uni0498 (U+0498): X=403.0,Y=-1.0 (should be at baseline 0?)

	* uni0499 (U+0499): X=140.0,Y=2.0 (should be at baseline 0?)

	* uni04BB (U+04BB): X=139.5,Y=702.0 (should be at cap-height 700?)

	* uni04BB (U+04BB): X=372.5,Y=702.0 (should be at cap-height 700?)

	* uni04C2 (U+04C2): X=608.0,Y=701.0 (should be at cap-height 700?)

	* uni04CF (U+04CF): X=139.5,Y=702.0 (should be at cap-height 700?)

	* uni04CF (U+04CF): X=356.5,Y=702.0 (should be at cap-height 700?)

	* uni04D1 (U+04D1): X=409.0,Y=701.0 (should be at cap-height 700?)

	* uni04D5 (U+04D5): X=281.0,Y=1.0 (should be at baseline 0?)

	* uni04D7 (U+04D7): X=402.0,Y=701.0 (should be at cap-height 700?)

	* uni05DC (U+05DC): X=124.5,Y=702.0 (should be at cap-height 700?)

	* uni05DC (U+05DC): X=315.5,Y=702.0 (should be at cap-height 700?)

	* quoteleft (U+2018): X=211.0,Y=699.0 (should be at cap-height 700?)

	* quotedblleft (U+201C): X=495.0,Y=699.0 (should be at cap-height 700?)

	* quotedblleft (U+201C): X=211.0,Y=699.0 (should be at cap-height 700?)

	* uni2082 (U+2082): X=250.5,Y=-1.5 (should be at baseline 0?)

	* uni2085 (U+2085): X=-9.0,Y=-1.0 (should be at baseline 0?)

	* uni208E (U+208E): X=175.0,Y=2.0 (should be at baseline 0?)

	* uni20B8 (U+20B8): X=128.0,Y=699.0 (should be at cap-height 700?)

	* uni20B8 (U+20B8): X=714.0,Y=699.0 (should be at cap-height 700?)

	* lozenge (U+25CA): X=321.5,Y=698.5 (should be at cap-height 700?)

	* lozenge (U+25CA): X=471.5,Y=698.5 (should be at cap-height 700?)

	* uniFB2A (U+FB2A): X=765.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2B (U+FB2B): X=330.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2C (U+FB2C): X=765.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2D (U+FB2D): X=330.5,Y=699.0 (should be at cap-height 700?)

	* uniFB3C (U+FB3C): X=124.5,Y=702.0 (should be at cap-height 700?) 

	* And uniFB3C (U+FB3C): X=315.5,Y=702.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni04A2 (U+04A2): L<<450.0,220.0>--<450.0,220.0>> -> L<<450.0,220.0>--<450.0,220.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0494 (U+0494): B<<296.5,180.5>-<279.0,172.0>-<274.0,149.0>>/L<<274.0,149.0>--<275.0,153.0>> = 1.7714697400342114

	* uni0494 (U+0494): L<<274.0,149.0>--<275.0,153.0>>/L<<275.0,153.0>--<248.0,27.0>> = 1.9414863909143467

	* uni0496 (U+0496): L<<847.0,0.0>--<847.0,0.0>>/B<<847.0,0.0>-<829.0,1.0>-<822.0,10.0>> = 3.1798301198641643 

	* And uni049B (U+049B): L<<356.0,0.0>--<356.0,0.0>>/B<<356.0,0.0>-<347.0,2.0>-<342.0,6.5>> = 12.528807709151492 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[11] Rubik-Medium.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x04B2 (CYRILLIC CAPITAL LETTER HA WITH DESCENDER)
 

	- And 0x04B3 (CYRILLIC SMALL LETTER HA WITH DESCENDER)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* Hbar
	* Ustraitstrokecy
	* hbar
	* uni044E
	* uni0462
	* uni0463
	* uni0473
	* uni0492
	* uni0496
	* uni0497
	* uni049A
	* uni049B
	* uni04A2
	* uni04A3
	* uni04B6
	* uni04B7
	* uni04CB
	* uni04CC
	* uni04E8
	* uni04E9
	* uni04F6
	* uni04F7
	* uni0524
	* uni0525
	* uni05B8
	* uni05D2
	* uni05E0
	* uni05E2
	* uni20AE
	* uni20B4
	* uni20B9
	* uniFB32
	* uniFB40
	* yen
	* zero.tf.zero and zero.zero
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.BRACKET.125

	- parenleft.denominator

	- parenleft.numerator

	- parenright.denominator

	- parenright.numerator

	- uni030C.alt

	- uni20B4.BRACKET.125 

	- And yen.BRACKET.125
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0493	Contours detected: 2	Expected: 1

	- Glyph name: ustraitstrokecy	Contours detected: 2	Expected: 1

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uni0493	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* i (U+0069): X=62.0,Y=702.0 (should be at cap-height 700?)

	* i (U+0069): X=202.0,Y=702.0 (should be at cap-height 700?)

	* j (U+006A): X=73.0,Y=702.0 (should be at cap-height 700?)

	* j (U+006A): X=216.0,Y=702.0 (should be at cap-height 700?)

	* j (U+006A): X=77.0,Y=1.0 (should be at baseline 0?)

	* j (U+006A): X=212.0,Y=-1.0 (should be at baseline 0?)

	* braceleft (U+007B): X=255.0,Y=-1.5 (should be at baseline 0?)

	* uni00B5 (U+00B5): X=323.0,Y=1.0 (should be at baseline 0?)

	* atilde (U+00E3): X=170.5,Y=701.0 (should be at cap-height 700?)

	* ntilde (U+00F1): X=201.5,Y=701.0 (should be at cap-height 700?)

	* otilde (U+00F5): X=183.5,Y=701.0 (should be at cap-height 700?)

	* aogonek (U+0105): X=490.0,Y=1.0 (should be at baseline 0?)

	* dcaron (U+010F): X=627.5,Y=700.5 (should be at cap-height 700?)

	* itilde (U+0129): X=19.5,Y=701.0 (should be at cap-height 700?)

	* iogonek (U+012F): X=74.0,Y=702.0 (should be at cap-height 700?)

	* iogonek (U+012F): X=214.0,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=62.0,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=202.0,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=355.0,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=498.0,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=359.0,Y=1.0 (should be at baseline 0?)

	* ij (U+0133): X=494.0,Y=-1.0 (should be at baseline 0?)

	* lcaron (U+013E): X=278.5,Y=700.5 (should be at cap-height 700?)

	* utilde (U+0169): X=196.5,Y=701.0 (should be at cap-height 700?)

	* uogonek (U+0173): X=526.0,Y=-1.0 (should be at baseline 0?)

	* tilde (U+02DC): X=103.5,Y=701.0 (should be at cap-height 700?)

	* tildecomb (U+0303): X=103.5,Y=701.0 (should be at cap-height 700?)

	* uni0409 (U+0409): X=51.0,Y=1.0 (should be at baseline 0?)

	* uni0409 (U+0409): X=51.0,Y=1.0 (should be at baseline 0?)

	* uni041B (U+041B): X=51.0,Y=1.0 (should be at baseline 0?)

	* uni0456 (U+0456): X=62.0,Y=702.0 (should be at cap-height 700?)

	* uni0456 (U+0456): X=202.0,Y=702.0 (should be at cap-height 700?)

	* uni0458 (U+0458): X=73.0,Y=702.0 (should be at cap-height 700?)

	* uni0458 (U+0458): X=216.0,Y=702.0 (should be at cap-height 700?)

	* uni0458 (U+0458): X=77.0,Y=1.0 (should be at baseline 0?)

	* uni0458 (U+0458): X=212.0,Y=-1.0 (should be at baseline 0?)

	* uni0459 (U+0459): X=50.0,Y=1.0 (should be at baseline 0?)

	* uni05B0 (U+05B0): X=-43.0,Y=-248.0 (should be at descender -250?)

	* uni05B0 (U+05B0): X=44.0,Y=-248.0 (should be at descender -250?)

	* uni05B1 (U+05B1): X=-43.0,Y=-248.0 (should be at descender -250?)

	* uni05B1 (U+05B1): X=44.0,Y=-248.0 (should be at descender -250?)

	* uni05B1 (U+05B1): X=-43.0,Y=-248.0 (should be at descender -250?)

	* uni05B1 (U+05B1): X=45.0,Y=-248.0 (should be at descender -250?)

	* uni05B2 (U+05B2): X=-43.0,Y=-248.0 (should be at descender -250?)

	* uni05B2 (U+05B2): X=44.0,Y=-248.0 (should be at descender -250?)

	* uni05B3 (U+05B3): X=-43.0,Y=-248.0 (should be at descender -250?)

	* uni05B3 (U+05B3): X=44.0,Y=-248.0 (should be at descender -250?)

	* uni05B3 (U+05B3): X=12.0,Y=-251.0 (should be at descender -250?)

	* uni05B3 (U+05B3): X=-11.0,Y=-251.0 (should be at descender -250?)

	* uni05B6 (U+05B6): X=-43.0,Y=-248.0 (should be at descender -250?)

	* uni05B6 (U+05B6): X=45.0,Y=-248.0 (should be at descender -250?)

	* uni05B8 (U+05B8): X=12.0,Y=-251.0 (should be at descender -250?)

	* uni05B8 (U+05B8): X=-11.0,Y=-251.0 (should be at descender -250?)

	* uni05C7 (U+05C7): X=12.0,Y=-251.0 (should be at descender -250?)

	* uni05C7 (U+05C7): X=-11.0,Y=-251.0 (should be at descender -250?)

	* uni05DC (U+05DC): X=238.0,Y=2.0 (should be at baseline 0?)

	* uni05E7 (U+05E7): X=349.0,Y=2.0 (should be at baseline 0?)

	* uni05EA (U+05EA): X=72.0,Y=1.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=119.0,Y=702.0 (should be at cap-height 700?)

	* quoteright (U+2019): X=85.0,Y=700.5 (should be at cap-height 700?)

	* quotedblleft (U+201C): X=309.0,Y=702.0 (should be at cap-height 700?)

	* quotedblleft (U+201C): X=119.0,Y=702.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=275.5,Y=700.5 (should be at cap-height 700?)

	* quotedblright (U+201D): X=85.0,Y=700.5 (should be at cap-height 700?)

	* uni2086 (U+2086): X=178.0,Y=1.0 (should be at baseline 0?)

	* lozenge (U+25CA): X=231.0,Y=698.5 (should be at cap-height 700?)

	* lozenge (U+25CA): X=338.0,Y=698.5 (should be at cap-height 700?)

	* uniFB2F (U+FB2F): X=310.0,Y=-251.0 (should be at descender -250?)

	* uniFB2F (U+FB2F): X=287.0,Y=-251.0 (should be at descender -250?)

	* uniFB3C (U+FB3C): X=238.0,Y=2.0 (should be at baseline 0?)

	* uniFB47 (U+FB47): X=349.0,Y=2.0 (should be at baseline 0?)

	* uniFB4A (U+FB4A): X=72.0,Y=1.0 (should be at baseline 0?)

	* uniFB4B (U+FB4B): X=89.0,Y=699.0 (should be at cap-height 700?) 

	* And uniFB4B (U+FB4B): X=176.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0524 (U+0524): L<<512.0,24.0>--<512.0,124.0>> -> L<<512.0,124.0>--<512.0,125.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* g (U+0067): L<<548.0,495.0>--<549.0,13.0>>

	* gbreve (U+011F): L<<548.0,495.0>--<549.0,13.0>>

	* gcircumflex (U+011D): L<<548.0,495.0>--<549.0,13.0>>

	* gdotaccent (U+0121): L<<548.0,495.0>--<549.0,13.0>>

	* uni0123 (U+0123): L<<548.0,495.0>--<549.0,13.0>>

	* uni0434 (U+0434): L<<208.0,106.0>--<403.0,107.0>>

	* uni05E9 (U+05E9): L<<182.0,547.0>--<184.0,284.0>>

	* uni05EA (U+05EA): L<<246.0,0.0>--<72.0,1.0>>

	* uniFB2A (U+FB2A): L<<182.0,547.0>--<184.0,284.0>>

	* uniFB2B (U+FB2B): L<<182.0,547.0>--<184.0,284.0>>

	* uniFB2C (U+FB2C): L<<182.0,547.0>--<184.0,284.0>>

	* uniFB2D (U+FB2D): L<<182.0,547.0>--<184.0,284.0>>

	* uniFB49 (U+FB49): L<<182.0,547.0>--<184.0,284.0>> 

	* And uniFB4A (U+FB4A): L<<246.0,0.0>--<72.0,1.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] Rubik-MediumItalic.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x04B2 (CYRILLIC CAPITAL LETTER HA WITH DESCENDER)
 

	- And 0x04B3 (CYRILLIC SMALL LETTER HA WITH DESCENDER)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* Hbar
	* Ustraitstrokecy
	* hbar
	* uni044E
	* uni0462
	* uni0463
	* uni0473
	* uni0492
	* uni0493
	* uni0496
	* uni0497
	* uni049A
	* uni049B
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04B6
	* uni04B7
	* uni04CB
	* uni04CC
	* uni04E8
	* uni04E9
	* uni04F6
	* uni04F7
	* uni0524
	* uni0525
	* uni05B8
	* uni05D2
	* uni05E0
	* uni05E2
	* uni20AE
	* uni20B4
	* uni20B9
	* uniFB32
	* uniFB40
	* yen
	* zero.tf.zero and zero.zero
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.BRACKET.125

	- parenleft.denominator

	- parenleft.numerator

	- parenright.denominator

	- parenright.numerator

	- uni030C.alt

	- uni20B4.BRACKET.125 

	- And yen.BRACKET.125
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: ustraitstrokecy	Contours detected: 2	Expected: 1

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2 

	- And Glyph name: uni00AD	Contours detected: 1	Expected: 0
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* i (U+0069): X=149.0,Y=702.0 (should be at cap-height 700?)

	* i (U+0069): X=289.0,Y=702.0 (should be at cap-height 700?)

	* j (U+006A): X=159.0,Y=702.0 (should be at cap-height 700?)

	* j (U+006A): X=302.0,Y=702.0 (should be at cap-height 700?)

	* j (U+006A): X=14.0,Y=1.0 (should be at baseline 0?)

	* j (U+006A): X=149.0,Y=-1.0 (should be at baseline 0?)

	* braceleft (U+007B): X=206.5,Y=-1.5 (should be at baseline 0?)

	* atilde (U+00E3): X=266.5,Y=701.0 (should be at cap-height 700?)

	* ntilde (U+00F1): X=282.5,Y=701.0 (should be at cap-height 700?)

	* otilde (U+00F5): X=265.5,Y=701.0 (should be at cap-height 700?)

	* dcaron (U+010F): X=709.0,Y=700.5 (should be at cap-height 700?)

	* itilde (U+0129): X=104.5,Y=701.0 (should be at cap-height 700?)

	* iogonek (U+012F): X=175.0,Y=702.0 (should be at cap-height 700?)

	* iogonek (U+012F): X=314.0,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=149.0,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=289.0,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=423.0,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=566.0,Y=702.0 (should be at cap-height 700?)

	* ij (U+0133): X=278.0,Y=1.0 (should be at baseline 0?)

	* ij (U+0133): X=413.0,Y=-1.0 (should be at baseline 0?)

	* Lcaron (U+013D): X=418.5,Y=700.5 (should be at cap-height 700?)

	* lcaron (U+013E): X=363.0,Y=700.5 (should be at cap-height 700?)

	* utilde (U+0169): X=271.5,Y=701.0 (should be at cap-height 700?)

	* uogonek (U+0173): X=477.0,Y=-1.0 (should be at baseline 0?)

	* tilde (U+02DC): X=86.5,Y=701.0 (should be at cap-height 700?)

	* tildecomb (U+0303): X=86.5,Y=701.0 (should be at cap-height 700?)

	* uni0409 (U+0409): X=-19.0,Y=1.0 (should be at baseline 0?)

	* uni0409 (U+0409): X=-19.0,Y=1.0 (should be at baseline 0?)

	* uni041B (U+041B): X=-19.0,Y=1.0 (should be at baseline 0?)

	* uni0434 (U+0434): X=479.5,Y=699.0 (should be at cap-height 700?)

	* uni0456 (U+0456): X=149.0,Y=702.0 (should be at cap-height 700?)

	* uni0456 (U+0456): X=289.0,Y=702.0 (should be at cap-height 700?)

	* uni0458 (U+0458): X=159.0,Y=702.0 (should be at cap-height 700?)

	* uni0458 (U+0458): X=302.0,Y=702.0 (should be at cap-height 700?)

	* uni0458 (U+0458): X=14.0,Y=1.0 (should be at baseline 0?)

	* uni0458 (U+0458): X=149.0,Y=-1.0 (should be at baseline 0?)

	* uni0459 (U+0459): X=-3.0,Y=1.0 (should be at baseline 0?)

	* uni04AB (U+04AB): X=163.0,Y=-2.0 (should be at baseline 0?)

	* uni05B0 (U+05B0): X=-144.0,Y=-248.0 (should be at descender -250?)

	* uni05B0 (U+05B0): X=-57.0,Y=-248.0 (should be at descender -250?)

	* uni05B1 (U+05B1): X=-144.0,Y=-248.0 (should be at descender -250?)

	* uni05B1 (U+05B1): X=-57.0,Y=-248.0 (should be at descender -250?)

	* uni05B1 (U+05B1): X=-144.0,Y=-248.0 (should be at descender -250?)

	* uni05B1 (U+05B1): X=-57.0,Y=-248.0 (should be at descender -250?)

	* uni05B2 (U+05B2): X=-144.0,Y=-248.0 (should be at descender -250?)

	* uni05B2 (U+05B2): X=-57.0,Y=-248.0 (should be at descender -250?)

	* uni05B3 (U+05B3): X=-144.0,Y=-248.0 (should be at descender -250?)

	* uni05B3 (U+05B3): X=-57.0,Y=-248.0 (should be at descender -250?)

	* uni05B3 (U+05B3): X=-90.0,Y=-251.0 (should be at descender -250?)

	* uni05B3 (U+05B3): X=-113.0,Y=-251.0 (should be at descender -250?)

	* uni05B6 (U+05B6): X=-144.0,Y=-248.0 (should be at descender -250?)

	* uni05B6 (U+05B6): X=-57.0,Y=-248.0 (should be at descender -250?)

	* uni05B8 (U+05B8): X=-90.0,Y=-251.0 (should be at descender -250?)

	* uni05B8 (U+05B8): X=-113.0,Y=-251.0 (should be at descender -250?)

	* uni05C7 (U+05C7): X=-90.0,Y=-251.0 (should be at descender -250?)

	* uni05C7 (U+05C7): X=-113.0,Y=-251.0 (should be at descender -250?)

	* uni05DC (U+05DC): X=190.0,Y=2.0 (should be at baseline 0?)

	* uni05E7 (U+05E7): X=301.0,Y=2.0 (should be at baseline 0?)

	* uni05EA (U+05EA): X=24.0,Y=1.0 (should be at baseline 0?)

	* quoteright (U+2019): X=169.0,Y=700.5 (should be at cap-height 700?)

	* quoteright (U+2019): X=304.5,Y=700.5 (should be at cap-height 700?)

	* quotedblright (U+201D): X=169.0,Y=700.5 (should be at cap-height 700?)

	* quotedblright (U+201D): X=304.5,Y=700.5 (should be at cap-height 700?)

	* quotedblright (U+201D): X=363.5,Y=700.5 (should be at cap-height 700?)

	* quotedblright (U+201D): X=498.5,Y=700.5 (should be at cap-height 700?)

	* uni2086 (U+2086): X=129.0,Y=1.0 (should be at baseline 0?)

	* lozenge (U+25CA): X=421.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2A (U+FB2A): X=737.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2B (U+FB2B): X=277.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2C (U+FB2C): X=737.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2D (U+FB2D): X=277.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2F (U+FB2F): X=208.0,Y=-251.0 (should be at descender -250?)

	* uniFB2F (U+FB2F): X=185.0,Y=-251.0 (should be at descender -250?)

	* uniFB3C (U+FB3C): X=190.0,Y=2.0 (should be at baseline 0?)

	* uniFB47 (U+FB47): X=301.0,Y=2.0 (should be at baseline 0?)

	* uniFB4A (U+FB4A): X=24.0,Y=1.0 (should be at baseline 0?)

	* uniFB4B (U+FB4B): X=193.0,Y=699.0 (should be at cap-height 700?) 

	* And uniFB4B (U+FB4B): X=280.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni04CB (U+04CB): L<<563.0,84.0>--<563.0,84.0>> -> L<<563.0,84.0>--<563.0,84.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0494 (U+0494): B<<233.0,273.5>-<208.0,252.0>-<199.0,210.0>>/L<<199.0,210.0>--<199.0,211.0>> = 12.094757077012089

	* uni0494 (U+0494): L<<199.0,210.0>--<199.0,211.0>>/L<<199.0,211.0>--<160.0,24.0>> = 11.780523776915402 

	* And uni04A1 (U+04A1): L<<138.0,24.0>--<222.0,415.0>>/L<<222.0,415.0>--<222.0,414.0>> = 12.12477582008083 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[10] Rubik-ExtraBoldItalic.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x04B2 (CYRILLIC CAPITAL LETTER HA WITH DESCENDER)
 

	- And 0x04B3 (CYRILLIC SMALL LETTER HA WITH DESCENDER)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* Hbar
	* Ustraitstrokecy
	* hbar
	* uni00B5
	* uni043C
	* uni0443
	* uni044E
	* uni045E
	* uni0462
	* uni0463
	* uni046B
	* uni0473
	* uni0492
	* uni0493
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04AA
	* uni04AB
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04CB
	* uni04CC
	* uni04E8
	* uni04E9
	* uni04EF
	* uni04F1
	* uni04F3
	* uni04F6
	* uni04F7
	* uni0524
	* uni0525
	* uni05B8
	* uni05D2
	* uni05DC
	* uni05DE
	* uni05E0
	* uni05E2
	* uni05EA
	* uni20AE
	* uni20B4
	* uni20B9
	* uniFB2F
	* uniFB32
	* uniFB3C
	* uniFB3E
	* uniFB40
	* uniFB4A
	* yen
	* zero.tf.zero and zero.zero
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.BRACKET.125

	- parenleft.denominator

	- parenleft.numerator

	- parenright.denominator

	- parenright.numerator

	- uni030C.alt

	- uni20B4.BRACKET.125 

	- And yen.BRACKET.125
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: ustraitstrokecy	Contours detected: 2	Expected: 1

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2 

	- And Glyph name: uni00AD	Contours detected: 1	Expected: 0
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* quotedbl (U+0022): X=296.0,Y=701.0 (should be at cap-height 700?)

	* quotedbl (U+0022): X=528.0,Y=701.0 (should be at cap-height 700?)

	* dollar (U+0024): X=496.0,Y=699.0 (should be at cap-height 700?)

	* ampersand (U+0026): X=359.0,Y=1.5 (should be at baseline 0?)

	* quotesingle (U+0027): X=296.0,Y=701.0 (should be at cap-height 700?)

	* parenleft (U+0028): X=292.0,Y=-1.0 (should be at baseline 0?)

	* parenright (U+0029): X=-16.0,Y=-1.0 (should be at baseline 0?)

	* less (U+003C): X=403.0,Y=-1.0 (should be at baseline 0?)

	* less (U+003C): X=403.0,Y=-1.0 (should be at baseline 0?)

	* greater (U+003E): X=21.0,Y=-2.0 (should be at baseline 0?)

	* greater (U+003E): X=21.0,Y=-2.0 (should be at baseline 0?)

	* at (U+0040): X=722.5,Y=1.5 (should be at baseline 0?)

	* Q (U+0051): X=387.0,Y=-2.0 (should be at baseline 0?)

	* braceleft (U+007B): X=352.0,Y=1.0 (should be at baseline 0?)

	* cent (U+00A2): X=327.0,Y=-2.0 (should be at baseline 0?)

	* abreve (U+0103): X=369.0,Y=698.5 (should be at cap-height 700?)

	* abreve (U+0103): X=436.5,Y=698.5 (should be at cap-height 700?)

	* aogonek (U+0105): X=354.0,Y=1.0 (should be at baseline 0?)

	* aogonek (U+0105): X=505.0,Y=-1.0 (should be at baseline 0?)

	* aogonek (U+0105): X=499.0,Y=-1.0 (should be at baseline 0?)

	* dcaron (U+010F): X=760.5,Y=698.0 (should be at cap-height 700?)

	* ebreve (U+0115): X=365.0,Y=698.5 (should be at cap-height 700?)

	* ebreve (U+0115): X=432.5,Y=698.5 (should be at cap-height 700?)

	* eogonek (U+0119): X=156.0,Y=2.0 (should be at baseline 0?)

	* gbreve (U+011F): X=361.0,Y=698.5 (should be at cap-height 700?)

	* gbreve (U+011F): X=428.5,Y=698.5 (should be at cap-height 700?)

	* ibreve (U+012D): X=205.0,Y=698.5 (should be at cap-height 700?)

	* ibreve (U+012D): X=272.5,Y=698.5 (should be at cap-height 700?)

	* Lcaron (U+013D): X=467.0,Y=698.0 (should be at cap-height 700?)

	* lcaron (U+013E): X=420.5,Y=698.0 (should be at cap-height 700?)

	* obreve (U+014F): X=360.0,Y=698.5 (should be at cap-height 700?)

	* obreve (U+014F): X=427.5,Y=698.5 (should be at cap-height 700?)

	* oe (U+0153): X=364.5,Y=2.0 (should be at baseline 0?)

	* ubreve (U+016D): X=370.0,Y=698.5 (should be at cap-height 700?)

	* ubreve (U+016D): X=437.5,Y=698.5 (should be at cap-height 700?)

	* breve (U+02D8): X=152.0,Y=698.5 (should be at cap-height 700?)

	* breve (U+02D8): X=219.5,Y=698.5 (should be at cap-height 700?)

	* uni0306 (U+0306): X=152.0,Y=698.5 (should be at cap-height 700?)

	* uni0306 (U+0306): X=219.5,Y=698.5 (should be at cap-height 700?)

	* uni0474 (U+0474): X=738.0,Y=702.0 (should be at cap-height 700?)

	* uni0474 (U+0474): X=777.0,Y=702.0 (should be at cap-height 700?)

	* uni0498 (U+0498): X=377.0,Y=-2.0 (should be at baseline 0?)

	* uni0499 (U+0499): X=146.0,Y=-1.0 (should be at baseline 0?)

	* uni0499 (U+0499): X=348.0,Y=1.0 (should be at baseline 0?)

	* uni04AA (U+04AA): X=195.0,Y=1.0 (should be at baseline 0?)

	* uni04AA (U+04AA): X=411.0,Y=2.0 (should be at baseline 0?)

	* uni051A (U+051A): X=387.0,Y=-2.0 (should be at baseline 0?)

	* uni05B8 (U+05B8): X=-65.5,Y=-252.0 (should be at descender -250?)

	* quoteright (U+2019): X=164.5,Y=698.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=164.5,Y=698.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=418.5,Y=698.0 (should be at cap-height 700?)

	* uni2085 (U+2085): X=-7.0,Y=1.0 (should be at baseline 0?)

	* uni20B8 (U+20B8): X=128.0,Y=699.0 (should be at cap-height 700?)

	* uni20B8 (U+20B8): X=690.0,Y=699.0 (should be at cap-height 700?)

	* summation (U+2211): X=20.0,Y=1.0 (should be at baseline 0?)

	* summation (U+2211): X=287.0,Y=-1.0 (should be at baseline 0?)

	* summation (U+2211): X=520.0,Y=-1.0 (should be at baseline 0?)

	* lozenge (U+25CA): X=320.0,Y=699.0 (should be at cap-height 700?)

	* lozenge (U+25CA): X=456.5,Y=698.5 (should be at cap-height 700?)

	* uniFB2A (U+FB2A): X=756.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2B (U+FB2B): X=314.0,Y=699.0 (should be at cap-height 700?)

	* uniFB2C (U+FB2C): X=756.5,Y=699.0 (should be at cap-height 700?) 

	* And uniFB2D (U+FB2D): X=314.0,Y=699.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0494 (U+0494): B<<284.5,215.0>-<258.0,203.0>-<250.0,168.0>>/L<<250.0,168.0>--<251.0,171.0>> = 5.559947263309426 

	* And uni0494 (U+0494): L<<250.0,168.0>--<251.0,171.0>>/L<<251.0,171.0>--<220.0,26.0>> = 6.367179864268598 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[11] Rubik-BoldItalic.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x04B2 (CYRILLIC CAPITAL LETTER HA WITH DESCENDER)
 

	- And 0x04B3 (CYRILLIC SMALL LETTER HA WITH DESCENDER)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* Hbar
	* Ustraitstrokecy
	* hbar
	* uni00B5
	* uni044E
	* uni0462
	* uni0463
	* uni046B
	* uni0473
	* uni0492
	* uni0493
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04AA
	* uni04AB
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04CB
	* uni04CC
	* uni04E8
	* uni04E9
	* uni04F6
	* uni04F7
	* uni0524
	* uni0525
	* uni05B8
	* uni05D2
	* uni05DC
	* uni05DE
	* uni05E0
	* uni05E2
	* uni05EA
	* uni20AE
	* uni20B4
	* uni20B9
	* uniFB2F
	* uniFB32
	* uniFB3C
	* uniFB3E
	* uniFB40
	* uniFB4A
	* yen
	* zero.tf.zero and zero.zero
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.BRACKET.125

	- parenleft.denominator

	- parenleft.numerator

	- parenright.denominator

	- parenright.numerator

	- uni030C.alt

	- uni20B4.BRACKET.125 

	- And yen.BRACKET.125
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: ustraitstrokecy	Contours detected: 2	Expected: 1

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2 

	- And Glyph name: uni00AD	Contours detected: 1	Expected: 0
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* quotedbl (U+0022): X=279.0,Y=702.0 (should be at cap-height 700?)

	* quotedbl (U+0022): X=488.5,Y=702.0 (should be at cap-height 700?)

	* dollar (U+0024): X=477.0,Y=701.0 (should be at cap-height 700?)

	* quotesingle (U+0027): X=279.0,Y=702.0 (should be at cap-height 700?)

	* at (U+0040): X=704.5,Y=0.5 (should be at baseline 0?)

	* macron (U+00AF): X=46.0,Y=698.0 (should be at cap-height 700?)

	* macron (U+00AF): X=370.0,Y=698.0 (should be at cap-height 700?)

	* aring (U+00E5): X=411.5,Y=699.0 (should be at cap-height 700?)

	* aring (U+00E5): X=368.0,Y=699.0 (should be at cap-height 700?)

	* amacron (U+0101): X=228.0,Y=698.0 (should be at cap-height 700?)

	* amacron (U+0101): X=552.0,Y=698.0 (should be at cap-height 700?)

	* aogonek (U+0105): X=484.0,Y=-2.0 (should be at baseline 0?)

	* dcaron (U+010F): X=737.0,Y=699.0 (should be at cap-height 700?)

	* emacron (U+0113): X=229.0,Y=698.0 (should be at cap-height 700?)

	* emacron (U+0113): X=553.0,Y=698.0 (should be at cap-height 700?)

	* eogonek (U+0119): X=158.0,Y=1.0 (should be at baseline 0?)

	* imacron (U+012B): X=65.0,Y=698.0 (should be at cap-height 700?)

	* imacron (U+012B): X=389.0,Y=698.0 (should be at cap-height 700?)

	* Lcaron (U+013D): X=445.0,Y=699.0 (should be at cap-height 700?)

	* lcaron (U+013E): X=394.0,Y=699.0 (should be at cap-height 700?)

	* Eng (U+014A): X=430.0,Y=1.0 (should be at baseline 0?)

	* omacron (U+014D): X=223.0,Y=698.0 (should be at cap-height 700?)

	* omacron (U+014D): X=547.0,Y=698.0 (should be at cap-height 700?)

	* umacron (U+016B): X=231.0,Y=698.0 (should be at cap-height 700?)

	* umacron (U+016B): X=555.0,Y=698.0 (should be at cap-height 700?)

	* uring (U+016F): X=414.5,Y=699.0 (should be at cap-height 700?)

	* uring (U+016F): X=371.0,Y=699.0 (should be at cap-height 700?)

	* Uogonek (U+0172): X=225.0,Y=-2.0 (should be at baseline 0?)

	* uogonek (U+0173): X=499.0,Y=-1.0 (should be at baseline 0?)

	* ring (U+02DA): X=151.5,Y=699.0 (should be at cap-height 700?)

	* ring (U+02DA): X=108.0,Y=699.0 (should be at cap-height 700?)

	* uni0304 (U+0304): X=46.0,Y=698.0 (should be at cap-height 700?)

	* uni0304 (U+0304): X=370.0,Y=698.0 (should be at cap-height 700?)

	* uni030A (U+030A): X=151.5,Y=699.0 (should be at cap-height 700?)

	* uni030A (U+030A): X=108.0,Y=699.0 (should be at cap-height 700?)

	* uni0337 (U+0337): X=-54.0,Y=2.0 (should be at baseline 0?)

	* uni0498 (U+0498): X=170.0,Y=-1.0 (should be at baseline 0?)

	* uni0499 (U+0499): X=322.0,Y=-1.0 (should be at baseline 0?)

	* uni04AA (U+04AA): X=205.0,Y=-2.0 (should be at baseline 0?)

	* uni04AA (U+04AA): X=385.0,Y=-1.0 (should be at baseline 0?)

	* uni04AB (U+04AB): X=157.0,Y=1.0 (should be at baseline 0?)

	* uni04AB (U+04AB): X=325.0,Y=-1.0 (should be at baseline 0?)

	* uni04E3 (U+04E3): X=236.0,Y=698.0 (should be at cap-height 700?)

	* uni04E3 (U+04E3): X=560.0,Y=698.0 (should be at cap-height 700?)

	* uni04EF (U+04EF): X=225.0,Y=698.0 (should be at cap-height 700?)

	* uni04EF (U+04EF): X=549.0,Y=698.0 (should be at cap-height 700?)

	* uni05E2 (U+05E2): X=267.0,Y=-1.0 (should be at baseline 0?)

	* uni05EA (U+05EA): X=20.0,Y=1.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=207.0,Y=701.0 (should be at cap-height 700?)

	* quoteright (U+2019): X=166.5,Y=699.0 (should be at cap-height 700?)

	* quoteright (U+2019): X=332.5,Y=700.5 (should be at cap-height 700?)

	* quotedblleft (U+201C): X=434.5,Y=701.0 (should be at cap-height 700?)

	* quotedblleft (U+201C): X=207.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=166.5,Y=699.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=332.5,Y=700.5 (should be at cap-height 700?)

	* quotedblright (U+201D): X=393.5,Y=699.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=559.5,Y=700.5 (should be at cap-height 700?)

	* uni2085 (U+2085): X=-6.0,Y=2.0 (should be at baseline 0?)

	* uni20B8 (U+20B8): X=129.0,Y=699.0 (should be at cap-height 700?)

	* uni20B8 (U+20B8): X=667.0,Y=699.0 (should be at cap-height 700?)

	* lozenge (U+25CA): X=318.5,Y=699.5 (should be at cap-height 700?)

	* lozenge (U+25CA): X=440.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2A (U+FB2A): X=748.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2B (U+FB2B): X=297.0,Y=699.0 (should be at cap-height 700?)

	* uniFB2C (U+FB2C): X=748.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2D (U+FB2D): X=297.0,Y=699.0 (should be at cap-height 700?) 

	* And uniFB4A (U+FB4A): X=20.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni05DC (U+05DC): L<<238.0,434.0>--<237.0,434.0>> -> L<<237.0,434.0>--<105.0,434.0>>

	* uni05DC (U+05DC): L<<261.0,434.0>--<238.0,434.0>> -> L<<238.0,434.0>--<237.0,434.0>>

	* uniFB3C (U+FB3C): L<<238.0,434.0>--<237.0,434.0>> -> L<<237.0,434.0>--<105.0,434.0>> 

	* And uniFB3C (U+FB3C): L<<261.0,434.0>--<238.0,434.0>> -> L<<238.0,434.0>--<237.0,434.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0494 (U+0494): B<<252.0,236.0>-<233.0,219.0>-<227.0,188.0>>/L<<227.0,188.0>--<227.0,190.0>> = 10.954062643398332 

	* And uni0494 (U+0494): L<<227.0,188.0>--<227.0,190.0>>/L<<227.0,190.0>--<192.0,25.0>> = 11.976132444203333 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[10] Rubik-Italic.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x04B2 (CYRILLIC CAPITAL LETTER HA WITH DESCENDER)
 

	- And 0x04B3 (CYRILLIC SMALL LETTER HA WITH DESCENDER)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* A
	* AE
	* AEacute
	* Aacute
	* Abreve
	* Acircumflex
	* Adieresis
	* Agrave
	* Amacron
	* Aogonek
	* Aring
	* Atilde
	* B
	* C
	* Cacute
	* Ccaron
	* Ccedilla
	* Ccircumflex
	* Cdotaccent
	* D
	* Dcaron
	* Dcroat
	* E
	* Eacute
	* Ebreve
	* Ecaron
	* Ecircumflex
	* Edieresis
	* Edotaccent
	* Egrave
	* Emacron
	* Eng
	* Eogonek
	* Eth
	* Euro
	* F
	* G
	* Gbreve
	* Gcircumflex
	* Gdotaccent
	* H
	* Hbar
	* Hcircumflex
	* I
	* IJ
	* Iacute
	* Ibreve
	* Icircumflex
	* Idieresis
	* Idotaccent
	* Igrave
	* Imacron
	* Iogonek
	* Itilde
	* J
	* Jcircumflex
	* K
	* L
	* Lacute
	* Lcaron
	* Ldot
	* Lslash
	* M
	* N
	* Nacute
	* Ncaron
	* Ntilde
	* O
	* OE
	* Oacute
	* Obreve
	* Ocircumflex
	* Odieresis
	* Ograve
	* Ohungarumlaut
	* Omacron
	* Oslash
	* Oslashacute
	* Otilde
	* P
	* Q
	* R
	* Racute
	* Rcaron
	* S
	* Sacute
	* Scaron
	* Scedilla
	* Scircumflex
	* T
	* Tbar
	* Tcaron
	* Thorn
	* U
	* Uacute
	* Ubreve
	* Ucircumflex
	* Udieresis
	* Ugrave
	* Uhungarumlaut
	* Umacron
	* Uogonek
	* Uring
	* Ustraitcy
	* Ustraitstrokecy
	* Utilde
	* V
	* W
	* Wacute
	* Wcircumflex
	* Wdieresis
	* Wgrave
	* X
	* Y
	* Yacute
	* Ycircumflex
	* Ydieresis
	* Ygrave
	* Z
	* Zacute
	* Zcaron
	* Zdotaccent
	* a
	* aacute
	* abreve
	* acircumflex
	* adieresis
	* ae
	* aeacute
	* agrave
	* amacron
	* ampersand
	* aogonek
	* approxequal
	* approxequal.case
	* aring
	* asciitilde
	* asciitilde.case
	* asterisk
	* at
	* at.case
	* atilde
	* b
	* backslash
	* bar
	* braceleft
	* braceleft.case
	* braceright
	* braceright.case
	* bracketleft
	* bracketleft.case
	* bracketright
	* bracketright.case
	* brokenbar
	* c
	* cacute
	* ccaron
	* ccedilla
	* ccircumflex
	* cdotaccent
	* cent
	* colon
	* copyright
	* currency
	* d
	* dagger
	* daggerdbl
	* dcaron
	* dcroat
	* degree
	* divide
	* divide.case
	* dollar
	* dotlessi
	* e
	* eacute
	* ebreve
	* ecaron
	* ecircumflex
	* edieresis
	* edotaccent
	* egrave
	* eight
	* eight.dnom
	* eight.numr
	* eight.tf
	* ellipsis
	* emacron
	* emdash
	* emdash.case
	* endash
	* endash.case
	* eng
	* eogonek
	* equal
	* equal.case
	* estimated
	* eth
	* exclam
	* exclamdown
	* f
	* f_f
	* f_f_i
	* f_f_l
	* fi
	* five
	* five.dnom
	* five.numr
	* five.tf
	* fiveeighths
	* fl
	* florin
	* four
	* four.dnom
	* four.numr
	* four.tf
	* fraction
	* g
	* gbreve
	* gcircumflex
	* gdotaccent
	* germandbls
	* greater
	* greaterequal
	* guillemotleft
	* guillemotleft.case
	* guillemotright
	* guillemotright.case
	* guilsinglleft
	* guilsinglleft.case
	* guilsinglright
	* guilsinglright.case
	* h
	* hbar
	* hcircumflex
	* hyphen
	* hyphen.case
	* i
	* iacute
	* ibreve
	* icircumflex
	* idieresis
	* igrave
	* ij
	* imacron
	* infinity
	* integral
	* iogonek
	* itilde
	* j
	* jcircumflex
	* k
	* kgreenlandic
	* l
	* lacute
	* lcaron
	* ldot
	* less
	* lessequal
	* logicalnot
	* longs
	* lozenge
	* lslash
	* m
	* minus
	* minus.case
	* multiply
	* multiply.case
	* n
	* nacute
	* napostrophe
	* ncaron
	* nine
	* nine.dnom
	* nine.numr
	* nine.tf
	* notequal
	* notequal.case
	* ntilde
	* numbersign
	* o
	* oacute
	* obreve
	* ocircumflex
	* odieresis
	* oe
	* ograve
	* ohungarumlaut
	* omacron
	* one
	* one.tf
	* oneeighth
	* onehalf
	* onequarter
	* oslash
	* oslashacute
	* otilde
	* p
	* paragraph
	* parenleft
	* parenleft.case
	* parenleft.tf
	* parenright
	* parenright.case
	* parenright.tf
	* partialdiff
	* percent
	* perthousand
	* plus
	* plus.case
	* plusminus
	* product
	* q
	* question
	* questiondown
	* quotedbl
	* quotedblbase
	* quotedblleft
	* quotedblright
	* r
	* racute
	* radical
	* rcaron
	* registered
	* s
	* sacute
	* scaron
	* scedilla
	* scircumflex
	* section
	* semicolon
	* seven
	* seven.tf
	* seveneighths
	* six
	* six.tf
	* slash
	* sterling
	* summation
	* t
	* tbar
	* tcaron
	* thorn
	* three
	* three.dnom
	* three.numr
	* three.tf
	* threeeighths
	* threequarters
	* trademark
	* two
	* two.dnom
	* two.numr
	* two.tf
	* u
	* uacute
	* ubreve
	* ucircumflex
	* udieresis
	* ugrave
	* uhungarumlaut
	* umacron
	* underscore
	* uni004A0301
	* uni006A0301
	* uni00AD
	* uni00B2
	* uni00B3
	* uni00B5
	* uni0122
	* uni0123
	* uni0136
	* uni0137
	* uni013B
	* uni013C
	* uni0145
	* uni0146
	* uni0156
	* uni0157
	* uni0218
	* uni0219
	* uni021A
	* uni021B
	* uni0237
	* uni0400
	* uni0401
	* uni0402
	* uni0403
	* uni0404
	* uni0405
	* uni0406
	* uni0407
	* uni0408
	* uni0409
	* uni040A
	* uni040B
	* uni040C
	* uni040D
	* uni040E
	* uni040F
	* uni0410
	* uni0411
	* uni0412
	* uni0413
	* uni0414
	* uni0415
	* uni0416
	* uni0417
	* uni0418
	* uni0419
	* uni041A
	* uni041B
	* uni041C
	* uni041D
	* uni041E
	* uni041F
	* uni0420
	* uni0421
	* uni0422
	* uni0423
	* uni0424
	* uni0425
	* uni0426
	* uni0427
	* uni0428
	* uni0429
	* uni042A
	* uni042B
	* uni042C
	* uni042D
	* uni042E
	* uni042F
	* uni0430
	* uni0431
	* uni0432
	* uni0433
	* uni0434
	* uni0435
	* uni0436
	* uni0437
	* uni0438
	* uni0439
	* uni043A
	* uni043B
	* uni043C
	* uni043D
	* uni043E
	* uni043F
	* uni0440
	* uni0441
	* uni0442
	* uni0443
	* uni0444
	* uni0445
	* uni0446
	* uni0447
	* uni0448
	* uni0449
	* uni044A
	* uni044B
	* uni044C
	* uni044D
	* uni044E
	* uni044F
	* uni0450
	* uni0451
	* uni0452
	* uni0453
	* uni0454
	* uni0455
	* uni0456
	* uni0457
	* uni0458
	* uni0459
	* uni045A
	* uni045B
	* uni045C
	* uni045D
	* uni045E
	* uni045F
	* uni0462
	* uni0463
	* uni046A
	* uni046B
	* uni0472
	* uni0473
	* uni0474
	* uni0475
	* uni0490
	* uni0491
	* uni0492
	* uni0493
	* uni0494
	* uni0495
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni049C
	* uni049D
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04A4
	* uni04A5
	* uni04AA
	* uni04AB
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04BA
	* uni04BB
	* uni04C0
	* uni04C1
	* uni04C2
	* uni04CB
	* uni04CC
	* uni04CF
	* uni04D0
	* uni04D1
	* uni04D2
	* uni04D3
	* uni04D4
	* uni04D5
	* uni04D6
	* uni04D7
	* uni04D8
	* uni04D9
	* uni04DC
	* uni04DD
	* uni04DE
	* uni04DF
	* uni04E2
	* uni04E3
	* uni04E4
	* uni04E5
	* uni04E6
	* uni04E7
	* uni04E8
	* uni04E9
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F4
	* uni04F5
	* uni04F6
	* uni04F7
	* uni04F8
	* uni04F9
	* uni051A
	* uni051B
	* uni051C
	* uni051D
	* uni0524
	* uni0525
	* uni05B8
	* uni05D0
	* uni05D1
	* uni05D2
	* uni05D3
	* uni05D4
	* uni05D5
	* uni05D6
	* uni05D7
	* uni05D8
	* uni05D9
	* uni05DA
	* uni05DB
	* uni05DC
	* uni05DD
	* uni05DE
	* uni05DF
	* uni05E0
	* uni05E1
	* uni05E2
	* uni05E3
	* uni05E4
	* uni05E5
	* uni05E6
	* uni05E7
	* uni05E8
	* uni05E9
	* uni05EA
	* uni05F2
	* uni05F4
	* uni1E9E
	* uni2070
	* uni2074
	* uni2075
	* uni2078
	* uni2079
	* uni2080
	* uni2082
	* uni2083
	* uni2084
	* uni2085
	* uni2088
	* uni2089
	* uni20AA
	* uni20AE
	* uni20B4
	* uni20B8
	* uni20B9
	* uni20BD
	* uni2116
	* uni2153
	* uni2154
	* uni2206
	* uni2215
	* uniFB2A
	* uniFB2B
	* uniFB2C
	* uniFB2D
	* uniFB2E
	* uniFB2F
	* uniFB30
	* uniFB31
	* uniFB32
	* uniFB33
	* uniFB34
	* uniFB35
	* uniFB36
	* uniFB38
	* uniFB39
	* uniFB3A
	* uniFB3B
	* uniFB3C
	* uniFB3E
	* uniFB40
	* uniFB41
	* uniFB43
	* uniFB44
	* uniFB46
	* uniFB47
	* uniFB48
	* uniFB49
	* uniFB4A
	* uniFB4B
	* uogonek
	* uring
	* ustraitcy
	* ustraitstrokecy
	* utilde
	* v
	* w
	* wacute
	* wcircumflex
	* wdieresis
	* wgrave
	* x
	* y
	* yacute
	* ycircumflex
	* ydieresis
	* yen
	* ygrave
	* z
	* zacute
	* zcaron
	* zdotaccent
	* zero
	* zero.dnom
	* zero.numr
	* zero.tf
	* zero.tf.zero and zero.zero
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.BRACKET.125

	- parenleft.denominator

	- parenleft.numerator

	- parenright.denominator

	- parenright.numerator

	- uni030C.alt

	- uni20B4.BRACKET.125 

	- And yen.BRACKET.125
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: ustraitstrokecy	Contours detected: 2	Expected: 1

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2 

	- And Glyph name: uni00AD	Contours detected: 1	Expected: 0
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni04CB (U+04CB): L<<531.0,71.0>--<531.0,71.0>> -> L<<531.0,71.0>--<531.0,71.0>> 

	* And uni0524 (U+0524): L<<488.0,90.0>--<488.0,90.0>> -> L<<488.0,90.0>--<488.0,90.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0495 (U+0495): L<<202.0,440.0>--<163.0,254.0>>/L<<163.0,254.0>--<167.0,273.0>> = 0.04658192429955475 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[11] Rubik-Bold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x04B2 (CYRILLIC CAPITAL LETTER HA WITH DESCENDER)
 

	- And 0x04B3 (CYRILLIC SMALL LETTER HA WITH DESCENDER)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* Hbar
	* Ustraitstrokecy
	* hbar
	* uni044E
	* uni0462
	* uni0463
	* uni0473
	* uni0492
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni04A2
	* uni04A3
	* uni04AA
	* uni04AB
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04CB
	* uni04CC
	* uni04E8
	* uni04E9
	* uni04F6
	* uni04F7
	* uni0524
	* uni0525
	* uni05B8
	* uni05D2
	* uni05DC
	* uni05DE
	* uni05E0
	* uni05E2
	* uni05EA
	* uni20AE
	* uni20B4
	* uni20B9
	* uniFB2F
	* uniFB32
	* uniFB3C
	* uniFB3E
	* uniFB40
	* uniFB4A
	* yen
	* zero.tf.zero and zero.zero
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.BRACKET.125

	- parenleft.denominator

	- parenleft.numerator

	- parenright.denominator

	- parenright.numerator

	- uni030C.alt

	- uni20B4.BRACKET.125 

	- And yen.BRACKET.125
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0493	Contours detected: 2	Expected: 1

	- Glyph name: ustraitstrokecy	Contours detected: 2	Expected: 1

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uni0493	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* quotedbl (U+0022): X=255.5,Y=702.0 (should be at cap-height 700?)

	* quotedbl (U+0022): X=405.5,Y=702.0 (should be at cap-height 700?)

	* quotedbl (U+0022): X=46.5,Y=702.0 (should be at cap-height 700?)

	* quotedbl (U+0022): X=196.5,Y=702.0 (should be at cap-height 700?)

	* quotesingle (U+0027): X=46.5,Y=702.0 (should be at cap-height 700?)

	* quotesingle (U+0027): X=196.5,Y=702.0 (should be at cap-height 700?)

	* cent (U+00A2): X=221.0,Y=-1.0 (should be at baseline 0?)

	* cent (U+00A2): X=370.0,Y=-2.0 (should be at baseline 0?)

	* macron (U+00AF): X=58.0,Y=698.0 (should be at cap-height 700?)

	* macron (U+00AF): X=382.0,Y=698.0 (should be at cap-height 700?)

	* aring (U+00E5): X=314.5,Y=699.0 (should be at cap-height 700?)

	* aring (U+00E5): X=271.5,Y=699.0 (should be at cap-height 700?)

	* oslash (U+00F8): X=46.0,Y=-2.0 (should be at baseline 0?)

	* amacron (U+0101): X=131.0,Y=698.0 (should be at cap-height 700?)

	* amacron (U+0101): X=455.0,Y=698.0 (should be at cap-height 700?)

	* dcaron (U+010F): X=655.0,Y=699.0 (should be at cap-height 700?)

	* emacron (U+0113): X=136.0,Y=698.0 (should be at cap-height 700?)

	* emacron (U+0113): X=460.0,Y=698.0 (should be at cap-height 700?)

	* eogonek (U+0119): X=206.0,Y=1.0 (should be at baseline 0?)

	* imacron (U+012B): X=-19.0,Y=698.0 (should be at cap-height 700?)

	* imacron (U+012B): X=305.0,Y=698.0 (should be at cap-height 700?)

	* lcaron (U+013E): X=309.0,Y=699.0 (should be at cap-height 700?)

	* Eng (U+014A): X=479.0,Y=1.0 (should be at baseline 0?)

	* omacron (U+014D): X=143.0,Y=698.0 (should be at cap-height 700?)

	* omacron (U+014D): X=467.0,Y=698.0 (should be at cap-height 700?)

	* umacron (U+016B): X=157.0,Y=698.0 (should be at cap-height 700?)

	* umacron (U+016B): X=481.0,Y=698.0 (should be at cap-height 700?)

	* uring (U+016F): X=340.5,Y=699.0 (should be at cap-height 700?)

	* uring (U+016F): X=297.5,Y=699.0 (should be at cap-height 700?)

	* uogonek (U+0173): X=548.0,Y=-1.0 (should be at baseline 0?)

	* oslashacute (U+01FF): X=46.0,Y=-2.0 (should be at baseline 0?)

	* ring (U+02DA): X=171.5,Y=699.0 (should be at cap-height 700?)

	* ring (U+02DA): X=128.5,Y=699.0 (should be at cap-height 700?)

	* uni0304 (U+0304): X=58.0,Y=698.0 (should be at cap-height 700?)

	* uni0304 (U+0304): X=382.0,Y=698.0 (should be at cap-height 700?)

	* uni030A (U+030A): X=171.5,Y=699.0 (should be at cap-height 700?)

	* uni030A (U+030A): X=128.5,Y=699.0 (should be at cap-height 700?)

	* uni0498 (U+0498): X=426.0,Y=-2.0 (should be at baseline 0?)

	* uni0499 (U+0499): X=378.0,Y=1.0 (should be at baseline 0?)

	* uni04AA (U+04AA): X=268.0,Y=-2.0 (should be at baseline 0?)

	* uni04AA (U+04AA): X=448.0,Y=-1.0 (should be at baseline 0?)

	* uni04AB (U+04AB): X=218.0,Y=-1.0 (should be at baseline 0?)

	* uni04E3 (U+04E3): X=170.0,Y=698.0 (should be at cap-height 700?)

	* uni04E3 (U+04E3): X=494.0,Y=698.0 (should be at cap-height 700?)

	* uni04EF (U+04EF): X=140.0,Y=698.0 (should be at cap-height 700?)

	* uni04EF (U+04EF): X=464.0,Y=698.0 (should be at cap-height 700?)

	* uni05E2 (U+05E2): X=317.0,Y=-1.0 (should be at baseline 0?)

	* uni05EA (U+05EA): X=68.0,Y=1.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=121.0,Y=701.0 (should be at cap-height 700?)

	* quoteright (U+2019): X=82.5,Y=699.0 (should be at cap-height 700?)

	* quotedblleft (U+201C): X=341.5,Y=701.0 (should be at cap-height 700?)

	* quotedblleft (U+201C): X=121.0,Y=701.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=302.5,Y=699.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=82.5,Y=699.0 (should be at cap-height 700?)

	* uni2085 (U+2085): X=43.0,Y=2.0 (should be at baseline 0?)

	* uni20B8 (U+20B8): X=46.0,Y=699.0 (should be at cap-height 700?)

	* uni20B8 (U+20B8): X=584.0,Y=699.0 (should be at cap-height 700?)

	* lozenge (U+25CA): X=233.0,Y=698.5 (should be at cap-height 700?)

	* lozenge (U+25CA): X=356.0,Y=698.5 (should be at cap-height 700?) 

	* And uniFB4A (U+FB4A): X=68.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni05DC (U+05DC): L<<195.0,434.0>--<193.0,434.0>> -> L<<193.0,434.0>--<61.0,434.0>>

	* uni05DC (U+05DC): L<<218.0,434.0>--<195.0,434.0>> -> L<<195.0,434.0>--<193.0,434.0>>

	* uniFB3C (U+FB3C): L<<195.0,434.0>--<193.0,434.0>> -> L<<193.0,434.0>--<61.0,434.0>> 

	* And uniFB3C (U+FB3C): L<<218.0,434.0>--<195.0,434.0>> -> L<<195.0,434.0>--<193.0,434.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni0434 (U+0434): L<<249.0,131.0>--<399.0,132.0>>

	* uni0446 (U+0446): L<<568.0,495.0>--<567.0,131.0>>

	* uni0474 (U+0474): L<<702.0,678.0>--<701.0,561.0>>

	* uni05E3 (U+05E3): L<<527.0,315.0>--<528.0,-99.0>>

	* uni05E9 (U+05E9): L<<207.0,547.0>--<208.0,302.0>>

	* uni05EA (U+05EA): L<<275.0,0.0>--<68.0,1.0>>

	* uniFB2A (U+FB2A): L<<207.0,547.0>--<208.0,302.0>>

	* uniFB2B (U+FB2B): L<<207.0,547.0>--<208.0,302.0>>

	* uniFB2C (U+FB2C): L<<207.0,547.0>--<208.0,302.0>>

	* uniFB2D (U+FB2D): L<<207.0,547.0>--<208.0,302.0>>

	* uniFB43 (U+FB43): L<<527.0,315.0>--<528.0,-99.0>>

	* uniFB49 (U+FB49): L<<207.0,547.0>--<208.0,302.0>> 

	* And uniFB4A (U+FB4A): L<<275.0,0.0>--<68.0,1.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] Rubik-Black.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x04B2 (CYRILLIC CAPITAL LETTER HA WITH DESCENDER)
 

	- And 0x04B3 (CYRILLIC SMALL LETTER HA WITH DESCENDER)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* Hbar
	* Ustraitstrokecy
	* hbar
	* uni040E
	* uni0423
	* uni0443
	* uni044E
	* uni045E
	* uni0462
	* uni0463
	* uni0473
	* uni0492
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni04A2
	* uni04A3
	* uni04AA
	* uni04AB
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04CB
	* uni04CC
	* uni04E8
	* uni04E9
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F6
	* uni04F7
	* uni0524
	* uni0525
	* uni05B8
	* uni05D2
	* uni05DC
	* uni05DE
	* uni05E0
	* uni05E2
	* uni05EA
	* uni20AE
	* uni20B4
	* uni20B9
	* uniFB2F
	* uniFB32
	* uniFB3C
	* uniFB3E
	* uniFB40
	* uniFB4A
	* yen
	* zero.tf.zero and zero.zero
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.BRACKET.125

	- parenleft.denominator

	- parenleft.numerator

	- parenright.denominator

	- parenright.numerator

	- uni030C.alt

	- uni20B4.BRACKET.125 

	- And yen.BRACKET.125
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0493	Contours detected: 2	Expected: 1

	- Glyph name: ustraitstrokecy	Contours detected: 2	Expected: 1

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uni0493	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* quotedbl (U+0022): X=289.5,Y=700.5 (should be at cap-height 700?)

	* quotedbl (U+0022): X=484.5,Y=700.5 (should be at cap-height 700?)

	* quotedbl (U+0022): X=34.5,Y=700.5 (should be at cap-height 700?)

	* quotedbl (U+0022): X=229.5,Y=700.5 (should be at cap-height 700?)

	* ampersand (U+0026): X=406.5,Y=-2.0 (should be at baseline 0?)

	* quotesingle (U+0027): X=34.5,Y=700.5 (should be at cap-height 700?)

	* quotesingle (U+0027): X=229.5,Y=700.5 (should be at cap-height 700?)

	* b (U+0062): X=53.0,Y=702.0 (should be at cap-height 700?)

	* b (U+0062): X=276.0,Y=702.0 (should be at cap-height 700?)

	* d (U+0064): X=385.0,Y=702.0 (should be at cap-height 700?)

	* d (U+0064): X=608.0,Y=702.0 (should be at cap-height 700?)

	* h (U+0068): X=53.0,Y=702.0 (should be at cap-height 700?)

	* h (U+0068): X=286.0,Y=702.0 (should be at cap-height 700?)

	* j (U+006A): X=48.0,Y=-1.5 (should be at baseline 0?)

	* k (U+006B): X=53.0,Y=702.0 (should be at cap-height 700?)

	* k (U+006B): X=266.0,Y=702.0 (should be at cap-height 700?)

	* l (U+006C): X=53.0,Y=702.0 (should be at cap-height 700?)

	* l (U+006C): X=270.0,Y=702.0 (should be at cap-height 700?)

	* t (U+0074): X=125.0,Y=702.0 (should be at cap-height 700?)

	* t (U+0074): X=338.0,Y=702.0 (should be at cap-height 700?)

	* braceleft (U+007B): X=123.0,Y=1.5 (should be at baseline 0?)

	* braceleft (U+007B): X=451.0,Y=1.0 (should be at baseline 0?)

	* braceright (U+007D): X=351.0,Y=2.0 (should be at baseline 0?)

	* braceright (U+007D): X=23.0,Y=1.0 (should be at baseline 0?)

	* cent (U+00A2): X=410.0,Y=2.0 (should be at baseline 0?)

	* sterling (U+00A3): X=429.0,Y=1.0 (should be at baseline 0?)

	* ae (U+00E6): X=328.5,Y=1.0 (should be at baseline 0?)

	* eth (U+00F0): X=540.0,Y=699.0 (should be at cap-height 700?)

	* thorn (U+00FE): X=54.0,Y=702.0 (should be at cap-height 700?)

	* thorn (U+00FE): X=277.0,Y=702.0 (should be at cap-height 700?)

	* dcaron (U+010F): X=385.0,Y=702.0 (should be at cap-height 700?)

	* dcaron (U+010F): X=608.0,Y=702.0 (should be at cap-height 700?)

	* dcroat (U+0111): X=385.0,Y=702.0 (should be at cap-height 700?)

	* dcroat (U+0111): X=608.0,Y=702.0 (should be at cap-height 700?)

	* hcircumflex (U+0125): X=53.0,Y=702.0 (should be at cap-height 700?)

	* hcircumflex (U+0125): X=286.0,Y=702.0 (should be at cap-height 700?)

	* hbar (U+0127): X=53.0,Y=702.0 (should be at cap-height 700?)

	* hbar (U+0127): X=286.0,Y=702.0 (should be at cap-height 700?)

	* IJ (U+0132): X=401.0,Y=-2.0 (should be at baseline 0?)

	* ij (U+0133): X=415.0,Y=-1.5 (should be at baseline 0?)

	* uni0137 (U+0137): X=53.0,Y=702.0 (should be at cap-height 700?)

	* uni0137 (U+0137): X=266.0,Y=702.0 (should be at cap-height 700?)

	* lacute (U+013A): X=53.0,Y=702.0 (should be at cap-height 700?)

	* lacute (U+013A): X=270.0,Y=702.0 (should be at cap-height 700?)

	* uni013C (U+013C): X=53.0,Y=702.0 (should be at cap-height 700?)

	* uni013C (U+013C): X=270.0,Y=702.0 (should be at cap-height 700?)

	* lcaron (U+013E): X=53.0,Y=702.0 (should be at cap-height 700?)

	* lcaron (U+013E): X=270.0,Y=702.0 (should be at cap-height 700?)

	* ldot (U+0140): X=53.0,Y=702.0 (should be at cap-height 700?)

	* ldot (U+0140): X=270.0,Y=702.0 (should be at cap-height 700?)

	* lslash (U+0142): X=92.0,Y=702.0 (should be at cap-height 700?)

	* lslash (U+0142): X=309.0,Y=702.0 (should be at cap-height 700?)

	* oe (U+0153): X=566.0,Y=-2.0 (should be at baseline 0?)

	* tcaron (U+0165): X=125.0,Y=702.0 (should be at cap-height 700?)

	* tcaron (U+0165): X=338.0,Y=702.0 (should be at cap-height 700?)

	* tbar (U+0167): X=126.0,Y=702.0 (should be at cap-height 700?)

	* tbar (U+0167): X=339.0,Y=702.0 (should be at cap-height 700?)

	* aeacute (U+01FD): X=328.5,Y=1.0 (should be at baseline 0?)

	* uni021B (U+021B): X=125.0,Y=702.0 (should be at cap-height 700?)

	* uni021B (U+021B): X=338.0,Y=702.0 (should be at cap-height 700?)

	* uni0439 (U+0439): X=352.0,Y=701.0 (should be at cap-height 700?)

	* uni0444 (U+0444): X=333.0,Y=702.0 (should be at cap-height 700?)

	* uni0444 (U+0444): X=550.0,Y=702.0 (should be at cap-height 700?)

	* uni0452 (U+0452): X=76.0,Y=702.0 (should be at cap-height 700?)

	* uni0452 (U+0452): X=309.0,Y=702.0 (should be at cap-height 700?)

	* uni0458 (U+0458): X=48.0,Y=-1.5 (should be at baseline 0?)

	* uni045B (U+045B): X=76.0,Y=702.0 (should be at cap-height 700?)

	* uni045B (U+045B): X=309.0,Y=702.0 (should be at cap-height 700?)

	* uni045E (U+045E): X=326.0,Y=701.0 (should be at cap-height 700?)

	* uni0463 (U+0463): X=87.0,Y=702.0 (should be at cap-height 700?)

	* uni0463 (U+0463): X=305.0,Y=702.0 (should be at cap-height 700?)

	* uni0498 (U+0498): X=478.0,Y=1.0 (should be at baseline 0?)

	* uni0499 (U+0499): X=196.0,Y=-1.0 (should be at baseline 0?)

	* uni04BB (U+04BB): X=53.0,Y=702.0 (should be at cap-height 700?)

	* uni04BB (U+04BB): X=286.0,Y=702.0 (should be at cap-height 700?)

	* uni04C2 (U+04C2): X=507.0,Y=701.0 (should be at cap-height 700?)

	* uni04CF (U+04CF): X=53.0,Y=702.0 (should be at cap-height 700?)

	* uni04CF (U+04CF): X=270.0,Y=702.0 (should be at cap-height 700?)

	* uni04D1 (U+04D1): X=321.0,Y=701.0 (should be at cap-height 700?)

	* uni04D5 (U+04D5): X=328.5,Y=1.0 (should be at baseline 0?)

	* uni04D7 (U+04D7): X=311.0,Y=701.0 (should be at cap-height 700?)

	* uni05DC (U+05DC): X=24.0,Y=702.0 (should be at cap-height 700?)

	* uni05DC (U+05DC): X=215.0,Y=702.0 (should be at cap-height 700?)

	* quoteleft (U+2018): X=125.0,Y=699.0 (should be at cap-height 700?)

	* quotedblleft (U+201C): X=397.0,Y=699.0 (should be at cap-height 700?)

	* quotedblleft (U+201C): X=125.0,Y=699.0 (should be at cap-height 700?)

	* uni2082 (U+2082): X=299.5,Y=-1.5 (should be at baseline 0?)

	* uni2085 (U+2085): X=40.0,Y=-1.0 (should be at baseline 0?)

	* uni20B8 (U+20B8): X=44.0,Y=699.0 (should be at cap-height 700?)

	* uni20B8 (U+20B8): X=630.0,Y=699.0 (should be at cap-height 700?)

	* lozenge (U+25CA): X=237.0,Y=698.5 (should be at cap-height 700?)

	* lozenge (U+25CA): X=387.0,Y=698.5 (should be at cap-height 700?)

	* uniFB3C (U+FB3C): X=24.0,Y=702.0 (should be at cap-height 700?) 

	* And uniFB3C (U+FB3C): X=215.0,Y=702.0 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni049C (U+049C): L<<393.0,448.0>--<394.0,450.0>> -> L<<394.0,450.0>--<523.0,678.0>>

	* uni05E9 (U+05E9): L<<250.0,545.0>--<250.0,335.0>> -> L<<250.0,335.0>--<250.0,334.0>>

	* uniFB2A (U+FB2A): L<<250.0,545.0>--<250.0,335.0>> -> L<<250.0,335.0>--<250.0,334.0>>

	* uniFB2B (U+FB2B): L<<250.0,545.0>--<250.0,335.0>> -> L<<250.0,335.0>--<250.0,334.0>>

	* uniFB2C (U+FB2C): L<<250.0,545.0>--<250.0,335.0>> -> L<<250.0,335.0>--<250.0,334.0>>

	* uniFB2D (U+FB2D): L<<250.0,545.0>--<250.0,335.0>> -> L<<250.0,335.0>--<250.0,334.0>> 

	* And uniFB49 (U+FB49): L<<250.0,545.0>--<250.0,335.0>> -> L<<250.0,335.0>--<250.0,334.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* g (U+0067): L<<620.0,493.0>--<621.0,17.0>>

	* gbreve (U+011F): L<<620.0,493.0>--<621.0,17.0>>

	* gcircumflex (U+011D): L<<620.0,493.0>--<621.0,17.0>>

	* gdotaccent (U+0121): L<<620.0,493.0>--<621.0,17.0>>

	* uni0123 (U+0123): L<<620.0,493.0>--<621.0,17.0>>

	* uni0474 (U+0474): L<<736.0,672.0>--<735.0,495.0>>

	* uni05E3 (U+05E3): L<<548.0,308.0>--<549.0,-97.0>> 

	* And uniFB43 (U+FB43): L<<548.0,308.0>--<549.0,-97.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] Rubik-Light.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x04B2 (CYRILLIC CAPITAL LETTER HA WITH DESCENDER)
 

	- And 0x04B3 (CYRILLIC SMALL LETTER HA WITH DESCENDER)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* Hbar
	* uni05B8
	* uni20AE
	* uni20B4 and yen
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.BRACKET.125

	- parenleft.denominator

	- parenleft.numerator

	- parenright.denominator

	- parenright.numerator

	- uni030C.alt

	- uni20B4.BRACKET.125 

	- And yen.BRACKET.125
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0493	Contours detected: 2	Expected: 1

	- Glyph name: ustraitstrokecy	Contours detected: 2	Expected: 1

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uni0493	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft (U+0028): X=204.0,Y=698.5 (should be at cap-height 700?)

	* parenright (U+0029): X=115.0,Y=698.5 (should be at cap-height 700?)

	* one (U+0031): X=263.0,Y=699.0 (should be at cap-height 700?)

	* braceright (U+007D): X=197.0,Y=699.5 (should be at cap-height 700?)

	* questiondown (U+00BF): X=97.0,Y=-2.0 (should be at baseline 0?)

	* aogonek (U+0105): X=445.0,Y=1.0 (should be at baseline 0?)

	* eogonek (U+0119): X=213.0,Y=-2.0 (should be at baseline 0?)

	* uogonek (U+0173): X=485.0,Y=-2.0 (should be at baseline 0?)

	* uni0409 (U+0409): X=43.0,Y=1.0 (should be at baseline 0?)

	* uni0409 (U+0409): X=43.0,Y=1.0 (should be at baseline 0?)

	* uni041B (U+041B): X=43.0,Y=1.0 (should be at baseline 0?)

	* uni0431 (U+0431): X=473.0,Y=702.0 (should be at cap-height 700?)

	* uni0459 (U+0459): X=48.0,Y=1.0 (should be at baseline 0?)

	* uni04CC (U+04CC): X=399.0,Y=1.0 (should be at baseline 0?)

	* uni05E2 (U+05E2): X=62.0,Y=1.0 (should be at baseline 0?)

	* uni05EA (U+05EA): X=79.0,Y=2.0 (should be at baseline 0?)

	* uni2085 (U+2085): X=129.0,Y=-1.5 (should be at baseline 0?)

	* lozenge (U+25CA): X=227.5,Y=699.0 (should be at cap-height 700?)

	* lozenge (U+25CA): X=304.5,Y=699.0 (should be at cap-height 700?) 

	* And uniFB4A (U+FB4A): X=79.0,Y=2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni05B3 (U+05B3): L<<26.0,-131.0>--<26.0,-134.0>> -> L<<26.0,-134.0>--<26.0,-223.0>>

	* uni05C7 (U+05C7): L<<26.0,-131.0>--<26.0,-134.0>> -> L<<26.0,-134.0>--<26.0,-223.0>>

	* uni05DC (U+05DC): L<<173.0,513.0>--<170.0,513.0>> -> L<<170.0,513.0>--<92.0,514.0>>

	* uni05DC (U+05DC): L<<207.0,513.0>--<173.0,513.0>> -> L<<173.0,513.0>--<170.0,513.0>>

	* uniFB2F (U+FB2F): L<<311.0,-131.0>--<311.0,-134.0>> -> L<<311.0,-134.0>--<311.0,-223.0>>

	* uniFB3C (U+FB3C): L<<173.0,513.0>--<170.0,513.0>> -> L<<170.0,513.0>--<92.0,514.0>> 

	* And uniFB3C (U+FB3C): L<<207.0,513.0>--<173.0,513.0>> -> L<<173.0,513.0>--<170.0,513.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* uni0434 (U+0434): L<<133.0,58.0>--<409.0,60.0>> 

	* And uni0446 (U+0446): L<<495.0,498.0>--<494.0,58.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[10] Rubik-ExtraBold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x04B2 (CYRILLIC CAPITAL LETTER HA WITH DESCENDER)
 

	- And 0x04B3 (CYRILLIC SMALL LETTER HA WITH DESCENDER)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* Hbar
	* Ustraitstrokecy
	* hbar
	* uni040E
	* uni0423
	* uni0443
	* uni044E
	* uni045E
	* uni0462
	* uni0463
	* uni0473
	* uni0492
	* uni0496
	* uni0497
	* uni0498
	* uni0499
	* uni049A
	* uni049B
	* uni04A2
	* uni04A3
	* uni04AA
	* uni04AB
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04B9
	* uni04CB
	* uni04CC
	* uni04E8
	* uni04E9
	* uni04EE
	* uni04EF
	* uni04F0
	* uni04F1
	* uni04F2
	* uni04F3
	* uni04F6
	* uni04F7
	* uni0524
	* uni0525
	* uni05B8
	* uni05D2
	* uni05DC
	* uni05DE
	* uni05E0
	* uni05E2
	* uni05EA
	* uni20AE
	* uni20B4
	* uni20B9
	* uniFB2F
	* uniFB32
	* uniFB3C
	* uniFB3E
	* uniFB40
	* uniFB4A
	* yen
	* zero.tf.zero and zero.zero
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.BRACKET.125

	- parenleft.denominator

	- parenleft.numerator

	- parenright.denominator

	- parenright.numerator

	- uni030C.alt

	- uni20B4.BRACKET.125 

	- And yen.BRACKET.125
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0493	Contours detected: 2	Expected: 1

	- Glyph name: ustraitstrokecy	Contours detected: 2	Expected: 1

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uni0493	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* quotedbl (U+0022): X=272.5,Y=701.0 (should be at cap-height 700?)

	* quotedbl (U+0022): X=445.0,Y=701.0 (should be at cap-height 700?)

	* quotedbl (U+0022): X=40.0,Y=701.0 (should be at cap-height 700?)

	* quotedbl (U+0022): X=213.0,Y=701.0 (should be at cap-height 700?)

	* dollar (U+0024): X=419.0,Y=702.0 (should be at cap-height 700?)

	* ampersand (U+0026): X=407.5,Y=1.5 (should be at baseline 0?)

	* quotesingle (U+0027): X=40.0,Y=701.0 (should be at cap-height 700?)

	* quotesingle (U+0027): X=213.0,Y=701.0 (should be at cap-height 700?)

	* parenleft (U+0028): X=355.0,Y=-1.0 (should be at baseline 0?)

	* parenright (U+0029): X=48.0,Y=-1.0 (should be at baseline 0?)

	* less (U+003C): X=450.0,Y=-1.0 (should be at baseline 0?)

	* less (U+003C): X=450.0,Y=-1.0 (should be at baseline 0?)

	* greater (U+003E): X=77.0,Y=-2.0 (should be at baseline 0?)

	* greater (U+003E): X=77.0,Y=-2.0 (should be at baseline 0?)

	* Q (U+0051): X=436.0,Y=-2.0 (should be at baseline 0?)

	* braceleft (U+007B): X=401.0,Y=1.0 (should be at baseline 0?)

	* cent (U+00A2): X=214.0,Y=1.0 (should be at baseline 0?)

	* oslash (U+00F8): X=43.0,Y=-1.5 (should be at baseline 0?)

	* abreve (U+0103): X=268.0,Y=698.5 (should be at cap-height 700?)

	* abreve (U+0103): X=336.0,Y=698.5 (should be at cap-height 700?)

	* dcaron (U+010F): X=678.5,Y=698.0 (should be at cap-height 700?)

	* ebreve (U+0115): X=271.0,Y=698.5 (should be at cap-height 700?)

	* ebreve (U+0115): X=339.0,Y=698.5 (should be at cap-height 700?)

	* eogonek (U+0119): X=204.0,Y=2.0 (should be at baseline 0?)

	* gbreve (U+011F): X=284.0,Y=698.5 (should be at cap-height 700?)

	* gbreve (U+011F): X=352.0,Y=698.5 (should be at cap-height 700?)

	* ibreve (U+012D): X=119.0,Y=698.5 (should be at cap-height 700?)

	* ibreve (U+012D): X=187.0,Y=698.5 (should be at cap-height 700?)

	* lcaron (U+013E): X=334.5,Y=698.0 (should be at cap-height 700?)

	* obreve (U+014F): X=279.0,Y=698.5 (should be at cap-height 700?)

	* obreve (U+014F): X=347.0,Y=698.5 (should be at cap-height 700?)

	* oe (U+0153): X=413.0,Y=2.0 (should be at baseline 0?)

	* ubreve (U+016D): X=294.0,Y=698.5 (should be at cap-height 700?)

	* ubreve (U+016D): X=362.0,Y=698.5 (should be at cap-height 700?)

	* oslashacute (U+01FF): X=43.0,Y=-1.5 (should be at baseline 0?)

	* breve (U+02D8): X=181.0,Y=698.5 (should be at cap-height 700?)

	* breve (U+02D8): X=249.0,Y=698.5 (should be at cap-height 700?)

	* uni0306 (U+0306): X=181.0,Y=698.5 (should be at cap-height 700?)

	* uni0306 (U+0306): X=249.0,Y=698.5 (should be at cap-height 700?)

	* uni0474 (U+0474): X=656.0,Y=702.0 (should be at cap-height 700?)

	* uni0474 (U+0474): X=695.0,Y=702.0 (should be at cap-height 700?)

	* uni04AA (U+04AA): X=258.0,Y=1.0 (should be at baseline 0?)

	* uni04AA (U+04AA): X=473.0,Y=2.0 (should be at baseline 0?)

	* uni04AB (U+04AB): X=208.0,Y=2.0 (should be at baseline 0?)

	* uni051A (U+051A): X=436.0,Y=-2.0 (should be at baseline 0?)

	* quoteright (U+2019): X=79.5,Y=698.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=326.0,Y=698.0 (should be at cap-height 700?)

	* quotedblright (U+201D): X=79.5,Y=698.0 (should be at cap-height 700?)

	* uni2085 (U+2085): X=41.0,Y=1.0 (should be at baseline 0?)

	* uni20B8 (U+20B8): X=45.0,Y=699.0 (should be at cap-height 700?)

	* uni20B8 (U+20B8): X=607.0,Y=699.0 (should be at cap-height 700?)

	* summation (U+2211): X=68.0,Y=1.0 (should be at baseline 0?)

	* summation (U+2211): X=336.0,Y=-1.0 (should be at baseline 0?)

	* summation (U+2211): X=569.0,Y=-1.0 (should be at baseline 0?)

	* lozenge (U+25CA): X=235.0,Y=698.5 (should be at cap-height 700?) 

	* And lozenge (U+25CA): X=372.0,Y=698.5 (should be at cap-height 700?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* g (U+0067): L<<597.0,494.0>--<598.0,16.0>>

	* gbreve (U+011F): L<<597.0,494.0>--<598.0,16.0>>

	* gcircumflex (U+011D): L<<597.0,494.0>--<598.0,16.0>>

	* gdotaccent (U+0121): L<<597.0,494.0>--<598.0,16.0>>

	* uni0123 (U+0123): L<<597.0,494.0>--<598.0,16.0>>

	* uni0474 (U+0474): L<<719.0,675.0>--<718.0,528.0>>

	* uni05E9 (U+05E9): L<<228.0,546.0>--<229.0,318.0>>

	* uniFB2A (U+FB2A): L<<228.0,546.0>--<229.0,318.0>>

	* uniFB2B (U+FB2B): L<<228.0,546.0>--<229.0,318.0>>

	* uniFB2C (U+FB2C): L<<228.0,546.0>--<229.0,318.0>>

	* uniFB2D (U+FB2D): L<<228.0,546.0>--<229.0,318.0>>

	* uniFB43 (U+FB43): L<<538.0,312.0>--<539.0,-98.0>> 

	* And uniFB49 (U+FB49): L<<228.0,546.0>--<229.0,318.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] Rubik-SemiBold.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x04B2 (CYRILLIC CAPITAL LETTER HA WITH DESCENDER)
 

	- And 0x04B3 (CYRILLIC SMALL LETTER HA WITH DESCENDER)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* Hbar
	* Ustraitstrokecy
	* hbar
	* uni044E
	* uni0462
	* uni0463
	* uni0473
	* uni0492
	* uni0496
	* uni0497
	* uni0498
	* uni049A
	* uni049B
	* uni04A2
	* uni04A3
	* uni04AA
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04CB
	* uni04CC
	* uni04E8
	* uni04E9
	* uni04F6
	* uni04F7
	* uni0524
	* uni0525
	* uni05B8
	* uni05D2
	* uni05E0
	* uni05E2
	* uni05EA
	* uni20AE
	* uni20B4
	* uni20B9
	* uniFB2F
	* uniFB32
	* uniFB40
	* uniFB4A
	* yen
	* zero.tf.zero and zero.zero
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.BRACKET.125

	- parenleft.denominator

	- parenleft.numerator

	- parenright.denominator

	- parenright.numerator

	- uni030C.alt

	- uni20B4.BRACKET.125 

	- And yen.BRACKET.125
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: uni0493	Contours detected: 2	Expected: 1

	- Glyph name: ustraitstrokecy	Contours detected: 2	Expected: 1

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0 

	- And Glyph name: uni0493	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* cent (U+00A2): X=225.0,Y=-2.0 (should be at baseline 0?)

	* atilde (U+00E3): X=303.5,Y=702.0 (should be at cap-height 700?)

	* atilde (U+00E3): X=353.0,Y=700.5 (should be at cap-height 700?)

	* ntilde (U+00F1): X=334.5,Y=702.0 (should be at cap-height 700?)

	* ntilde (U+00F1): X=384.0,Y=700.5 (should be at cap-height 700?)

	* otilde (U+00F5): X=316.5,Y=702.0 (should be at cap-height 700?)

	* otilde (U+00F5): X=366.0,Y=700.5 (should be at cap-height 700?)

	* eogonek (U+0119): X=207.0,Y=1.0 (should be at baseline 0?)

	* itilde (U+0129): X=153.5,Y=702.0 (should be at cap-height 700?)

	* itilde (U+0129): X=203.0,Y=700.5 (should be at cap-height 700?)

	* eng (U+014B): X=420.0,Y=2.0 (should be at baseline 0?)

	* utilde (U+0169): X=329.5,Y=702.0 (should be at cap-height 700?)

	* utilde (U+0169): X=379.0,Y=700.5 (should be at cap-height 700?)

	* uogonek (U+0173): X=537.0,Y=-1.0 (should be at baseline 0?)

	* florin (U+0192): X=134.0,Y=2.0 (should be at baseline 0?)

	* tilde (U+02DC): X=238.5,Y=702.0 (should be at cap-height 700?)

	* tilde (U+02DC): X=288.0,Y=700.5 (should be at cap-height 700?)

	* tildecomb (U+0303): X=238.5,Y=702.0 (should be at cap-height 700?)

	* tildecomb (U+0303): X=288.0,Y=700.5 (should be at cap-height 700?)

	* uni0337 (U+0337): X=27.0,Y=-2.0 (should be at baseline 0?)

	* uni0499 (U+0499): X=362.0,Y=-1.0 (should be at baseline 0?)

	* uni04AB (U+04AB): X=373.0,Y=-2.0 (should be at baseline 0?)

	* uni05DC (U+05DC): X=237.0,Y=1.0 (should be at baseline 0?)

	* uni05E7 (U+05E7): X=356.0,Y=1.0 (should be at baseline 0?)

	* uni05EA (U+05EA): X=70.0,Y=1.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=120.5,Y=701.5 (should be at cap-height 700?)

	* quotedblleft (U+201C): X=325.0,Y=701.5 (should be at cap-height 700?)

	* quotedblleft (U+201C): X=120.5,Y=701.5 (should be at cap-height 700?)

	* uni2086 (U+2086): X=180.0,Y=-2.0 (should be at baseline 0?)

	* uni20B8 (U+20B8): X=46.0,Y=699.0 (should be at cap-height 700?)

	* uni20B8 (U+20B8): X=570.0,Y=699.0 (should be at cap-height 700?)

	* lozenge (U+25CA): X=232.0,Y=698.5 (should be at cap-height 700?)

	* lozenge (U+25CA): X=347.0,Y=698.5 (should be at cap-height 700?)

	* uniFB3C (U+FB3C): X=237.0,Y=1.0 (should be at baseline 0?)

	* uniFB47 (U+FB47): X=356.0,Y=1.0 (should be at baseline 0?) 

	* And uniFB4A (U+FB4A): X=70.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni0524 (U+0524): L<<504.0,25.0>--<504.0,140.0>> -> L<<504.0,140.0>--<504.0,142.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* g (U+0067): L<<561.0,495.0>--<562.0,14.0>>

	* gbreve (U+011F): L<<561.0,495.0>--<562.0,14.0>>

	* gcircumflex (U+011D): L<<561.0,495.0>--<562.0,14.0>>

	* gdotaccent (U+0121): L<<561.0,495.0>--<562.0,14.0>>

	* uni0123 (U+0123): L<<561.0,495.0>--<562.0,14.0>>

	* uni0434 (U+0434): L<<228.0,118.0>--<401.0,119.0>>

	* uni05E9 (U+05E9): L<<194.0,547.0>--<196.0,293.0>>

	* uni05EA (U+05EA): L<<260.0,0.0>--<70.0,1.0>>

	* uniFB2A (U+FB2A): L<<194.0,547.0>--<196.0,293.0>>

	* uniFB2B (U+FB2B): L<<194.0,547.0>--<196.0,293.0>>

	* uniFB2C (U+FB2C): L<<194.0,547.0>--<196.0,293.0>>

	* uniFB2D (U+FB2D): L<<194.0,547.0>--<196.0,293.0>>

	* uniFB43 (U+FB43): L<<521.0,317.0>--<522.0,-100.0>>

	* uniFB49 (U+FB49): L<<194.0,547.0>--<196.0,293.0>> 

	* And uniFB4A (U+FB4A): L<<260.0,0.0>--<70.0,1.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[11] Rubik-SemiBoldItalic.ttf</b></summary><div><details><summary>⚠ <b>WARN:</b> Checking OS/2 achVendID. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/vendor_id">com.google.fonts/check/vendor_id</a>)</summary><div>


* ⚠ **WARN** OS/2 VendorID value 'NONE' is not yet recognized. If you registered it recently, then it's safe to ignore this warning message. Otherwise, you should set it to your own unique 4 character code, and register it with Microsoft at https://www.microsoft.com/typography/links/vendorlist.aspx
 [code: unknown]
</div></details><details><summary>⚠ <b>WARN:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* ⚠ **WARN** GF_Cyrillic_Plus is almost fulfilled. Missing codepoints:

	- 0x04B2 (CYRILLIC CAPITAL LETTER HA WITH DESCENDER)
 

	- And 0x04B3 (CYRILLIC SMALL LETTER HA WITH DESCENDER)
 [code: missing-codepoints]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* Euro
	* Hbar
	* Ustraitstrokecy
	* hbar
	* uni044E
	* uni0462
	* uni0463
	* uni0473
	* uni0492
	* uni0493
	* uni0496
	* uni0497
	* uni0498
	* uni049A
	* uni049B
	* uni04A0
	* uni04A1
	* uni04A2
	* uni04A3
	* uni04AA
	* uni04B6
	* uni04B7
	* uni04B8
	* uni04CB
	* uni04CC
	* uni04E8
	* uni04E9
	* uni04F6
	* uni04F7
	* uni0524
	* uni0525
	* uni05B8
	* uni05D2
	* uni05DE
	* uni05E0
	* uni05E2
	* uni05EA
	* uni20AE
	* uni20B4
	* uni20B9
	* uniFB2F
	* uniFB32
	* uniFB3E
	* uniFB40
	* uniFB4A
	* yen
	* zero.tf.zero and zero.zero
</div></details><details><summary>⚠ <b>WARN:</b> Is there kerning info for non-ligated sequences? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/kerning_for_non_ligated_sequences">com.google.fonts/check/kerning_for_non_ligated_sequences</a>)</summary><div>


* ⚠ **WARN** GPOS table lacks kerning info for the following non-ligated sequences:

	- f + f

	- f + i

	- i + f

	- f + l

	- l + f 

	- And i + l [code: lacks-kern-info]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- Euro.BRACKET.125

	- parenleft.denominator

	- parenleft.numerator

	- parenright.denominator

	- parenright.numerator

	- uni030C.alt

	- uni20B4.BRACKET.125 

	- And yen.BRACKET.125
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: uni00AD	Contours detected: 1	Expected: 0

	- Glyph name: ustraitstrokecy	Contours detected: 2	Expected: 1

	- Glyph name: fi	Contours detected: 1	Expected: 3

	- Glyph name: fl	Contours detected: 1	Expected: 2 

	- And Glyph name: uni00AD	Contours detected: 1	Expected: 0
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* ⚠ **WARN** No dotted circle glyph present [code: missing-dotted-circle]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=465.0,Y=702.0 (should be at cap-height 700?)

	* at (U+0040): X=694.0,Y=0.5 (should be at baseline 0?)

	* cent (U+00A2): X=162.0,Y=1.0 (should be at baseline 0?)

	* uni00B5 (U+00B5): X=160.0,Y=2.0 (should be at baseline 0?)

	* atilde (U+00E3): X=404.0,Y=702.0 (should be at cap-height 700?)

	* atilde (U+00E3): X=455.5,Y=700.5 (should be at cap-height 700?)

	* ntilde (U+00F1): X=418.0,Y=702.0 (should be at cap-height 700?)

	* ntilde (U+00F1): X=469.5,Y=700.5 (should be at cap-height 700?)

	* otilde (U+00F5): X=401.0,Y=702.0 (should be at cap-height 700?)

	* otilde (U+00F5): X=452.5,Y=700.5 (should be at cap-height 700?)

	* eogonek (U+0119): X=159.0,Y=1.0 (should be at baseline 0?)

	* itilde (U+0129): X=242.0,Y=702.0 (should be at cap-height 700?)

	* itilde (U+0129): X=293.5,Y=700.5 (should be at cap-height 700?)

	* eng (U+014B): X=358.0,Y=2.0 (should be at baseline 0?)

	* utilde (U+0169): X=408.0,Y=702.0 (should be at cap-height 700?)

	* utilde (U+0169): X=459.5,Y=700.5 (should be at cap-height 700?)

	* Uogonek (U+0172): X=225.0,Y=-2.0 (should be at baseline 0?)

	* uogonek (U+0173): X=488.0,Y=-1.0 (should be at baseline 0?)

	* florin (U+0192): X=67.0,Y=2.0 (should be at baseline 0?)

	* tilde (U+02DC): X=226.0,Y=702.0 (should be at cap-height 700?)

	* tilde (U+02DC): X=277.5,Y=700.5 (should be at cap-height 700?)

	* tildecomb (U+0303): X=226.0,Y=702.0 (should be at cap-height 700?)

	* tildecomb (U+0303): X=277.5,Y=700.5 (should be at cap-height 700?)

	* uni0337 (U+0337): X=-53.0,Y=-2.0 (should be at baseline 0?)

	* uni0434 (U+0434): X=478.5,Y=702.0 (should be at cap-height 700?)

	* uni05DC (U+05DC): X=188.0,Y=1.0 (should be at baseline 0?)

	* uni05E7 (U+05E7): X=308.0,Y=1.0 (should be at baseline 0?)

	* uni05EA (U+05EA): X=22.0,Y=1.0 (should be at baseline 0?)

	* quoteleft (U+2018): X=206.0,Y=701.5 (should be at cap-height 700?)

	* quoteright (U+2019): X=318.0,Y=700.5 (should be at cap-height 700?)

	* quotedblleft (U+201C): X=416.5,Y=701.5 (should be at cap-height 700?)

	* quotedblleft (U+201C): X=206.0,Y=701.5 (should be at cap-height 700?)

	* quotedblright (U+201D): X=318.0,Y=700.5 (should be at cap-height 700?)

	* quotedblright (U+201D): X=528.0,Y=700.5 (should be at cap-height 700?)

	* uni2086 (U+2086): X=130.0,Y=-2.0 (should be at baseline 0?)

	* uni20B8 (U+20B8): X=129.0,Y=699.0 (should be at cap-height 700?)

	* uni20B8 (U+20B8): X=653.0,Y=699.0 (should be at cap-height 700?)

	* lozenge (U+25CA): X=430.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2A (U+FB2A): X=742.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2B (U+FB2B): X=287.0,Y=699.0 (should be at cap-height 700?)

	* uniFB2C (U+FB2C): X=742.5,Y=699.0 (should be at cap-height 700?)

	* uniFB2D (U+FB2D): X=287.0,Y=699.0 (should be at cap-height 700?)

	* uniFB3C (U+FB3C): X=188.0,Y=1.0 (should be at baseline 0?)

	* uniFB47 (U+FB47): X=308.0,Y=1.0 (should be at baseline 0?) 

	* And uniFB4A (U+FB4A): X=22.0,Y=1.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* uni04A1 (U+04A1): L<<217.0,402.0>--<216.0,402.0>> -> L<<216.0,402.0>--<69.0,402.0>>

	* uni05DC (U+05DC): L<<237.0,448.0>--<236.0,448.0>> -> L<<236.0,448.0>--<113.0,448.0>>

	* uni05DC (U+05DC): L<<262.0,448.0>--<237.0,448.0>> -> L<<237.0,448.0>--<236.0,448.0>>

	* uniFB3C (U+FB3C): L<<237.0,448.0>--<236.0,448.0>> -> L<<236.0,448.0>--<113.0,448.0>> 

	* And uniFB3C (U+FB3C): L<<262.0,448.0>--<237.0,448.0>> -> L<<237.0,448.0>--<236.0,448.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0494 (U+0494): B<<242.0,255.0>-<220.0,236.0>-<213.0,199.0>>/L<<213.0,199.0>--<213.0,201.0>> = 10.713123022791033 

	* And uni0494 (U+0494): L<<213.0,199.0>--<213.0,201.0>>/L<<213.0,201.0>--<175.0,25.0>> = 12.183656585987368 [code: found-jaggy-segments]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 0 | 151 | 1521 | 99 | 1212 | 0 |
| 0% | 0% | 5% | 51% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
