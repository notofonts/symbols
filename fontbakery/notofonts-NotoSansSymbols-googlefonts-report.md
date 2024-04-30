## FontBakery report

fontbakery version: 0.12.4



## Experimental checks

These won't break the CI job for now, but will become effective after some time if nobody raises any concern.


<details><summary>[1] NotoSansSymbols[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Validate location, size and resolution of article images. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.article.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Family metadata at fonts/NotoSansSymbols/googlefonts/variable does not have an article.</p>
 [code: lacks-article]



</div>
</details>
</div>
</details>




## All other checks



<details><summary>[10] NotoSansSymbols[wght].ttf</summary>
<div>
<details>
    <summary>⚠️ <b>WARN</b> Detect any interpolation issues in the font. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>Interpolation issues were found in the font:</p>
<pre><code>- Contour 2 point 10 in glyph 'u1F75D' has a kink between location wght=100 and location wght=900

- Contour 0 point 51 in glyph 'uni2649' has a kink between location wght=400 and location wght=100

- Contour 0 point 51 in glyph 'uni2649' has a kink between location wght=100 and location wght=900
</code></pre>
 [code: interpolation-issues]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check math signs have the same width. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The most common width is 572 among a set of 6 math glyphs.
The following math glyphs have a different width, though:</p>
<p>Width = 322:
minus</p>
 [code: width-outliers]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Check font contains no unreachable glyphs <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The following glyphs could not be reached by codepoint or substitution rules:</p>
<pre><code>- enclosingcircle

- enclosingcirclebackslash

- enclosingdiamond

- enclosingsquare

- enclosingupwardpointingtriangle
</code></pre>
 [code: unreachable-glyphs]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure soft_dotted characters lose their dot when combined with marks that replace the dot. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>The dot of soft dotted characters used in orthographies <em>must</em> disappear in the following strings: į̀ į́ į̂ į̃ į̄ į̌</p>
<p>The dot of soft dotted characters <em>should</em> disappear in other cases, for example: į̆ į̇ į̈ į̊ į̋ į̦̀ į̦́ į̦̂ į̦̃ į̦̄ į̦̆ į̦̇ į̦̈ į̦̊ į̦̋ į̦̌ į̧̀ į̧́ į̧̂ į̧̃</p>
<p>Your font fully covers the following languages that require the soft-dotted feature: Lithuanian (Latn, 2,357,094 speakers).</p>
<p>Your font does <em>not</em> cover the following languages that require the soft-dotted feature: Southern Kisi (Latn, 360,000 speakers), Dutch (Latn, 31,709,104 speakers), Sar (Latn, 500,000 speakers), Mango (Latn, 77,000 speakers), Belarusian (Cyrl, 10,064,517 speakers), Cicipu (Latn, 44,000 speakers), Makaa (Latn, 221,000 speakers), Koonzime (Latn, 40,000 speakers), Lugbara (Latn, 2,200,000 speakers), Dan (Latn, 1,099,244 speakers), Nzakara (Latn, 50,000 speakers), Dii (Latn, 71,000 speakers), Bete-Bendi (Latn, 100,000 speakers), Avokaya (Latn, 100,000 speakers), Aghem (Latn, 38,843 speakers), Kom (Latn, 360,685 speakers), Nateni (Latn, 100,000 speakers), Zapotec (Latn, 490,000 speakers), Igbo (Latn, 27,823,640 speakers), Bafut (Latn, 158,146 speakers), Ekpeye (Latn, 226,000 speakers), Yala (Latn, 200,000 speakers), Kpelle, Guinea (Latn, 622,000 speakers), Ijo, Southeast (Latn, 2,471,000 speakers), Ukrainian (Cyrl, 29,273,587 speakers), Mundani (Latn, 34,000 speakers), Mfumte (Latn, 79,000 speakers), Gulay (Latn, 250,478 speakers), South Central Banda (Latn, 244,000 speakers), Ngbaka (Latn, 1,020,000 speakers), Ebira (Latn, 2,200,000 speakers), Basaa (Latn, 332,940 speakers), Ejagham (Latn, 120,000 speakers), Navajo (Latn, 166,319 speakers), Fur (Latn, 1,230,163 speakers), Ma’di (Latn, 584,000 speakers).</p>
 [code: soft-dotted]



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
<li>U+02C7 CARON: try adding one of: canadian-aboriginal, yi, tifinagh</li>
<li>U+02C9 MODIFIER LETTER MACRON: not included in any glyphset definition</li>
<li>U+02D8 BREVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02D9 DOT ABOVE: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DB OGONEK: try adding one of: canadian-aboriginal, yi</li>
<li>U+02DD DOUBLE ACUTE ACCENT: not included in any glyphset definition</li>
<li>U+0302 COMBINING CIRCUMFLEX ACCENT: try adding one of: cherokee, tifinagh, coptic, math</li>
<li>U+0306 COMBINING BREVE: try adding one of: old-permic, tifinagh</li>
<li>U+0307 COMBINING DOT ABOVE: try adding one of: malayalam, tifinagh, canadian-aboriginal, syriac, tai-le, coptic, old-permic, math</li>
<li>U+030A COMBINING RING ABOVE: try adding syriac</li>
<li>U+030B COMBINING DOUBLE ACUTE ACCENT: try adding one of: cherokee, osage</li>
<li>U+030C COMBINING CARON: try adding one of: cherokee, tai-le</li>
<li>U+0326 COMBINING COMMA BELOW: not included in any glyphset definition</li>
<li>U+0327 COMBINING CEDILLA: not included in any glyphset definition</li>
<li>U+0328 COMBINING OGONEK: not included in any glyphset definition</li>
<li>U+20DD COMBINING ENCLOSING CIRCLE: try adding symbols</li>
<li>U+20DE COMBINING ENCLOSING SQUARE: try adding symbols</li>
<li>U+20DF COMBINING ENCLOSING DIAMOND: try adding symbols</li>
<li>U+20E0 COMBINING ENCLOSING CIRCLE BACKSLASH: try adding symbols</li>
<li>U+20E2 COMBINING ENCLOSING SCREEN: try adding symbols</li>
<li>U+20E3 COMBINING ENCLOSING KEYCAP: try adding symbols</li>
<li>U+20E4 COMBINING ENCLOSING UPWARD POINTING TRIANGLE: try adding symbols</li>
<li>U+2160 ROMAN NUMERAL ONE: try adding symbols</li>
<li>U+2161 ROMAN NUMERAL TWO: try adding symbols</li>
<li>U+2162 ROMAN NUMERAL THREE: try adding symbols</li>
<li>U+2163 ROMAN NUMERAL FOUR: try adding symbols</li>
<li>U+2164 ROMAN NUMERAL FIVE: try adding symbols</li>
<li>U+2165 ROMAN NUMERAL SIX: try adding symbols</li>
<li>U+2166 ROMAN NUMERAL SEVEN: try adding symbols</li>
<li>U+2167 ROMAN NUMERAL EIGHT: try adding symbols</li>
<li>U+2168 ROMAN NUMERAL NINE: try adding symbols</li>
<li>U+2169 ROMAN NUMERAL TEN: try adding symbols</li>
<li>U+216A ROMAN NUMERAL ELEVEN: try adding symbols</li>
<li>U+216B ROMAN NUMERAL TWELVE: try adding symbols</li>
<li>U+216C ROMAN NUMERAL FIFTY: try adding symbols</li>
<li>U+216D ROMAN NUMERAL ONE HUNDRED: try adding symbols</li>
<li>U+216E ROMAN NUMERAL FIVE HUNDRED: try adding symbols</li>
<li>U+216F ROMAN NUMERAL ONE THOUSAND: try adding symbols</li>
<li>U+2170 SMALL ROMAN NUMERAL ONE: try adding symbols</li>
<li>U+2171 SMALL ROMAN NUMERAL TWO: try adding symbols</li>
<li>U+2172 SMALL ROMAN NUMERAL THREE: try adding symbols</li>
<li>U+2173 SMALL ROMAN NUMERAL FOUR: try adding symbols</li>
<li>U+2174 SMALL ROMAN NUMERAL FIVE: try adding symbols</li>
<li>U+2175 SMALL ROMAN NUMERAL SIX: try adding symbols</li>
<li>U+2176 SMALL ROMAN NUMERAL SEVEN: try adding symbols</li>
<li>U+2177 SMALL ROMAN NUMERAL EIGHT: try adding symbols</li>
<li>U+2178 SMALL ROMAN NUMERAL NINE: try adding symbols</li>
<li>U+2179 SMALL ROMAN NUMERAL TEN: try adding symbols</li>
<li>U+217A SMALL ROMAN NUMERAL ELEVEN: try adding symbols</li>
<li>U+217B SMALL ROMAN NUMERAL TWELVE: try adding symbols</li>
<li>U+217C SMALL ROMAN NUMERAL FIFTY: try adding symbols</li>
<li>U+217D SMALL ROMAN NUMERAL ONE HUNDRED: try adding symbols</li>
<li>U+217E SMALL ROMAN NUMERAL FIVE HUNDRED: try adding symbols</li>
<li>U+217F SMALL ROMAN NUMERAL ONE THOUSAND: try adding symbols</li>
<li>U+2180 ROMAN NUMERAL ONE THOUSAND C D: try adding symbols</li>
<li>U+2181 ROMAN NUMERAL FIVE THOUSAND: try adding symbols</li>
<li>U+2182 ROMAN NUMERAL TEN THOUSAND: try adding symbols</li>
<li>U+2183 ROMAN NUMERAL REVERSED ONE HUNDRED: try adding symbols</li>
<li>U+2185 ROMAN NUMERAL SIX LATE FORM: try adding symbols</li>
<li>U+2186 ROMAN NUMERAL FIFTY EARLY FORM: try adding symbols</li>
<li>U+2187 ROMAN NUMERAL FIFTY THOUSAND: try adding symbols</li>
<li>U+2188 ROMAN NUMERAL ONE HUNDRED THOUSAND: try adding symbols</li>
<li>U+218A TURNED DIGIT TWO: try adding symbols</li>
<li>U+218B TURNED DIGIT THREE: try adding symbols</li>
<li>U+2190 LEFTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2192 RIGHTWARDS ARROW: try adding one of: symbols, math</li>
<li>U+2194 LEFT RIGHT ARROW: try adding one of: symbols, math</li>
<li>U+2195 UP DOWN ARROW: try adding one of: symbols, math</li>
<li>U+2196 NORTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2197 NORTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2198 SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2199 SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+2300 DIAMETER SIGN: try adding symbols</li>
<li>U+2301 ELECTRIC ARROW: try adding symbols</li>
<li>U+2302 HOUSE: try adding symbols</li>
<li>U+2303 UP ARROWHEAD: try adding symbols</li>
<li>U+2304 DOWN ARROWHEAD: try adding symbols</li>
<li>U+2305 PROJECTIVE: try adding symbols</li>
<li>U+2306 PERSPECTIVE: try adding symbols</li>
<li>U+2307 WAVY LINE: try adding symbols</li>
<li>U+2308 LEFT CEILING: try adding one of: symbols, math</li>
<li>U+2309 RIGHT CEILING: try adding one of: symbols, math</li>
<li>U+230A LEFT FLOOR: try adding one of: symbols, math</li>
<li>U+230B RIGHT FLOOR: try adding one of: symbols, math</li>
<li>U+230C BOTTOM RIGHT CROP: try adding symbols</li>
<li>U+230D BOTTOM LEFT CROP: try adding symbols</li>
<li>U+230E TOP RIGHT CROP: try adding symbols</li>
<li>U+230F TOP LEFT CROP: try adding symbols</li>
<li>U+2311 SQUARE LOZENGE: try adding symbols</li>
<li>U+2312 ARC: try adding symbols</li>
<li>U+2313 SEGMENT: try adding symbols</li>
<li>U+2314 SECTOR: try adding symbols</li>
<li>U+2315 TELEPHONE RECORDER: try adding symbols</li>
<li>U+2317 VIEWDATA SQUARE: try adding symbols</li>
<li>U+231C TOP LEFT CORNER: try adding one of: symbols, math</li>
<li>U+231D TOP RIGHT CORNER: try adding one of: symbols, math</li>
<li>U+231E BOTTOM LEFT CORNER: try adding one of: symbols, math</li>
<li>U+231F BOTTOM RIGHT CORNER: try adding one of: symbols, math</li>
<li>U+2322 FROWN: try adding symbols</li>
<li>U+2323 SMILE: try adding symbols</li>
<li>U+2329 LEFT-POINTING ANGLE BRACKET: try adding symbols</li>
<li>U+232A RIGHT-POINTING ANGLE BRACKET: try adding symbols</li>
<li>U+232C BENZENE RING: try adding symbols</li>
<li>U+232D CYLINDRICITY: try adding symbols</li>
<li>U+232E ALL AROUND-PROFILE: try adding symbols</li>
<li>U+232F SYMMETRY: try adding symbols</li>
<li>U+2330 TOTAL RUNOUT: try adding symbols</li>
<li>U+2331 DIMENSION ORIGIN: try adding symbols</li>
<li>U+2332 CONICAL TAPER: try adding symbols</li>
<li>U+2333 SLOPE: try adding symbols</li>
<li>U+2334 COUNTERBORE: try adding symbols</li>
<li>U+2335 COUNTERSINK: try adding symbols</li>
<li>U+237C RIGHT ANGLE WITH DOWNWARDS ZIGZAG ARROW: try adding one of: symbols, math</li>
<li>U+2380 INSERTION SYMBOL: try adding symbols</li>
<li>U+2381 CONTINUOUS UNDERLINE SYMBOL: try adding symbols</li>
<li>U+2382 DISCONTINUOUS UNDERLINE SYMBOL: try adding symbols</li>
<li>U+2383 EMPHASIS SYMBOL: try adding symbols</li>
<li>U+2384 COMPOSITION SYMBOL: try adding symbols</li>
<li>U+2385 WHITE SQUARE WITH CENTRE VERTICAL LINE: try adding symbols</li>
<li>U+2386 ENTER SYMBOL: try adding symbols</li>
<li>U+2387 ALTERNATIVE KEY SYMBOL: try adding symbols</li>
<li>U+2388 HELM SYMBOL: try adding symbols</li>
<li>U+2389 CIRCLED HORIZONTAL BAR WITH NOTCH: try adding symbols</li>
<li>U+238A CIRCLED TRIANGLE DOWN: try adding symbols</li>
<li>U+238B BROKEN CIRCLE WITH NORTHWEST ARROW: try adding symbols</li>
<li>U+238C UNDO SYMBOL: try adding symbols</li>
<li>U+238D MONOSTABLE SYMBOL: try adding symbols</li>
<li>U+238E HYSTERESIS SYMBOL: try adding symbols</li>
<li>U+238F OPEN-CIRCUIT-OUTPUT H-TYPE SYMBOL: try adding symbols</li>
<li>U+2390 OPEN-CIRCUIT-OUTPUT L-TYPE SYMBOL: try adding symbols</li>
<li>U+2391 PASSIVE-PULL-DOWN-OUTPUT SYMBOL: try adding symbols</li>
<li>U+2392 PASSIVE-PULL-UP-OUTPUT SYMBOL: try adding symbols</li>
<li>U+2393 DIRECT CURRENT SYMBOL FORM TWO: try adding symbols</li>
<li>U+2394 SOFTWARE-FUNCTION SYMBOL: try adding symbols</li>
<li>U+2396 DECIMAL SEPARATOR KEY SYMBOL: try adding symbols</li>
<li>U+2397 PREVIOUS PAGE: try adding symbols</li>
<li>U+2398 NEXT PAGE: try adding symbols</li>
<li>U+2399 PRINT SCREEN SYMBOL: try adding symbols</li>
<li>U+239A CLEAR SCREEN SYMBOL: try adding symbols</li>
<li>U+23AF HORIZONTAL LINE EXTENSION: try adding one of: symbols, math</li>
<li>U+23BE DENTISTRY SYMBOL LIGHT VERTICAL AND TOP RIGHT: try adding symbols</li>
<li>U+23BF DENTISTRY SYMBOL LIGHT VERTICAL AND BOTTOM RIGHT: try adding symbols</li>
<li>U+23C0 DENTISTRY SYMBOL LIGHT VERTICAL WITH CIRCLE: try adding symbols</li>
<li>U+23C1 DENTISTRY SYMBOL LIGHT DOWN AND HORIZONTAL WITH CIRCLE: try adding symbols</li>
<li>U+23C2 DENTISTRY SYMBOL LIGHT UP AND HORIZONTAL WITH CIRCLE: try adding symbols</li>
<li>U+23C3 DENTISTRY SYMBOL LIGHT VERTICAL WITH TRIANGLE: try adding symbols</li>
<li>U+23C4 DENTISTRY SYMBOL LIGHT DOWN AND HORIZONTAL WITH TRIANGLE: try adding symbols</li>
<li>U+23C5 DENTISTRY SYMBOL LIGHT UP AND HORIZONTAL WITH TRIANGLE: try adding symbols</li>
<li>U+23C6 DENTISTRY SYMBOL LIGHT VERTICAL AND WAVE: try adding symbols</li>
<li>U+23C7 DENTISTRY SYMBOL LIGHT DOWN AND HORIZONTAL WITH WAVE: try adding symbols</li>
<li>U+23C8 DENTISTRY SYMBOL LIGHT UP AND HORIZONTAL WITH WAVE: try adding symbols</li>
<li>U+23C9 DENTISTRY SYMBOL LIGHT DOWN AND HORIZONTAL: try adding symbols</li>
<li>U+23CA DENTISTRY SYMBOL LIGHT UP AND HORIZONTAL: try adding symbols</li>
<li>U+23CB DENTISTRY SYMBOL LIGHT VERTICAL AND TOP LEFT: try adding symbols</li>
<li>U+23CC DENTISTRY SYMBOL LIGHT VERTICAL AND BOTTOM LEFT: try adding symbols</li>
<li>U+23CD SQUARE FOOT: try adding symbols</li>
<li>U+23D0 VERTICAL LINE EXTENSION: try adding one of: symbols, math</li>
<li>U+23D1 METRICAL BREVE: try adding symbols</li>
<li>U+23D2 METRICAL LONG OVER SHORT: try adding symbols</li>
<li>U+23D3 METRICAL SHORT OVER LONG: try adding symbols</li>
<li>U+23D4 METRICAL LONG OVER TWO SHORTS: try adding symbols</li>
<li>U+23D5 METRICAL TWO SHORTS OVER LONG: try adding symbols</li>
<li>U+23D6 METRICAL TWO SHORTS JOINED: try adding symbols</li>
<li>U+23D7 METRICAL TRISEME: try adding symbols</li>
<li>U+23D8 METRICAL TETRASEME: try adding symbols</li>
<li>U+23D9 METRICAL PENTASEME: try adding symbols</li>
<li>U+23DA EARTH GROUND: try adding symbols</li>
<li>U+23DB FUSE: try adding symbols</li>
<li>U+23E2 WHITE TRAPEZIUM: try adding symbols</li>
<li>U+23E3 BENZENE RING WITH CIRCLE: try adding symbols</li>
<li>U+23E4 STRAIGHTNESS: try adding symbols</li>
<li>U+23E5 FLATNESS: try adding symbols</li>
<li>U+23E6 AC CURRENT: try adding symbols</li>
<li>U+23E7 ELECTRICAL INTERSECTION: try adding symbols</li>
<li>U+23E8 DECIMAL EXPONENT SYMBOL: try adding symbols</li>
<li>U+2460 CIRCLED DIGIT ONE: try adding one of: symbols, mongolian, yi</li>
<li>U+2461 CIRCLED DIGIT TWO: try adding one of: symbols, mongolian, yi</li>
<li>U+2462 CIRCLED DIGIT THREE: try adding one of: symbols, mongolian, yi</li>
<li>U+2463 CIRCLED DIGIT FOUR: try adding one of: symbols, mongolian, yi</li>
<li>U+2464 CIRCLED DIGIT FIVE: try adding one of: symbols, mongolian, yi</li>
<li>U+2465 CIRCLED DIGIT SIX: try adding one of: symbols, mongolian, yi</li>
<li>U+2466 CIRCLED DIGIT SEVEN: try adding one of: symbols, mongolian, yi</li>
<li>U+2467 CIRCLED DIGIT EIGHT: try adding one of: symbols, mongolian, yi</li>
<li>U+2468 CIRCLED DIGIT NINE: try adding one of: symbols, mongolian, yi</li>
<li>U+2469 CIRCLED NUMBER TEN: try adding one of: symbols, mongolian, yi</li>
<li>U+246A CIRCLED NUMBER ELEVEN: try adding one of: symbols, mongolian, yi</li>
<li>U+246B CIRCLED NUMBER TWELVE: try adding one of: symbols, mongolian, yi</li>
<li>U+246C CIRCLED NUMBER THIRTEEN: try adding one of: symbols, mongolian, yi</li>
<li>U+246D CIRCLED NUMBER FOURTEEN: try adding one of: symbols, mongolian, yi</li>
<li>U+246E CIRCLED NUMBER FIFTEEN: try adding one of: symbols, mongolian, yi</li>
<li>U+246F CIRCLED NUMBER SIXTEEN: try adding one of: symbols, mongolian, yi</li>
<li>U+2470 CIRCLED NUMBER SEVENTEEN: try adding one of: symbols, mongolian, yi</li>
<li>U+2471 CIRCLED NUMBER EIGHTEEN: try adding one of: symbols, mongolian, yi</li>
<li>U+2472 CIRCLED NUMBER NINETEEN: try adding one of: symbols, mongolian, yi</li>
<li>U+2473 CIRCLED NUMBER TWENTY: try adding one of: symbols, mongolian, yi</li>
<li>U+2474 PARENTHESIZED DIGIT ONE: try adding one of: symbols, math</li>
<li>U+2475 PARENTHESIZED DIGIT TWO: try adding one of: symbols, math</li>
<li>U+2476 PARENTHESIZED DIGIT THREE: try adding symbols</li>
<li>U+2477 PARENTHESIZED DIGIT FOUR: try adding symbols</li>
<li>U+2478 PARENTHESIZED DIGIT FIVE: try adding symbols</li>
<li>U+2479 PARENTHESIZED DIGIT SIX: try adding symbols</li>
<li>U+247A PARENTHESIZED DIGIT SEVEN: try adding symbols</li>
<li>U+247B PARENTHESIZED DIGIT EIGHT: try adding symbols</li>
<li>U+247C PARENTHESIZED DIGIT NINE: try adding symbols</li>
<li>U+247D PARENTHESIZED NUMBER TEN: try adding symbols</li>
<li>U+247E PARENTHESIZED NUMBER ELEVEN: try adding symbols</li>
<li>U+247F PARENTHESIZED NUMBER TWELVE: try adding symbols</li>
<li>U+2480 PARENTHESIZED NUMBER THIRTEEN: try adding symbols</li>
<li>U+2481 PARENTHESIZED NUMBER FOURTEEN: try adding symbols</li>
<li>U+2482 PARENTHESIZED NUMBER FIFTEEN: try adding symbols</li>
<li>U+2483 PARENTHESIZED NUMBER SIXTEEN: try adding symbols</li>
<li>U+2484 PARENTHESIZED NUMBER SEVENTEEN: try adding symbols</li>
<li>U+2485 PARENTHESIZED NUMBER EIGHTEEN: try adding symbols</li>
<li>U+2486 PARENTHESIZED NUMBER NINETEEN: try adding symbols</li>
<li>U+2487 PARENTHESIZED NUMBER TWENTY: try adding symbols</li>
<li>U+2488 DIGIT ONE FULL STOP: try adding symbols</li>
<li>U+2489 DIGIT TWO FULL STOP: try adding symbols</li>
<li>U+248A DIGIT THREE FULL STOP: try adding symbols</li>
<li>U+248B DIGIT FOUR FULL STOP: try adding symbols</li>
<li>U+248C DIGIT FIVE FULL STOP: try adding symbols</li>
<li>U+248D DIGIT SIX FULL STOP: try adding symbols</li>
<li>U+248E DIGIT SEVEN FULL STOP: try adding symbols</li>
<li>U+248F DIGIT EIGHT FULL STOP: try adding symbols</li>
<li>U+2490 DIGIT NINE FULL STOP: try adding symbols</li>
<li>U+2491 NUMBER TEN FULL STOP: try adding symbols</li>
<li>U+2492 NUMBER ELEVEN FULL STOP: try adding symbols</li>
<li>U+2493 NUMBER TWELVE FULL STOP: try adding symbols</li>
<li>U+2494 NUMBER THIRTEEN FULL STOP: try adding symbols</li>
<li>U+2495 NUMBER FOURTEEN FULL STOP: try adding symbols</li>
<li>U+2496 NUMBER FIFTEEN FULL STOP: try adding symbols</li>
<li>U+2497 NUMBER SIXTEEN FULL STOP: try adding symbols</li>
<li>U+2498 NUMBER SEVENTEEN FULL STOP: try adding symbols</li>
<li>U+2499 NUMBER EIGHTEEN FULL STOP: try adding symbols</li>
<li>U+249A NUMBER NINETEEN FULL STOP: try adding symbols</li>
<li>U+249B NUMBER TWENTY FULL STOP: try adding symbols</li>
<li>U+249C PARENTHESIZED LATIN SMALL LETTER A: try adding symbols</li>
<li>U+249D PARENTHESIZED LATIN SMALL LETTER B: try adding symbols</li>
<li>U+249E PARENTHESIZED LATIN SMALL LETTER C: try adding symbols</li>
<li>U+249F PARENTHESIZED LATIN SMALL LETTER D: try adding symbols</li>
<li>U+24A0 PARENTHESIZED LATIN SMALL LETTER E: try adding symbols</li>
<li>U+24A1 PARENTHESIZED LATIN SMALL LETTER F: try adding symbols</li>
<li>U+24A2 PARENTHESIZED LATIN SMALL LETTER G: try adding symbols</li>
<li>U+24A3 PARENTHESIZED LATIN SMALL LETTER H: try adding symbols</li>
<li>U+24A4 PARENTHESIZED LATIN SMALL LETTER I: try adding symbols</li>
<li>U+24A5 PARENTHESIZED LATIN SMALL LETTER J: try adding symbols</li>
<li>U+24A6 PARENTHESIZED LATIN SMALL LETTER K: try adding symbols</li>
<li>U+24A7 PARENTHESIZED LATIN SMALL LETTER L: try adding symbols</li>
<li>U+24A8 PARENTHESIZED LATIN SMALL LETTER M: try adding symbols</li>
<li>U+24A9 PARENTHESIZED LATIN SMALL LETTER N: try adding symbols</li>
<li>U+24AA PARENTHESIZED LATIN SMALL LETTER O: try adding symbols</li>
<li>U+24AB PARENTHESIZED LATIN SMALL LETTER P: try adding symbols</li>
<li>U+24AC PARENTHESIZED LATIN SMALL LETTER Q: try adding symbols</li>
<li>U+24AD PARENTHESIZED LATIN SMALL LETTER R: try adding symbols</li>
<li>U+24AE PARENTHESIZED LATIN SMALL LETTER S: try adding symbols</li>
<li>U+24AF PARENTHESIZED LATIN SMALL LETTER T: try adding symbols</li>
<li>U+24B0 PARENTHESIZED LATIN SMALL LETTER U: try adding symbols</li>
<li>U+24B1 PARENTHESIZED LATIN SMALL LETTER V: try adding symbols</li>
<li>U+24B2 PARENTHESIZED LATIN SMALL LETTER W: try adding symbols</li>
<li>U+24B3 PARENTHESIZED LATIN SMALL LETTER X: try adding symbols</li>
<li>U+24B4 PARENTHESIZED LATIN SMALL LETTER Y: try adding symbols</li>
<li>U+24B5 PARENTHESIZED LATIN SMALL LETTER Z: try adding symbols</li>
<li>U+24B6 CIRCLED LATIN CAPITAL LETTER A: try adding symbols</li>
<li>U+24B7 CIRCLED LATIN CAPITAL LETTER B: try adding symbols</li>
<li>U+24B8 CIRCLED LATIN CAPITAL LETTER C: try adding symbols</li>
<li>U+24B9 CIRCLED LATIN CAPITAL LETTER D: try adding symbols</li>
<li>U+24BA CIRCLED LATIN CAPITAL LETTER E: try adding symbols</li>
<li>U+24BB CIRCLED LATIN CAPITAL LETTER F: try adding symbols</li>
<li>U+24BC CIRCLED LATIN CAPITAL LETTER G: try adding symbols</li>
<li>U+24BD CIRCLED LATIN CAPITAL LETTER H: try adding symbols</li>
<li>U+24BE CIRCLED LATIN CAPITAL LETTER I: try adding symbols</li>
<li>U+24BF CIRCLED LATIN CAPITAL LETTER J: try adding symbols</li>
<li>U+24C0 CIRCLED LATIN CAPITAL LETTER K: try adding symbols</li>
<li>U+24C1 CIRCLED LATIN CAPITAL LETTER L: try adding symbols</li>
<li>U+24C2 CIRCLED LATIN CAPITAL LETTER M: try adding symbols</li>
<li>U+24C3 CIRCLED LATIN CAPITAL LETTER N: try adding symbols</li>
<li>U+24C4 CIRCLED LATIN CAPITAL LETTER O: try adding symbols</li>
<li>U+24C5 CIRCLED LATIN CAPITAL LETTER P: try adding symbols</li>
<li>U+24C6 CIRCLED LATIN CAPITAL LETTER Q: try adding symbols</li>
<li>U+24C7 CIRCLED LATIN CAPITAL LETTER R: try adding symbols</li>
<li>U+24C8 CIRCLED LATIN CAPITAL LETTER S: try adding symbols</li>
<li>U+24C9 CIRCLED LATIN CAPITAL LETTER T: try adding symbols</li>
<li>U+24CA CIRCLED LATIN CAPITAL LETTER U: try adding symbols</li>
<li>U+24CB CIRCLED LATIN CAPITAL LETTER V: try adding symbols</li>
<li>U+24CC CIRCLED LATIN CAPITAL LETTER W: try adding symbols</li>
<li>U+24CD CIRCLED LATIN CAPITAL LETTER X: try adding symbols</li>
<li>U+24CE CIRCLED LATIN CAPITAL LETTER Y: try adding symbols</li>
<li>U+24CF CIRCLED LATIN CAPITAL LETTER Z: try adding symbols</li>
<li>U+24D0 CIRCLED LATIN SMALL LETTER A: try adding symbols</li>
<li>U+24D1 CIRCLED LATIN SMALL LETTER B: try adding symbols</li>
<li>U+24D2 CIRCLED LATIN SMALL LETTER C: try adding symbols</li>
<li>U+24D3 CIRCLED LATIN SMALL LETTER D: try adding symbols</li>
<li>U+24D4 CIRCLED LATIN SMALL LETTER E: try adding symbols</li>
<li>U+24D5 CIRCLED LATIN SMALL LETTER F: try adding symbols</li>
<li>U+24D6 CIRCLED LATIN SMALL LETTER G: try adding symbols</li>
<li>U+24D7 CIRCLED LATIN SMALL LETTER H: try adding symbols</li>
<li>U+24D8 CIRCLED LATIN SMALL LETTER I: try adding symbols</li>
<li>U+24D9 CIRCLED LATIN SMALL LETTER J: try adding symbols</li>
<li>U+24DA CIRCLED LATIN SMALL LETTER K: try adding symbols</li>
<li>U+24DB CIRCLED LATIN SMALL LETTER L: try adding symbols</li>
<li>U+24DC CIRCLED LATIN SMALL LETTER M: try adding symbols</li>
<li>U+24DD CIRCLED LATIN SMALL LETTER N: try adding symbols</li>
<li>U+24DE CIRCLED LATIN SMALL LETTER O: try adding symbols</li>
<li>U+24DF CIRCLED LATIN SMALL LETTER P: try adding symbols</li>
<li>U+24E0 CIRCLED LATIN SMALL LETTER Q: try adding symbols</li>
<li>U+24E1 CIRCLED LATIN SMALL LETTER R: try adding symbols</li>
<li>U+24E2 CIRCLED LATIN SMALL LETTER S: try adding symbols</li>
<li>U+24E3 CIRCLED LATIN SMALL LETTER T: try adding symbols</li>
<li>U+24E4 CIRCLED LATIN SMALL LETTER U: try adding symbols</li>
<li>U+24E5 CIRCLED LATIN SMALL LETTER V: try adding symbols</li>
<li>U+24E6 CIRCLED LATIN SMALL LETTER W: try adding symbols</li>
<li>U+24E7 CIRCLED LATIN SMALL LETTER X: try adding symbols</li>
<li>U+24E8 CIRCLED LATIN SMALL LETTER Y: try adding symbols</li>
<li>U+24E9 CIRCLED LATIN SMALL LETTER Z: try adding symbols</li>
<li>U+24EA CIRCLED DIGIT ZERO: try adding symbols</li>
<li>U+24EB NEGATIVE CIRCLED NUMBER ELEVEN: try adding symbols</li>
<li>U+24EC NEGATIVE CIRCLED NUMBER TWELVE: try adding symbols</li>
<li>U+24ED NEGATIVE CIRCLED NUMBER THIRTEEN: try adding symbols</li>
<li>U+24EE NEGATIVE CIRCLED NUMBER FOURTEEN: try adding symbols</li>
<li>U+24EF NEGATIVE CIRCLED NUMBER FIFTEEN: try adding symbols</li>
<li>U+24F0 NEGATIVE CIRCLED NUMBER SIXTEEN: try adding symbols</li>
<li>U+24F1 NEGATIVE CIRCLED NUMBER SEVENTEEN: try adding symbols</li>
<li>U+24F2 NEGATIVE CIRCLED NUMBER EIGHTEEN: try adding symbols</li>
<li>U+24F3 NEGATIVE CIRCLED NUMBER NINETEEN: try adding symbols</li>
<li>U+24F4 NEGATIVE CIRCLED NUMBER TWENTY: try adding symbols</li>
<li>U+24F5 DOUBLE CIRCLED DIGIT ONE: try adding symbols</li>
<li>U+24F6 DOUBLE CIRCLED DIGIT TWO: try adding symbols</li>
<li>U+24F7 DOUBLE CIRCLED DIGIT THREE: try adding symbols</li>
<li>U+24F8 DOUBLE CIRCLED DIGIT FOUR: try adding symbols</li>
<li>U+24F9 DOUBLE CIRCLED DIGIT FIVE: try adding symbols</li>
<li>U+24FA DOUBLE CIRCLED DIGIT SIX: try adding symbols</li>
<li>U+24FB DOUBLE CIRCLED DIGIT SEVEN: try adding symbols</li>
<li>U+24FC DOUBLE CIRCLED DIGIT EIGHT: try adding symbols</li>
<li>U+24FD DOUBLE CIRCLED DIGIT NINE: try adding symbols</li>
<li>U+24FE DOUBLE CIRCLED NUMBER TEN: try adding symbols</li>
<li>U+24FF NEGATIVE CIRCLED DIGIT ZERO: try adding symbols</li>
<li>U+25CC DOTTED CIRCLE: try adding one of: phags-pa, duployan, thaana, mongolian, brahmi, thai, mahajani, hebrew, canadian-aboriginal, devanagari, old-permic, yi, balinese, zanabazar-square, tai-tham, tai-viet, elbasan, buginese, khmer, hanifi-rohingya, bhaiksuki, dogra, tagalog, osage, tibetan, armenian, sharada, bengali, modi, psalter-pahlavi, tamil, manichaean, warang-citi, mandaic, new-tai-lue, ahom, adlam, soyombo, coptic, miao, mende-kikakui, oriya, hanunoo, malayalam, buhid, grantha, music, syloti-nagri, sogdian, masaram-gondi, lepcha, saurashtra, batak, cham, bassa-vah, gunjala-gondi, tirhuta, kayah-li, gurmukhi, pahawh-hmong, kaithi, wancho, siddham, newa, math, sinhala, kharoshthi, rejang, tai-le, gujarati, meetei-mayek, limbu, myanmar, chakma, symbols, takri, telugu, lao, khudawadi, caucasian-albanian, tifinagh, javanese, tagbanwa, marchen, nko, sundanese, kannada, syriac, khojki</li>
<li>U+260A ASCENDING NODE: try adding symbols</li>
<li>U+260B DESCENDING NODE: try adding symbols</li>
<li>U+260C CONJUNCTION: try adding symbols</li>
<li>U+260D OPPOSITION: try adding symbols</li>
<li>U+2613 SALTIRE: try adding symbols</li>
<li>U+2624 CADUCEUS: try adding symbols</li>
<li>U+2625 ANKH: try adding symbols</li>
<li>U+2626 ORTHODOX CROSS: try adding symbols</li>
<li>U+2627 CHI RHO: try adding symbols</li>
<li>U+2628 CROSS OF LORRAINE: try adding symbols</li>
<li>U+2629 CROSS OF JERUSALEM: try adding symbols</li>
<li>U+262A STAR AND CRESCENT: try adding symbols</li>
<li>U+262B FARSI SYMBOL: try adding symbols</li>
<li>U+262C ADI SHAKTI: try adding one of: symbols, gurmukhi</li>
<li>U+262D HAMMER AND SICKLE: try adding symbols</li>
<li>U+262E PEACE SYMBOL: try adding symbols</li>
<li>U+262F YIN YANG: try adding symbols</li>
<li>U+2638 WHEEL OF DHARMA: try adding symbols</li>
<li>U+2639 WHITE FROWNING FACE: try adding symbols</li>
<li>U+263A WHITE SMILING FACE: try adding symbols</li>
<li>U+263B BLACK SMILING FACE: try adding symbols</li>
<li>U+263D FIRST QUARTER MOON: try adding symbols</li>
<li>U+263E LAST QUARTER MOON: try adding symbols</li>
<li>U+263F MERCURY: try adding symbols</li>
<li>U+2640 FEMALE SIGN: try adding symbols</li>
<li>U+2641 EARTH: try adding symbols</li>
<li>U+2642 MALE SIGN: try adding symbols</li>
<li>U+2643 JUPITER: try adding symbols</li>
<li>U+2644 SATURN: try adding symbols</li>
<li>U+2645 URANUS: try adding symbols</li>
<li>U+2646 NEPTUNE: try adding symbols</li>
<li>U+2647 PLUTO: try adding symbols</li>
<li>U+2648 ARIES: try adding symbols</li>
<li>U+2649 TAURUS: try adding symbols</li>
<li>U+264A GEMINI: try adding symbols</li>
<li>U+264B CANCER: try adding symbols</li>
<li>U+264C LEO: try adding symbols</li>
<li>U+264D VIRGO: try adding symbols</li>
<li>U+264E LIBRA: try adding symbols</li>
<li>U+264F SCORPIUS: try adding symbols</li>
<li>U+2650 SAGITTARIUS: try adding symbols</li>
<li>U+2651 CAPRICORN: try adding symbols</li>
<li>U+2652 AQUARIUS: try adding symbols</li>
<li>U+2653 PISCES: try adding symbols</li>
<li>U+2669 QUARTER NOTE: try adding one of: music, symbols</li>
<li>U+266A EIGHTH NOTE: try adding one of: music, symbols</li>
<li>U+266B BEAMED EIGHTH NOTES: try adding one of: music, symbols</li>
<li>U+266C BEAMED SIXTEENTH NOTES: try adding one of: music, symbols</li>
<li>U+266D MUSIC FLAT SIGN: try adding one of: music, symbols, math</li>
<li>U+266E MUSIC NATURAL SIGN: try adding one of: music, symbols, math</li>
<li>U+266F MUSIC SHARP SIGN: try adding one of: music, symbols, math</li>
<li>U+2670 WEST SYRIAC CROSS: try adding one of: symbols, syriac</li>
<li>U+2671 EAST SYRIAC CROSS: try adding one of: symbols, syriac</li>
<li>U+2672 UNIVERSAL RECYCLING SYMBOL: try adding symbols</li>
<li>U+2673 RECYCLING SYMBOL FOR TYPE-1 PLASTICS: try adding symbols</li>
<li>U+2674 RECYCLING SYMBOL FOR TYPE-2 PLASTICS: try adding symbols</li>
<li>U+2675 RECYCLING SYMBOL FOR TYPE-3 PLASTICS: try adding symbols</li>
<li>U+2676 RECYCLING SYMBOL FOR TYPE-4 PLASTICS: try adding symbols</li>
<li>U+2677 RECYCLING SYMBOL FOR TYPE-5 PLASTICS: try adding symbols</li>
<li>U+2678 RECYCLING SYMBOL FOR TYPE-6 PLASTICS: try adding symbols</li>
<li>U+2679 RECYCLING SYMBOL FOR TYPE-7 PLASTICS: try adding symbols</li>
<li>U+267A RECYCLING SYMBOL FOR GENERIC MATERIALS: try adding symbols</li>
<li>U+267B BLACK UNIVERSAL RECYCLING SYMBOL: try adding symbols</li>
<li>U+267C RECYCLED PAPER SYMBOL: try adding symbols</li>
<li>U+267D PARTIALLY-RECYCLED PAPER SYMBOL: try adding symbols</li>
<li>U+267E PERMANENT PAPER SIGN: try adding symbols</li>
<li>U+2690 WHITE FLAG: try adding symbols</li>
<li>U+2691 BLACK FLAG: try adding symbols</li>
<li>U+2692 HAMMER AND PICK: try adding symbols</li>
<li>U+2693 ANCHOR: try adding symbols</li>
<li>U+2694 CROSSED SWORDS: try adding symbols</li>
<li>U+2695 STAFF OF AESCULAPIUS: try adding symbols</li>
<li>U+2696 SCALES: try adding symbols</li>
<li>U+2697 ALEMBIC: try adding symbols</li>
<li>U+2698 FLOWER: try adding symbols</li>
<li>U+2699 GEAR: try adding symbols</li>
<li>U+269A STAFF OF HERMES: try adding symbols</li>
<li>U+269B ATOM SYMBOL: try adding symbols</li>
<li>U+269C FLEUR-DE-LIS: try adding symbols</li>
<li>U+269D OUTLINED WHITE STAR: try adding symbols</li>
<li>U+26A2 DOUBLED FEMALE SIGN: try adding symbols</li>
<li>U+26A3 DOUBLED MALE SIGN: try adding symbols</li>
<li>U+26A4 INTERLOCKED FEMALE AND MALE SIGN: try adding symbols</li>
<li>U+26A5 MALE AND FEMALE SIGN: try adding symbols</li>
<li>U+26A6 MALE WITH STROKE SIGN: try adding symbols</li>
<li>U+26A7 MALE WITH STROKE AND MALE AND FEMALE SIGN: try adding symbols</li>
<li>U+26A8 VERTICAL MALE WITH STROKE SIGN: try adding symbols</li>
<li>U+26A9 HORIZONTAL MALE WITH STROKE SIGN: try adding symbols</li>
<li>U+26AD MARRIAGE SYMBOL: try adding symbols</li>
<li>U+26AE DIVORCE SYMBOL: try adding symbols</li>
<li>U+26AF UNMARRIED PARTNERSHIP SYMBOL: try adding symbols</li>
<li>U+26B0 COFFIN: try adding symbols</li>
<li>U+26B1 FUNERAL URN: try adding symbols</li>
<li>U+26B2 NEUTER: try adding symbols</li>
<li>U+26B3 CERES: try adding symbols</li>
<li>U+26B4 PALLAS: try adding symbols</li>
<li>U+26B5 JUNO: try adding symbols</li>
<li>U+26B6 VESTA: try adding symbols</li>
<li>U+26B7 CHIRON: try adding symbols</li>
<li>U+26B8 BLACK MOON LILITH: try adding symbols</li>
<li>U+26B9 SEXTILE: try adding symbols</li>
<li>U+26BA SEMISEXTILE: try adding symbols</li>
<li>U+26BB QUINCUNX: try adding symbols</li>
<li>U+26BC SESQUIQUADRATE: try adding symbols</li>
<li>U+26CE OPHIUCHUS: try adding symbols</li>
<li>U+26E2 ASTRONOMICAL SYMBOL FOR URANUS: try adding symbols</li>
<li>U+26E3 HEAVY CIRCLE WITH STROKE AND TWO DOTS ABOVE: try adding symbols</li>
<li>U+26E4 PENTAGRAM: try adding symbols</li>
<li>U+26E5 RIGHT-HANDED INTERLACED PENTAGRAM: try adding symbols</li>
<li>U+26E6 LEFT-HANDED INTERLACED PENTAGRAM: try adding symbols</li>
<li>U+26E7 INVERTED PENTAGRAM: try adding symbols</li>
<li>U+26E8 BLACK CROSS ON SHIELD: try adding symbols</li>
<li>U+26E9 SHINTO SHRINE: try adding symbols</li>
<li>U+26EA CHURCH: try adding symbols</li>
<li>U+26EB CASTLE: try adding symbols</li>
<li>U+26EC HISTORIC SITE: try adding symbols</li>
<li>U+26ED GEAR WITHOUT HUB: try adding symbols</li>
<li>U+26EE GEAR WITH HANDLES: try adding symbols</li>
<li>U+26EF MAP SYMBOL FOR LIGHTHOUSE: try adding symbols</li>
<li>U+26F0 MOUNTAIN: try adding symbols</li>
<li>U+26F1 UMBRELLA ON GROUND: try adding symbols</li>
<li>U+26F2 FOUNTAIN: try adding symbols</li>
<li>U+26F3 FLAG IN HOLE: try adding symbols</li>
<li>U+26F4 FERRY: try adding symbols</li>
<li>U+26F5 SAILBOAT: try adding symbols</li>
<li>U+26F6 SQUARE FOUR CORNERS: try adding symbols</li>
<li>U+26F7 SKIER: try adding symbols</li>
<li>U+26F8 ICE SKATE: try adding symbols</li>
<li>U+26F9 PERSON WITH BALL: try adding symbols</li>
<li>U+26FA TENT: try adding symbols</li>
<li>U+26FB JAPANESE BANK SYMBOL: try adding symbols</li>
<li>U+26FC HEADSTONE GRAVEYARD SYMBOL: try adding symbols</li>
<li>U+26FD FUEL PUMP: try adding symbols</li>
<li>U+26FE CUP ON BLACK SQUARE: try adding symbols</li>
<li>U+26FF WHITE FLAG WITH HORIZONTAL MIDDLE BLACK STRIPE: try adding symbols</li>
<li>U+271D LATIN CROSS: try adding symbols</li>
<li>U+271E SHADOWED WHITE LATIN CROSS: try adding symbols</li>
<li>U+271F OUTLINED LATIN CROSS: try adding symbols</li>
<li>U+2720 MALTESE CROSS: try adding symbols</li>
<li>U+2721 STAR OF DAVID: try adding symbols</li>
<li>U+2776 DINGBAT NEGATIVE CIRCLED DIGIT ONE: try adding symbols</li>
<li>U+2777 DINGBAT NEGATIVE CIRCLED DIGIT TWO: try adding symbols</li>
<li>U+2778 DINGBAT NEGATIVE CIRCLED DIGIT THREE: try adding symbols</li>
<li>U+2779 DINGBAT NEGATIVE CIRCLED DIGIT FOUR: try adding symbols</li>
<li>U+277A DINGBAT NEGATIVE CIRCLED DIGIT FIVE: try adding symbols</li>
<li>U+277B DINGBAT NEGATIVE CIRCLED DIGIT SIX: try adding symbols</li>
<li>U+277C DINGBAT NEGATIVE CIRCLED DIGIT SEVEN: try adding symbols</li>
<li>U+277D DINGBAT NEGATIVE CIRCLED DIGIT EIGHT: try adding symbols</li>
<li>U+277E DINGBAT NEGATIVE CIRCLED DIGIT NINE: try adding symbols</li>
<li>U+277F DINGBAT NEGATIVE CIRCLED NUMBER TEN: try adding symbols</li>
<li>U+2780 DINGBAT CIRCLED SANS-SERIF DIGIT ONE: try adding symbols</li>
<li>U+2781 DINGBAT CIRCLED SANS-SERIF DIGIT TWO: try adding symbols</li>
<li>U+2782 DINGBAT CIRCLED SANS-SERIF DIGIT THREE: try adding symbols</li>
<li>U+2783 DINGBAT CIRCLED SANS-SERIF DIGIT FOUR: try adding symbols</li>
<li>U+2784 DINGBAT CIRCLED SANS-SERIF DIGIT FIVE: try adding symbols</li>
<li>U+2785 DINGBAT CIRCLED SANS-SERIF DIGIT SIX: try adding symbols</li>
<li>U+2786 DINGBAT CIRCLED SANS-SERIF DIGIT SEVEN: try adding symbols</li>
<li>U+2787 DINGBAT CIRCLED SANS-SERIF DIGIT EIGHT: try adding symbols</li>
<li>U+2788 DINGBAT CIRCLED SANS-SERIF DIGIT NINE: try adding symbols</li>
<li>U+2789 DINGBAT CIRCLED SANS-SERIF NUMBER TEN: try adding symbols</li>
<li>U+278A DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT ONE: try adding symbols</li>
<li>U+278B DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT TWO: try adding symbols</li>
<li>U+278C DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT THREE: try adding symbols</li>
<li>U+278D DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT FOUR: try adding symbols</li>
<li>U+278E DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT FIVE: try adding symbols</li>
<li>U+278F DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT SIX: try adding symbols</li>
<li>U+2790 DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT SEVEN: try adding symbols</li>
<li>U+2791 DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT EIGHT: try adding symbols</li>
<li>U+2792 DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT NINE: try adding symbols</li>
<li>U+2793 DINGBAT NEGATIVE CIRCLED SANS-SERIF NUMBER TEN: try adding symbols</li>
<li>U+2921 NORTH WEST AND SOUTH EAST ARROW: try adding one of: symbols, math</li>
<li>U+2922 NORTH EAST AND SOUTH WEST ARROW: try adding one of: symbols, math</li>
<li>U+1F100 DIGIT ZERO FULL STOP: try adding symbols</li>
<li>U+1F101 DIGIT ZERO COMMA: try adding symbols</li>
<li>U+1F102 DIGIT ONE COMMA: try adding symbols</li>
<li>U+1F103 DIGIT TWO COMMA: try adding symbols</li>
<li>U+1F104 DIGIT THREE COMMA: try adding symbols</li>
<li>U+1F105 DIGIT FOUR COMMA: try adding symbols</li>
<li>U+1F106 DIGIT FIVE COMMA: try adding symbols</li>
<li>U+1F107 DIGIT SIX COMMA: try adding symbols</li>
<li>U+1F108 DIGIT SEVEN COMMA: try adding symbols</li>
<li>U+1F109 DIGIT EIGHT COMMA: try adding symbols</li>
<li>U+1F10A DIGIT NINE COMMA: try adding symbols</li>
<li>U+1F10B DINGBAT CIRCLED SANS-SERIF DIGIT ZERO: try adding symbols</li>
<li>U+1F10C DINGBAT NEGATIVE CIRCLED SANS-SERIF DIGIT ZERO: try adding symbols</li>
<li>U+1F110 PARENTHESIZED LATIN CAPITAL LETTER A: try adding symbols</li>
<li>U+1F111 PARENTHESIZED LATIN CAPITAL LETTER B: try adding symbols</li>
<li>U+1F112 PARENTHESIZED LATIN CAPITAL LETTER C: try adding symbols</li>
<li>U+1F113 PARENTHESIZED LATIN CAPITAL LETTER D: try adding symbols</li>
<li>U+1F114 PARENTHESIZED LATIN CAPITAL LETTER E: try adding symbols</li>
<li>U+1F115 PARENTHESIZED LATIN CAPITAL LETTER F: try adding symbols</li>
<li>U+1F116 PARENTHESIZED LATIN CAPITAL LETTER G: try adding symbols</li>
<li>U+1F117 PARENTHESIZED LATIN CAPITAL LETTER H: try adding symbols</li>
<li>U+1F118 PARENTHESIZED LATIN CAPITAL LETTER I: try adding symbols</li>
<li>U+1F119 PARENTHESIZED LATIN CAPITAL LETTER J: try adding symbols</li>
<li>U+1F11A PARENTHESIZED LATIN CAPITAL LETTER K: try adding symbols</li>
<li>U+1F11B PARENTHESIZED LATIN CAPITAL LETTER L: try adding symbols</li>
<li>U+1F11C PARENTHESIZED LATIN CAPITAL LETTER M: try adding symbols</li>
<li>U+1F11D PARENTHESIZED LATIN CAPITAL LETTER N: try adding symbols</li>
<li>U+1F11E PARENTHESIZED LATIN CAPITAL LETTER O: try adding symbols</li>
<li>U+1F11F PARENTHESIZED LATIN CAPITAL LETTER P: try adding symbols</li>
<li>U+1F120 PARENTHESIZED LATIN CAPITAL LETTER Q: try adding symbols</li>
<li>U+1F121 PARENTHESIZED LATIN CAPITAL LETTER R: try adding symbols</li>
<li>U+1F122 PARENTHESIZED LATIN CAPITAL LETTER S: try adding symbols</li>
<li>U+1F123 PARENTHESIZED LATIN CAPITAL LETTER T: try adding symbols</li>
<li>U+1F124 PARENTHESIZED LATIN CAPITAL LETTER U: try adding symbols</li>
<li>U+1F125 PARENTHESIZED LATIN CAPITAL LETTER V: try adding symbols</li>
<li>U+1F126 PARENTHESIZED LATIN CAPITAL LETTER W: try adding symbols</li>
<li>U+1F127 PARENTHESIZED LATIN CAPITAL LETTER X: try adding symbols</li>
<li>U+1F128 PARENTHESIZED LATIN CAPITAL LETTER Y: try adding symbols</li>
<li>U+1F129 PARENTHESIZED LATIN CAPITAL LETTER Z: try adding symbols</li>
<li>U+1F12A TORTOISE SHELL BRACKETED LATIN CAPITAL LETTER S: try adding symbols</li>
<li>U+1F12B CIRCLED ITALIC LATIN CAPITAL LETTER C: try adding symbols</li>
<li>U+1F12C CIRCLED ITALIC LATIN CAPITAL LETTER R: try adding symbols</li>
<li>U+1F12D CIRCLED CD: try adding symbols</li>
<li>U+1F12E CIRCLED WZ: try adding symbols</li>
<li>U+1F12F COPYLEFT SYMBOL: try adding symbols</li>
<li>U+1F130 SQUARED LATIN CAPITAL LETTER A: try adding symbols</li>
<li>U+1F131 SQUARED LATIN CAPITAL LETTER B: try adding symbols</li>
<li>U+1F132 SQUARED LATIN CAPITAL LETTER C: try adding symbols</li>
<li>U+1F133 SQUARED LATIN CAPITAL LETTER D: try adding symbols</li>
<li>U+1F134 SQUARED LATIN CAPITAL LETTER E: try adding symbols</li>
<li>U+1F135 SQUARED LATIN CAPITAL LETTER F: try adding symbols</li>
<li>U+1F136 SQUARED LATIN CAPITAL LETTER G: try adding symbols</li>
<li>U+1F137 SQUARED LATIN CAPITAL LETTER H: try adding symbols</li>
<li>U+1F138 SQUARED LATIN CAPITAL LETTER I: try adding symbols</li>
<li>U+1F139 SQUARED LATIN CAPITAL LETTER J: try adding symbols</li>
<li>U+1F13A SQUARED LATIN CAPITAL LETTER K: try adding symbols</li>
<li>U+1F13B SQUARED LATIN CAPITAL LETTER L: try adding symbols</li>
<li>U+1F13C SQUARED LATIN CAPITAL LETTER M: try adding symbols</li>
<li>U+1F13D SQUARED LATIN CAPITAL LETTER N: try adding symbols</li>
<li>U+1F13E SQUARED LATIN CAPITAL LETTER O: try adding symbols</li>
<li>U+1F13F SQUARED LATIN CAPITAL LETTER P: try adding symbols</li>
<li>U+1F140 SQUARED LATIN CAPITAL LETTER Q: try adding symbols</li>
<li>U+1F141 SQUARED LATIN CAPITAL LETTER R: try adding symbols</li>
<li>U+1F142 SQUARED LATIN CAPITAL LETTER S: try adding symbols</li>
<li>U+1F143 SQUARED LATIN CAPITAL LETTER T: try adding symbols</li>
<li>U+1F144 SQUARED LATIN CAPITAL LETTER U: try adding symbols</li>
<li>U+1F145 SQUARED LATIN CAPITAL LETTER V: try adding symbols</li>
<li>U+1F146 SQUARED LATIN CAPITAL LETTER W: try adding symbols</li>
<li>U+1F147 SQUARED LATIN CAPITAL LETTER X: try adding symbols</li>
<li>U+1F148 SQUARED LATIN CAPITAL LETTER Y: try adding symbols</li>
<li>U+1F149 SQUARED LATIN CAPITAL LETTER Z: try adding symbols</li>
<li>U+1F14A SQUARED HV: try adding symbols</li>
<li>U+1F14B SQUARED MV: try adding symbols</li>
<li>U+1F14C SQUARED SD: try adding symbols</li>
<li>U+1F14D SQUARED SS: try adding symbols</li>
<li>U+1F14E SQUARED PPV: try adding symbols</li>
<li>U+1F14F SQUARED WC: try adding symbols</li>
<li>U+1F150 NEGATIVE CIRCLED LATIN CAPITAL LETTER A: try adding symbols</li>
<li>U+1F151 NEGATIVE CIRCLED LATIN CAPITAL LETTER B: try adding symbols</li>
<li>U+1F152 NEGATIVE CIRCLED LATIN CAPITAL LETTER C: try adding symbols</li>
<li>U+1F153 NEGATIVE CIRCLED LATIN CAPITAL LETTER D: try adding symbols</li>
<li>U+1F154 NEGATIVE CIRCLED LATIN CAPITAL LETTER E: try adding symbols</li>
<li>U+1F155 NEGATIVE CIRCLED LATIN CAPITAL LETTER F: try adding symbols</li>
<li>U+1F156 NEGATIVE CIRCLED LATIN CAPITAL LETTER G: try adding symbols</li>
<li>U+1F157 NEGATIVE CIRCLED LATIN CAPITAL LETTER H: try adding symbols</li>
<li>U+1F158 NEGATIVE CIRCLED LATIN CAPITAL LETTER I: try adding symbols</li>
<li>U+1F159 NEGATIVE CIRCLED LATIN CAPITAL LETTER J: try adding symbols</li>
<li>U+1F15A NEGATIVE CIRCLED LATIN CAPITAL LETTER K: try adding symbols</li>
<li>U+1F15B NEGATIVE CIRCLED LATIN CAPITAL LETTER L: try adding symbols</li>
<li>U+1F15C NEGATIVE CIRCLED LATIN CAPITAL LETTER M: try adding symbols</li>
<li>U+1F15D NEGATIVE CIRCLED LATIN CAPITAL LETTER N: try adding symbols</li>
<li>U+1F15E NEGATIVE CIRCLED LATIN CAPITAL LETTER O: try adding symbols</li>
<li>U+1F15F NEGATIVE CIRCLED LATIN CAPITAL LETTER P: try adding symbols</li>
<li>U+1F160 NEGATIVE CIRCLED LATIN CAPITAL LETTER Q: try adding symbols</li>
<li>U+1F161 NEGATIVE CIRCLED LATIN CAPITAL LETTER R: try adding symbols</li>
<li>U+1F162 NEGATIVE CIRCLED LATIN CAPITAL LETTER S: try adding symbols</li>
<li>U+1F163 NEGATIVE CIRCLED LATIN CAPITAL LETTER T: try adding symbols</li>
<li>U+1F164 NEGATIVE CIRCLED LATIN CAPITAL LETTER U: try adding symbols</li>
<li>U+1F165 NEGATIVE CIRCLED LATIN CAPITAL LETTER V: try adding symbols</li>
<li>U+1F166 NEGATIVE CIRCLED LATIN CAPITAL LETTER W: try adding symbols</li>
<li>U+1F167 NEGATIVE CIRCLED LATIN CAPITAL LETTER X: try adding symbols</li>
<li>U+1F168 NEGATIVE CIRCLED LATIN CAPITAL LETTER Y: try adding symbols</li>
<li>U+1F169 NEGATIVE CIRCLED LATIN CAPITAL LETTER Z: try adding symbols</li>
<li>U+1F16A RAISED MC SIGN: try adding symbols</li>
<li>U+1F16B RAISED MD SIGN: try adding symbols</li>
<li>U+1F16C RAISED MR SIGN: try adding symbols</li>
<li>U+1F170 NEGATIVE SQUARED LATIN CAPITAL LETTER A: try adding symbols</li>
<li>U+1F171 NEGATIVE SQUARED LATIN CAPITAL LETTER B: try adding symbols</li>
<li>U+1F172 NEGATIVE SQUARED LATIN CAPITAL LETTER C: try adding symbols</li>
<li>U+1F173 NEGATIVE SQUARED LATIN CAPITAL LETTER D: try adding symbols</li>
<li>U+1F174 NEGATIVE SQUARED LATIN CAPITAL LETTER E: try adding symbols</li>
<li>U+1F175 NEGATIVE SQUARED LATIN CAPITAL LETTER F: try adding symbols</li>
<li>U+1F176 NEGATIVE SQUARED LATIN CAPITAL LETTER G: try adding symbols</li>
<li>U+1F177 NEGATIVE SQUARED LATIN CAPITAL LETTER H: try adding symbols</li>
<li>U+1F178 NEGATIVE SQUARED LATIN CAPITAL LETTER I: try adding symbols</li>
<li>U+1F179 NEGATIVE SQUARED LATIN CAPITAL LETTER J: try adding symbols</li>
<li>U+1F17A NEGATIVE SQUARED LATIN CAPITAL LETTER K: try adding symbols</li>
<li>U+1F17B NEGATIVE SQUARED LATIN CAPITAL LETTER L: try adding symbols</li>
<li>U+1F17C NEGATIVE SQUARED LATIN CAPITAL LETTER M: try adding symbols</li>
<li>U+1F17D NEGATIVE SQUARED LATIN CAPITAL LETTER N: try adding symbols</li>
<li>U+1F17E NEGATIVE SQUARED LATIN CAPITAL LETTER O: try adding symbols</li>
<li>U+1F17F NEGATIVE SQUARED LATIN CAPITAL LETTER P: try adding symbols</li>
<li>U+1F180 NEGATIVE SQUARED LATIN CAPITAL LETTER Q: try adding symbols</li>
<li>U+1F181 NEGATIVE SQUARED LATIN CAPITAL LETTER R: try adding symbols</li>
<li>U+1F182 NEGATIVE SQUARED LATIN CAPITAL LETTER S: try adding symbols</li>
<li>U+1F183 NEGATIVE SQUARED LATIN CAPITAL LETTER T: try adding symbols</li>
<li>U+1F184 NEGATIVE SQUARED LATIN CAPITAL LETTER U: try adding symbols</li>
<li>U+1F185 NEGATIVE SQUARED LATIN CAPITAL LETTER V: try adding symbols</li>
<li>U+1F186 NEGATIVE SQUARED LATIN CAPITAL LETTER W: try adding symbols</li>
<li>U+1F187 NEGATIVE SQUARED LATIN CAPITAL LETTER X: try adding symbols</li>
<li>U+1F188 NEGATIVE SQUARED LATIN CAPITAL LETTER Y: try adding symbols</li>
<li>U+1F189 NEGATIVE SQUARED LATIN CAPITAL LETTER Z: try adding symbols</li>
<li>U+1F18A CROSSED NEGATIVE SQUARED LATIN CAPITAL LETTER P: try adding symbols</li>
<li>U+1F18B NEGATIVE SQUARED IC: try adding symbols</li>
<li>U+1F18C NEGATIVE SQUARED PA: try adding symbols</li>
<li>U+1F18D NEGATIVE SQUARED SA: try adding symbols</li>
<li>U+1F18E NEGATIVE SQUARED AB: try adding symbols</li>
<li>U+1F18F NEGATIVE SQUARED WC: try adding symbols</li>
<li>U+1F190 SQUARE DJ: try adding symbols</li>
<li>U+1F19B SQUARED THREE D: try adding symbols</li>
<li>U+1F19C SQUARED SECOND SCREEN: try adding symbols</li>
<li>U+1F19D SQUARED TWO K: try adding symbols</li>
<li>U+1F19E SQUARED FOUR K: try adding symbols</li>
<li>U+1F19F SQUARED EIGHT K: try adding symbols</li>
<li>U+1F1A0 SQUARED FIVE POINT ONE: try adding symbols</li>
<li>U+1F1A1 SQUARED SEVEN POINT ONE: try adding symbols</li>
<li>U+1F1A2 SQUARED TWENTY-TWO POINT TWO: try adding symbols</li>
<li>U+1F1A3 SQUARED SIXTY P: try adding symbols</li>
<li>U+1F1A4 SQUARED ONE HUNDRED TWENTY P: try adding symbols</li>
<li>U+1F1A5 SQUARED LATIN SMALL LETTER D: try adding symbols</li>
<li>U+1F1A6 SQUARED HC: try adding symbols</li>
<li>U+1F1A7 SQUARED HDR: try adding symbols</li>
<li>U+1F1A8 SQUARED HI-RES: try adding symbols</li>
<li>U+1F1A9 SQUARED LOSSLESS: try adding symbols</li>
<li>U+1F1AA SQUARED SHV: try adding symbols</li>
<li>U+1F1AB SQUARED UHD: try adding symbols</li>
<li>U+1F1AC SQUARED VOD: try adding symbols</li>
<li>U+1F546 WHITE LATIN CROSS: try adding symbols</li>
<li>U+1F547 HEAVY LATIN CROSS: try adding symbols</li>
<li>U+1F548 CELTIC CROSS: try adding symbols</li>
<li>U+1F549 OM SYMBOL: try adding symbols</li>
<li>U+1F54F BOWL OF HYGIEIA: try adding symbols</li>
<li>U+1F610 NEUTRAL FACE: try adding symbols</li>
<li>U+1F700 ALCHEMICAL SYMBOL FOR QUINTESSENCE: try adding symbols</li>
<li>U+1F701 ALCHEMICAL SYMBOL FOR AIR: try adding symbols</li>
<li>U+1F702 ALCHEMICAL SYMBOL FOR FIRE: try adding symbols</li>
<li>U+1F703 ALCHEMICAL SYMBOL FOR EARTH: try adding symbols</li>
<li>U+1F704 ALCHEMICAL SYMBOL FOR WATER: try adding symbols</li>
<li>U+1F705 ALCHEMICAL SYMBOL FOR AQUAFORTIS: try adding symbols</li>
<li>U+1F706 ALCHEMICAL SYMBOL FOR AQUA REGIA: try adding symbols</li>
<li>U+1F707 ALCHEMICAL SYMBOL FOR AQUA REGIA-2: try adding symbols</li>
<li>U+1F708 ALCHEMICAL SYMBOL FOR AQUA VITAE: try adding symbols</li>
<li>U+1F709 ALCHEMICAL SYMBOL FOR AQUA VITAE-2: try adding symbols</li>
<li>U+1F70A ALCHEMICAL SYMBOL FOR VINEGAR: try adding symbols</li>
<li>U+1F70B ALCHEMICAL SYMBOL FOR VINEGAR-2: try adding symbols</li>
<li>U+1F70C ALCHEMICAL SYMBOL FOR VINEGAR-3: try adding symbols</li>
<li>U+1F70D ALCHEMICAL SYMBOL FOR SULFUR: try adding symbols</li>
<li>U+1F70E ALCHEMICAL SYMBOL FOR PHILOSOPHERS SULFUR: try adding symbols</li>
<li>U+1F70F ALCHEMICAL SYMBOL FOR BLACK SULFUR: try adding symbols</li>
<li>U+1F710 ALCHEMICAL SYMBOL FOR MERCURY SUBLIMATE: try adding symbols</li>
<li>U+1F711 ALCHEMICAL SYMBOL FOR MERCURY SUBLIMATE-2: try adding symbols</li>
<li>U+1F712 ALCHEMICAL SYMBOL FOR MERCURY SUBLIMATE-3: try adding symbols</li>
<li>U+1F713 ALCHEMICAL SYMBOL FOR CINNABAR: try adding symbols</li>
<li>U+1F714 ALCHEMICAL SYMBOL FOR SALT: try adding symbols</li>
<li>U+1F715 ALCHEMICAL SYMBOL FOR NITRE: try adding symbols</li>
<li>U+1F716 ALCHEMICAL SYMBOL FOR VITRIOL: try adding symbols</li>
<li>U+1F717 ALCHEMICAL SYMBOL FOR VITRIOL-2: try adding symbols</li>
<li>U+1F718 ALCHEMICAL SYMBOL FOR ROCK SALT: try adding symbols</li>
<li>U+1F719 ALCHEMICAL SYMBOL FOR ROCK SALT-2: try adding symbols</li>
<li>U+1F71A ALCHEMICAL SYMBOL FOR GOLD: try adding symbols</li>
<li>U+1F71B ALCHEMICAL SYMBOL FOR SILVER: try adding symbols</li>
<li>U+1F71C ALCHEMICAL SYMBOL FOR IRON ORE: try adding symbols</li>
<li>U+1F71D ALCHEMICAL SYMBOL FOR IRON ORE-2: try adding symbols</li>
<li>U+1F71E ALCHEMICAL SYMBOL FOR CROCUS OF IRON: try adding symbols</li>
<li>U+1F71F ALCHEMICAL SYMBOL FOR REGULUS OF IRON: try adding symbols</li>
<li>U+1F720 ALCHEMICAL SYMBOL FOR COPPER ORE: try adding symbols</li>
<li>U+1F721 ALCHEMICAL SYMBOL FOR IRON-COPPER ORE: try adding symbols</li>
<li>U+1F722 ALCHEMICAL SYMBOL FOR SUBLIMATE OF COPPER: try adding symbols</li>
<li>U+1F723 ALCHEMICAL SYMBOL FOR CROCUS OF COPPER: try adding symbols</li>
<li>U+1F724 ALCHEMICAL SYMBOL FOR CROCUS OF COPPER-2: try adding symbols</li>
<li>U+1F725 ALCHEMICAL SYMBOL FOR COPPER ANTIMONIATE: try adding symbols</li>
<li>U+1F726 ALCHEMICAL SYMBOL FOR SALT OF COPPER ANTIMONIATE: try adding symbols</li>
<li>U+1F727 ALCHEMICAL SYMBOL FOR SUBLIMATE OF SALT OF COPPER: try adding symbols</li>
<li>U+1F728 ALCHEMICAL SYMBOL FOR VERDIGRIS: try adding symbols</li>
<li>U+1F729 ALCHEMICAL SYMBOL FOR TIN ORE: try adding symbols</li>
<li>U+1F72A ALCHEMICAL SYMBOL FOR LEAD ORE: try adding symbols</li>
<li>U+1F72B ALCHEMICAL SYMBOL FOR ANTIMONY ORE: try adding symbols</li>
<li>U+1F72C ALCHEMICAL SYMBOL FOR SUBLIMATE OF ANTIMONY: try adding symbols</li>
<li>U+1F72D ALCHEMICAL SYMBOL FOR SALT OF ANTIMONY: try adding symbols</li>
<li>U+1F72E ALCHEMICAL SYMBOL FOR SUBLIMATE OF SALT OF ANTIMONY: try adding symbols</li>
<li>U+1F72F ALCHEMICAL SYMBOL FOR VINEGAR OF ANTIMONY: try adding symbols</li>
<li>U+1F730 ALCHEMICAL SYMBOL FOR REGULUS OF ANTIMONY: try adding symbols</li>
<li>U+1F731 ALCHEMICAL SYMBOL FOR REGULUS OF ANTIMONY-2: try adding symbols</li>
<li>U+1F732 ALCHEMICAL SYMBOL FOR REGULUS: try adding symbols</li>
<li>U+1F733 ALCHEMICAL SYMBOL FOR REGULUS-2: try adding symbols</li>
<li>U+1F734 ALCHEMICAL SYMBOL FOR REGULUS-3: try adding symbols</li>
<li>U+1F735 ALCHEMICAL SYMBOL FOR REGULUS-4: try adding symbols</li>
<li>U+1F736 ALCHEMICAL SYMBOL FOR ALKALI: try adding symbols</li>
<li>U+1F737 ALCHEMICAL SYMBOL FOR ALKALI-2: try adding symbols</li>
<li>U+1F738 ALCHEMICAL SYMBOL FOR MARCASITE: try adding symbols</li>
<li>U+1F739 ALCHEMICAL SYMBOL FOR SAL-AMMONIAC: try adding symbols</li>
<li>U+1F73A ALCHEMICAL SYMBOL FOR ARSENIC: try adding symbols</li>
<li>U+1F73B ALCHEMICAL SYMBOL FOR REALGAR: try adding symbols</li>
<li>U+1F73C ALCHEMICAL SYMBOL FOR REALGAR-2: try adding symbols</li>
<li>U+1F73D ALCHEMICAL SYMBOL FOR AURIPIGMENT: try adding symbols</li>
<li>U+1F73E ALCHEMICAL SYMBOL FOR BISMUTH ORE: try adding symbols</li>
<li>U+1F73F ALCHEMICAL SYMBOL FOR TARTAR: try adding symbols</li>
<li>U+1F740 ALCHEMICAL SYMBOL FOR TARTAR-2: try adding symbols</li>
<li>U+1F741 ALCHEMICAL SYMBOL FOR QUICK LIME: try adding symbols</li>
<li>U+1F742 ALCHEMICAL SYMBOL FOR BORAX: try adding symbols</li>
<li>U+1F743 ALCHEMICAL SYMBOL FOR BORAX-2: try adding symbols</li>
<li>U+1F744 ALCHEMICAL SYMBOL FOR BORAX-3: try adding symbols</li>
<li>U+1F745 ALCHEMICAL SYMBOL FOR ALUM: try adding symbols</li>
<li>U+1F746 ALCHEMICAL SYMBOL FOR OIL: try adding symbols</li>
<li>U+1F747 ALCHEMICAL SYMBOL FOR SPIRIT: try adding symbols</li>
<li>U+1F748 ALCHEMICAL SYMBOL FOR TINCTURE: try adding symbols</li>
<li>U+1F749 ALCHEMICAL SYMBOL FOR GUM: try adding symbols</li>
<li>U+1F74A ALCHEMICAL SYMBOL FOR WAX: try adding symbols</li>
<li>U+1F74B ALCHEMICAL SYMBOL FOR POWDER: try adding symbols</li>
<li>U+1F74C ALCHEMICAL SYMBOL FOR CALX: try adding symbols</li>
<li>U+1F74D ALCHEMICAL SYMBOL FOR TUTTY: try adding symbols</li>
<li>U+1F74E ALCHEMICAL SYMBOL FOR CAPUT MORTUUM: try adding symbols</li>
<li>U+1F74F ALCHEMICAL SYMBOL FOR SCEPTER OF JOVE: try adding symbols</li>
<li>U+1F750 ALCHEMICAL SYMBOL FOR CADUCEUS: try adding symbols</li>
<li>U+1F751 ALCHEMICAL SYMBOL FOR TRIDENT: try adding symbols</li>
<li>U+1F752 ALCHEMICAL SYMBOL FOR STARRED TRIDENT: try adding symbols</li>
<li>U+1F753 ALCHEMICAL SYMBOL FOR LODESTONE: try adding symbols</li>
<li>U+1F754 ALCHEMICAL SYMBOL FOR SOAP: try adding symbols</li>
<li>U+1F755 ALCHEMICAL SYMBOL FOR URINE: try adding symbols</li>
<li>U+1F756 ALCHEMICAL SYMBOL FOR HORSE DUNG: try adding symbols</li>
<li>U+1F757 ALCHEMICAL SYMBOL FOR ASHES: try adding symbols</li>
<li>U+1F758 ALCHEMICAL SYMBOL FOR POT ASHES: try adding symbols</li>
<li>U+1F759 ALCHEMICAL SYMBOL FOR BRICK: try adding symbols</li>
<li>U+1F75A ALCHEMICAL SYMBOL FOR POWDERED BRICK: try adding symbols</li>
<li>U+1F75B ALCHEMICAL SYMBOL FOR AMALGAM: try adding symbols</li>
<li>U+1F75C ALCHEMICAL SYMBOL FOR STRATUM SUPER STRATUM: try adding symbols</li>
<li>U+1F75D ALCHEMICAL SYMBOL FOR STRATUM SUPER STRATUM-2: try adding symbols</li>
<li>U+1F75E ALCHEMICAL SYMBOL FOR SUBLIMATION: try adding symbols</li>
<li>U+1F75F ALCHEMICAL SYMBOL FOR PRECIPITATE: try adding symbols</li>
<li>U+1F760 ALCHEMICAL SYMBOL FOR DISTILL: try adding symbols</li>
<li>U+1F761 ALCHEMICAL SYMBOL FOR DISSOLVE: try adding symbols</li>
<li>U+1F762 ALCHEMICAL SYMBOL FOR DISSOLVE-2: try adding symbols</li>
<li>U+1F763 ALCHEMICAL SYMBOL FOR PURIFY: try adding symbols</li>
<li>U+1F764 ALCHEMICAL SYMBOL FOR PUTREFACTION: try adding symbols</li>
<li>U+1F765 ALCHEMICAL SYMBOL FOR CRUCIBLE: try adding symbols</li>
<li>U+1F766 ALCHEMICAL SYMBOL FOR CRUCIBLE-2: try adding symbols</li>
<li>U+1F767 ALCHEMICAL SYMBOL FOR CRUCIBLE-3: try adding symbols</li>
<li>U+1F768 ALCHEMICAL SYMBOL FOR CRUCIBLE-4: try adding symbols</li>
<li>U+1F769 ALCHEMICAL SYMBOL FOR CRUCIBLE-5: try adding symbols</li>
<li>U+1F76A ALCHEMICAL SYMBOL FOR ALEMBIC: try adding symbols</li>
<li>U+1F76B ALCHEMICAL SYMBOL FOR BATH OF MARY: try adding symbols</li>
<li>U+1F76C ALCHEMICAL SYMBOL FOR BATH OF VAPOURS: try adding symbols</li>
<li>U+1F76D ALCHEMICAL SYMBOL FOR RETORT: try adding symbols</li>
<li>U+1F76E ALCHEMICAL SYMBOL FOR HOUR: try adding symbols</li>
<li>U+1F76F ALCHEMICAL SYMBOL FOR NIGHT: try adding symbols</li>
<li>U+1F770 ALCHEMICAL SYMBOL FOR DAY-NIGHT: try adding symbols</li>
<li>U+1F771 ALCHEMICAL SYMBOL FOR MONTH: try adding symbols</li>
<li>U+1F772 ALCHEMICAL SYMBOL FOR HALF DRAM: try adding symbols</li>
<li>U+1F773 ALCHEMICAL SYMBOL FOR HALF OUNCE: try adding symbols</li>
</ul>
<p>Or you can add the above codepoints to one of the subsets supported by the font: <code>cyrillic-ext</code>, <code>greek-ext</code>, <code>latin</code>, <code>latin-ext</code></p>
 [code: unreachable-subsetting]



</div>
</details>

<details>
    <summary>⚠️ <b>WARN</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.meta.html#"></a></summary>
    <div>







* ⚠️ **WARN** <p>This font file does not have a 'meta' table.</p>
 [code: lacks-meta-table]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure the font supports case swapping for all its glyphs. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/universal.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs lack their case-swapping counterparts:</p>
<table>
<thead>
<tr>
<th align="left">Glyph present in the font</th>
<th align="left">Missing case-swapping counterpart</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">U+2183: ROMAN NUMERAL REVERSED ONE HUNDRED</td>
<td align="left">U+2184: LATIN SMALL LETTER REVERSED C</td>
</tr>
</tbody>
</table>
 [code: missing-case-counterparts]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Ensure dotted circle glyph is present and can attach marks. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/shaping.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>The following glyphs could not be attached to the dotted circle glyph:</p>
<pre><code>- acutecomb

- gravecomb

- tildecomb

- uni0302

- uni0304

- uni0306

- uni0307

- uni0308

- uni030A

- uni030B

- uni030C

- uni0326

- uni0327

- uni0328
</code></pre>
 [code: unattached-dotted-circle-marks]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Shapes languages in all GF glyphsets. <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.glyphset.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>GF_Latin_Core glyphset:</p>
<table>
<thead>
<tr>
<th align="left">Language</th>
<th align="left">FAIL messages</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">nl_Latn (Dutch)</td>
<td align="left">Shaper didn't attach acutecomb to J</td>
</tr>
</tbody>
</table>
 [code: failed-language-shaping]



</div>
</details>

<details>
    <summary>🔥 <b>FAIL</b> Check for presence of an ARTICLE.en_us.html file <a href="https://fontbakery.readthedocs.io/en/stable/fontbakery/checks/googlefonts.description.html#"></a></summary>
    <div>







* 🔥 **FAIL** <p>This is a Noto font but it lacks an ARTICLE.en_us.html file</p>
 [code: missing-article]



* 🔥 **FAIL** <p>This is a Noto font but it lacks a DESCRIPTION.en_us.html file</p>
 [code: empty-description]



</div>
</details>
</div>
</details>




### Summary

| 💥 ERROR | ☠ FATAL | 🔥 FAIL | ⚠️ WARN | ⏩ SKIP | ℹ️ INFO | ✅ PASS | 🔎 DEBUG | 
| ---|---|---|---|---|---|---|---|
| 0 | 0 | 4 | 7 | 97 | 7 | 134 | 0 | 
| 0% | 0% | 2% | 3% | 39% | 3% | 54% | 0% | 



**Note:** The following loglevels were omitted in this report:


* SKIP
* INFO
* PASS
* DEBUG
