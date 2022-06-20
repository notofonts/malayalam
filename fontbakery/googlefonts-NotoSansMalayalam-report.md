## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[4] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Each font in a family must have the same set of vertical metrics values. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/vertical_metrics">com.google.fonts/check/family/vertical_metrics</a>)</summary><div>


* 🔥 **FAIL** sTypoAscender is not the same across the family:
Noto Sans Malayalam Regular: 864
Noto Sans Malayalam Black: 864
Noto Sans Malayalam Bold: 864
Noto Sans Malayalam ExtraBold: 864
Noto Sans Malayalam ExtraLight: 864
Noto Sans Malayalam Light: 864
Noto Sans Malayalam Medium: 864
Noto Sans Malayalam SemiBold: 864
Noto Sans Malayalam Thin: 864
Noto Sans Malayalam UI Black: 1069
Noto Sans Malayalam UI Bold: 1069
Noto Sans Malayalam UI ExtraBold: 1069
Noto Sans Malayalam UI ExtraLight: 1069
Noto Sans Malayalam UI Light: 1069
Noto Sans Malayalam UI Medium: 1069
Noto Sans Malayalam UI Regular: 1069
Noto Sans Malayalam UI SemiBold: 1069
Noto Sans Malayalam UI Thin: 1069 [code: sTypoAscender-mismatch]
* 🔥 **FAIL** sTypoDescender is not the same across the family:
Noto Sans Malayalam Regular: -383
Noto Sans Malayalam Black: -383
Noto Sans Malayalam Bold: -383
Noto Sans Malayalam ExtraBold: -383
Noto Sans Malayalam ExtraLight: -383
Noto Sans Malayalam Light: -383
Noto Sans Malayalam Medium: -383
Noto Sans Malayalam SemiBold: -383
Noto Sans Malayalam Thin: -383
Noto Sans Malayalam UI Black: -293
Noto Sans Malayalam UI Bold: -293
Noto Sans Malayalam UI ExtraBold: -293
Noto Sans Malayalam UI ExtraLight: -293
Noto Sans Malayalam UI Light: -293
Noto Sans Malayalam UI Medium: -293
Noto Sans Malayalam UI Regular: -293
Noto Sans Malayalam UI SemiBold: -293
Noto Sans Malayalam UI Thin: -293 [code: sTypoDescender-mismatch]
* 🔥 **FAIL** usWinAscent is not the same across the family:
Noto Sans Malayalam Regular: 864
Noto Sans Malayalam Black: 864
Noto Sans Malayalam Bold: 864
Noto Sans Malayalam ExtraBold: 864
Noto Sans Malayalam ExtraLight: 864
Noto Sans Malayalam Light: 864
Noto Sans Malayalam Medium: 864
Noto Sans Malayalam SemiBold: 864
Noto Sans Malayalam Thin: 864
Noto Sans Malayalam UI Black: 1069
Noto Sans Malayalam UI Bold: 1069
Noto Sans Malayalam UI ExtraBold: 1069
Noto Sans Malayalam UI ExtraLight: 1069
Noto Sans Malayalam UI Light: 1069
Noto Sans Malayalam UI Medium: 1069
Noto Sans Malayalam UI Regular: 1069
Noto Sans Malayalam UI SemiBold: 1069
Noto Sans Malayalam UI Thin: 1069 [code: usWinAscent-mismatch]
* 🔥 **FAIL** usWinDescent is not the same across the family:
Noto Sans Malayalam Regular: 383
Noto Sans Malayalam Black: 383
Noto Sans Malayalam Bold: 383
Noto Sans Malayalam ExtraBold: 383
Noto Sans Malayalam ExtraLight: 383
Noto Sans Malayalam Light: 383
Noto Sans Malayalam Medium: 383
Noto Sans Malayalam SemiBold: 383
Noto Sans Malayalam Thin: 383
Noto Sans Malayalam UI Black: 293
Noto Sans Malayalam UI Bold: 293
Noto Sans Malayalam UI ExtraBold: 293
Noto Sans Malayalam UI ExtraLight: 293
Noto Sans Malayalam UI Light: 293
Noto Sans Malayalam UI Medium: 293
Noto Sans Malayalam UI Regular: 293
Noto Sans Malayalam UI SemiBold: 293
Noto Sans Malayalam UI Thin: 293 [code: usWinDescent-mismatch]
* 🔥 **FAIL** ascent is not the same across the family:
Noto Sans Malayalam Regular: 864
Noto Sans Malayalam Black: 864
Noto Sans Malayalam Bold: 864
Noto Sans Malayalam ExtraBold: 864
Noto Sans Malayalam ExtraLight: 864
Noto Sans Malayalam Light: 864
Noto Sans Malayalam Medium: 864
Noto Sans Malayalam SemiBold: 864
Noto Sans Malayalam Thin: 864
Noto Sans Malayalam UI Black: 1069
Noto Sans Malayalam UI Bold: 1069
Noto Sans Malayalam UI ExtraBold: 1069
Noto Sans Malayalam UI ExtraLight: 1069
Noto Sans Malayalam UI Light: 1069
Noto Sans Malayalam UI Medium: 1069
Noto Sans Malayalam UI Regular: 1069
Noto Sans Malayalam UI SemiBold: 1069
Noto Sans Malayalam UI Thin: 1069 [code: ascent-mismatch]
* 🔥 **FAIL** descent is not the same across the family:
Noto Sans Malayalam Regular: -383
Noto Sans Malayalam Black: -383
Noto Sans Malayalam Bold: -383
Noto Sans Malayalam ExtraBold: -383
Noto Sans Malayalam ExtraLight: -383
Noto Sans Malayalam Light: -383
Noto Sans Malayalam Medium: -383
Noto Sans Malayalam SemiBold: -383
Noto Sans Malayalam Thin: -383
Noto Sans Malayalam UI Black: -293
Noto Sans Malayalam UI Bold: -293
Noto Sans Malayalam UI ExtraBold: -293
Noto Sans Malayalam UI ExtraLight: -293
Noto Sans Malayalam UI Light: -293
Noto Sans Malayalam UI Medium: -293
Noto Sans Malayalam UI Regular: -293
Noto Sans Malayalam UI SemiBold: -293
Noto Sans Malayalam UI Thin: -293 [code: descent-mismatch]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><br></div></details><details><summary><b>[17] NotoSansMalayalam-MM[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSansMalayalam-MM[wght].ttf' must be renamed to 'NotoSansMalayalam[wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Is the Grid-fitting and Scan-conversion Procedure ('gasp') table set to optimize rendering? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/gasp">com.google.fonts/check/gasp</a>)</summary><div>


* 🔥 **FAIL** Font is missing the 'gasp' table. Try exporting the font with autohinting enabled.
If you are dealing with an unhinted font, it can be fixed by running the fonts through the command 'gftools fix-nonhinting'
GFTools is available at https://pypi.org/project/gftools/ [code: lacks-gasp]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> Font enables smart dropout control in "prep" table instructions? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/smart_dropout">com.google.fonts/check/smart_dropout</a>)</summary><div>


* 🔥 **FAIL** The 'prep' table does not contain TrueType instructions enabling smart dropout control. To fix, export the font with autohinting enabled, or run ttfautohint on the font, or run the `gftools fix-nonhinting` script. [code: lacks-smart-dropout]
</div></details><details><summary>🔥 <b>FAIL:</b> Check variable font instances don't have duplicate names (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/varfont_duplicate_instance_names">com.google.fonts/check/varfont_duplicate_instance_names</a>)</summary><div>


* 🔥 **FAIL** Following instances names are duplicate: 
	- ExtraLight
	- Light
	- Regular
	- Medium
	- SemiBold
	- Bold
 [code: duplicate-instance-names]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 261. [code: invalid-default-instance-subfamily-nameid:261]
* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its postScriptNameID should be 6, instead of 270. [code: invalid-default-instance-postscript-nameid:270]
* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 261. [code: invalid-default-instance-subfamily-nameid:261]
* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its postScriptNameID should be 6, instead of 279. [code: invalid-default-instance-postscript-nameid:279]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- llvocalicvowelsignUImlym

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[17] NotoSansMalayalam-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* onehalfmlym
	* jajamlym
	* sevenmlym
	* nnannamlym
	* nnaddhamlym
	* ddhaprehalfmlym
	* ralvocalicmlym
	* ngakamlym
	* gamamlym
	* badhamlym and 178 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Malayalam Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- llvocalicvowelsignUImlym

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=391.5,Y=-2.0 (should be at baseline 0?)

	* parenleft.mlym (U+0028): X=78.0,Y=-1.5 (should be at baseline 0?)

	* parenright.mlym (U+0029): X=296.0,Y=-1.5 (should be at baseline 0?)

	* three.mlym (U+0033): X=125.5,Y=-1.0 (should be at baseline 0?)

	* five.mlym (U+0035): X=136.0,Y=-1.0 (should be at baseline 0?)

	* six.mlym (U+0036): X=498.0,Y=716.0 (should be at cap-height 714?)

	* nine.mlym (U+0039): X=72.0,Y=-2.0 (should be at baseline 0?)

	* C (U+0043): X=490.5,Y=-0.5 (should be at baseline 0?)

	* C (U+0043): X=506.0,Y=712.0 (should be at cap-height 714?)

	* G (U+0047): X=545.5,Y=2.0 (should be at baseline 0?) 

	* And 86 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<339.5,236.0>-<346.0,204.0>-<347.0,184.0>>/B<<347.0,184.0>-<349.0,204.0>-<354.5,235.5>> = 8.57299836361137

	* W (U+0057): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* W (U+0057): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* W (U+0057): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wacute (U+1E82): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wacute (U+1E82): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wacute (U+1E82): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432

	* Wcircumflex (U+0174): B<<308.0,211.5>-<313.0,185.0>-<315.0,167.0>>/B<<315.0,167.0>-<319.0,197.0>-<325.5,236.0>> = 13.934835114501363

	* Wcircumflex (U+0174): B<<527.0,442.0>-<523.0,468.0>-<521.0,486.0>>/B<<521.0,486.0>-<519.0,468.0>-<514.5,442.0>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<714.0,235.0>-<721.0,196.0>-<724.0,167.0>>/B<<724.0,167.0>-<727.0,192.0>-<734.0,229.0>> = 12.748914526401432 

	* And 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] NotoSansMalayalam-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* onehalfmlym
	* jajamlym
	* nnannamlym
	* nnaddhamlym
	* ddhaprehalfmlym
	* ralvocalicmlym
	* ngakamlym
	* gamamlym
	* badhamlym
	* shacamlym and 159 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- llvocalicvowelsignUImlym

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* numbersign.mlym (U+0023): X=246.0,Y=713.0 (should be at cap-height 714?)

	* numbersign.mlym (U+0023): X=353.0,Y=713.0 (should be at cap-height 714?)

	* numbersign.mlym (U+0023): X=450.0,Y=713.0 (should be at cap-height 714?)

	* numbersign.mlym (U+0023): X=555.0,Y=713.0 (should be at cap-height 714?)

	* six.mlym (U+0036): X=489.0,Y=715.0 (should be at cap-height 714?)

	* seven.mlym (U+0037): X=27.0,Y=713.0 (should be at cap-height 714?)

	* seven.mlym (U+0037): X=539.0,Y=713.0 (should be at cap-height 714?)

	* question.mlym (U+003F): X=133.0,Y=712.5 (should be at cap-height 714?)

	* C (U+0043): X=482.0,Y=-1.0 (should be at baseline 0?)

	* G (U+0047): X=527.5,Y=1.0 (should be at baseline 0?) 

	* And 62 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,505.5>-<485.0,529.0>-<483.0,542.0>>/B<<483.0,542.0>-<482.0,529.0>-<477.5,505.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,196.0>-<689.0,161.0>-<692.0,137.0>>/B<<692.0,137.0>-<695.0,162.0>-<701.0,196.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,196.0>-<272.0,161.0>-<275.0,137.0>>/B<<275.0,137.0>-<278.0,162.0>-<284.0,196.5>> = 13.967789761532726 

	* And 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] NotoSansMalayalam-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* onehalfmlym
	* jajamlym
	* sevenmlym
	* nnannamlym
	* nnaddhamlym
	* ddhaprehalfmlym
	* ralvocalicmlym
	* ngakamlym
	* gamamlym
	* badhamlym and 177 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Malayalam ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- llvocalicvowelsignUImlym

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<326.0,209.5>-<333.0,177.0>-<335.0,156.0>>/B<<335.0,156.0>-<338.0,177.0>-<344.5,209.0>> = 13.570434385161475

	* W (U+0057): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* W (U+0057): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wacute (U+1E82): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wacute (U+1E82): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wcircumflex (U+0174): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wcircumflex (U+0174): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wdieresis (U+1E84): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357

	* Wdieresis (U+1E84): B<<506.5,475.5>-<502.0,500.0>-<501.0,516.0>>/B<<501.0,516.0>-<499.0,500.0>-<494.5,475.5>> = 10.701350723899111

	* Wgrave (U+1E80): B<<283.5,211.5>-<290.0,175.0>-<293.0,151.0>>/B<<293.0,151.0>-<297.0,183.0>-<305.0,226.5>> = 14.25003269780357 

	* And 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] NotoSansMalayalam-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* nnaddhamlym
	* ddhaprehalfmlym
	* badhamlym
	* nyajamlym
	* nnaddamlym
	* sixmlym
	* ngakalamlym
	* baprehalfmlym
	* nnamamlym
	* nachillumlym and 31 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Malayalam ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- llvocalicvowelsignUImlym

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[17] NotoSansMalayalam-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* jajamlym
	* nnannamlym
	* nnaddhamlym
	* ddhaprehalfmlym
	* ngakamlym
	* gamamlym
	* badhamlym
	* nyajamlym
	* nnaddamlym
	* sixmlym and 70 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Malayalam Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- llvocalicvowelsignUImlym

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* lllamlym (U+0D34): L<<315.0,207.0>--<327.0,207.0>> -> L<<327.0,207.0>--<328.0,207.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* jamlym (U+0D1C): B<<517.5,154.5>-<552.0,172.0>-<581.0,183.0>>/B<<581.0,183.0>-<559.0,180.0>-<532.0,178.5>> = 13.007088663620442 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] NotoSansMalayalam-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* onehalfmlym
	* jajamlym
	* nnannamlym
	* nnaddhamlym
	* ddhaprehalfmlym
	* ralvocalicmlym
	* ngakamlym
	* gamamlym
	* badhamlym
	* shacamlym and 136 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Malayalam Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- llvocalicvowelsignUImlym

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* jamlym (U+0D1C): B<<231.0,490.0>-<200.0,486.0>-<175.0,474.0>>/B<<175.0,474.0>-<198.0,479.0>-<220.0,479.0>> = 13.376232096412883 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] NotoSansMalayalam-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* onehalfmlym
	* jajamlym
	* nnannamlym
	* nnaddhamlym
	* ddhaprehalfmlym
	* ralvocalicmlym
	* ngakamlym
	* gamamlym
	* badhamlym
	* shacamlym and 120 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- llvocalicvowelsignUImlym

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* jamlym (U+0D1C): B<<506.5,148.0>-<537.0,161.0>-<569.0,172.0>>/B<<569.0,172.0>-<541.0,169.0>-<503.5,167.5>> = 12.854904242201115 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] NotoSansMalayalam-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* onehalfmlym
	* jajamlym
	* nnannamlym
	* nnaddhamlym
	* ddhaprehalfmlym
	* ralvocalicmlym
	* ngakamlym
	* gamamlym
	* badhamlym
	* shacamlym and 151 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Malayalam SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- llvocalicvowelsignUImlym

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* W (U+0057): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<257.0,182.5>-<263.0,150.0>-<266.0,126.0>>/B<<266.0,126.0>-<269.0,151.0>-<275.0,184.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<678.0,182.0>-<684.0,150.0>-<687.0,126.0>>/B<<687.0,126.0>-<690.0,151.0>-<695.5,183.0>> = 13.967789761532726

	* jamlym (U+0D1C): B<<255.0,487.0>-<230.0,485.0>-<208.0,478.0>>/B<<208.0,478.0>-<218.0,479.0>-<229.0,479.0>> = 11.939531082430465 

	* And jamlym (U+0D1C): B<<491.5,141.0>-<522.0,151.0>-<550.0,160.0>>/L<<550.0,160.0>--<546.0,159.0>> = 3.782645446596307 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[18] NotoSansMalayalam-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* nnaddhamlym
	* ddhaprehalfmlym
	* badhamlym
	* nyajamlym
	* nnaddamlym
	* baprehalfmlym
	* nnamamlym
	* uni200C
	* babamlym
	* balamlym and 5 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Malayalam Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- llvocalicvowelsignUImlym

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* kachillumlym (U+0D7F): L<<317.0,302.0>--<319.0,302.0>> -> L<<319.0,302.0>--<663.0,302.0>> 

	* And kamlym (U+0D15): L<<317.0,302.0>--<319.0,302.0>> -> L<<319.0,302.0>--<663.0,302.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* rrvocalicmlym (U+0D60): B<<174.0,90.0>-<222.0,106.0>-<285.0,111.0>>/B<<285.0,111.0>-<238.0,117.0>-<197.0,130.5>> = 11.812777465795877

	* rrvocalicmlym (U+0D60): B<<603.0,130.5>-<562.0,117.0>-<516.0,111.0>>/B<<516.0,111.0>-<579.0,107.0>-<627.0,91.0>> = 11.064358710660672

	* rvocalicmlym (U+0D0B): B<<174.0,90.0>-<222.0,106.0>-<285.0,111.0>>/B<<285.0,111.0>-<238.0,117.0>-<197.0,130.5>> = 11.812777465795877

	* rvocalicmlym (U+0D0B): B<<603.0,130.5>-<562.0,117.0>-<516.0,111.0>>/B<<516.0,111.0>-<579.0,107.0>-<627.0,91.0>> = 11.064358710660672 

	* And uuvowelsignmlym (U+0D42): B<<32.0,12.0>-<32.0,33.0>-<45.0,53.0>>/B<<45.0,53.0>-<9.0,19.0>-<9.0,-55.0>> = 13.612709485820046 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.mlym (U+0021): L<<105.0,174.0>--<103.0,714.0>>

	* exclam.mlym (U+0021): L<<131.0,714.0>--<129.0,174.0>>

	* exclamdown (U+00A1): L<<122.0,354.0>--<124.0,-186.0>> 

	* And exclamdown (U+00A1): L<<96.0,-186.0>--<98.0,354.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSansMalayalamUI-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 367, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Malayalam UI Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum

	- ellipsis 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* dollar (U+0024): X=535.0,Y=712.0 (should be at cap-height 714?)

	* J (U+004A): X=-79.0,Y=2.0 (should be at baseline 0?)

	* f (U+0066): X=22.0,Y=570.0 (should be at x-height 569?)

	* cent (U+00A2): X=377.0,Y=715.0 (should be at cap-height 714?)

	* section (U+00A7): X=326.5,Y=715.5 (should be at cap-height 714?)

	* cedilla (U+00B8): X=56.0,Y=-2.0 (should be at baseline 0?)

	* Ccedilla (U+00C7): X=286.0,Y=-2.0 (should be at baseline 0?)

	* ccedilla (U+00E7): X=222.0,Y=-2.0 (should be at baseline 0?)

	* IJ (U+0132): X=361.0,Y=2.0 (should be at baseline 0?)

	* Eng (U+014A): X=563.0,Y=-0.5 (should be at baseline 0?) 

	* And 23 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<339.5,302.0>-<346.0,270.0>-<347.0,250.0>>/B<<347.0,250.0>-<349.0,270.0>-<354.5,301.5>> = 8.57299836361137

	* W (U+0057): B<<308.0,277.5>-<313.0,251.0>-<315.0,233.0>>/B<<315.0,233.0>-<319.0,263.0>-<325.5,302.0>> = 13.934835114501363

	* W (U+0057): B<<527.0,508.0>-<523.0,534.0>-<521.0,552.0>>/B<<521.0,552.0>-<519.0,534.0>-<514.5,508.0>> = 12.680383491819825

	* W (U+0057): B<<714.0,301.0>-<721.0,262.0>-<724.0,233.0>>/B<<724.0,233.0>-<727.0,258.0>-<734.0,295.0>> = 12.748914526401432

	* Wacute (U+1E82): B<<308.0,277.5>-<313.0,251.0>-<315.0,233.0>>/B<<315.0,233.0>-<319.0,263.0>-<325.5,302.0>> = 13.934835114501363

	* Wacute (U+1E82): B<<527.0,508.0>-<523.0,534.0>-<521.0,552.0>>/B<<521.0,552.0>-<519.0,534.0>-<514.5,508.0>> = 12.680383491819825

	* Wacute (U+1E82): B<<714.0,301.0>-<721.0,262.0>-<724.0,233.0>>/B<<724.0,233.0>-<727.0,258.0>-<734.0,295.0>> = 12.748914526401432

	* Wcircumflex (U+0174): B<<308.0,277.5>-<313.0,251.0>-<315.0,233.0>>/B<<315.0,233.0>-<319.0,263.0>-<325.5,302.0>> = 13.934835114501363

	* Wcircumflex (U+0174): B<<527.0,508.0>-<523.0,534.0>-<521.0,552.0>>/B<<521.0,552.0>-<519.0,534.0>-<514.5,508.0>> = 12.680383491819825

	* Wcircumflex (U+0174): B<<714.0,301.0>-<721.0,262.0>-<724.0,233.0>>/B<<724.0,233.0>-<727.0,258.0>-<734.0,295.0>> = 12.748914526401432 

	* And 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] NotoSansMalayalamUI-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 367, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum

	- ellipsis 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=127.5,Y=713.0 (should be at cap-height 714?)

	* parenleft.mlym (U+0028): X=106.5,Y=715.5 (should be at cap-height 714?)

	* eight.mlym (U+0038): X=89.0,Y=713.0 (should be at cap-height 714?)

	* eight.mlym (U+0038): X=482.5,Y=713.0 (should be at cap-height 714?)

	* f (U+0066): X=311.0,Y=713.0 (should be at cap-height 714?)

	* t (U+0074): X=23.0,Y=563.0 (should be at x-height 562?)

	* cent (U+00A2): X=362.0,Y=713.0 (should be at cap-height 714?)

	* ordfeminine (U+00AA): X=180.0,Y=712.0 (should be at cap-height 714?)

	* germandbls (U+00DF): X=347.0,Y=715.0 (should be at cap-height 714?)

	* Uring (U+016E): X=376.0,Y=1071.0 (should be at ascender 1069?) 

	* And 13 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<266.0,262.0>-<272.0,227.0>-<275.0,203.0>>/B<<275.0,203.0>-<278.0,228.0>-<284.0,262.5>> = 13.967789761532726

	* W (U+0057): B<<489.0,571.5>-<485.0,595.0>-<483.0,608.0>>/B<<483.0,608.0>-<482.0,595.0>-<477.5,571.5>> = 13.144867617550734

	* W (U+0057): B<<683.0,262.0>-<689.0,227.0>-<692.0,203.0>>/B<<692.0,203.0>-<695.0,228.0>-<701.0,262.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<266.0,262.0>-<272.0,227.0>-<275.0,203.0>>/B<<275.0,203.0>-<278.0,228.0>-<284.0,262.5>> = 13.967789761532726

	* Wacute (U+1E82): B<<489.0,571.5>-<485.0,595.0>-<483.0,608.0>>/B<<483.0,608.0>-<482.0,595.0>-<477.5,571.5>> = 13.144867617550734

	* Wacute (U+1E82): B<<683.0,262.0>-<689.0,227.0>-<692.0,203.0>>/B<<692.0,203.0>-<695.0,228.0>-<701.0,262.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<266.0,262.0>-<272.0,227.0>-<275.0,203.0>>/B<<275.0,203.0>-<278.0,228.0>-<284.0,262.5>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<489.0,571.5>-<485.0,595.0>-<483.0,608.0>>/B<<483.0,608.0>-<482.0,595.0>-<477.5,571.5>> = 13.144867617550734

	* Wcircumflex (U+0174): B<<683.0,262.0>-<689.0,227.0>-<692.0,203.0>>/B<<692.0,203.0>-<695.0,228.0>-<701.0,262.5>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<266.0,262.0>-<272.0,227.0>-<275.0,203.0>>/B<<275.0,203.0>-<278.0,228.0>-<284.0,262.5>> = 13.967789761532726 

	* And 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] NotoSansMalayalamUI-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 367, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Malayalam UI ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum

	- ellipsis 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* parenleft.mlym (U+0028): X=107.0,Y=712.5 (should be at cap-height 714?)

	* eight.mlym (U+0038): X=83.5,Y=712.0 (should be at cap-height 714?)

	* at (U+0040): X=571.5,Y=-2.0 (should be at baseline 0?)

	* Eng (U+014A): X=563.0,Y=-2.0 (should be at baseline 0?)

	* aamlym (U+0D06): X=1588.5,Y=1.0 (should be at baseline 0?)

	* avagrahamlym (U+0D3D): X=181.5,Y=1.5 (should be at baseline 0?)

	* rrvocalicmlym (U+0D60): X=616.5,Y=1.0 (should be at baseline 0?)

	* rrvocalicmlym (U+0D60): X=569.0,Y=0.5 (should be at baseline 0?)

	* rrvocalicmlym (U+0D60): X=464.5,Y=1.0 (should be at baseline 0?)

	* rrvocalicmlym (U+0D60): X=417.5,Y=-0.5 (should be at baseline 0?)

	* llvocalicmlym (U+0D61): X=1227.0,Y=1.0 (should be at baseline 0?) 

	* And llvocalicvowelsignUImlym (U+0D63): X=-229.0,Y=-2.0 (should be at baseline 0?) [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<326.0,275.5>-<333.0,243.0>-<335.0,222.0>>/B<<335.0,222.0>-<338.0,243.0>-<344.5,275.0>> = 13.570434385161475

	* W (U+0057): B<<283.5,277.5>-<290.0,241.0>-<293.0,217.0>>/B<<293.0,217.0>-<297.0,249.0>-<305.0,292.5>> = 14.25003269780357

	* W (U+0057): B<<506.5,541.5>-<502.0,566.0>-<501.0,582.0>>/B<<501.0,582.0>-<499.0,566.0>-<494.5,541.5>> = 10.701350723899111

	* Wacute (U+1E82): B<<283.5,277.5>-<290.0,241.0>-<293.0,217.0>>/B<<293.0,217.0>-<297.0,249.0>-<305.0,292.5>> = 14.25003269780357

	* Wacute (U+1E82): B<<506.5,541.5>-<502.0,566.0>-<501.0,582.0>>/B<<501.0,582.0>-<499.0,566.0>-<494.5,541.5>> = 10.701350723899111

	* Wcircumflex (U+0174): B<<283.5,277.5>-<290.0,241.0>-<293.0,217.0>>/B<<293.0,217.0>-<297.0,249.0>-<305.0,292.5>> = 14.25003269780357

	* Wcircumflex (U+0174): B<<506.5,541.5>-<502.0,566.0>-<501.0,582.0>>/B<<501.0,582.0>-<499.0,566.0>-<494.5,541.5>> = 10.701350723899111

	* Wdieresis (U+1E84): B<<283.5,277.5>-<290.0,241.0>-<293.0,217.0>>/B<<293.0,217.0>-<297.0,249.0>-<305.0,292.5>> = 14.25003269780357

	* Wdieresis (U+1E84): B<<506.5,541.5>-<502.0,566.0>-<501.0,582.0>>/B<<501.0,582.0>-<499.0,566.0>-<494.5,541.5>> = 10.701350723899111

	* Wgrave (U+1E80): B<<283.5,277.5>-<290.0,241.0>-<293.0,217.0>>/B<<293.0,217.0>-<297.0,249.0>-<305.0,292.5>> = 14.25003269780357 

	* And 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] NotoSansMalayalamUI-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 367, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Malayalam UI ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum

	- ellipsis 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* zero.mlym (U+0030): X=401.0,Y=712.0 (should be at cap-height 714?)

	* three.mlym (U+0033): X=53.0,Y=716.0 (should be at cap-height 714?)

	* eight.mlym (U+0038): X=112.0,Y=713.5 (should be at cap-height 714?)

	* question.mlym (U+003F): X=53.0,Y=716.0 (should be at cap-height 714?)

	* at (U+0040): X=418.0,Y=2.0 (should be at baseline 0?)

	* C (U+0043): X=241.5,Y=712.0 (should be at cap-height 714?)

	* G (U+0047): X=617.0,Y=712.0 (should be at cap-height 714?)

	* G (U+0047): X=252.0,Y=713.0 (should be at cap-height 714?)

	* O (U+004F): X=227.0,Y=713.0 (should be at cap-height 714?)

	* Q (U+0051): X=227.0,Y=713.0 (should be at cap-height 714?) 

	* And 52 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><br></div></details><details><summary><b>[17] NotoSansMalayalamUI-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 367, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Malayalam UI Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum

	- ellipsis 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* ampersand (U+0026): X=217.5,Y=715.0 (should be at cap-height 714?)

	* ampersand (U+0026): X=382.0,Y=715.5 (should be at cap-height 714?)

	* zero.mlym (U+0030): X=373.5,Y=715.5 (should be at cap-height 714?)

	* zero.mlym (U+0030): X=199.0,Y=715.0 (should be at cap-height 714?)

	* three.mlym (U+0033): X=454.0,Y=713.5 (should be at cap-height 714?)

	* eight.mlym (U+0038): X=108.5,Y=715.0 (should be at cap-height 714?)

	* eight.mlym (U+0038): X=392.5,Y=713.0 (should be at cap-height 714?)

	* a (U+0061): X=195.0,Y=548.0 (should be at x-height 550?)

	* c (U+0063): X=371.0,Y=550.5 (should be at x-height 550?)

	* f (U+0066): X=295.0,Y=552.0 (should be at x-height 550?) 

	* And 38 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* lllamlym (U+0D34): L<<315.0,273.0>--<327.0,273.0>> -> L<<327.0,273.0>--<328.0,273.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* jamlym (U+0D1C): B<<517.5,220.5>-<552.0,238.0>-<581.0,249.0>>/B<<581.0,249.0>-<559.0,246.0>-<532.0,244.5>> = 13.007088663620442 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] NotoSansMalayalamUI-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 367, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Malayalam UI Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum

	- ellipsis 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* percent.mlym (U+0025): X=196.0,Y=716.0 (should be at cap-height 714?)

	* parenleft.mlym (U+0028): X=106.0,Y=713.0 (should be at cap-height 714?)

	* eight.mlym (U+0038): X=99.0,Y=716.0 (should be at cap-height 714?)

	* eight.mlym (U+0038): X=473.5,Y=716.0 (should be at cap-height 714?)

	* braceleft.mlym (U+007B): X=254.0,Y=-2.0 (should be at baseline 0?)

	* braceright.mlym (U+007D): X=120.0,Y=-2.0 (should be at baseline 0?)

	* ordfeminine (U+00AA): X=225.5,Y=716.0 (should be at cap-height 714?)

	* eth (U+00F0): X=405.0,Y=712.0 (should be at cap-height 714?)

	* eth (U+00F0): X=264.0,Y=713.0 (should be at cap-height 714?)

	* candrabindumlym (U+0D01): X=-278.0,Y=713.0 (should be at cap-height 714?) 

	* And 11 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* jamlym (U+0D1C): B<<231.0,556.0>-<200.0,552.0>-<175.0,540.0>>/B<<175.0,540.0>-<198.0,545.0>-<220.0,545.0>> = 13.376232096412883 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] NotoSansMalayalamUI-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 367, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Malayalam UI' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum

	- ellipsis 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* zero.mlym (U+0030): X=286.0,Y=716.0 (should be at cap-height 714?)

	* two.mlym (U+0032): X=275.0,Y=716.0 (should be at cap-height 714?)

	* three.mlym (U+0033): X=463.5,Y=714.5 (should be at cap-height 714?)

	* seven.mlym (U+0037): X=523.0,Y=712.0 (should be at cap-height 714?)

	* question.mlym (U+003F): X=216.0,Y=713.0 (should be at cap-height 714?)

	* O (U+004F): X=392.0,Y=712.0 (should be at cap-height 714?)

	* Q (U+0051): X=392.0,Y=712.0 (should be at cap-height 714?)

	* Z (U+005A): X=523.0,Y=712.0 (should be at cap-height 714?)

	* sterling (U+00A3): X=336.0,Y=716.0 (should be at cap-height 714?)

	* copyright (U+00A9): X=540.5,Y=712.5 (should be at cap-height 714?) 

	* And 51 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* jamlym (U+0D1C): B<<506.5,214.0>-<537.0,227.0>-<569.0,238.0>>/B<<569.0,238.0>-<541.0,235.0>-<503.5,233.5>> = 12.854904242201115 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[16] NotoSansMalayalamUI-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 367, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Malayalam UI SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum

	- ellipsis 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* eight.mlym (U+0038): X=94.5,Y=714.5 (should be at cap-height 714?)

	* f (U+0066): X=383.0,Y=716.0 (should be at cap-height 714?)

	* j (U+006A): X=207.0,Y=-1.0 (should be at baseline 0?)

	* cent (U+00A2): X=359.0,Y=712.0 (should be at cap-height 714?)

	* ordfeminine (U+00AA): X=127.5,Y=713.0 (should be at cap-height 714?)

	* questiondown (U+00BF): X=171.5,Y=-2.0 (should be at baseline 0?)

	* germandbls (U+00DF): X=415.5,Y=712.0 (should be at cap-height 714?)

	* atilde (U+00E3): X=262.5,Y=712.5 (should be at cap-height 714?)

	* ntilde (U+00F1): X=290.5,Y=712.5 (should be at cap-height 714?)

	* otilde (U+00F5): X=276.5,Y=712.5 (should be at cap-height 714?) 

	* And 26 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* W (U+0057): B<<257.0,248.5>-<263.0,216.0>-<266.0,192.0>>/B<<266.0,192.0>-<269.0,217.0>-<275.0,250.0>> = 13.967789761532726

	* W (U+0057): B<<678.0,248.0>-<684.0,216.0>-<687.0,192.0>>/B<<687.0,192.0>-<690.0,217.0>-<695.5,249.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<257.0,248.5>-<263.0,216.0>-<266.0,192.0>>/B<<266.0,192.0>-<269.0,217.0>-<275.0,250.0>> = 13.967789761532726

	* Wacute (U+1E82): B<<678.0,248.0>-<684.0,216.0>-<687.0,192.0>>/B<<687.0,192.0>-<690.0,217.0>-<695.5,249.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<257.0,248.5>-<263.0,216.0>-<266.0,192.0>>/B<<266.0,192.0>-<269.0,217.0>-<275.0,250.0>> = 13.967789761532726

	* Wcircumflex (U+0174): B<<678.0,248.0>-<684.0,216.0>-<687.0,192.0>>/B<<687.0,192.0>-<690.0,217.0>-<695.5,249.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<257.0,248.5>-<263.0,216.0>-<266.0,192.0>>/B<<266.0,192.0>-<269.0,217.0>-<275.0,250.0>> = 13.967789761532726

	* Wdieresis (U+1E84): B<<678.0,248.0>-<684.0,216.0>-<687.0,192.0>>/B<<687.0,192.0>-<690.0,217.0>-<695.5,249.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<257.0,248.5>-<263.0,216.0>-<266.0,192.0>>/B<<266.0,192.0>-<269.0,217.0>-<275.0,250.0>> = 13.967789761532726

	* Wgrave (U+1E80): B<<678.0,248.0>-<684.0,216.0>-<687.0,192.0>>/B<<687.0,192.0>-<690.0,217.0>-<695.5,249.0>> = 13.967789761532726

	* jamlym (U+0D1C): B<<255.0,553.0>-<230.0,551.0>-<208.0,544.0>>/B<<208.0,544.0>-<218.0,545.0>-<229.0,545.0>> = 11.939531082430465 

	* And jamlym (U+0D1C): B<<491.5,207.0>-<522.0,217.0>-<550.0,226.0>>/L<<550.0,226.0>--<546.0,225.0>> = 3.782645446596307 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[18] NotoSansMalayalamUI-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 1069 instead [code: ascent]
* 🔥 **FAIL** OS/2.usWinDescent value should be equal or greater than 367, but got 293 instead. [code: descent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Sans Malayalam UI Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum

	- ellipsis 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 7 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* percent.mlym (U+0025): X=280.0,Y=713.5 (should be at cap-height 714?)

	* percent.mlym (U+0025): X=115.5,Y=715.5 (should be at cap-height 714?)

	* three.mlym (U+0033): X=54.0,Y=716.0 (should be at cap-height 714?)

	* at (U+0040): X=516.0,Y=1.5 (should be at baseline 0?)

	* P (U+0050): X=434.5,Y=715.0 (should be at cap-height 714?)

	* c (U+0063): X=195.0,Y=547.0 (should be at x-height 546?)

	* m (U+006D): X=148.0,Y=547.0 (should be at x-height 546?)

	* o (U+006F): X=406.0,Y=545.5 (should be at x-height 546?)

	* w (U+0077): X=351.0,Y=548.0 (should be at x-height 546?)

	* w (U+0077): X=349.0,Y=548.0 (should be at x-height 546?) 

	* And 49 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do any segments have colinear vectors? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_colinear_vectors">com.google.fonts/check/outline_colinear_vectors</a>)</summary><div>


* ⚠ **WARN** The following glyphs have colinear vectors:

	* kachillumlym (U+0D7F): L<<317.0,368.0>--<319.0,368.0>> -> L<<319.0,368.0>--<663.0,368.0>> 

	* And kamlym (U+0D15): L<<317.0,368.0>--<319.0,368.0>> -> L<<319.0,368.0>--<663.0,368.0>> [code: found-colinear-vectors]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* rrvocalicmlym (U+0D60): B<<174.0,156.0>-<222.0,172.0>-<285.0,177.0>>/B<<285.0,177.0>-<238.0,183.0>-<197.0,196.5>> = 11.812777465795877

	* rrvocalicmlym (U+0D60): B<<603.0,196.5>-<562.0,183.0>-<516.0,177.0>>/B<<516.0,177.0>-<579.0,173.0>-<627.0,157.0>> = 11.064358710660672

	* rvocalicmlym (U+0D0B): B<<174.0,156.0>-<222.0,172.0>-<285.0,177.0>>/B<<285.0,177.0>-<238.0,183.0>-<197.0,196.5>> = 11.812777465795877

	* rvocalicmlym (U+0D0B): B<<603.0,196.5>-<562.0,183.0>-<516.0,177.0>>/B<<516.0,177.0>-<579.0,173.0>-<627.0,157.0>> = 11.064358710660672 

	* And uuvowelsignmlym (U+0D42): B<<32.0,78.0>-<32.0,99.0>-<45.0,119.0>>/B<<45.0,119.0>-<9.0,85.0>-<9.0,11.0>> = 13.612709485820046 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.mlym (U+0021): L<<105.0,240.0>--<103.0,780.0>>

	* exclam.mlym (U+0021): L<<131.0,780.0>--<129.0,240.0>>

	* exclamdown (U+00A1): L<<122.0,420.0>--<124.0,-120.0>> 

	* And exclamdown (U+00A1): L<<96.0,-120.0>--<98.0,420.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[14] NotoSansMalayalam-MM[wdth,wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking file is named canonically. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/canonical_filename">com.google.fonts/check/canonical_filename</a>)</summary><div>


* 🔥 **FAIL** The file 'NotoSansMalayalam-MM[wdth,wght].ttf' must be renamed to 'NotoSansMalayalam[wdth,wght].ttf' according to the Google Fonts naming policy for variable fonts. [code: bad-varfont-filename]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2018 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSansMalayalam/googlefonts/slim-variable-ttf/NotoSansMalayalam-MM[wght].ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalam-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Black.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Bold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-ExtraLight.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Light.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Medium.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Regular.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-SemiBold.ttf', 'fonts/NotoSansMalayalam/googlefonts/ttf/NotoSansMalayalamUI-Thin.ttf', 'fonts/NotoSansMalayalam/googlefonts/variable-ttf/NotoSansMalayalam-MM[wdth,wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 1078, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Font has **proper** whitespace glyph names? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/whitespace_glyphnames">com.google.fonts/check/whitespace_glyphnames</a>)</summary><div>


* 🔥 **FAIL** Glyph 0x00A0 is called "uni00A0.mlym": Change to "uni00A0" [code: non-compliant-00a0]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0951

	- uni0D00

	- rephmlym

	- viramamlym

	- uni0952 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 292. [code: invalid-default-instance-subfamily-nameid:292]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- braceright

	- emdash

	- one

	- llvocalicvowelsignUImlym

	- equal

	- plus

	- bracketright

	- two

	- tthallvocalicUImlym

	- asciicircum 

	- And 44 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aivowelsignmlym (U+0D48), anusvaramlym (U+0D02), auvowelsignmlym (U+0D4C), eevowelsignmlym (U+0D47), evowelsignmlym (U+0D46), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A) and 5 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 6 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D02, U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D46, U+0D47, U+0D48, U+0D4A, U+0D4B, U+0D4C and U+0D4E [code: non-mark-chars]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 151 | 175 | 2266 | 142 | 1681 | 0 |
| 0% | 3% | 4% | 51% | 3% | 38% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
