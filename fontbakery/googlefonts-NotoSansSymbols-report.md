## Fontbakery report

Fontbakery version: 0.8.11a9

<details><summary><b>[4] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansSymbols/googlefonts/ttf', 'fonts/NotoSansSymbols/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that OS/2.fsSelection bold & italic settings are unique for each NameID1 (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.adobe.fonts/check/family/bold_italic_unique_for_nameid1">com.adobe.fonts/check/family/bold_italic_unique_for_nameid1</a>)</summary><div>


* 🔥 **FAIL** Family 'Noto Sans Symbols' has 2 fonts (should be no more than 1) with the same OS/2.fsSelection bold & italic settings: Bold=False, Italic=False [code: unique-fsselection]
</div></details><br></div></details><details><summary><b>[9] NotoSansSymbols-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* A.001_enccirclebackslashcomb
	* B.001_enccirclebackslashcomb
	* C.001_enccirclebackslashcomb
	* D.001_enccirclebackslashcomb
	* E.001_enccirclebackslashcomb
	* F.001_enccirclebackslashcomb
	* G.001_enccirclebackslashcomb
	* H.001_enccirclebackslashcomb
	* I.001_enccirclebackslashcomb
	* J.001_enccirclebackslashcomb and 80 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Symbols Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u1F19C (U+1F19C): L<<665.0,521.0>--<664.0,534.0>> -> L<<664.0,534.0>--<664.0,596.0>>

	* u1F764 (U+1F764): L<<393.0,0.0>--<396.0,171.0>> -> L<<396.0,171.0>--<401.0,273.0>>

	* u1F764 (U+1F764): L<<527.0,275.0>--<533.0,171.0>> -> L<<533.0,171.0>--<537.0,0.0>>

	* uni262B (U+262B): L<<201.0,24.0>--<215.0,23.0>> -> L<<215.0,23.0>--<228.0,23.0>>

	* uni262B (U+262B): L<<636.0,23.0>--<650.0,23.0>> -> L<<650.0,23.0>--<663.0,24.0>>

	* uni2697 (U+2697): L<<274.0,62.0>--<276.0,74.0>> -> L<<276.0,74.0>--<313.0,237.0>>

	* uni2697 (U+2697): L<<777.0,237.0>--<813.0,74.0>> -> L<<813.0,74.0>--<815.0,62.0>> 

	* uni26FD (U+26FD): L<<553.0,610.0>--<554.0,541.0>> -> L<<554.0,541.0>--<554.0,524.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<340.0,236.0>-<346.0,204.0>-<347.0,184.0>>/B<<347.0,184.0>-<349.0,204.0>-<354.5,235.5>> = 8.57299836361137

	* W (U+0057): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* W (U+0057): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* W (U+0057): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wacute (U+1E82): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wacute (U+1E82): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wacute (U+1E82): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wcircumflex (U+0174): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wcircumflex (U+0174): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432 

	* 55 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* male (U+2642): L<<575.0,556.0>--<576.0,247.0>>

	* uni218B (U+218B): L<<456.0,423.0>--<455.0,276.0>>

	* uni218B (U+218B): L<<557.0,706.0>--<556.0,547.0>>

	* uni2673 (U+2673): L<<666.0,418.0>--<540.0,419.0>>

	* uni2674 (U+2674): L<<666.0,418.0>--<540.0,419.0>>

	* uni2675 (U+2675): L<<666.0,418.0>--<540.0,419.0>>

	* uni2677 (U+2677): L<<666.0,418.0>--<540.0,419.0>>

	* uni2678 (U+2678): L<<666.0,418.0>--<540.0,419.0>>

	* uni2679 (U+2679): L<<666.0,418.0>--<540.0,419.0>>

	* uni267A (U+267A): L<<666.0,418.0>--<540.0,419.0>> 

	* 10 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] NotoSansSymbols-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* A.001_enccirclebackslashcomb
	* B.001_enccirclebackslashcomb
	* C.001_enccirclebackslashcomb
	* D.001_enccirclebackslashcomb
	* E.001_enccirclebackslashcomb
	* F.001_enccirclebackslashcomb
	* G.001_enccirclebackslashcomb
	* H.001_enccirclebackslashcomb
	* I.001_enccirclebackslashcomb
	* J.001_enccirclebackslashcomb and 78 more.

Use -F or --full-lists to disable shortening of long lists.
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
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u1F17C (U+1F17C): L<<640.0,475.0>--<640.0,476.0>> -> L<<640.0,476.0>--<640.0,477.0>>

	* u1F764 (U+1F764): L<<403.0,0.0>--<406.0,171.0>> -> L<<406.0,171.0>--<411.0,282.0>>

	* u1F764 (U+1F764): L<<517.0,283.0>--<524.0,171.0>> -> L<<524.0,171.0>--<527.0,0.0>>

	* uni262B (U+262B): L<<201.0,24.0>--<215.0,23.0>> -> L<<215.0,23.0>--<228.0,23.0>>

	* uni262B (U+262B): L<<636.0,23.0>--<650.0,23.0>> -> L<<650.0,23.0>--<663.0,24.0>>

	* uni2697 (U+2697): L<<281.0,48.0>--<283.0,60.0>> -> L<<283.0,60.0>--<321.0,230.0>>

	* uni2697 (U+2697): L<<774.0,230.0>--<812.0,60.0>> -> L<<812.0,60.0>--<814.0,48.0>> 

	* uni26FD (U+26FD): L<<553.0,610.0>--<554.0,541.0>> -> L<<554.0,541.0>--<554.0,524.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723

	* W (U+0057): B<<506.0,484.5>-<500.0,516.0>-<498.0,534.0>>/B<<498.0,534.0>-<496.0,516.0>-<490.0,484.5>> = 12.680383491819825

	* W (U+0057): B<<693.5,221.0>-<702.0,177.0>-<706.0,144.0>>/B<<706.0,144.0>-<709.0,168.0>-<715.0,202.0>> = 14.03624346792643

	* Wacute (U+1E82): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723

	* Wacute (U+1E82): B<<506.0,484.5>-<500.0,516.0>-<498.0,534.0>>/B<<498.0,534.0>-<496.0,516.0>-<490.0,484.5>> = 12.680383491819825

	* Wacute (U+1E82): B<<693.5,221.0>-<702.0,177.0>-<706.0,144.0>>/B<<706.0,144.0>-<709.0,168.0>-<715.0,202.0>> = 14.03624346792643

	* Wcircumflex (U+0174): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723

	* Wcircumflex (U+0174): B<<506.0,484.5>-<500.0,516.0>-<498.0,534.0>>/B<<498.0,534.0>-<496.0,516.0>-<490.0,484.5>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<693.5,221.0>-<702.0,177.0>-<706.0,144.0>>/B<<706.0,144.0>-<709.0,168.0>-<715.0,202.0>> = 14.03624346792643

	* Wdieresis (U+1E84): B<<280.5,202.0>-<287.0,168.0>-<290.0,144.0>>/B<<290.0,144.0>-<294.0,179.0>-<302.5,223.0>> = 13.644818100558723 

	* 58 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* male (U+2642): L<<571.0,547.0>--<572.0,293.0>>

	* uni218B (U+218B): L<<453.0,410.0>--<452.0,287.0>>

	* uni218B (U+218B): L<<559.0,707.0>--<558.0,575.0>>

	* uni2676 (U+2676): L<<664.0,427.0>--<545.0,428.0>>

	* uni267C (U+267C): L<<456.0,108.0>--<455.0,231.0>>

	* uni267D (U+267D): L<<455.0,231.0>--<456.0,106.0>>

	* uni2693 (U+2693): L<<50.0,100.0>--<49.0,325.0>>

	* uni2693 (U+2693): L<<709.0,325.0>--<708.0,100.0>>

	* uni2696 (U+2696): L<<198.0,137.0>--<196.0,396.0>>

	* uni2696 (U+2696): L<<250.0,396.0>--<249.0,137.0>> 

	* 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[9] NotoSansSymbols-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* A.001_enccirclebackslashcomb
	* B.001_enccirclebackslashcomb
	* C.001_enccirclebackslashcomb
	* D.001_enccirclebackslashcomb
	* E.001_enccirclebackslashcomb
	* F.001_enccirclebackslashcomb
	* G.001_enccirclebackslashcomb
	* H.001_enccirclebackslashcomb
	* I.001_enccirclebackslashcomb
	* J.001_enccirclebackslashcomb and 78 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Symbols ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u1F18E (U+1F18E): L<<751.0,368.0>--<751.0,368.0>> -> L<<751.0,368.0>--<751.0,368.0>>

	* u1F19C (U+1F19C): L<<679.0,530.0>--<678.0,543.0>> -> L<<678.0,543.0>--<678.0,610.0>>

	* u1F764 (U+1F764): L<<398.0,0.0>--<401.0,171.0>> -> L<<401.0,171.0>--<406.0,278.0>>

	* u1F764 (U+1F764): L<<522.0,279.0>--<528.0,171.0>> -> L<<528.0,171.0>--<532.0,0.0>>

	* uni262B (U+262B): L<<201.0,24.0>--<215.0,23.0>> -> L<<215.0,23.0>--<228.0,23.0>>

	* uni262B (U+262B): L<<636.0,23.0>--<650.0,23.0>> -> L<<650.0,23.0>--<663.0,24.0>>

	* uni2697 (U+2697): L<<278.0,54.0>--<280.0,67.0>> -> L<<280.0,67.0>--<317.0,233.0>>

	* uni2697 (U+2697): L<<776.0,233.0>--<813.0,67.0>> -> L<<813.0,67.0>--<815.0,54.0>> 

	* uni26FD (U+26FD): L<<553.0,610.0>--<554.0,541.0>> -> L<<554.0,541.0>--<554.0,524.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<329.0,217.5>-<335.0,187.0>-<337.0,166.0>>/B<<337.0,166.0>-<340.0,187.0>-<345.5,217.0>> = 13.570434385161475

	* W (U+0057): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475

	* W (U+0057): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* Wacute (U+1E82): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475

	* Wacute (U+1E82): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* Wcircumflex (U+0174): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475

	* Wcircumflex (U+0174): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* Wdieresis (U+1E84): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475

	* Wdieresis (U+1E84): B<<705.0,216.0>-<711.0,181.0>-<714.0,155.0>>/B<<714.0,155.0>-<717.0,179.0>-<723.5,214.5>> = 13.70696100407981

	* Wgrave (U+1E80): B<<517.0,457.0>-<511.0,491.0>-<508.0,512.0>>/B<<508.0,512.0>-<506.0,491.0>-<500.0,457.0>> = 13.570434385161475 

	* 55 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* male (U+2642): L<<573.0,551.0>--<574.0,272.0>>

	* uni218B (U+218B): L<<455.0,416.0>--<454.0,282.0>>

	* uni218B (U+218B): L<<558.0,706.0>--<557.0,562.0>>

	* uni2676 (U+2676): L<<665.0,423.0>--<543.0,424.0>>

	* uni2696 (U+2696): L<<196.0,138.0>--<194.0,393.0>>

	* uni2696 (U+2696): L<<252.0,393.0>--<251.0,138.0>>

	* uni2696 (U+2696): L<<649.0,138.0>--<648.0,393.0>>

	* uni2696 (U+2696): L<<706.0,393.0>--<704.0,138.0>>

	* uni26A3 (U+26A3): L<<758.0,551.0>--<759.0,272.0>>

	* uni26A4 (U+26A4): L<<672.0,774.0>--<673.0,492.0>>

	* uni26A5 (U+26A5): L<<573.0,774.0>--<574.0,492.0>> 

	* uni26FD (U+26FD): L<<804.0,444.0>--<805.0,234.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[9] NotoSansSymbols-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* u1F548
	* u1F54F
	* uni2388
	* uni2638
	* uni267B
	* uni2696 and uni26F7
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Symbols ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u1F19C (U+1F19C): L<<748.0,552.0>--<746.0,579.0>> -> L<<746.0,579.0>--<746.0,662.0>>

	* u1F764 (U+1F764): L<<441.0,0.0>--<443.0,170.0>> -> L<<443.0,170.0>--<447.0,308.0>>

	* u1F764 (U+1F764): L<<484.0,308.0>--<487.0,170.0>> -> L<<487.0,170.0>--<489.0,0.0>>

	* uni262B (U+262B): L<<201.0,24.0>--<215.0,23.0>> -> L<<215.0,23.0>--<228.0,23.0>>

	* uni262B (U+262B): L<<636.0,23.0>--<650.0,23.0>> -> L<<650.0,23.0>--<663.0,24.0>>

	* uni2697 (U+2697): L<<303.0,14.0>--<304.0,21.0>> -> L<<304.0,21.0>--<358.0,250.0>>

	* uni2697 (U+2697): L<<746.0,250.0>--<800.0,21.0>> -> L<<800.0,21.0>--<801.0,14.0>> 

	* uni26FD (U+26FD): L<<553.0,610.0>--<554.0,541.0>> -> L<<554.0,541.0>--<554.0,524.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* u1F126 (U+1F126): B<<505.5,495.0>-<502.0,513.0>-<500.0,531.0>>/B<<500.0,531.0>-<498.0,516.0>-<494.0,497.0>> = 13.934835114501363

	* u1F12E (U+1F12E): B<<285.5,257.0>-<289.0,242.0>-<291.0,227.0>>/B<<291.0,227.0>-<292.0,240.0>-<296.0,256.5>> = 11.993348723586953

	* u1F146 (U+1F146): B<<379.5,228.5>-<383.0,211.0>-<384.0,193.0>>/B<<384.0,193.0>-<390.0,232.0>-<403.0,280.0>> = 11.925992382419398

	* u1F146 (U+1F146): B<<515.0,457.0>-<504.0,498.0>-<500.0,531.0>>/B<<500.0,531.0>-<496.0,497.0>-<484.0,456.0>> = 13.62106392678159

	* u1F14A (U+1F14A): B<<656.0,223.5>-<661.0,205.0>-<662.0,195.0>>/B<<662.0,195.0>-<664.0,209.0>-<672.0,238.0>> = 13.840695491655614

	* u1F14B (U+1F14B): B<<501.0,493.0>-<501.0,516.0>-<503.0,536.0>>/L<<503.0,536.0>--<390.0,156.0>> = 10.850222326187128

	* u1F14B (U+1F14B): B<<684.5,222.5>-<688.0,202.0>-<689.0,191.0>>/B<<689.0,191.0>-<691.0,205.0>-<695.5,229.5>> = 13.324531261890755

	* u1F14B (U+1F14B): L<<361.0,156.0>--<248.0,537.0>>/B<<248.0,537.0>-<249.0,514.0>-<250.0,491.5>> = 14.030167885582099

	* u1F14E (U+1F14E): B<<703.5,225.0>-<707.0,202.0>-<709.0,191.0>>/B<<709.0,191.0>-<710.0,206.0>-<714.5,230.0>> = 14.118921303056382

	* u1F14F (U+1F14F): B<<277.5,237.0>-<279.0,222.0>-<281.0,202.0>>/B<<281.0,202.0>-<283.0,221.0>-<286.5,241.0>> = 11.719599094994122 

	* 19 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* male (U+2642): L<<557.0,522.0>--<556.0,381.0>>

	* uni26A4 (U+26A4): L<<659.0,764.0>--<658.0,622.0>>

	* uni26A5 (U+26A5): L<<557.0,764.0>--<556.0,623.0>>

	* uni26A7 (U+26A7): L<<655.0,764.0>--<654.0,623.0>> 

	* uni26FD (U+26FD): L<<804.0,444.0>--<805.0,234.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[9] NotoSansSymbols-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* u1F548
	* u1F54F
	* uni2317
	* uni2388
	* uni2626
	* uni2638
	* uni267B
	* uni2695
	* uni2696
	* uni26F7 and uni2721
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Symbols Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u1F19C (U+1F19C): L<<743.0,556.0>--<741.0,579.0>> -> L<<741.0,579.0>--<741.0,662.0>>

	* u1F764 (U+1F764): L<<433.0,0.0>--<435.0,170.0>> -> L<<435.0,170.0>--<440.0,303.0>>

	* u1F764 (U+1F764): L<<491.0,303.0>--<496.0,170.0>> -> L<<496.0,170.0>--<498.0,0.0>>

	* uni262B (U+262B): L<<201.0,24.0>--<215.0,23.0>> -> L<<215.0,23.0>--<228.0,23.0>>

	* uni262B (U+262B): L<<636.0,23.0>--<650.0,23.0>> -> L<<650.0,23.0>--<663.0,24.0>>

	* uni2697 (U+2697): L<<755.0,239.0>--<804.0,28.0>> -> L<<804.0,28.0>--<806.0,18.0>> 

	* uni26FD (U+26FD): L<<553.0,610.0>--<554.0,541.0>> -> L<<554.0,541.0>--<554.0,524.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* u1F11C (U+1F11C): L<<481.0,146.0>--<330.0,528.0>>/B<<330.0,528.0>-<337.0,483.0>-<337.0,429.0>> = 12.72647595231493

	* u1F126 (U+1F126): B<<377.5,252.0>-<381.0,233.0>-<384.0,208.0>>/B<<384.0,208.0>-<387.0,236.0>-<395.0,265.0>> = 12.95827697891631

	* u1F12E (U+1F12E): B<<287.5,273.0>-<291.0,257.0>-<292.0,243.0>>/B<<292.0,243.0>-<293.0,253.0>-<296.0,265.5>> = 9.796209917474465

	* u1F146 (U+1F146): B<<374.0,267.0>-<380.0,244.0>-<384.0,208.0>>/B<<384.0,208.0>-<385.0,224.0>-<389.5,246.0>> = 9.916526120907228

	* u1F14B (U+1F14B): B<<368.0,261.0>-<373.0,239.0>-<376.0,217.0>>/B<<376.0,217.0>-<378.0,237.0>-<383.0,256.0>> = 13.475759155924964

	* u1F14B (U+1F14B): B<<491.5,479.5>-<492.0,503.0>-<494.0,524.0>>/L<<494.0,524.0>--<392.0,156.0>> = 10.051653497002489

	* u1F14B (U+1F14B): B<<685.5,230.5>-<688.0,213.0>-<690.0,202.0>>/B<<690.0,202.0>-<691.0,221.0>-<695.5,245.5>> = 13.317633972949379

	* u1F14B (U+1F14B): L<<359.0,156.0>--<255.0,526.0>>/B<<255.0,526.0>-<257.0,503.0>-<258.5,479.0>> = 10.729927818024212

	* u1F14E (U+1F14E): B<<702.5,236.5>-<705.0,213.0>-<707.0,202.0>>/B<<707.0,202.0>-<708.0,222.0>-<712.0,246.5>> = 13.167251694877788

	* u1F14F (U+1F14F): B<<280.5,247.5>-<282.0,234.0>-<283.0,218.0>>/B<<283.0,218.0>-<285.0,236.0>-<288.5,256.0>> = 9.916526120907228 

	* 22 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* u1F15C (U+1F15C): L<<337.0,146.0>--<336.0,429.0>>

	* u1F17C (U+1F17C): L<<337.0,146.0>--<336.0,429.0>>

	* uni26A3 (U+26A3): L<<752.0,527.0>--<751.0,375.0>>

	* uni26A4 (U+26A4): L<<663.0,769.0>--<662.0,617.0>>

	* uni26A7 (U+26A7): L<<659.0,769.0>--<658.0,617.0>> 

	* uni26FD (U+26FD): L<<804.0,444.0>--<805.0,234.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[9] NotoSansSymbols-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* W.001_encupwardpointingtricomb
	* u1F548
	* u1F54F
	* uni2317
	* uni2331
	* uni2388
	* uni2626
	* uni2638
	* uni267B
	* uni2693 and 10 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Symbols Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u1F764 (U+1F764): L<<414.0,0.0>--<417.0,170.0>> -> L<<417.0,170.0>--<422.0,291.0>>

	* u1F764 (U+1F764): L<<507.0,291.0>--<513.0,170.0>> -> L<<513.0,170.0>--<517.0,0.0>>

	* uni262B (U+262B): L<<201.0,24.0>--<215.0,23.0>> -> L<<215.0,23.0>--<228.0,23.0>>

	* uni262B (U+262B): L<<636.0,23.0>--<650.0,23.0>> -> L<<650.0,23.0>--<663.0,24.0>>

	* uni2697 (U+2697): L<<288.0,32.0>--<290.0,45.0>> -> L<<290.0,45.0>--<330.0,222.0>>

	* uni2697 (U+2697): L<<771.0,222.0>--<811.0,45.0>> -> L<<811.0,45.0>--<813.0,32.0>> 

	* uni26FD (U+26FD): L<<553.0,610.0>--<554.0,541.0>> -> L<<554.0,541.0>--<554.0,524.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wacute (U+1E82): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wcircumflex (U+0174): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wdieresis (U+1E84): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* Wgrave (U+1E80): B<<479.0,550.0>-<473.0,575.0>-<472.0,587.0>>/B<<472.0,587.0>-<471.0,575.0>-<465.5,550.0>> = 9.527283381452328

	* u1F11C (U+1F11C): B<<497.0,255.0>-<499.0,246.0>-<500.0,237.0>>/B<<500.0,237.0>-<501.0,246.0>-<503.0,255.0>> = 12.680383491819825

	* u1F11C (U+1F11C): B<<651.5,457.0>-<653.0,487.0>-<655.0,504.0>>/L<<655.0,504.0>--<531.0,144.0>> = 12.296147388279808

	* u1F11C (U+1F11C): L<<465.0,144.0>--<336.0,502.0>>/B<<336.0,502.0>-<347.0,453.0>-<347.0,389.0>> = 7.1633198869503705

	* u1F125 (U+1F125): B<<492.0,267.0>-<499.0,242.0>-<501.0,228.0>>/B<<501.0,228.0>-<502.0,240.0>-<510.0,265.0>> = 12.893744044882132

	* u1F126 (U+1F126): B<<376.0,288.5>-<380.0,266.0>-<383.0,238.0>>/B<<383.0,238.0>-<384.0,248.0>-<386.5,261.5>> = 11.826096703785012 

	* 41 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* male (U+2642): L<<567.0,538.0>--<568.0,344.0>>

	* uni2696 (U+2696): L<<202.0,134.0>--<201.0,401.0>>

	* uni2696 (U+2696): L<<245.0,403.0>--<244.0,134.0>>

	* uni2696 (U+2696): L<<656.0,134.0>--<655.0,403.0>>

	* uni2696 (U+2696): L<<699.0,401.0>--<698.0,134.0>>

	* uni26A3 (U+26A3): L<<568.0,699.0>--<569.0,516.0>>

	* uni26A3 (U+26A3): L<<758.0,538.0>--<759.0,344.0>>

	* uni26A4 (U+26A4): L<<669.0,776.0>--<670.0,581.0>>

	* uni26A5 (U+26A5): L<<567.0,776.0>--<568.0,581.0>>

	* uni26A7 (U+26A7): L<<669.0,779.0>--<670.0,588.0>> 

	* uni26FD (U+26FD): L<<804.0,444.0>--<805.0,234.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] NotoSansSymbols-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* u1F548
	* u1F54F
	* uni2317
	* uni2331
	* uni2388
	* uni2626
	* uni2638
	* uni267B
	* uni2693
	* uni2695 and 9 more.

Use -F or --full-lists to disable shortening of long lists.
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
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u1F764 (U+1F764): L<<418.0,0.0>--<421.0,170.0>> -> L<<421.0,170.0>--<427.0,295.0>>

	* u1F764 (U+1F764): L<<502.0,295.0>--<509.0,170.0>> -> L<<509.0,170.0>--<512.0,0.0>>

	* uni262B (U+262B): L<<201.0,24.0>--<215.0,23.0>> -> L<<215.0,23.0>--<228.0,23.0>>

	* uni262B (U+262B): L<<636.0,23.0>--<650.0,23.0>> -> L<<650.0,23.0>--<663.0,24.0>>

	* uni2697 (U+2697): L<<291.0,25.0>--<293.0,39.0>> -> L<<293.0,39.0>--<334.0,219.0>>

	* uni2697 (U+2697): L<<770.0,219.0>--<811.0,39.0>> -> L<<811.0,39.0>--<813.0,25.0>> 

	* uni26FD (U+26FD): L<<553.0,610.0>--<554.0,541.0>> -> L<<554.0,541.0>--<554.0,524.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* u1F11C (U+1F11C): B<<651.0,401.0>-<651.0,479.0>-<656.0,512.0>>/L<<656.0,512.0>--<525.0,146.0>> = 11.07783378727433

	* u1F11C (U+1F11C): L<<470.0,146.0>--<334.0,510.0>>/B<<334.0,510.0>-<345.0,463.0>-<345.0,402.0>> = 7.314460770003778

	* u1F126 (U+1F126): B<<370.0,314.0>-<374.0,295.0>-<382.0,234.0>>/B<<382.0,234.0>-<382.0,246.0>-<385.0,259.0>> = 7.471559176592385

	* u1F126 (U+1F126): B<<505.5,456.5>-<502.0,475.0>-<499.0,499.0>>/B<<499.0,499.0>-<498.0,490.0>-<494.0,467.5>> = 13.465208094811695

	* u1F12E (U+1F12E): B<<290.0,300.5>-<293.0,283.0>-<294.0,270.0>>/B<<294.0,270.0>-<294.0,275.0>-<296.0,280.5>> = 4.398705354995508

	* u1F13C (U+1F13C): L<<470.0,146.0>--<340.0,494.0>>/B<<340.0,494.0>-<345.0,453.0>-<345.0,402.0>> = 13.530881388232878

	* u1F146 (U+1F146): B<<378.5,263.0>-<380.0,251.0>-<382.0,234.0>>/B<<382.0,234.0>-<382.0,247.0>-<386.5,266.5>> = 6.709836807756896

	* u1F146 (U+1F146): B<<618.0,262.0>-<622.0,247.0>-<622.0,231.0>>/B<<622.0,231.0>-<624.0,252.0>-<628.0,273.0>> = 5.4403320310054815

	* u1F14B (U+1F14B): B<<476.0,456.0>-<477.0,481.0>-<479.0,501.0>>/L<<479.0,501.0>--<395.0,156.0>> = 7.973426614747843

	* u1F14B (U+1F14B): B<<688.0,244.0>-<689.0,232.0>-<690.0,220.0>>/B<<690.0,220.0>-<692.0,248.0>-<695.5,272.0>> = 8.849258470700986 

	* 27 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* male (U+2642): L<<565.0,534.0>--<566.0,365.0>>

	* uni2696 (U+2696): L<<204.0,133.0>--<203.0,404.0>>

	* uni2696 (U+2696): L<<243.0,405.0>--<242.0,133.0>>

	* uni2696 (U+2696): L<<658.0,133.0>--<657.0,405.0>>

	* uni2696 (U+2696): L<<697.0,404.0>--<696.0,133.0>>

	* uni26A3 (U+26A3): L<<565.0,698.0>--<566.0,529.0>>

	* uni26A3 (U+26A3): L<<758.0,534.0>--<759.0,365.0>>

	* uni26A4 (U+26A4): L<<668.0,776.0>--<669.0,607.0>>

	* uni26A5 (U+26A5): L<<565.0,776.0>--<566.0,607.0>>

	* uni26A6 (U+26A6): L<<565.0,534.0>--<566.0,365.0>> 

	* 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[9] NotoSansSymbols-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* A.001_enccirclebackslashcomb
	* B.001_enccirclebackslashcomb
	* C.001_enccirclebackslashcomb
	* D.001_enccirclebackslashcomb
	* E.001_enccirclebackslashcomb
	* F.001_enccirclebackslashcomb
	* G.001_enccirclebackslashcomb
	* H.001_enccirclebackslashcomb
	* I.001_enccirclebackslashcomb
	* J.001_enccirclebackslashcomb and 76 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Symbols SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u1F764 (U+1F764): L<<409.0,0.0>--<412.0,170.0>> -> L<<412.0,170.0>--<417.0,287.0>>

	* u1F764 (U+1F764): L<<512.0,287.0>--<518.0,170.0>> -> L<<518.0,170.0>--<522.0,0.0>>

	* uni262B (U+262B): L<<201.0,24.0>--<215.0,23.0>> -> L<<215.0,23.0>--<228.0,23.0>>

	* uni262B (U+262B): L<<636.0,23.0>--<650.0,23.0>> -> L<<650.0,23.0>--<663.0,24.0>>

	* uni2697 (U+2697): L<<285.0,39.0>--<287.0,52.0>> -> L<<287.0,52.0>--<326.0,226.0>>

	* uni2697 (U+2697): L<<773.0,226.0>--<812.0,52.0>> -> L<<812.0,52.0>--<814.0,39.0>> 

	* uni26FD (U+26FD): L<<553.0,610.0>--<554.0,541.0>> -> L<<554.0,541.0>--<554.0,524.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wacute (U+1E82): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wcircumflex (U+0174): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wdieresis (U+1E84): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* Wgrave (U+1E80): B<<684.5,198.0>-<692.0,160.0>-<695.0,130.0>>/B<<695.0,130.0>-<700.0,167.0>-<710.5,217.5>> = 13.406644859516216

	* u1F11C (U+1F11C): L<<459.0,141.0>--<338.0,494.0>>/B<<338.0,494.0>-<343.0,472.0>-<346.0,439.5>> = 6.116228587643326

	* u1F11C (U+1F11C): L<<654.0,495.0>--<657.0,503.0>>/L<<657.0,503.0>--<538.0,141.0>> = 2.3588368559543875

	* u1F125 (U+1F125): B<<492.0,277.0>-<499.0,251.0>-<501.0,236.0>>/B<<501.0,236.0>-<502.0,250.0>-<509.5,276.0>> = 11.68026014856632

	* u1F126 (U+1F126): B<<377.5,293.5>-<382.0,268.0>-<385.0,242.0>>/B<<385.0,242.0>-<386.0,257.0>-<390.5,279.0>> = 10.396019489468372

	* u1F126 (U+1F126): B<<507.0,425.0>-<502.0,449.0>-<500.0,472.0>>/B<<500.0,472.0>-<499.0,459.0>-<494.0,432.0>> = 9.368446083105818 

	* 47 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* male (U+2642): L<<569.0,542.0>--<570.0,320.0>>

	* uni218B (U+218B): L<<560.0,707.0>--<559.0,592.0>>

	* uni2696 (U+2696): L<<200.0,135.0>--<199.0,399.0>>

	* uni2696 (U+2696): L<<247.0,400.0>--<246.0,135.0>>

	* uni2696 (U+2696): L<<654.0,135.0>--<653.0,400.0>>

	* uni2696 (U+2696): L<<701.0,399.0>--<700.0,135.0>>

	* uni26A3 (U+26A3): L<<572.0,700.0>--<573.0,521.0>>

	* uni26A3 (U+26A3): L<<758.0,542.0>--<759.0,320.0>>

	* uni26A4 (U+26A4): L<<670.0,775.0>--<671.0,552.0>>

	* uni26A5 (U+26A5): L<<569.0,775.0>--<570.0,552.0>>

	* uni26A7 (U+26A7): L<<674.0,781.0>--<675.0,566.0>> 

	* uni26FD (U+26FD): L<<804.0,444.0>--<805.0,234.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[9] NotoSansSymbols-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* u1F54F
	* uni2638
	* uni267B and uni2696
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Symbols Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
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
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* u1F19C (U+1F19C): L<<751.0,549.0>--<750.0,579.0>> -> L<<750.0,579.0>--<750.0,662.0>>

	* u1F764 (U+1F764): L<<447.0,0.0>--<449.0,170.0>> -> L<<449.0,170.0>--<452.0,311.0>>

	* u1F764 (U+1F764): L<<479.0,311.0>--<482.0,170.0>> -> L<<482.0,170.0>--<483.0,0.0>>

	* uni262B (U+262B): L<<201.0,24.0>--<215.0,23.0>> -> L<<215.0,23.0>--<228.0,23.0>>

	* uni262B (U+262B): L<<636.0,23.0>--<650.0,23.0>> -> L<<650.0,23.0>--<663.0,24.0>>

	* uni2697 (U+2697): L<<306.0,11.0>--<307.0,17.0>> -> L<<307.0,17.0>--<364.0,258.0>>

	* uni2697 (U+2697): L<<740.0,258.0>--<797.0,17.0>> -> L<<797.0,17.0>--<798.0,11.0>> 

	* uni26FD (U+26FD): L<<553.0,610.0>--<554.0,541.0>> -> L<<554.0,541.0>--<554.0,524.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* u1F126 (U+1F126): B<<380.0,220.0>-<384.0,202.0>-<385.0,182.0>>/B<<385.0,182.0>-<388.0,202.0>-<393.0,225.5>> = 11.393170836059864

	* u1F126 (U+1F126): B<<505.5,505.5>-<502.0,523.0>-<500.0,539.0>>/B<<500.0,539.0>-<498.0,523.0>-<494.0,505.0>> = 14.25003269780357

	* u1F12E (U+1F12E): B<<285.0,246.5>-<289.0,232.0>-<290.0,216.0>>/B<<290.0,216.0>-<292.0,232.0>-<296.5,251.0>> = 10.701350723899111

	* u1F12E (U+1F12E): B<<399.0,443.0>-<389.0,477.0>-<386.0,502.0>>/B<<386.0,502.0>-<383.0,477.0>-<374.0,443.0>> = 13.685546825261865

	* u1F12E (U+1F12E): B<<479.0,250.5>-<484.0,230.0>-<485.0,216.0>>/B<<485.0,216.0>-<488.0,234.0>-<491.5,250.5>> = 13.547938988000464

	* u1F146 (U+1F146): B<<380.0,220.0>-<384.0,202.0>-<385.0,182.0>>/B<<385.0,182.0>-<388.0,202.0>-<393.0,225.5>> = 11.393170836059864

	* u1F146 (U+1F146): B<<505.5,505.5>-<502.0,523.0>-<500.0,539.0>>/B<<500.0,539.0>-<498.0,523.0>-<494.0,505.0>> = 14.25003269780357

	* u1F14A (U+1F14A): B<<655.5,219.5>-<661.0,199.0>-<662.0,188.0>>/B<<662.0,188.0>-<664.0,201.0>-<673.0,231.0>> = 13.94059117029001

	* u1F14B (U+1F14B): B<<507.0,500.5>-<507.0,522.0>-<509.0,544.0>>/L<<509.0,544.0>--<389.0,156.0>> = 11.991277236489928

	* u1F14F (U+1F14F): B<<276.0,230.5>-<278.0,214.0>-<280.0,191.0>>/B<<280.0,191.0>-<282.0,211.0>-<285.5,231.5>> = 10.68033386560994 

	* 22 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam (U+0021): L<<100.0,174.0>--<98.0,714.0>>

	* exclam (U+0021): L<<127.0,714.0>--<125.0,174.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>>

	* exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>>

	* u1F764 (U+1F764): L<<482.0,170.0>--<483.0,0.0>>

	* uni2696 (U+2696): L<<210.0,133.0>--<211.0,443.0>>

	* uni2696 (U+2696): L<<235.0,443.0>--<236.0,133.0>>

	* uni2696 (U+2696): L<<664.0,133.0>--<665.0,443.0>>

	* uni2696 (U+2696): L<<689.0,443.0>--<690.0,133.0>> 

	* uni26FD (U+26FD): L<<804.0,444.0>--<805.0,234.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[8] NotoSansSymbols[wght].ttf</b></summary><div><details><summary>💔 <b>ERROR:</b> Check font names are correct (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_names">com.google.fonts/check/font_names</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check a font's STAT table contains compulsory Axis Values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/STAT">com.google.fonts/check/STAT</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>💔 <b>ERROR:</b> Check variable font instances (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/fvar_instances">com.google.fonts/check/fvar_instances</a>)</summary><div>


* 💔 **ERROR** The condition <FontBakeryCondition:expected_font_names> had an error: KeyError: 'fvar'
</div></details><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- _blackCircledComp

	- _boxComp

	- _circledComp

	- _doubleCircled

	- _parenComp 

	- _roundBlackBoxComp
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Detect any interpolation issues in the font. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/interpolation_issues">com.google.fonts/check/interpolation_issues</a>)</summary><div>


* ⚠ **WARN** Interpolation issues were found in the font: 	- Contour 3 start point differs in glyph 'uni26A2' between location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7fa4307c9ed0> and location <fontTools.ttLib.ttGlyphSet._TTGlyphSetGlyf object at 0x7fa42fdf3210> [code: interpolation-issues]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0307 (U+0307), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B) and 12 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 3 | 14 | 74 | 1123 | 62 | 919 | 0 |
| 0% | 1% | 3% | 51% | 3% | 42% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
