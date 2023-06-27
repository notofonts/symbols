## Fontbakery report

Fontbakery version: 0.8.13

<details><summary><b>[9] NotoSansSymbols2-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* 🔥 **FAIL** The dot of soft dotted characters used in orthographies must disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters should disappear in other cases, for example: i⃢̀ i⃢́ i⃢̂ i⃢̃ i⃢̄ i⃢̆ i⃢̇ i⃢̈ i⃢̊ i⃢̋ i⃢̌ i⃢̒ i⃣̀ i⃣́ i⃣̂ i⃣̃ i⃣̄ i⃣̆ i⃣̇ i⃣̈ [code: soft-dotted]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure files are not too large. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/file_size">com.google.fonts/check/file_size</a>)</summary><div>


* ⚠ **WARN** Font file is 1.2Mb; ideally it should be less than 1.0Mb [code: large-font]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni2611	Contours detected: 3	Expected: 2

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni2611	Contours detected: 3	Expected: 2 

	- Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni20E2 (U+20E2) and uni20E3 (U+20E3) [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* u101D1 (U+101D1): L<<158.0,655.0>--<202.0,553.0>>/L<<202.0,553.0>--<167.0,658.0>> = 4.8990924537876985

	* u101D1 (U+101D1): L<<196.0,669.0>--<231.0,563.0>>/L<<231.0,563.0>--<221.0,676.0>> = 13.21538973442621

	* u101D1 (U+101D1): L<<290.0,688.0>--<289.0,558.0>>/L<<289.0,558.0>--<300.0,680.0>> = 4.71135362944517

	* u101D1 (U+101D1): L<<408.0,660.0>--<382.0,547.0>>/L<<382.0,547.0>--<424.0,635.0>> = 12.55629033344111

	* u101D1 (U+101D1): L<<451.0,623.0>--<410.0,538.0>>/L<<410.0,538.0>--<466.0,619.0>> = 8.907880578202827

	* u101D1 (U+101D1): L<<490.0,602.0>--<441.0,532.0>>/L<<441.0,532.0>--<501.0,590.0>> = 10.979001732520492

	* u101D3 (U+101D3): B<<230.0,133.5>-<227.0,152.0>-<225.0,180.0>>/B<<225.0,180.0>-<225.0,153.0>-<211.0,120.0>> = 4.085616779974798

	* u101D4 (U+101D4): B<<127.0,331.0>-<127.0,364.0>-<133.0,388.0>>/B<<133.0,388.0>-<125.0,373.0>-<120.0,326.0>> = 14.036243467926484

	* u101D5 (U+101D5): B<<262.0,599.0>-<295.0,599.0>-<341.0,560.0>>/B<<341.0,560.0>-<317.0,588.0>-<287.0,604.5>> = 9.106557599367749

	* u101D9 (U+101D9): B<<140.0,253.0>-<140.0,110.0>-<146.0,-22.0>>/B<<146.0,-22.0>-<154.0,23.0>-<158.5,91.5>> = 12.683160190042093 

	* 220 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* u101D1 (U+101D1): L<<290.0,688.0>--<289.0,558.0>>

	* u101DD (U+101DD): L<<50.0,22.0>--<54.0,655.0>>

	* u101DD (U+101DD): L<<80.0,285.0>--<78.0,29.0>>

	* u101DD (U+101DD): L<<83.0,657.0>--<81.0,394.0>>

	* u102F5 (U+102F5): L<<373.0,188.0>--<764.0,190.0>>

	* u102F5 (U+102F5): L<<765.0,100.0>--<201.0,97.0>>

	* u1F5B4 (U+1F5B4): L<<287.0,499.0>--<419.0,498.0>>

	* u1F5DC (U+1F5DC): L<<303.0,859.0>--<753.0,856.0>>

	* u1F6E8 (U+1F6E8): L<<460.0,328.0>--<87.0,325.0>>

	* u1F6E8 (U+1F6E8): L<<943.0,325.0>--<569.0,328.0>> 

	* 26 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 2 | 7 | 118 | 7 | 112 | 0 |
| 0% | 1% | 3% | 48% | 3% | 46% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
