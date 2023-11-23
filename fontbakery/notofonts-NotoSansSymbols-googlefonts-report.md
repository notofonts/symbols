## FontBakery report

fontbakery version: 0.10.4

<details><summary><b>[1] Experimental checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Shapes languages in all GF glyphsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyphsets/shape_languages">com.google.fonts/check/glyphsets/shape_languages</a>)</summary><div>


* 🔥 **FAIL** GF_Latin_Core glyphset:

| Language | FAIL messages |
| :--- | :--- |
| br_Latn (Breton) | Some base glyphs were missing: CʼH, cʼh |
|  ^  | Shaper produced a .notdef |
| nl_Latn (Dutch) | Shaper didn't attach acutecomb to J |
| haw_Latn (Hawaiian) | Some base glyphs were missing: ʻ |
|  ^  | Shaper produced a .notdef |
| mh_Latn (Marshallese) | Some base glyphs were missing: Ḷ, ḷ, Ṃ, ṃ, Ṇ, ṇ, Ọ, ọ |
|  ^  | Some mark glyphs were missing: ◌̣ |
|  ^  | Shaper produced a .notdef |
| qu_Latn (Quechua) | Some base glyphs were missing: CHʼ, Kʼ, Pʼ, Qʼ, Tʼ, chʼ, kʼ, pʼ, qʼ, tʼ |
|  ^  | Shaper produced a .notdef |
| scn_Latn (Sicilian) | Some base glyphs were missing: Ḍ, ḍ |
|  ^  | Shaper produced a .notdef |
| teo_Latn (Teso) | Some base glyphs were missing: Ɔ, Ɛ, Ɨ, Ʉ, ɔ, ɛ, ɨ, ʉ, ᵃ, ᵉ, ᵋ, ᵒ, ᵓ, ᵘ, ᶤ, ᶶ, ⁱ |
|  ^  | Shaper produced a .notdef |

 [code: failed-language-shaping]
* ⚠ **WARN** GF_Latin_Core glyphset:

| Language | FAIL messages |
| :--- | :--- |
| lg_Latn (Ganda) | No variant glyphs were found for Eng |
| dyo_Latn (Jola-Fonyi) | No variant glyphs were found for Eng |
| ny_Latn (Nyanja) | No variant glyphs were found for Eng |
| wo_Latn (Wolof) | No variant glyphs were found for Eng |

 [code: warning-language-shaping]
</div></details><br></div></details><details><summary><b>[7] NotoSansSymbols[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Noto fonts must have an ARTICLE.en_us.html file (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/description/noto_has_article">com.google.fonts/check/description/noto_has_article</a>)</summary><div>


* 🔥 **FAIL** This is a Noto font but it lacks an ARTICLE.en_us.html file [code: missing-article]
</div></details><details><summary>🔥 <b>FAIL:</b> Check that legacy accents aren't used in composite glyphs. (derived from com.google.fonts/check/legacy_accents) (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/legacy_accents">com.google.fonts/check/legacy_accents</a>)</summary><div>


* 🔥 **FAIL** Glyph "Aacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Acircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Adieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Agrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Aring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Cacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ccaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ccedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Cdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Dcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Eacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ecaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ecircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Edieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Edotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Egrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Eogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Gdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Iacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Icircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Idieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Idotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Igrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Iogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Lacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Nacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ncaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Oacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ocircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Odieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ograve" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Racute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Rcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Sacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Scaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Scedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Tcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ucircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Udieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ugrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Uring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wcircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wdieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Wgrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Yacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ycircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ydieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Ygrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "Zdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "abreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "acircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "acutecomb" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "adieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "agrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "aring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "atilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0306" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "cacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030C" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ccaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ccedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "cdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0327" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0302" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0308" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0307" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "eacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ecaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ecircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "edieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "edotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "egrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gbreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "gravecomb" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030B" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "iacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "icircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "idieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "igrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "iogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "lacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "nacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ncaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ntilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "oacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ocircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "odieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni0328" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ograve" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ohungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "otilde" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "racute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "rcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uni030A" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "sacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "scaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "scedilla" has a legacy accent component (cedilla). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "tildecomb" has a legacy accent component (tilde). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ubreve" has a legacy accent component (breve). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ucircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "udieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ugrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uhungarumlaut" has a legacy accent component (hungarumlaut). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uogonek" has a legacy accent component (ogonek). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "uring" has a legacy accent component (ring). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wcircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wdieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "wgrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "yacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ycircumflex" has a legacy accent component (circumflex). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ydieresis" has a legacy accent component (dieresis). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "ygrave" has a legacy accent component (grave). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zacute" has a legacy accent component (acute). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zcaron" has a legacy accent component (caron). It needs to be replaced by a combining mark. [code: legacy-accents-component]
* 🔥 **FAIL** Glyph "zdotaccent" has a legacy accent component (dotaccent). It needs to be replaced by a combining mark. [code: legacy-accents-component]
</div></details><details><summary>⚠ <b>WARN:</b> Check for codepoints not covered by METADATA subsets. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/metadata/unreachable_subsetting">com.google.fonts/check/metadata/unreachable_subsetting</a>)</summary><div>


* ⚠ **WARN** The following codepoints supported by the font are not covered by
    any subsets defined in the font's metadata file, and will never
    be served. You can solve this by either manually adding additional
    subset declarations to METADATA.pb, or by editing the glyphset
    definitions.

 * U+02C7 CARON: try adding one of: tifinagh, canadian-aboriginal, yi
 * U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition
 * U+02D8 BREVE: try adding one of: canadian-aboriginal, yi
 * U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi
 * U+02DB OGONEK: try adding one of: canadian-aboriginal, yi
 * U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition
 * U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: tifinagh, coptic, cherokee, math
 * U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh
 * U+0307 COMBINING DOT ABOVE: try adding one of: canadian-aboriginal, malayalam, old-permic, tifinagh, syriac, math, tai-le, coptic
 * U+030A COMBINING RING ABOVE: try adding syriac
 * U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: osage, cherokee
 * U+030C COMBINING CARON: try adding one of: tai-le, cherokee
 * U+0312 COMBINING TURNED COMMA ABOVE: not included in any glyphset definition
 * U+0326 COMBINING COMMA BELOW: not included in any glyphset definition
 * U+0327 COMBINING CEDILLA: not included in any glyphset definition
 * U+0328 COMBINING OGONEK: not included in any glyphset definition
 * U+20DD COMBINING ENCLOSING CIRCLE: try adding symbols
 * U+20DE COMBINING ENCLOSING SQUARE: try adding symbols
 * U+20DF COMBINING ENCLOSING DIAMOND: try adding symbols
 * U+20E0 COMBINING ENCLOSING CIRCLE BACKSLASH: try adding symbols
 * U+20E2 COMBINING ENCLOSING SCREEN: try adding symbols
 * U+20E3 COMBINING ENCLOSING KEYCAP: try adding symbols
 * U+20E4 COMBINING ENCLOSING UPWARD POINTING TRIANGLE: try adding symbols
 * U+2160 ROMAN NUMERAL ONE: try adding symbols
 * U+2161 ROMAN NUMERAL TWO: try adding symbols
 * U+2162 ROMAN NUMERAL THREE: try adding symbols
 * U+2163 ROMAN NUMERAL FOUR: try adding symbols
 * U+2164 ROMAN NUMERAL FIVE: try adding symbols
 * U+2165 ROMAN NUMERAL SIX: try adding symbols
 * U+2166 ROMAN NUMERAL SEVEN: try adding symbols
 * U+2167 ROMAN NUMERAL EIGHT: try adding symbols
 * U+2168 ROMAN NUMERAL NINE: try adding symbols
 * U+2169 ROMAN NUMERAL TEN: try adding symbols
 * U+216A ROMAN NUMERAL ELEVEN: try adding symbols
 * U+216B ROMAN NUMERAL TWELVE: try adding symbols
 * U+216C ROMAN NUMERAL FIFTY: try adding symbols
 * U+216D ROMAN NUMERAL ONE HUNDRED: try adding symbols
 * U+216E ROMAN NUMERAL FIVE HUNDRED: try adding symbols
 * U+216F ROMAN NUMERAL ONE THOUSAND: try adding symbols
 * U+2170 SMALL ROMAN NUMERAL ONE: try adding symbols
 * U+2171 SMALL ROMAN NUMERAL TWO: try adding symbols
 * U+2172 SMALL ROMAN NUMERAL THREE: try adding symbols
 * U+2173 SMALL ROMAN NUMERAL FOUR: try adding symbols
 * U+2174 SMALL ROMAN NUMERAL FIVE: try adding symbols
 * U+2175 SMALL ROMAN NUMERAL SIX: try adding symbols
 * U+2176 SMALL ROMAN NUMERAL SEVEN: try adding symbols
 * U+2177 SMALL ROMAN NUMERAL EIGHT: try adding symbols
 * U+2178 SMALL ROMAN NUMERAL NINE: try adding symbols
 * U+2179 SMALL ROMAN NUMERAL TEN: try adding symbols
 * U+217A SMALL ROMAN NUMERAL ELEVEN: try adding symbols
 * U+217B SMALL ROMAN NUMERAL TWELVE: try adding symbols
 * U+217C SMALL ROMAN NUMERAL FIFTY: try adding symbols
 * U+217D SMALL ROMAN NUMERAL ONE HUNDRED: try adding symbols
 * U+217E SMALL ROMAN NUMERAL FIVE HUNDRED: try adding symbols
 * U+217F SMALL ROMAN NUMERAL ONE THOUSAND: try adding symbols
 * U+2180 ROMAN NUMERAL ONE THOUSAND C D: try adding symbols
 * U+2181 ROMAN NUMERAL FIVE THOUSAND: try adding symbols
 * U+2182 ROMAN NUMERAL TEN THOUSAND: try adding symbols
 * U+2183 ROMAN NUMERAL REVERSED ONE HUNDRED: try adding symbols
 * U+2185 ROMAN NUMERAL SIX LATE FORM: try adding symbols
 * U+2186 ROMAN NUMERAL FIFTY EARLY FORM: try adding symbols
 * U+2187 ROMAN NUMERAL FIFTY THOUSAND: try adding symbols
 * U+2188 ROMAN NUMERAL ONE HUNDRED THOUSAND: try adding symbols
 * U+218A TURNED DIGIT TWO: try adding symbols
 * U+218B TURNED DIGIT THREE: try adding symbols
 * U+2190 LEFTWARDS ARROW: try adding one of: symbols, math
 * U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math
 * U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math
 * U+2195 UP DOWN ARROW: try adding one of: symbols, math
 * U+2196 NORTH WEST ARROW: try adding one of: symbols, math
 * U+2197 NORTH EAST ARROW: try adding one of: symbols, math
 * U+2198 SOUTH EAST ARROW: try adding one of: symbols, math
 * U+2199 SOUTH WEST ARROW: try adding one of: symbols, math
 * U+2300 DIAMETER SIGN: try adding symbols
 * U+2301 ELECTRIC ARROW: try adding symbols
 * U+2302 HOUSE: try adding symbols
 * U+2303 UP ARROWHEAD: try adding symbols
 * U+2304 DOWN ARROWHEAD: try adding symbols
 * U+2305 PROJECTIVE: try adding symbols
 * U+2306 PERSPECTIVE: try adding symbols
 * U+2307 WAVY LINE: try adding symbols
 * U+2308 LEFT CEILING: try adding one of: symbols, math
 * U+2309 RIGHT CEILING: try adding one of: symbols, math
 * U+230A LEFT FLOOR: try adding one of: symbols, math
 * U+230B RIGHT FLOOR: try adding one of: symbols, math
 * U+230C BOTTOM RIGHT CROP: try adding symbols
 * U+230D BOTTOM LEFT CROP: try adding symbols
 * U+230E TOP RIGHT CROP: try adding symbols
 * U+230F TOP LEFT CROP: try adding symbols
 * U+2311 SQUARE LOZENGE: try adding symbols
 * U+2312 ARC: try adding symbols
 * U+2313 SEGMENT: try adding symbols
 * U+2314 SECTOR: try adding symbols
 * U+2315 TELEPHONE RECORDER: try adding symbols
 * U+2317 VIEWDATA SQUARE: try adding symbols
 * U+231C TOP LEFT CORNER: try adding one of: symbols, math
 * U+231D TOP RIGHT CORNER: try adding one of: symbols, math
 * U+231E BOTTOM LEFT CORNER: try adding one of: symbols, math
 * U+231F BOTTOM RIGHT CORNER: try adding one of: symbols, math
 * U+2322 FROWN: try adding symbols
 * U+2323 SMILE: try adding symbols
 * U+2329 LEFT-POINTING ANGLE BRACKET: try adding symbols
 * U+232A RIGHT-POINTING ANGLE BRACKET: try adding symbols
 * U+232C BENZENE RING: try adding symbols
 * U+232D CYLINDRICITY: try adding symbols
 * U+232E ALL AROUND-PROFILE: try adding symbols
 * U+232F SYMMETRY: try adding symbols
 * U+2330 TOTAL RUNOUT: try adding symbols
 * U+2331 DIMENSION ORIGIN: try adding symbols
 * U+2332 CONICAL TAPER: try adding symbols
 * U+2333 SLOPE: try adding symbols
 * U+2334 COUNTERBORE: try adding symbols
 * U+2335 COUNTERSINK: try adding symbols
 * U+237C RIGHT ANGLE WITH DOWNWARDS ZIGZAG ARROW: try adding one of: symbols, math
 * U+2380 INSERTION SYMBOL: try adding symbols
 * U+2381 CONTINUOUS UNDERLINE SYMBOL: try adding symbols
 * U+2382 DISCONTINUOUS UNDERLINE SYMBOL: try adding symbols
 * U+2383 EMPHASIS SYMBOL: try adding symbols
 * U+2384 COMPOSITION SYMBOL: try adding symbols
 * U+2385 WHITE SQUARE WITH CENTRE VERTICAL LINE: try adding symbols
 * U+2386 ENTER SYMBOL: try adding symbols
 * U+2387 ALTERNATIVE KEY SYMBOL: try adding symbols
 * U+2388 HELM SYMBOL: try adding symbols
 * U+2389 CIRCLED HORIZONTAL BAR WITH NOTCH: try adding symbols
 * U+238A CIRCLED TRIANGLE DOWN: try adding symbols
 * U+238B BROKEN CIRCLE WITH NORTHWEST ARROW: try adding symbols
 * U+238C UNDO SYMBOL: try adding symbols
 * U+238D MONOSTABLE SYMBOL: try adding symbols
 * U+238E HYSTERESIS SYMBOL: try adding symbols
 * U+238F OPEN-CIRCUIT-OUTPUT H-TYPE SYMBOL: try adding symbols
 * U+2390 OPEN-CIRCUIT-OUTPUT L-TYPE SYMBOL: try adding symbols
 * U+2391 PASSIVE-PULL-DOWN-OUTPUT SYMBOL: try adding symbols
 * U+2392 PASSIVE-PULL-UP-OUTPUT SYMBOL: try adding symbols
 * U+2393 DIRECT CURRENT SYMBOL FORM TWO: try adding symbols
 * U+2394 SOFTWARE-FUNCTION SYMBOL: try adding symbols
 * U+2396 DECIMAL SEPARATOR KEY SYMBOL: try adding symbols
 * U+2397 PREVIOUS PAGE: try adding symbols
 * U+2398 NEXT PAGE: try adding symbols
 * U+2399 PRINT SCREEN SYMBOL: try adding symbols
 * U+239A CLEAR SCREEN SYMBOL: try adding symbols
 * U+23AF HORIZONTAL LINE EXTENSION: try adding one of: symbols, math
 * U+23BE DENTISTRY SYMBOL LIGHT VERTICAL AND TOP RIGHT: try adding symbols
 * U+23BF DENTISTRY SYMBOL LIGHT VERTICAL AND BOTTOM RIGHT: try adding symbols
 * U+23C0 DENTISTRY SYMBOL LIGHT VERTICAL WITH CIRCLE: try adding symbols
 * U+23C1 DENTISTRY SYMBOL LIGHT DOWN AND HORIZONTAL WITH CIRCLE: try adding symbols
 * U+23C2 DENTISTRY SYMBOL LIGHT UP AND HORIZONTAL WITH CIRCLE: try adding symbols
 * U+23C3 DENTISTRY SYMBOL LIGHT VERTICAL WITH TRIANGLE: try adding symbols
 * U+23C4 DENTISTRY SYMBOL LIGHT DOWN AND HORIZONTAL WITH TRIANGLE: try adding symbols
 * U+23C5 DENTISTRY SYMBOL LIGHT UP AND HORIZONTAL WITH TRIANGLE: try adding symbols
 * U+23C6 DENTISTRY SYMBOL LIGHT VERTICAL AND WAVE: try adding symbols
 * U+23C7 DENTISTRY SYMBOL LIGHT DOWN AND HORIZONTAL WITH WAVE: try adding symbols
 * U+23C8 DENTISTRY SYMBOL LIGHT UP AND HORIZONTAL WITH WAVE: try adding symbols
 * U+23C9 DENTISTRY SYMBOL LIGHT DOWN AND HORIZONTAL: try adding symbols
 * U+23CA DENTISTRY SYMBOL LIGHT UP AND HORIZONTAL: try adding symbols
 * U+23CB DENTISTRY SYMBOL LIGHT VERTICAL AND TOP LEFT: try adding symbols
 * U+23CC DENTISTRY SYMBOL LIGHT VERTICAL AND BOTTOM LEFT: try adding symbols
 * U+23CD SQUARE FOOT: try adding symbols
 * U+23D0 VERTICAL LINE EXTENSION: try adding one of: symbols, math
 * U+23D1 METRICAL BREVE: try adding symbols
 * U+23D2 METRICAL LONG OVER SHORT: try adding symbols
 * U+23D3 METRICAL SHORT OVER LONG: try adding symbols
 * U+23D4 METRICAL LONG OVER TWO SHORTS: try adding symbols
 * U+23D5 METRICAL TWO SHORTS OVER LONG: try adding symbols
 * U+23D6 METRICAL TWO SHORTS JOINED: try adding symbols
 * U+23D7 METRICAL TRISEME: try adding symbols
 * U+23D8 METRICAL TETRASEME: try adding symbols
 * U+23D9 METRICAL PENTASEME: try adding symbols
 * U+23DA EARTH GROUND: try adding symbols
 * U+23DB FUSE: try adding symbols
 * U+23E2 WHITE TRAPEZIUM: try adding symbols
 * U+23E3 BENZENE RING WITH CIRCLE: try adding symbols
 * U+23E4 STRAIGHTNESS: try adding symbols
 * U+23E5 FLATNESS: try adding symbols
 * U+23E6 AC CURRENT: try adding symbols
 * U+23E7 ELECTRICAL INTERSECTION: try adding symbols
 * U+23E8 DECIMAL EXPONENT SYMBOL: try adding symbols
 * U+2460 CIRCLED DIGIT ONE: try adding one of: symbols, mongolian, yi
 * U+2461 CIRCLED DIGIT TWO: try adding one of: symbols, mongolian, yi
 * U+2462 CIRCLED DIGIT THREE: try adding one of: symbols, mongolian, yi
 * U+2463 CIRCLED DIGIT FOUR: try adding one of: symbols, mongolian, yi
 * U+2464 CIRCLED DIGIT FIVE: try adding one of: symbols, mongolian, yi
 * U+2465 CIRCLED DIGIT SIX: try adding one of: symbols, mongolian, yi
 * U+2466 CIRCLED DIGIT SEVEN: try adding one of: symbols, mongolian, yi
 * U+2467 CIRCLED DIGIT EIGHT: try adding one of: symbols, mongolian, yi
 * U+2468 CIRCLED DIGIT NINE: try adding one of: symbols, mongolian, yi
 * U+2469 CIRCLED NUMBER TEN: try adding one of: symbols, mongolian, yi
 * U+246A CIRCLED NUMBER ELEVEN: try adding one of: symbols, mongolian, yi
 * U+246B CIRCLED NUMBER TWELVE: try adding one of: symbols, mongolian, yi
 * U+246C CIRCLED NUMBER THIRTEEN: try adding one of: symbols, mongolian, yi
 * U+246D CIRCLED NUMBER FOURTEEN: try adding one of: symbols, mongolian, yi
 * U+246E CIRCLED NUMBER FIFTEEN: try adding one of: symbols, mongolian, yi
 * U+246F CIRCLED NUMBER SIXTEEN: try adding one of: symbols, mongolian, yi
 * U+2470 CIRCLED NUMBER SEVENTEEN: try adding one of: symbols, mongolian, yi
 * U+2471 CIRCLED NUMBER EIGHTEEN: try adding one of: symbols, mongolian, yi
 * U+2472 CIRCLED NUMBER NINETEEN: try adding one of: symbols, mongolian, yi
 * U+2473 CIRCLED NUMBER TWENTY: try adding one of: symbols, mongolian, yi
 * U+2474 PARENTHESIZED DIGIT ONE: try adding one of: symbols, math
 * U+2475 PARENTHESIZED DIGIT TWO: try adding one of: symbols, math
 * U+2476 PARENTHESIZED DIGIT THREE: try adding symbols
 * U+2477 PARENTHESIZED DIGIT FOUR: try adding symbols
 * U+2478 PARENTHESIZED DIGIT FIVE: try adding symbols
 * U+2479 PARENTHESIZED DIGIT SIX: try adding symbols
 * U+247A PARENTHESIZED DIGIT SEVEN: try adding symbols
 * U+247B PARENTHESIZED DIGIT EIGHT: try adding symbols
 * U+247C PARENTHESIZED DIGIT NINE: try adding symbols
 * U+247D PARENTHESIZED NUMBER TEN: try adding symbols
 * U+247E PARENTHESIZED NUMBER ELEVEN: try adding symbols
 * U+247F PARENTHESIZED NUMBER TWELVE: try adding symbols
 * U+2480 PARENTHESIZED NUMBER THIRTEEN: try adding symbols
 * U+2481 PARENTHESIZED NUMBER FOURTEEN: try adding symbols
 * U+2482 PARENTHESIZED NUMBER FIFTEEN: try adding symbols
 * U+2483 PARENTHESIZED NUMBER SIXTEEN: try adding symbols
 * U+2484 PARENTHESIZED NUMBER SEVENTEEN: try adding symbols
 * U+2485 PARENTHESIZED NUMBER EIGHTEEN: try adding symbols
 * U+2486 PARENTHESIZED NUMBER NINETEEN: try adding symbols
 * U+2487 PARENTHESIZED NUMBER TWENTY: try adding symbols
 * U+2488 DIGIT ONE FULL STOP: try adding symbols
 * U+2489 DIGIT TWO FULL STOP: try adding symbols
 * U+248A DIGIT THREE FULL STOP: try adding symbols
 * U+248B DIGIT FOUR FULL STOP: try adding symbols
 * U+248C DIGIT FIVE FULL STOP: try adding symbols
 * U+248D DIGIT SIX FULL STOP: try adding symbols
 * U+248E DIGIT SEVEN FULL STOP: try adding symbols
 * U+248F DIGIT EIGHT FULL STOP: try adding symbols
 * U+2490 DIGIT NINE FULL STOP: try adding symbols
 * U+2491 NUMBER TEN FULL STOP: try adding symbols
 * U+2492 NUMBER ELEVEN FULL STOP: try adding symbols
 * U+2493 NUMBER TWELVE FULL STOP: try adding symbols
 * U+2494 NUMBER THIRTEEN FULL STOP: try adding symbols
 * U+2495 NUMBER FOURTEEN FULL STOP: try adding symbols
 * U+2496 NUMBER FIFTEEN FULL STOP: try adding symbols
 * U+2497 NUMBER SIXTEEN FULL STOP: try adding symbols
 * U+2498 NUMBER SEVENTEEN FULL STOP: try adding symbols
 * U+2499 NUMBER EIGHTEEN FULL STOP: try adding symbols
 * U+249A NUMBER NINETEEN FULL STOP: try adding symbols
 * U+249B NUMBER TWENTY FULL STOP: try adding symbols
 * U+249C PARENTHESIZED LATIN SMALL LETTER A: try adding symbols
 * U+249D PARENTHESIZED LATIN SMALL LETTER B: try adding symbols
 * U+249E PARENTHESIZED LATIN SMALL LETTER C: try adding symbols
 * U+249F PARENTHESIZED LATIN SMALL LETTER D: try adding symbols
 * U+24A0 PARENTHESIZED LATIN SMALL LETTER E: try adding symbols
 * U+24A1 PARENTHESIZED LATIN SMALL LETTER F: try adding symbols
 * U+24A2 PARENTHESIZED LATIN SMALL LETTER G: try adding symbols
 * U+24A3 PARENTHESIZED LATIN SMALL LETTER H: try adding symbols
 * U+24A4 PARENTHESIZED LATIN SMALL LETTER I: try adding symbols
 * U+24A5 PARENTHESIZED LATIN SMALL LETTER J: try adding symbols
 * U+24A6 PARENTHESIZED LATIN SMALL LETTER K: try adding symbols
 * U+24A7 PARENTHESIZED LATIN SMALL LETTER L: try adding symbols
 * U+24A8 PARENTHESIZED LATIN SMALL LETTER M: try adding symbols
 * U+24A9 PARENTHESIZED LATIN SMALL LETTER N: try adding symbols
 * U+24AA PARENTHESIZED LATIN SMALL LETTER O: try adding symbols
 * U+24AB PARENTHESIZED LATIN SMALL LETTER P: try adding symbols
 * U+24AC PARENTHESIZED LATIN SMALL LETTER Q: try adding symbols
 * U+24AD PARENTHESIZED LATIN SMALL LETTER R: try adding symbols
 * U+24AE PARENTHESIZED LATIN SMALL LETTER S: try adding symbols
 * U+24AF PARENTHESIZED LATIN SMALL LETTER T: try adding symbols
 * U+24B0 PARENTHESIZED LATIN SMALL LETTER U: try adding symbols
 * U+24B1 PARENTHESIZED LATIN SMALL LETTER V: try adding symbols
 * U+24B2 PARENTHESIZED LATIN SMALL LETTER W: try adding symbols
 * U+24B3 PARENTHESIZED LATIN SMALL LETTER X: try adding symbols
 * U+24B4 PARENTHESIZED LATIN SMALL LETTER Y: try adding symbols
 * U+24B5 PARENTHESIZED LATIN SMALL LETTER Z: try adding symbols
 * U+24B6 CIRCLED LATIN CAPITAL LETTER A: try adding symbols
 * U+24B7 CIRCLED LATIN CAPITAL LETTER B: try adding symbols
 * U+24B8 CIRCLED LATIN CAPITAL LETTER C: try adding symbols
 * U+24B9 CIRCLED LATIN CAPITAL LETTER D: try adding symbols
 * U+24BA CIRCLED LATIN CAPITAL LETTER E: try adding symbols
 * U+24BB CIRCLED LATIN CAPITAL LETTER F: try adding symbols
 * U+24BC CIRCLED LATIN CAPITAL LETTER G: try adding symbols
 * U+24BD CIRCLED LATIN CAPITAL LETTER H: try adding symbols
 * U+24BE CIRCLED LATIN CAPITAL LETTER I: try adding symbols
 * U+24BF CIRCLED LATIN CAPITAL LETTER J: try adding symbols
 * U+24C0 CIRCLED LATIN CAPITAL LETTER K: try adding symbols
 * U+24C1 CIRCLED LATIN CAPITAL LETTER L: try adding symbols
 * U+24C2 CIRCLED LATIN CAPITAL LETTER M: try adding symbols
 * U+24C3 CIRCLED LATIN CAPITAL LETTER N: try adding symbols
 * U+24C4 CIRCLED LATIN CAPITAL LETTER O: try adding symbols
 * U+24C5 CIRCLED LATIN CAPITAL LETTER P: try adding symbols
 * U+24C6 CIRCLED LATIN CAPITAL LETTER Q: try adding symbols
 * U+24C7 CIRCLED LATIN CAPITAL LETTER R: try adding symbols
 * U+24C8 CIRCLED LATIN CAPITAL LETTER S: try adding symbols
 * U+24C9 CIRCLED LATIN CAPITAL LETTER T: try adding symbols
 * U+24CA CIRCLED LATIN CAPITAL LETTER U: try adding symbols
 * U+24CB CIRCLED LATIN CAPITAL LETTER V: try adding symbols
 * U+24CC CIRCLED LATIN CAPITAL LETTER W: try adding symbols
 * U+24CD CIRCLED LATIN CAPITAL LETTER X: try adding symbols
 * U+24CE CIRCLED LATIN CAPITAL LETTER Y: try adding symbols
 * U+24CF CIRCLED LATIN CAPITAL LETTER Z: try adding symbols
 * U+24D0 CIRCLED LATIN SMALL LETTER A: try adding symbols
 * U+24D1 CIRCLED LATIN SMALL LETTER B: try adding symbols
 * U+24D2 CIRCLED LATIN SMALL LETTER C: try adding symbols
 * U+24D3 CIRCLED LATIN SMALL LETTER D: try adding symbols
 * U+24D4 CIRCLED LATIN SMALL LETTER E: try adding symbols
 * U+24D5 CIRCLED LATIN SMALL LETTER F: try adding symbols
 * U+24D6 CIRCLED LATIN SMALL LETTER G: try adding symbols
 * U+24D7 CIRCLED LATIN SMALL LETTER H: try adding symbols
 * U+24D8 CIRCLED LATIN SMALL LETTER I: try adding symbols
 * U+24D9 CIRCLED LATIN SMALL LETTER J: try adding symbols
 * U+24DA CIRCLED LATIN SMALL LETTER K: try adding symbols
 * U+24DB CIRCLED LATIN SMALL LETTER L: try adding symbols
 * U+24DC CIRCLED LATIN SMALL LETTER M: try adding symbols
 * U+24DD CIRCLED LATIN SMALL LETTER N: try adding symbols
 * U+24DE CIRCLED LATIN SMALL LETTER O: try adding symbols
 * U+24DF CIRCLED LATIN SMALL LETTER P: try adding symbols
 * U+24E0 CIRCLED LATIN SMALL LETTER Q: try adding symbols
 * U+24E1 CIRCLED LATIN SMALL LETTER R: try adding symbols
 * U+24E2 CIRCLED LATIN SMALL LETTER S: try adding symbols
 * U+24E3 CIRCLED LATIN SMALL LETTER T: try adding symbols
 * U+24E4 CIRCLED LATIN SMALL LETTER U: try adding symbols
 * U+24E5 CIRCLED LATIN SMALL LETTER V: try adding symbols
 * U+24E6 CIRCLED LATIN SMALL LETTER W: try adding symbols
 * U+24E7 CIRCLED LATIN SMALL LETTER X: try adding symbols
 * U+24E8 CIRCLED LATIN SMALL LETTER Y: try adding symbols
 * U+24E9 CIRCLED LATIN SMALL LETTER Z: try adding symbols
 * U+24EA CIRCLED DIGIT ZERO: try adding symbols
 * U+24EB NEGATIVE CIRCLED NUMBER ELEVEN: try adding symbols
 * U+24EC NEGATIVE CIRCLED NUMBER TWELVE: try adding symbols
 * U+24ED NEGATIVE CIRCLED NUMBER THIRTEEN: try adding symbols
 * U+24EE NEGATIVE CIRCLED NUMBER FOURTEEN: try adding symbols
 * U+24EF NEGATIVE CIRCLED NUMBER FIFTEEN: try adding symbols
 * U+24F0 NEGATIVE CIRCLED NUMBER SIXTEEN: try adding symbols
 * U+24F1 NEGATIVE CIRCLED NUMBER SEVENTEEN: try adding symbols
 * U+24F2 NEGATIVE CIRCLED NUMBER EIGHTEEN: try adding symbols
 * U+24F3 NEGATIVE CIRCLED NUMBER NINETEEN: try adding symbols
 * U+24F4 NEGATIVE CIRCLED NUMBER TWENTY: try adding symbols
 * U+24F5 DOUBLE CIRCLED DIGIT ONE: try adding symbols
 * U+24F6 DOUBLE CIRCLED DIGIT TWO: try adding symbols
 * U+24F7 DOUBLE CIRCLED DIGIT THREE: try adding symbols
 * U+24F8 DOUBLE CIRCLED DIGIT FOUR: try adding symbols
 * U+24F9 DOUBLE CIRCLED DIGIT FIVE: try adding symbols
 * U+24FA DOUBLE CIRCLED DIGIT SIX: try adding symbols
 * U+24FB DOUBLE CIRCLED DIGIT SEVEN: try adding symbols
 * U+24FC DOUBLE CIRCLED DIGIT EIGHT: try adding symbols
 * U+24FD DOUBLE CIRCLED DIGIT NINE: try adding symbols
 * U+24FE DOUBLE CIRCLED NUMBER TEN: try adding symbols
 * U+24FF NEGATIVE CIRCLED DIGIT ZERO: try adding symbols
 * U+25CC DOTTED CIRCLE: try adding one of: dogra, gujarati, buginese, math, khudawadi, sinhala, takri, miao, zanabazar-square, thaana, tirhuta, malayalam, chakma, oriya, sharada, bassa-vah, tagalog, tagbanwa, khojki, rejang, new-tai-lue, kharoshthi, osage, bhaiksuki, syriac, meetei-mayek, kaithi, devanagari, telugu, tibetan, ahom, duployan, modi, siddham, mende-kikakui, syloti-nagri, sogdian, buhid, kayah-li, adlam, gunjala-gondi, music, hanunoo, batak, manichaean, mahajani, tai-viet, coptic, wancho, lepcha, hebrew, soyombo, yi, pahawh-hmong, limbu, kannada, balinese, bengali, tamil, phags-pa, masaram-gondi, mandaic, myanmar, symbols, tifinagh, gurmukhi, mongolian, khmer, grantha, tai-le, cham, caucasian-albanian, brahmi, thai, marchen, sundanese, hanifi-rohingya, old-permic, lao, elbasan, javanese, psalter-pahlavi, nko, newa
 * U+260A ASCENDING NODE: try adding symbols
 * U+260B DESCENDING NODE: try adding symbols
 * U+260C CONJUNCTION: try adding symbols
 * U+260D OPPOSITION: try adding symbols
 * U+2613 SALTIRE: try adding symbols
 * U+2624 CADUCEUS: try adding symbols
 * U+2625 ANKH: try adding symbols
 * U+2626 ORTHODOX CROSS: try adding symbols
 * U+2627 CHI RHO: try adding symbols
 * U+2628 CROSS OF LORRAINE: try adding symbols
 * U+2629 CROSS OF JERUSALEM: try adding symbols
 * U+262A STAR AND CRESCENT: try adding symbols
 * U+262B FARSI SYMBOL: try adding symbols
 * U+262C ADI SHAKTI: try adding one of: symbols, gurmukhi
 * U+262D HAMMER AND SICKLE: try adding symbols
 * U+262E PEACE SYMBOL: try adding symbols
 * U+262F YIN YANG: try adding symbols
 * U+2638 WHEEL OF DHARMA: try adding symbols
 * U+2639 WHITE FROWNING FACE: try adding symbols
 * U+263A WHITE SMILING FACE: try adding symbols
 * U+263B BLACK SMILING FACE: try adding symbols
 * U+263D FIRST QUARTER MOON: try adding symbols
 * U+263E LAST QUARTER MOON: try adding symbols
 * U+263F MERCURY: try adding symbols
 * U+2640 FEMALE SIGN: try adding symbols
 * U+2641 EARTH: try adding symbols
 * U+2642 MALE SIGN: try adding symbols
 * U+2643 JUPITER: try adding symbols
 * U+2644 SATURN: try adding symbols
 * U+2645 URANUS: try adding symbols
 * U+2646 NEPTUNE: try adding symbols
 * U+2647 PLUTO: try adding symbols
 * U+2648 ARIES: try adding symbols
 * U+2649 TAURUS: try adding symbols
 * U+264A GEMINI: try adding symbols
 * U+264B CANCER: try adding symbols
 * U+264C LEO: try adding symbols
 * U+264D VIRGO: try adding symbols
 * U+264E LIBRA: try adding symbols
 * U+264F SCORPIUS: try adding symbols
 * U+2650 SAGITTARIUS: try adding symbols
 * U+2651 CAPRICORN: try adding symbols
 * U+2652 AQUARIUS: try adding symbols
 * U+2653 PISCES: try adding symbols
 * U+2669 QUARTER NOTE: try adding one of: symbols, music
 * U+266A EIGHTH NOTE: try adding one of: symbols, music
 * U+266B BEAMED EIGHTH NOTES: try adding one of: symbols, music
 * U+266C BEAMED SIXTEENTH NOTES: try adding one of: symbols, music
 * U+266D MUSIC FLAT SIGN: try adding one of: symbols, music, math
 * U+266E MUSIC NATURAL SIGN: try adding one of: symbols, music, math
 * U+266F MUSIC SHARP SIGN: try adding one of: symbols, music, math
 * U+2670 WEST SYRIAC CROSS: try adding one of: symbols, syriac
 * U+2671 EAST SYRIAC CROSS: try adding one of: symbols, syriac
 * U+2672 UNIVERSAL RECYCLING SYMBOL: try adding symbols
 * U+2673 RECYCLING SYMBOL FOR TYPE-1 PLASTICS: try adding symbols
 * U+2674 RECYCLING SYMBOL FOR TYPE-2 PLASTICS: try adding symbols
 * U+2675 RECYCLING SYMBOL FOR TYPE-3 PLASTICS: try adding symbols
 * U+2676 RECYCLING SYMBOL FOR TYPE-4 PLASTICS: try adding symbols
 * U+2677 RECYCLING SYMBOL FOR TYPE-5 PLASTICS: try adding symbols
 * U+2678 RECYCLING SYMBOL FOR TYPE-6 PLASTICS: try adding symbols
 * U+2679 RECYCLING SYMBOL FOR TYPE-7 PLASTICS: try adding symbols
 * U+267A RECYCLING SYMBOL FOR GENERIC MATERIALS: try adding symbols
 * U+267B BLACK UNIVERSAL RECYCLING SYMBOL: try adding symbols
 * U+267C RECYCLED PAPER SYMBOL: try adding symbols
 * U+267D PARTIALLY-RECYCLED PAPER SYMBOL: try adding symbols
 * U+267E PERMANENT PAPER SIGN: try adding symbols
 * U+2690 WHITE FLAG: try adding symbols
 * U+2691 BLACK FLAG: try adding symbols
 * U+2692 HAMMER AND PICK: try adding symbols
 * U+2693 ANCHOR: try adding symbols
 * U+2694 CROSSED SWORDS: try adding symbols
 * U+2695 STAFF OF AESCULAPIUS: try adding symbols
 * U+2696 SCALES: try adding symbols
 * U+2697 ALEMBIC: try adding symbols
 * U+2698 FLOWER: try adding symbols
 * U+2699 GEAR: try adding symbols
 * U+269A STAFF OF HERMES: try adding symbols
 * U+269B ATOM SYMBOL: try adding symbols
 * U+269C FLEUR-DE-LIS: try adding symbols
 * U+269D OUTLINED WHITE STAR: try adding symbols
 * U+26A2 DOUBLED FEMALE SIGN: try adding symbols
 * U+26A3 DOUBLED MALE SIGN: try adding symbols
 * U+26A4 INTERLOCKED FEMALE AND MALE SIGN: try adding symbols
 * U+26A5 MALE AND FEMALE SIGN: try adding symbols
 * U+26A6 MALE WITH STROKE SIGN: try adding symbols
 * U+26A7 MALE WITH STROKE AND MALE AND FEMALE SIGN: try adding symbols
 * U+26A8 VERTICAL MALE WITH STROKE SIGN: try adding symbols
 * U+26A9 HORIZONTAL MALE WITH STROKE SIGN: try adding symbols
 * U+26AD MARRIAGE SYMBOL: try adding symbols
 * U+26AE DIVORCE SYMBOL: try adding symbols
 * U+26AF UNMARRIED PARTNERSHIP SYMBOL: try adding symbols
 * U+26B0 COFFIN: try adding symbols
 * U+26B1 FUNERAL URN: try adding symbols
 * U+26B2 NEUTER: try adding symbols
 * U+26B3 CERES: try adding symbols
 * U+26B4 PALLAS: try adding symbols
 * U+26B5 JUNO: try adding symbols
 * U+26B6 VESTA: try adding symbols
 * U+26B7 CHIRON: try adding symbols
 * U+26B8 BLACK MOON LILITH: try adding symbols
 * U+26B9 SEXTILE: try adding symbols
 * U+26BA SEMISEXTILE: try adding symbols
 * U+26BB QUINCUNX: try adding symbols
 * U+26BC SESQUIQUADRATE: try adding symbols
 * U+26CE OPHIUCHUS: try adding symbols
 * U+26E2 ASTRONOMICAL SYMBOL FOR URANUS: try adding symbols
 * U+26E3 HEAVY CIRCLE WITH STROKE AND TWO DOTS ABOVE: try adding symbols
 * U+26E4 PENTAGRAM: try adding symbols
 * U+26E5 RIGHT-HANDED INTERLACED PENTAGRAM: try adding symbols
 * U+26E6 LEFT-HANDED INTERLACED PENTAGRAM: try adding symbols
 * U+26E7 INVERTED PENTAGRAM: try adding symbols
 * U+26E8 BLACK CROSS ON SHIELD: try adding symbols
 * U+26E9 SHINTO SHRINE: try adding symbols
 * U+26EA CHURCH: try adding symbols
 * U+26EB CASTLE: try adding symbols
 * U+26EC HISTORIC SITE: try adding symbols
 * U+26ED GEAR WITHOUT HUB: try adding symbols
 * U+26EE GEAR WITH HANDLES: try adding symbols
 * U+26EF MAP SYMBOL FOR LIGHTHOUSE: try adding symbols
 * U+26F0 MOUNTAIN: try adding symbols
 * U+26F1 UMBRELLA ON GROUND: try adding symbols
 * U+26F2 FOUNTAIN: try adding symbols
 * U+26F3 FLAG IN HOLE: try adding symbols
 * U+26F4 FERRY: try adding symbols
 * U+26F5 SAILBOAT: try adding symbols
 * U+26F6 SQUARE FOUR CORNERS: try adding symbols
 * U+26F7 SKIER: try adding symbols
 * U+26F8 ICE SKATE: try adding symbols
 * U+26F9 PERSON WITH BALL: try adding symbols
 * U+26FA TENT: try adding symbols
 * U+26FB JAPANESE BANK SYMBOL: try adding symbols
 * U+26FC HEADSTONE GRAVEYARD SYMBOL: try adding symbols
 * U+26FD FUEL PUMP: try adding symbols
 * U+26FE CUP ON BLACK SQUARE: try adding symbols
 * U+26FF WHITE FLAG WITH HORIZONTAL MIDDLE BLACK STRIPE: try adding symbols
 * U+271D LATIN CROSS: try adding symbols
 * U+271E SHADOWED WHITE LATIN CROSS: try adding symbols
 * U+271F OUTLINED LATIN CROSS: try adding symbols
 * U+2720 MALTESE CROSS: try adding symbols
 * U+2721 STAR OF DAVID: try adding symbols
 * U+2776 DINGBAT NEGATIVE CIRCLED DIGIT ONE: try adding symbols
 * U+2777 DINGBAT NEGATIVE CIRCLED DIGIT TWO: try adding symbols
 * U+2778 DINGBAT NEGATIVE CIRCLED DIGIT THREE: try adding symbols
 * U+2779 DINGBAT NEGATIVE CIRCLED DIGIT FOUR: try adding symbols
 * U+277A DINGBAT NEGATIVE CIRCLED DIGIT FIVE: try adding symbols
 * U+277B DINGBAT NEGATIVE CIRCLED DIGIT SIX: try adding symbols
 * U+277C DINGBAT NEGATIVE CIRCLED DIGIT SEVEN: try adding symbols
 * U+277D DINGBAT NEGATIVE CIRCLED DIGIT EIGHT: try adding symbols
 * U+277E DINGBAT NEGATIVE CIRCLED DIGIT NINE: try adding symbols
 * U+277F DINGBAT NEGATIVE CIRCLED NUMBER TEN: try adding symbols
 * U+2780 DINGBAT CIRCLED SANS-SERIF DIGIT ONE: try adding symbols
 * U+2781 DINGBAT CIRCLED SANS-SERIF DIGIT TWO: try adding symbols
 * U+2782 DINGBAT CIRCLED SANS-SERIF DIGIT THREE: try adding symbols
 * U+2783 DINGBAT CIRCLED SANS-SERIF DIGIT FOUR: try adding symbols
 * U+2784 DINGBAT CIRCLED SANS-SERIF DIGIT FIVE: try adding symbols
 * U+2785 DINGBAT CIRCLED SANS-SERIF DIGIT SIX: try adding symbols
 * U+2786 DINGBAT CIRCLED SANS-SERIF DIGIT SEVEN: try adding symbols
 * U+2787 DINGBAT CIRCLED SANS-SERIF DIGIT EIGHT: try adding symbols
 * U+2788 DINGBAT CIRCLED SANS-SERIF DIGIT NINE: try adding symbols
 * U+2789 DINGBAT CIRCLED SANS-SERIF NUMBER TEN: try adding symbols
 * U+278A DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT ONE: try adding symbols
 * U+278B DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT TWO: try adding symbols
 * U+278C DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT THREE: try adding symbols
 * U+278D DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT FOUR: try adding symbols
 * U+278E DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT FIVE: try adding symbols
 * U+278F DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT SIX: try adding symbols
 * U+2790 DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT SEVEN: try adding symbols
 * U+2791 DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT EIGHT: try adding symbols
 * U+2792 DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT NINE: try adding symbols
 * U+2793 DINGBAT NEGATIVE CIRCLED SANS-SERIF NUMBER TEN: try adding symbols
 * U+2921 NORTH WEST AND SOUTH EAST ARROW: try adding one of: symbols, math
 * U+2922 NORTH EAST AND SOUTH WEST ARROW: try adding one of: symbols, math
 * U+1F100 DIGIT ZERO FULL STOP: try adding symbols
 * U+1F101 DIGIT ZERO COMMA: try adding symbols
 * U+1F102 DIGIT ONE COMMA: try adding symbols
 * U+1F103 DIGIT TWO COMMA: try adding symbols
 * U+1F104 DIGIT THREE COMMA: try adding symbols
 * U+1F105 DIGIT FOUR COMMA: try adding symbols
 * U+1F106 DIGIT FIVE COMMA: try adding symbols
 * U+1F107 DIGIT SIX COMMA: try adding symbols
 * U+1F108 DIGIT SEVEN COMMA: try adding symbols
 * U+1F109 DIGIT EIGHT COMMA: try adding symbols
 * U+1F10A DIGIT NINE COMMA: try adding symbols
 * U+1F10B DINGBAT CIRCLED SANS-SERIF DIGIT ZERO: try adding symbols
 * U+1F10C DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT ZERO: try adding symbols
 * U+1F110 PARENTHESIZED LATIN CAPITAL LETTER A: try adding symbols
 * U+1F111 PARENTHESIZED LATIN CAPITAL LETTER B: try adding symbols
 * U+1F112 PARENTHESIZED LATIN CAPITAL LETTER C: try adding symbols
 * U+1F113 PARENTHESIZED LATIN CAPITAL LETTER D: try adding symbols
 * U+1F114 PARENTHESIZED LATIN CAPITAL LETTER E: try adding symbols
 * U+1F115 PARENTHESIZED LATIN CAPITAL LETTER F: try adding symbols
 * U+1F116 PARENTHESIZED LATIN CAPITAL LETTER G: try adding symbols
 * U+1F117 PARENTHESIZED LATIN CAPITAL LETTER H: try adding symbols
 * U+1F118 PARENTHESIZED LATIN CAPITAL LETTER I: try adding symbols
 * U+1F119 PARENTHESIZED LATIN CAPITAL LETTER J: try adding symbols
 * U+1F11A PARENTHESIZED LATIN CAPITAL LETTER K: try adding symbols
 * U+1F11B PARENTHESIZED LATIN CAPITAL LETTER L: try adding symbols
 * U+1F11C PARENTHESIZED LATIN CAPITAL LETTER M: try adding symbols
 * U+1F11D PARENTHESIZED LATIN CAPITAL LETTER N: try adding symbols
 * U+1F11E PARENTHESIZED LATIN CAPITAL LETTER O: try adding symbols
 * U+1F11F PARENTHESIZED LATIN CAPITAL LETTER P: try adding symbols
 * U+1F120 PARENTHESIZED LATIN CAPITAL LETTER Q: try adding symbols
 * U+1F121 PARENTHESIZED LATIN CAPITAL LETTER R: try adding symbols
 * U+1F122 PARENTHESIZED LATIN CAPITAL LETTER S: try adding symbols
 * U+1F123 PARENTHESIZED LATIN CAPITAL LETTER T: try adding symbols
 * U+1F124 PARENTHESIZED LATIN CAPITAL LETTER U: try adding symbols
 * U+1F125 PARENTHESIZED LATIN CAPITAL LETTER V: try adding symbols
 * U+1F126 PARENTHESIZED LATIN CAPITAL LETTER W: try adding symbols
 * U+1F127 PARENTHESIZED LATIN CAPITAL LETTER X: try adding symbols
 * U+1F128 PARENTHESIZED LATIN CAPITAL LETTER Y: try adding symbols
 * U+1F129 PARENTHESIZED LATIN CAPITAL LETTER Z: try adding symbols
 * U+1F12A TORTOISE SHELL BRACKETED LATIN CAPITAL LETTER S: try adding symbols
 * U+1F12B CIRCLED ITALIC LATIN CAPITAL LETTER C: try adding symbols
 * U+1F12C CIRCLED ITALIC LATIN CAPITAL LETTER R: try adding symbols
 * U+1F12D CIRCLED CD: try adding symbols
 * U+1F12E CIRCLED WZ: try adding symbols
 * U+1F12F COPYLEFT SYMBOL: try adding symbols
 * U+1F130 SQUARED LATIN CAPITAL LETTER A: try adding symbols
 * U+1F131 SQUARED LATIN CAPITAL LETTER B: try adding symbols
 * U+1F132 SQUARED LATIN CAPITAL LETTER C: try adding symbols
 * U+1F133 SQUARED LATIN CAPITAL LETTER D: try adding symbols
 * U+1F134 SQUARED LATIN CAPITAL LETTER E: try adding symbols
 * U+1F135 SQUARED LATIN CAPITAL LETTER F: try adding symbols
 * U+1F136 SQUARED LATIN CAPITAL LETTER G: try adding symbols
 * U+1F137 SQUARED LATIN CAPITAL LETTER H: try adding symbols
 * U+1F138 SQUARED LATIN CAPITAL LETTER I: try adding symbols
 * U+1F139 SQUARED LATIN CAPITAL LETTER J: try adding symbols
 * U+1F13A SQUARED LATIN CAPITAL LETTER K: try adding symbols
 * U+1F13B SQUARED LATIN CAPITAL LETTER L: try adding symbols
 * U+1F13C SQUARED LATIN CAPITAL LETTER M: try adding symbols
 * U+1F13D SQUARED LATIN CAPITAL LETTER N: try adding symbols
 * U+1F13E SQUARED LATIN CAPITAL LETTER O: try adding symbols
 * U+1F13F SQUARED LATIN CAPITAL LETTER P: try adding symbols
 * U+1F140 SQUARED LATIN CAPITAL LETTER Q: try adding symbols
 * U+1F141 SQUARED LATIN CAPITAL LETTER R: try adding symbols
 * U+1F142 SQUARED LATIN CAPITAL LETTER S: try adding symbols
 * U+1F143 SQUARED LATIN CAPITAL LETTER T: try adding symbols
 * U+1F144 SQUARED LATIN CAPITAL LETTER U: try adding symbols
 * U+1F145 SQUARED LATIN CAPITAL LETTER V: try adding symbols
 * U+1F146 SQUARED LATIN CAPITAL LETTER W: try adding symbols
 * U+1F147 SQUARED LATIN CAPITAL LETTER X: try adding symbols
 * U+1F148 SQUARED LATIN CAPITAL LETTER Y: try adding symbols
 * U+1F149 SQUARED LATIN CAPITAL LETTER Z: try adding symbols
 * U+1F14A SQUARED HV: try adding symbols
 * U+1F14B SQUARED MV: try adding symbols
 * U+1F14C SQUARED SD: try adding symbols
 * U+1F14D SQUARED SS: try adding symbols
 * U+1F14E SQUARED PPV: try adding symbols
 * U+1F14F SQUARED WC: try adding symbols
 * U+1F150 NEGATIVE CIRCLED LATIN CAPITAL LETTER A: try adding symbols
 * U+1F151 NEGATIVE CIRCLED LATIN CAPITAL LETTER B: try adding symbols
 * U+1F152 NEGATIVE CIRCLED LATIN CAPITAL LETTER C: try adding symbols
 * U+1F153 NEGATIVE CIRCLED LATIN CAPITAL LETTER D: try adding symbols
 * U+1F154 NEGATIVE CIRCLED LATIN CAPITAL LETTER E: try adding symbols
 * U+1F155 NEGATIVE CIRCLED LATIN CAPITAL LETTER F: try adding symbols
 * U+1F156 NEGATIVE CIRCLED LATIN CAPITAL LETTER G: try adding symbols
 * U+1F157 NEGATIVE CIRCLED LATIN CAPITAL LETTER H: try adding symbols
 * U+1F158 NEGATIVE CIRCLED LATIN CAPITAL LETTER I: try adding symbols
 * U+1F159 NEGATIVE CIRCLED LATIN CAPITAL LETTER J: try adding symbols
 * U+1F15A NEGATIVE CIRCLED LATIN CAPITAL LETTER K: try adding symbols
 * U+1F15B NEGATIVE CIRCLED LATIN CAPITAL LETTER L: try adding symbols
 * U+1F15C NEGATIVE CIRCLED LATIN CAPITAL LETTER M: try adding symbols
 * U+1F15D NEGATIVE CIRCLED LATIN CAPITAL LETTER N: try adding symbols
 * U+1F15E NEGATIVE CIRCLED LATIN CAPITAL LETTER O: try adding symbols
 * U+1F15F NEGATIVE CIRCLED LATIN CAPITAL LETTER P: try adding symbols
 * U+1F160 NEGATIVE CIRCLED LATIN CAPITAL LETTER Q: try adding symbols
 * U+1F161 NEGATIVE CIRCLED LATIN CAPITAL LETTER R: try adding symbols
 * U+1F162 NEGATIVE CIRCLED LATIN CAPITAL LETTER S: try adding symbols
 * U+1F163 NEGATIVE CIRCLED LATIN CAPITAL LETTER T: try adding symbols
 * U+1F164 NEGATIVE CIRCLED LATIN CAPITAL LETTER U: try adding symbols
 * U+1F165 NEGATIVE CIRCLED LATIN CAPITAL LETTER V: try adding symbols
 * U+1F166 NEGATIVE CIRCLED LATIN CAPITAL LETTER W: try adding symbols
 * U+1F167 NEGATIVE CIRCLED LATIN CAPITAL LETTER X: try adding symbols
 * U+1F168 NEGATIVE CIRCLED LATIN CAPITAL LETTER Y: try adding symbols
 * U+1F169 NEGATIVE CIRCLED LATIN CAPITAL LETTER Z: try adding symbols
 * U+1F16A RAISED MC SIGN: try adding symbols
 * U+1F16B RAISED MD SIGN: try adding symbols
 * U+1F16C RAISED MR SIGN: try adding symbols
 * U+1F170 NEGATIVE SQUARED LATIN CAPITAL LETTER A: try adding symbols
 * U+1F171 NEGATIVE SQUARED LATIN CAPITAL LETTER B: try adding symbols
 * U+1F172 NEGATIVE SQUARED LATIN CAPITAL LETTER C: try adding symbols
 * U+1F173 NEGATIVE SQUARED LATIN CAPITAL LETTER D: try adding symbols
 * U+1F174 NEGATIVE SQUARED LATIN CAPITAL LETTER E: try adding symbols
 * U+1F175 NEGATIVE SQUARED LATIN CAPITAL LETTER F: try adding symbols
 * U+1F176 NEGATIVE SQUARED LATIN CAPITAL LETTER G: try adding symbols
 * U+1F177 NEGATIVE SQUARED LATIN CAPITAL LETTER H: try adding symbols
 * U+1F178 NEGATIVE SQUARED LATIN CAPITAL LETTER I: try adding symbols
 * U+1F179 NEGATIVE SQUARED LATIN CAPITAL LETTER J: try adding symbols
 * U+1F17A NEGATIVE SQUARED LATIN CAPITAL LETTER K: try adding symbols
 * U+1F17B NEGATIVE SQUARED LATIN CAPITAL LETTER L: try adding symbols
 * U+1F17C NEGATIVE SQUARED LATIN CAPITAL LETTER M: try adding symbols
 * U+1F17D NEGATIVE SQUARED LATIN CAPITAL LETTER N: try adding symbols
 * U+1F17E NEGATIVE SQUARED LATIN CAPITAL LETTER O: try adding symbols
 * U+1F17F NEGATIVE SQUARED LATIN CAPITAL LETTER P: try adding symbols
 * U+1F180 NEGATIVE SQUARED LATIN CAPITAL LETTER Q: try adding symbols
 * U+1F181 NEGATIVE SQUARED LATIN CAPITAL LETTER R: try adding symbols
 * U+1F182 NEGATIVE SQUARED LATIN CAPITAL LETTER S: try adding symbols
 * U+1F183 NEGATIVE SQUARED LATIN CAPITAL LETTER T: try adding symbols
 * U+1F184 NEGATIVE SQUARED LATIN CAPITAL LETTER U: try adding symbols
 * U+1F185 NEGATIVE SQUARED LATIN CAPITAL LETTER V: try adding symbols
 * U+1F186 NEGATIVE SQUARED LATIN CAPITAL LETTER W: try adding symbols
 * U+1F187 NEGATIVE SQUARED LATIN CAPITAL LETTER X: try adding symbols
 * U+1F188 NEGATIVE SQUARED LATIN CAPITAL LETTER Y: try adding symbols
 * U+1F189 NEGATIVE SQUARED LATIN CAPITAL LETTER Z: try adding symbols
 * U+1F18A CROSSED NEGATIVE SQUARED LATIN CAPITAL LETTER P: try adding symbols
 * U+1F18B NEGATIVE SQUARED IC: try adding symbols
 * U+1F18C NEGATIVE SQUARED PA: try adding symbols
 * U+1F18D NEGATIVE SQUARED SA: try adding symbols
 * U+1F18E NEGATIVE SQUARED AB: try adding symbols
 * U+1F18F NEGATIVE SQUARED WC: try adding symbols
 * U+1F190 SQUARE DJ: try adding symbols
 * U+1F19B SQUARED THREE D: try adding symbols
 * U+1F19C SQUARED SECOND SCREEN: try adding symbols
 * U+1F19D SQUARED TWO K: try adding symbols
 * U+1F19E SQUARED FOUR K: try adding symbols
 * U+1F19F SQUARED EIGHT K: try adding symbols
 * U+1F1A0 SQUARED FIVE POINT ONE: try adding symbols
 * U+1F1A1 SQUARED SEVEN POINT ONE: try adding symbols
 * U+1F1A2 SQUARED TWENTY-TWO POINT TWO: try adding symbols
 * U+1F1A3 SQUARED SIXTY P: try adding symbols
 * U+1F1A4 SQUARED ONE HUNDRED TWENTY P: try adding symbols
 * U+1F1A5 SQUARED LATIN SMALL LETTER D: try adding symbols
 * U+1F1A6 SQUARED HC: try adding symbols
 * U+1F1A7 SQUARED HDR: try adding symbols
 * U+1F1A8 SQUARED HI-RES: try adding symbols
 * U+1F1A9 SQUARED LOSSLESS: try adding symbols
 * U+1F1AA SQUARED SHV: try adding symbols
 * U+1F1AB SQUARED UHD: try adding symbols
 * U+1F1AC SQUARED VOD: try adding symbols
 * U+1F546 WHITE LATIN CROSS: try adding symbols
 * U+1F547 HEAVY LATIN CROSS: try adding symbols
 * U+1F548 CELTIC CROSS: try adding symbols
 * U+1F549 OM SYMBOL: try adding symbols
 * U+1F54F BOWL OF HYGIEIA: try adding symbols
 * U+1F610 NEUTRAL FACE: try adding symbols
 * U+1F700 ALCHEMICAL SYMBOL FOR QUINTESSENCE: try adding symbols
 * U+1F701 ALCHEMICAL SYMBOL FOR AIR: try adding symbols
 * U+1F702 ALCHEMICAL SYMBOL FOR FIRE: try adding symbols
 * U+1F703 ALCHEMICAL SYMBOL FOR EARTH: try adding symbols
 * U+1F704 ALCHEMICAL SYMBOL FOR WATER: try adding symbols
 * U+1F705 ALCHEMICAL SYMBOL FOR AQUAFORTIS: try adding symbols
 * U+1F706 ALCHEMICAL SYMBOL FOR AQUA REGIA: try adding symbols
 * U+1F707 ALCHEMICAL SYMBOL FOR AQUA REGIA-2: try adding symbols
 * U+1F708 ALCHEMICAL SYMBOL FOR AQUA VITAE: try adding symbols
 * U+1F709 ALCHEMICAL SYMBOL FOR AQUA VITAE-2: try adding symbols
 * U+1F70A ALCHEMICAL SYMBOL FOR VINEGAR: try adding symbols
 * U+1F70B ALCHEMICAL SYMBOL FOR VINEGAR-2: try adding symbols
 * U+1F70C ALCHEMICAL SYMBOL FOR VINEGAR-3: try adding symbols
 * U+1F70D ALCHEMICAL SYMBOL FOR SULFUR: try adding symbols
 * U+1F70E ALCHEMICAL SYMBOL FOR PHILOSOPHERS SULFUR: try adding symbols
 * U+1F70F ALCHEMICAL SYMBOL FOR BLACK SULFUR: try adding symbols
 * U+1F710 ALCHEMICAL SYMBOL FOR MERCURY SUBLIMATE: try adding symbols
 * U+1F711 ALCHEMICAL SYMBOL FOR MERCURY SUBLIMATE-2: try adding symbols
 * U+1F712 ALCHEMICAL SYMBOL FOR MERCURY SUBLIMATE-3: try adding symbols
 * U+1F713 ALCHEMICAL SYMBOL FOR CINNABAR: try adding symbols
 * U+1F714 ALCHEMICAL SYMBOL FOR SALT: try adding symbols
 * U+1F715 ALCHEMICAL SYMBOL FOR NITRE: try adding symbols
 * U+1F716 ALCHEMICAL SYMBOL FOR VITRIOL: try adding symbols
 * U+1F717 ALCHEMICAL SYMBOL FOR VITRIOL-2: try adding symbols
 * U+1F718 ALCHEMICAL SYMBOL FOR ROCK SALT: try adding symbols
 * U+1F719 ALCHEMICAL SYMBOL FOR ROCK SALT-2: try adding symbols
 * U+1F71A ALCHEMICAL SYMBOL FOR GOLD: try adding symbols
 * U+1F71B ALCHEMICAL SYMBOL FOR SILVER: try adding symbols
 * U+1F71C ALCHEMICAL SYMBOL FOR IRON ORE: try adding symbols
 * U+1F71D ALCHEMICAL SYMBOL FOR IRON ORE-2: try adding symbols
 * U+1F71E ALCHEMICAL SYMBOL FOR CROCUS OF IRON: try adding symbols
 * U+1F71F ALCHEMICAL SYMBOL FOR REGULUS OF IRON: try adding symbols
 * U+1F720 ALCHEMICAL SYMBOL FOR COPPER ORE: try adding symbols
 * U+1F721 ALCHEMICAL SYMBOL FOR IRON-COPPER ORE: try adding symbols
 * U+1F722 ALCHEMICAL SYMBOL FOR SUBLIMATE OF COPPER: try adding symbols
 * U+1F723 ALCHEMICAL SYMBOL FOR CROCUS OF COPPER: try adding symbols
 * U+1F724 ALCHEMICAL SYMBOL FOR CROCUS OF COPPER-2: try adding symbols
 * U+1F725 ALCHEMICAL SYMBOL FOR COPPER ANTIMONIATE: try adding symbols
 * U+1F726 ALCHEMICAL SYMBOL FOR SALT OF COPPER ANTIMONIATE: try adding symbols
 * U+1F727 ALCHEMICAL SYMBOL FOR SUBLIMATE OF SALT OF COPPER: try adding symbols
 * U+1F728 ALCHEMICAL SYMBOL FOR VERDIGRIS: try adding symbols
 * U+1F729 ALCHEMICAL SYMBOL FOR TIN ORE: try adding symbols
 * U+1F72A ALCHEMICAL SYMBOL FOR LEAD ORE: try adding symbols
 * U+1F72B ALCHEMICAL SYMBOL FOR ANTIMONY ORE: try adding symbols
 * U+1F72C ALCHEMICAL SYMBOL FOR SUBLIMATE OF ANTIMONY: try adding symbols
 * U+1F72D ALCHEMICAL SYMBOL FOR SALT OF ANTIMONY: try adding symbols
 * U+1F72E ALCHEMICAL SYMBOL FOR SUBLIMATE OF SALT OF ANTIMONY: try adding symbols
 * U+1F72F ALCHEMICAL SYMBOL FOR VINEGAR OF ANTIMONY: try adding symbols
 * U+1F730 ALCHEMICAL SYMBOL FOR REGULUS OF ANTIMONY: try adding symbols
 * U+1F731 ALCHEMICAL SYMBOL FOR REGULUS OF ANTIMONY-2: try adding symbols
 * U+1F732 ALCHEMICAL SYMBOL FOR REGULUS: try adding symbols
 * U+1F733 ALCHEMICAL SYMBOL FOR REGULUS-2: try adding symbols
 * U+1F734 ALCHEMICAL SYMBOL FOR REGULUS-3: try adding symbols
 * U+1F735 ALCHEMICAL SYMBOL FOR REGULUS-4: try adding symbols
 * U+1F736 ALCHEMICAL SYMBOL FOR ALKALI: try adding symbols
 * U+1F737 ALCHEMICAL SYMBOL FOR ALKALI-2: try adding symbols
 * U+1F738 ALCHEMICAL SYMBOL FOR MARCASITE: try adding symbols
 * U+1F739 ALCHEMICAL SYMBOL FOR SAL-AMMONIAC: try adding symbols
 * U+1F73A ALCHEMICAL SYMBOL FOR ARSENIC: try adding symbols
 * U+1F73B ALCHEMICAL SYMBOL FOR REALGAR: try adding symbols
 * U+1F73C ALCHEMICAL SYMBOL FOR REALGAR-2: try adding symbols
 * U+1F73D ALCHEMICAL SYMBOL FOR AURIPIGMENT: try adding symbols
 * U+1F73E ALCHEMICAL SYMBOL FOR BISMUTH ORE: try adding symbols
 * U+1F73F ALCHEMICAL SYMBOL FOR TARTAR: try adding symbols
 * U+1F740 ALCHEMICAL SYMBOL FOR TARTAR-2: try adding symbols
 * U+1F741 ALCHEMICAL SYMBOL FOR QUICK LIME: try adding symbols
 * U+1F742 ALCHEMICAL SYMBOL FOR BORAX: try adding symbols
 * U+1F743 ALCHEMICAL SYMBOL FOR BORAX-2: try adding symbols
 * U+1F744 ALCHEMICAL SYMBOL FOR BORAX-3: try adding symbols
 * U+1F745 ALCHEMICAL SYMBOL FOR ALUM: try adding symbols
 * U+1F746 ALCHEMICAL SYMBOL FOR OIL: try adding symbols
 * U+1F747 ALCHEMICAL SYMBOL FOR SPIRIT: try adding symbols
 * U+1F748 ALCHEMICAL SYMBOL FOR TINCTURE: try adding symbols
 * U+1F749 ALCHEMICAL SYMBOL FOR GUM: try adding symbols
 * U+1F74A ALCHEMICAL SYMBOL FOR WAX: try adding symbols
 * U+1F74B ALCHEMICAL SYMBOL FOR POWDER: try adding symbols
 * U+1F74C ALCHEMICAL SYMBOL FOR CALX: try adding symbols
 * U+1F74D ALCHEMICAL SYMBOL FOR TUTTY: try adding symbols
 * U+1F74E ALCHEMICAL SYMBOL FOR CAPUT MORTUUM: try adding symbols
 * U+1F74F ALCHEMICAL SYMBOL FOR SCEPTER OF JOVE: try adding symbols
 * U+1F750 ALCHEMICAL SYMBOL FOR CADUCEUS: try adding symbols
 * U+1F751 ALCHEMICAL SYMBOL FOR TRIDENT: try adding symbols
 * U+1F752 ALCHEMICAL SYMBOL FOR STARRED TRIDENT: try adding symbols
 * U+1F753 ALCHEMICAL SYMBOL FOR LODESTONE: try adding symbols
 * U+1F754 ALCHEMICAL SYMBOL FOR SOAP: try adding symbols
 * U+1F755 ALCHEMICAL SYMBOL FOR URINE: try adding symbols
 * U+1F756 ALCHEMICAL SYMBOL FOR HORSE DUNG: try adding symbols
 * U+1F757 ALCHEMICAL SYMBOL FOR ASHES: try adding symbols
 * U+1F758 ALCHEMICAL SYMBOL FOR POT ASHES: try adding symbols
 * U+1F759 ALCHEMICAL SYMBOL FOR BRICK: try adding symbols
 * U+1F75A ALCHEMICAL SYMBOL FOR POWDERED BRICK: try adding symbols
 * U+1F75B ALCHEMICAL SYMBOL FOR AMALGAM: try adding symbols
 * U+1F75C ALCHEMICAL SYMBOL FOR STRATUM SUPER STRATUM: try adding symbols
 * U+1F75D ALCHEMICAL SYMBOL FOR STRATUM SUPER STRATUM-2: try adding symbols
 * U+1F75E ALCHEMICAL SYMBOL FOR SUBLIMATION: try adding symbols
 * U+1F75F ALCHEMICAL SYMBOL FOR PRECIPITATE: try adding symbols
 * U+1F760 ALCHEMICAL SYMBOL FOR DISTILL: try adding symbols
 * U+1F761 ALCHEMICAL SYMBOL FOR DISSOLVE: try adding symbols
 * U+1F762 ALCHEMICAL SYMBOL FOR DISSOLVE-2: try adding symbols
 * U+1F763 ALCHEMICAL SYMBOL FOR PURIFY: try adding symbols
 * U+1F764 ALCHEMICAL SYMBOL FOR PUTREFACTION: try adding symbols
 * U+1F765 ALCHEMICAL SYMBOL FOR CRUCIBLE: try adding symbols
 * U+1F766 ALCHEMICAL SYMBOL FOR CRUCIBLE-2: try adding symbols
 * U+1F767 ALCHEMICAL SYMBOL FOR CRUCIBLE-3: try adding symbols
 * U+1F768 ALCHEMICAL SYMBOL FOR CRUCIBLE-4: try adding symbols
 * U+1F769 ALCHEMICAL SYMBOL FOR CRUCIBLE-5: try adding symbols
 * U+1F76A ALCHEMICAL SYMBOL FOR ALEMBIC: try adding symbols
 * U+1F76B ALCHEMICAL SYMBOL FOR BATH OF MARY: try adding symbols
 * U+1F76C ALCHEMICAL SYMBOL FOR BATH OF VAPOURS: try adding symbols
 * U+1F76D ALCHEMICAL SYMBOL FOR RETORT: try adding symbols
 * U+1F76E ALCHEMICAL SYMBOL FOR HOUR: try adding symbols
 * U+1F76F ALCHEMICAL SYMBOL FOR NIGHT: try adding symbols
 * U+1F770 ALCHEMICAL SYMBOL FOR DAY-NIGHT: try adding symbols
 * U+1F771 ALCHEMICAL SYMBOL FOR MONTH: try adding symbols
 * U+1F772 ALCHEMICAL SYMBOL FOR HALF DRAM: try adding symbols
 * U+1F773 ALCHEMICAL SYMBOL FOR HALF OUNCE: try adding symbols

Or you can add the above codepoints to one of the subsets supported by the font: `latin`, `latin-ext` [code: unreachable-subsetting]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- enclosingcircle

	- enclosingcirclebackslash

	- enclosingdiamond

	- enclosingsquare

	- enclosingupwardpointingtriangle
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check math signs have the same width. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/math_signs_width">com.google.fonts/check/math_signs_width</a>)</summary><div>


* ⚠ **WARN** The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:

Width = 322:
minus
 [code: width-outliers]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Shaping Checks>.html#com.google.fonts/check/soft_dotted">com.google.fonts/check/soft_dotted</a>)</summary><div>


* ⚠ **WARN** The dot of soft dotted characters used in orthographies _must_ disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌

The dot of soft dotted characters _should_ disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̒ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̦̒ į̧̀ į̧́

Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers). 

Your font does *not* cover the following languages that require the soft-dotted feature: Lugbara (Latn, 2,200,000 speakers), Avokaya (Latn, 100,000 speakers), Ebira (Latn, 2,200,000 speakers), Dan (Latn, 1,099,244 speakers), Dutch (Latn, 31,709,104 speakers), Belarusian (Cyrl, 10,064,517 speakers), Igbo (Latn, 27,823,640 speakers), Kom (Latn, 360,685 speakers), Ma’di (Latn, 584,000 speakers), Basaa (Latn, 332,940 speakers), Nateni (Latn, 100,000 speakers), Gulay (Latn, 250,478 speakers), Ejagham (Latn, 120,000 speakers), Koonzime (Latn, 40,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mango (Latn, 77,000 speakers), Navajo (Latn, 166,319 speakers), Sar (Latn, 500,000 speakers), Aghem (Latn, 38,843 speakers). [code: soft-dotted]
</div></details><br></div></details>

### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 3 | 5 | 103 | 8 | 136 | 0 |
| 0% | 1% | 2% | 40% | 3% | 53% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
