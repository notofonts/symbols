## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[1] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Does font file include unacceptable control character glyphs? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/family/control_chars">com.google.fonts/check/family/control_chars</a>)</summary><div>


* 🔥 **FAIL** The following unacceptable control characters were identified:
 fonts/NotoSansSymbols2/googlefonts/ttf/NotoSansSymbols2-Regular.ttf: uni0001, uni0002, uni0003, uni0004, uni0005, uni0006, uni0007, uni0008, uni0009, uni000A, uni000B, uni000C, uni000E, uni000F, uni0010, uni0011, uni0012, uni0013, uni0014, uni0015, uni0016, uni0017, uni0018, uni0019, uni001A, uni001B, uni001C, uni001D, uni001E, uni001F
 [code: unacceptable]
</div></details><br></div></details><details><summary><b>[13] NotoSansSymbols2-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2017 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Version number has increased since previous release on Google Fonts? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/version_bump">com.google.fonts/check/version_bump</a>)</summary><div>


* 🔥 **FAIL** Version number 2.0030059814453125 is equal to version on Google Fonts.
* 🔥 **FAIL** Version number 2.0030059814453125 is equal to version on Google Fonts GitHub repo.
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FONT_FAMILY_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/familyname">com.google.fonts/check/name/familyname</a>)</summary><div>


* 🔥 **FAIL** Entry [FONT_FAMILY_NAME(1):WINDOWS(3)] on the "name" table: Expected "Noto Sans Symbols 2" but got "Noto Sans Symbols2". [code: mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Check name table: FULL_FONT_NAME entries. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/fullfontname">com.google.fonts/check/name/fullfontname</a>)</summary><div>


* 🔥 **FAIL** [FULL_FONT_NAME(4):WINDOWS(3)]
Expected: "Noto Sans Symbols 2 Regular"
But got:  "Noto Sans Symbols2 Regular" [code: bad-entry]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansSymbols2/googlefonts/ttf/NotoSansSymbols2-Regular.ttf']. [code: missing-os2-fsselection-bit7]
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

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 commaaccent2 (unencoded), sp_gobliquestrphaistosDisc (unencoded), space_20E3 (unencoded), space_u102E0 (unencoded) and uni20E3 (U+20E3) [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 uni20E2 (U+20E2) [code: mark-chars]
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

	* And 212 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<100.0,174.0>--<98.0,714.0>>

	* exclam (U+0021): L<<127.0,714.0>--<125.0,174.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>>

	* exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>>

	* u101D1 (U+101D1): L<<290.0,688.0>--<289.0,558.0>>

	* u101DD (U+101DD): L<<50.0,22.0>--<54.0,655.0>>

	* u101DD (U+101DD): L<<80.0,285.0>--<78.0,29.0>>

	* u101DD (U+101DD): L<<83.0,657.0>--<81.0,394.0>>

	* u102F5 (U+102F5): L<<373.0,188.0>--<764.0,190.0>>

	* u102F5 (U+102F5): L<<765.0,100.0>--<201.0,97.0>> 

	* And 28 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 8 | 6 | 116 | 8 | 97 | 0 |
| 0% | 3% | 3% | 49% | 3% | 41% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
