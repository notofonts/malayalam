## Fontbakery report

Fontbakery version: 0.8.9

<details><summary><b>[3] Family checks</b></summary><div><details><summary>🔥 <b>FAIL:</b> Checking all files are in the same directory. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/single_directory">com.google.fonts/check/family/single_directory</a>)</summary><div>


* 🔥 **FAIL** Not all fonts passed in the command line are in the same directory. This may lead to bad results as the tool will interpret all font files as belonging to a single font family. The detected directories are: ['fonts/NotoSerifMalayalam/googlefonts/slim-variable-ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf', 'fonts/NotoSerifMalayalam/googlefonts/variable-ttf'] [code: single-directory]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE proportion? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_proportion">com.google.fonts/check/family/panose_proportion</a>)</summary><div>


* 🔥 **FAIL** PANOSE proportion is not the same across this family. In order to fix this, please make sure that the panose.bProportion value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><details><summary>🔥 <b>FAIL:</b> Fonts have consistent PANOSE family type? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/os2.html#com.google.fonts/check/family/panose_familytype">com.google.fonts/check/family/panose_familytype</a>)</summary><div>


* 🔥 **FAIL** PANOSE family type is not the same across this family. In order to fix this, please make sure that the panose.bFamilyType value is the same in the OS/2 table of all of this family font files. [code: inconsistency]
</div></details><br></div></details><details><summary><b>[24] NotoSerifMalayalam[wght].ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifMalayalam/googlefonts/slim-variable-ttf/NotoSerifMalayalam[wght].ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Black.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Bold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraLight.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Light.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Medium.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Regular.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-SemiBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Thin.ttf', 'fonts/NotoSerifMalayalam/googlefonts/variable-ttf/NotoSerifMalayalam[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifMalayalam/googlefonts/slim-variable-ttf/NotoSerifMalayalam[wght].ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Black.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Bold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraLight.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Light.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Medium.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Regular.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-SemiBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Thin.ttf', 'fonts/NotoSerifMalayalam/googlefonts/variable-ttf/NotoSerifMalayalam[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0952

	- rephmlym

	- uni0951 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0952

	- rephmlym

	- uni0951 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 278. [code: invalid-default-instance-subfamily-nameid:278]
</div></details><details><summary>🔥 <b>FAIL:</b> Validates that when an instance record is included for the default instance, its subfamilyNameID value is set to either 2 or 17, and its postScriptNameID value is set to 6. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/fvar.html#com.adobe.fonts/check/varfont/valid_default_instance_nameids">com.adobe.fonts/check/varfont/valid_default_instance_nameids</a>)</summary><div>


* 🔥 **FAIL** 'Regular' instance has the same coordinates as the default instance; its subfamilyNameID should be either 2 or 17, instead of 278. [code: invalid-default-instance-subfamily-nameid:278]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quotedbl

	- parenright

	- question

	- four

	- eight

	- seven

	- ellipsis

	- quotedblright

	- asterisk

	- asciicircum 

	- And 37 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quotedbl

	- parenright

	- question

	- four

	- eight

	- seven

	- ellipsis

	- quotedblright

	- asterisk

	- asciicircum 

	- And 37 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aulengthmarkmlym (U+0D57), auvowelsignmlym (U+0D4C), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A), rrvocalicvowelsignmlym (U+0D44), rvocalicvowelsignmlym (U+0D43), uuvowelsignmlym (U+0D42) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D4A, U+0D4B, U+0D4C, U+0D4E and U+0D57 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aulengthmarkmlym (U+0D57), auvowelsignmlym (U+0D4C), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A), rrvocalicvowelsignmlym (U+0D44), rvocalicvowelsignmlym (U+0D43), uuvowelsignmlym (U+0D42) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), gravecomb (U+0300), tildecomb (U+0303), uni0302 (U+0302), uni0304 (U+0304), uni0306 (U+0306), uni0308 (U+0308), uni030A (U+030A), uni030B (U+030B), uni030C (U+030C) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D4A, U+0D4B, U+0D4C, U+0D4E and U+0D57 [code: non-mark-chars]
</div></details><br></div></details><details><summary><b>[17] NotoSerifMalayalam-Black.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifMalayalam/googlefonts/slim-variable-ttf/NotoSerifMalayalam[wght].ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Black.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Bold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraLight.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Light.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Medium.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Regular.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-SemiBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Thin.ttf', 'fonts/NotoSerifMalayalam/googlefonts/variable-ttf/NotoSerifMalayalam[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0952

	- rephmlym

	- uni0951 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* katamlym
	* tthalvocalicmlym
	* thousandmlym
	* lllachillumlym
	* bhallvocalicmlym
	* uni0D5A
	* nathamlym
	* malvocalicmlym
	* ngakalamlym
	* lachillumlym and 150 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Malayalam Black' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quotedbl

	- parenright

	- question

	- four

	- eight

	- seven

	- ellipsis

	- quotedblright

	- asterisk

	- asciicircum 

	- And 37 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aulengthmarkmlym (U+0D57), auvowelsignmlym (U+0D4C), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A), rrvocalicvowelsignmlym (U+0D44), rvocalicvowelsignmlym (U+0D43), uuvowelsignmlym (U+0D42) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D4A, U+0D4B, U+0D4C, U+0D4E and U+0D57 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* five.mlym (U+0035): X=91.0,Y=715.0 (should be at cap-height 714?)

	* five.mlym (U+0035): X=486.0,Y=715.0 (should be at cap-height 714?)

	* seven.mlym (U+0037): X=43.0,Y=715.0 (should be at cap-height 714?)

	* seven.mlym (U+0037): X=518.0,Y=715.0 (should be at cap-height 714?)

	* at (U+0040): X=765.0,Y=-2.0 (should be at baseline 0?)

	* J (U+004A): X=117.0,Y=1.0 (should be at baseline 0?)

	* J (U+004A): X=317.0,Y=2.0 (should be at baseline 0?)

	* Q (U+0051): X=317.0,Y=-1.0 (should be at baseline 0?)

	* f (U+0066): X=155.0,Y=713.5 (should be at cap-height 714?)

	* g (U+0067): X=560.5,Y=568.5 (should be at x-height 567?) 

	* And 59 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* V (U+0056): B<<402.5,227.0>-<406.0,208.0>-<407.0,194.0>>/B<<407.0,194.0>-<409.0,211.0>-<416.0,238.5>> = 10.79545358773178

	* eogonek (U+0119): B<<282.5,-58.0>-<309.0,-25.0>-<346.0,-9.0>>/B<<346.0,-9.0>-<340.0,-10.0>-<333.5,-10.0>> = 13.922898849188117

	* mamlym (U+0D2E): B<<364.0,508.0>-<347.0,508.0>-<331.0,507.0>>/B<<331.0,507.0>-<385.0,506.0>-<429.0,484.5>> = 4.637246065261516

	* uni0D5A (U+0D5A): B<<783.0,508.0>-<766.0,508.0>-<750.0,507.0>>/B<<750.0,507.0>-<804.0,506.0>-<848.0,484.5>> = 4.637246065261516

	* uni0D76 (U+0D76): B<<1037.0,508.0>-<1020.0,508.0>-<1004.0,507.0>>/B<<1004.0,507.0>-<1058.0,506.0>-<1102.0,484.5>> = 4.637246065261516

	* uni0D78 (U+0D78): B<<2259.0,508.0>-<2242.0,508.0>-<2226.0,507.0>>/B<<2226.0,507.0>-<2280.0,506.0>-<2324.0,484.5>> = 4.637246065261516

	* uuvowelsignmlym (U+0D42): B<<268.0,-63.0>-<268.0,-32.0>-<258.0,-7.0>>/B<<258.0,-7.0>-<259.0,-13.0>-<259.0,-19.0>> = 12.33908727832621

	* uuvowelsignmlym (U+0D42): B<<39.0,-19.0>-<39.0,-14.0>-<40.0,-8.0>>/B<<40.0,-8.0>-<30.0,-33.0>-<30.0,-65.0>> = 12.33908727832621

	* y (U+0079): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511

	* yacute (U+00FD): B<<336.0,187.0>-<342.0,160.0>-<343.0,142.0>>/B<<343.0,142.0>-<346.0,164.0>-<349.5,180.0>> = 10.944996138289511 

	* And 3 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<454.0,335.0>--<295.0,336.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NotoSerifMalayalam-Bold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifMalayalam/googlefonts/slim-variable-ttf/NotoSerifMalayalam[wght].ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Black.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Bold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraLight.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Light.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Medium.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Regular.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-SemiBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Thin.ttf', 'fonts/NotoSerifMalayalam/googlefonts/variable-ttf/NotoSerifMalayalam[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0952

	- rephmlym

	- uni0951 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* katamlym
	* tthalvocalicmlym
	* thousandmlym
	* lllachillumlym
	* bhallvocalicmlym
	* uni0D5A
	* nathamlym
	* malvocalicmlym
	* ngakalamlym
	* lachillumlym and 135 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quotedbl

	- parenright

	- question

	- four

	- eight

	- seven

	- ellipsis

	- quotedblright

	- asterisk

	- asciicircum 

	- And 37 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aulengthmarkmlym (U+0D57), auvowelsignmlym (U+0D4C), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A), rrvocalicvowelsignmlym (U+0D44), rvocalicvowelsignmlym (U+0D43), uuvowelsignmlym (U+0D42) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D4A, U+0D4B, U+0D4C, U+0D4E and U+0D57 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three.mlym (U+0033): X=339.0,Y=1.0 (should be at baseline 0?)

	* five.mlym (U+0035): X=336.0,Y=1.5 (should be at baseline 0?)

	* J (U+004A): X=282.0,Y=-2.0 (should be at baseline 0?)

	* a (U+0061): X=264.5,Y=-1.5 (should be at baseline 0?)

	* f (U+0066): X=320.0,Y=712.0 (should be at cap-height 714?)

	* g (U+0067): X=427.5,Y=561.0 (should be at x-height 562?)

	* g (U+0067): X=540.0,Y=561.5 (should be at x-height 562?)

	* p (U+0070): X=247.0,Y=1.5 (should be at baseline 0?)

	* t (U+0074): X=119.0,Y=561.0 (should be at x-height 562?)

	* t (U+0074): X=334.5,Y=-1.0 (should be at baseline 0?) 

	* And 75 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* mamlym (U+0D2E): B<<349.0,507.0>-<311.0,507.0>-<279.0,501.0>>/B<<279.0,501.0>-<289.0,502.0>-<300.0,502.0>> = 4.90906213865549

	* uni0D5A (U+0D5A): B<<744.0,507.0>-<705.0,507.0>-<674.0,501.0>>/B<<674.0,501.0>-<684.0,502.0>-<694.0,502.0>> = 5.243469505898641

	* uni0D76 (U+0D76): B<<1022.0,507.0>-<984.0,507.0>-<952.0,501.0>>/B<<952.0,501.0>-<962.0,502.0>-<973.0,502.0>> = 4.90906213865549

	* uni0D78 (U+0D78): B<<2093.0,507.0>-<2055.0,507.0>-<2023.0,501.0>>/B<<2023.0,501.0>-<2033.0,502.0>-<2044.0,502.0>> = 4.90906213865549

	* uuvowelsignmlym (U+0D42): B<<260.0,-63.0>-<260.0,-19.0>-<241.0,12.0>>/B<<241.0,12.0>-<247.0,-3.0>-<247.0,-19.0>> = 9.702857232852313 

	* And uuvowelsignmlym (U+0D42): B<<40.0,-19.0>-<40.0,-4.0>-<46.0,11.0>>/B<<46.0,11.0>-<27.0,-20.0>-<27.0,-65.0>> = 9.702857232852313 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifMalayalam-ExtraBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifMalayalam/googlefonts/slim-variable-ttf/NotoSerifMalayalam[wght].ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Black.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Bold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraLight.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Light.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Medium.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Regular.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-SemiBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Thin.ttf', 'fonts/NotoSerifMalayalam/googlefonts/variable-ttf/NotoSerifMalayalam[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0952

	- rephmlym

	- uni0951 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* katamlym
	* tthalvocalicmlym
	* thousandmlym
	* lllachillumlym
	* bhallvocalicmlym
	* uni0D5A
	* nathamlym
	* malvocalicmlym
	* ngakalamlym
	* lachillumlym and 145 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Malayalam ExtraBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quotedbl

	- parenright

	- question

	- four

	- eight

	- seven

	- ellipsis

	- quotedblright

	- asterisk

	- asciicircum 

	- And 37 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aulengthmarkmlym (U+0D57), auvowelsignmlym (U+0D4C), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A), rrvocalicvowelsignmlym (U+0D44), rvocalicvowelsignmlym (U+0D43), uuvowelsignmlym (U+0D42) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D4A, U+0D4B, U+0D4C, U+0D4E and U+0D57 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three.mlym (U+0033): X=346.5,Y=1.0 (should be at baseline 0?)

	* five.mlym (U+0035): X=96.0,Y=715.0 (should be at cap-height 714?)

	* five.mlym (U+0035): X=479.0,Y=715.0 (should be at cap-height 714?)

	* seven.mlym (U+0037): X=44.0,Y=715.0 (should be at cap-height 714?)

	* seven.mlym (U+0037): X=514.0,Y=715.0 (should be at cap-height 714?)

	* J (U+004A): X=120.0,Y=-1.0 (should be at baseline 0?)

	* Q (U+0051): X=319.0,Y=-2.0 (should be at baseline 0?)

	* Q (U+0051): X=509.0,Y=2.0 (should be at baseline 0?)

	* f (U+0066): X=108.0,Y=567.0 (should be at x-height 565?)

	* f (U+0066): X=157.5,Y=715.0 (should be at cap-height 714?) 

	* And 78 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* uni0D5A (U+0D5A): B<<765.0,507.0>-<737.0,507.0>-<713.0,504.0>>/B<<713.0,504.0>-<717.0,505.0>-<722.0,505.0>> = 6.911227119024662

	* uni0D78 (U+0D78): B<<2184.0,507.0>-<2156.0,507.0>-<2132.0,504.0>>/B<<2132.0,504.0>-<2136.0,505.0>-<2140.0,505.0>> = 6.911227119024662

	* uuvowelsignmlym (U+0D42): B<<40.0,-19.0>-<40.0,-9.0>-<42.0,0.0>>/B<<42.0,0.0>-<29.0,-28.0>-<29.0,-65.0>> = 12.375961098943664

	* y (U+0079): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* yacute (U+00FD): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* ycircumflex (U+0177): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124

	* ydieresis (U+00FF): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124 

	* And ygrave (U+1EF3): B<<327.5,180.5>-<335.0,151.0>-<337.0,131.0>>/B<<337.0,131.0>-<340.0,154.0>-<345.5,173.0>> = 13.142001108672124 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<444.0,335.0>--<285.0,336.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSerifMalayalam-ExtraLight.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifMalayalam/googlefonts/slim-variable-ttf/NotoSerifMalayalam[wght].ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Black.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Bold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraLight.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Light.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Medium.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Regular.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-SemiBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Thin.ttf', 'fonts/NotoSerifMalayalam/googlefonts/variable-ttf/NotoSerifMalayalam[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0952

	- rephmlym

	- uni0951 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* thousandmlym
	* nathamlym
	* ngakalamlym
	* phalamlym
	* ngamlym
	* namamlym
	* tamamlym
	* nnamamlym
	* threemlym
	* kassaprehalfmlym and 42 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Malayalam ExtraLight' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quotedbl

	- parenright

	- question

	- four

	- eight

	- seven

	- ellipsis

	- quotedblright

	- asterisk

	- asciicircum 

	- And 37 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aulengthmarkmlym (U+0D57), auvowelsignmlym (U+0D4C), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A), rrvocalicvowelsignmlym (U+0D44), rvocalicvowelsignmlym (U+0D43), uuvowelsignmlym (U+0D42) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D4A, U+0D4B, U+0D4C, U+0D4E and U+0D57 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* asterisk.mlym (U+002A): X=66.0,Y=716.0 (should be at cap-height 714?)

	* five.mlym (U+0035): X=138.0,Y=712.0 (should be at cap-height 714?)

	* five.mlym (U+0035): X=440.0,Y=712.0 (should be at cap-height 714?)

	* seven.mlym (U+0037): X=62.0,Y=712.0 (should be at cap-height 714?)

	* seven.mlym (U+0037): X=494.0,Y=712.0 (should be at cap-height 714?)

	* G (U+0047): X=486.5,Y=-1.0 (should be at baseline 0?)

	* W (U+0057): X=496.0,Y=713.0 (should be at cap-height 714?)

	* W (U+0057): X=533.0,Y=713.0 (should be at cap-height 714?)

	* a (U+0061): X=248.0,Y=543.0 (should be at x-height 545?)

	* b (U+0062): X=327.0,Y=544.0 (should be at x-height 545?) 

	* And 73 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<356.5,474.5>-<399.0,456.0>-<423.0,417.0>>/B<<423.0,417.0>-<401.0,487.0>-<370.5,540.5>> = 14.160313822966648

	* jamlym (U+0D1C): B<<578.0,153.0>-<596.0,162.0>-<613.0,169.0>>/B<<613.0,169.0>-<593.0,166.0>-<568.0,164.5>> = 13.849369442011424

	* mamlym (U+0D2E): B<<225.5,501.5>-<182.0,484.0>-<156.0,459.0>>/B<<156.0,459.0>-<201.0,488.0>-<256.0,488.0>> = 11.077166013305362

	* uni0D5A (U+0D5A): B<<566.5,501.5>-<523.0,484.0>-<497.0,459.0>>/B<<497.0,459.0>-<542.0,488.0>-<597.0,488.0>> = 11.077166013305362

	* uni0D76 (U+0D76): B<<871.5,501.5>-<828.0,484.0>-<802.0,459.0>>/B<<802.0,459.0>-<847.0,488.0>-<902.0,488.0>> = 11.077166013305362

	* uni0D78 (U+0D78): B<<1690.5,501.5>-<1647.0,484.0>-<1621.0,459.0>>/B<<1621.0,459.0>-<1666.0,488.0>-<1721.0,488.0>> = 11.077166013305362

	* uuvowelsignmlym (U+0D42): B<<232.5,3.5>-<218.0,33.0>-<193.0,55.0>>/B<<193.0,55.0>-<206.0,38.0>-<213.5,22.0>> = 11.246866148897755 

	* And uuvowelsignmlym (U+0D42): B<<40.5,23.5>-<48.0,39.0>-<61.0,55.0>>/B<<61.0,55.0>-<35.0,34.0>-<20.5,4.0>> = 11.97859752097818 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifMalayalam-Light.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifMalayalam/googlefonts/slim-variable-ttf/NotoSerifMalayalam[wght].ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Black.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Bold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraLight.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Light.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Medium.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Regular.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-SemiBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Thin.ttf', 'fonts/NotoSerifMalayalam/googlefonts/variable-ttf/NotoSerifMalayalam[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0952

	- rephmlym

	- uni0951 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* katamlym
	* tthalvocalicmlym
	* thousandmlym
	* bhallvocalicmlym
	* nathamlym
	* malvocalicmlym
	* ngakalamlym
	* phalamlym
	* dalvocalicmlym
	* ngamlym and 81 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Malayalam Light' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quotedbl

	- parenright

	- question

	- four

	- eight

	- seven

	- ellipsis

	- quotedblright

	- asterisk

	- asciicircum 

	- And 37 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aulengthmarkmlym (U+0D57), auvowelsignmlym (U+0D4C), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A), rrvocalicvowelsignmlym (U+0D44), rvocalicvowelsignmlym (U+0D43), uuvowelsignmlym (U+0D42) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D4A, U+0D4B, U+0D4C, U+0D4E and U+0D57 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* three.mlym (U+0033): X=324.0,Y=1.5 (should be at baseline 0?)

	* five.mlym (U+0035): X=128.0,Y=713.0 (should be at cap-height 714?)

	* five.mlym (U+0035): X=444.0,Y=713.0 (should be at cap-height 714?)

	* seven.mlym (U+0037): X=56.0,Y=713.0 (should be at cap-height 714?)

	* seven.mlym (U+0037): X=495.0,Y=713.0 (should be at cap-height 714?)

	* nine.mlym (U+0039): X=147.0,Y=1.0 (should be at baseline 0?)

	* g (U+0067): X=498.0,Y=548.0 (should be at x-height 549?)

	* t (U+0074): X=89.0,Y=551.0 (should be at x-height 549?)

	* t (U+0074): X=297.0,Y=1.0 (should be at baseline 0?)

	* y (U+0079): X=269.0,Y=-1.0 (should be at baseline 0?) 

	* And 74 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* jamlym (U+0D1C): B<<604.0,159.0>-<612.0,163.0>-<620.0,166.0>>/B<<620.0,166.0>-<597.0,163.0>-<565.5,161.0>> = 13.124637248410924

	* mamlym (U+0D2E): B<<242.5,501.5>-<206.0,490.0>-<181.0,473.0>>/B<<181.0,473.0>-<219.0,491.0>-<260.0,491.0>> = 8.86952619049067

	* uni0D5A (U+0D5A): B<<591.5,501.5>-<555.0,490.0>-<530.0,473.0>>/B<<530.0,473.0>-<568.0,491.0>-<609.0,491.0>> = 8.86952619049067

	* uni0D76 (U+0D76): B<<899.5,501.5>-<863.0,490.0>-<838.0,473.0>>/B<<838.0,473.0>-<876.0,491.0>-<917.0,491.0>> = 8.86952619049067

	* uni0D78 (U+0D78): B<<1737.0,501.5>-<1700.0,490.0>-<1675.0,473.0>>/B<<1675.0,473.0>-<1713.0,491.0>-<1755.0,491.0>> = 8.86952619049067

	* uuvowelsignmlym (U+0D42): B<<235.5,-0.5>-<223.0,26.0>-<201.0,47.0>>/B<<201.0,47.0>-<212.0,32.0>-<218.5,17.0>> = 10.078382116424827 

	* And uuvowelsignmlym (U+0D42): B<<43.0,17.0>-<49.0,32.0>-<60.0,46.0>>/B<<60.0,46.0>-<38.0,26.0>-<25.5,-1.5>> = 9.569084406537177 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* question.mlym (U+003F): L<<186.0,201.0>--<185.0,346.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[15] NotoSerifMalayalam-Medium.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifMalayalam/googlefonts/slim-variable-ttf/NotoSerifMalayalam[wght].ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Black.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Bold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraLight.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Light.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Medium.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Regular.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-SemiBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Thin.ttf', 'fonts/NotoSerifMalayalam/googlefonts/variable-ttf/NotoSerifMalayalam[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0952

	- rephmlym

	- uni0951 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* katamlym
	* tthalvocalicmlym
	* thousandmlym
	* lllachillumlym
	* bhallvocalicmlym
	* uni0D5A
	* nathamlym
	* malvocalicmlym
	* ngakalamlym
	* lachillumlym and 114 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Malayalam Medium' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quotedbl

	- parenright

	- question

	- four

	- eight

	- seven

	- ellipsis

	- quotedblright

	- asterisk

	- asciicircum 

	- And 37 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aulengthmarkmlym (U+0D57), auvowelsignmlym (U+0D4C), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A), rrvocalicvowelsignmlym (U+0D44), rvocalicvowelsignmlym (U+0D43), uuvowelsignmlym (U+0D42) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D4A, U+0D4B, U+0D4C, U+0D4E and U+0D57 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* lllachillumlym (U+0D56): B<<312.0,408.0>-<312.0,433.0>-<319.0,456.0>>/B<<319.0,456.0>-<309.0,436.0>-<296.0,411.0>> = 9.637538112930923

	* lllachillumlym (U+0D56): B<<379.0,596.0>-<366.0,554.0>-<337.0,494.0>>/B<<337.0,494.0>-<360.0,527.0>-<398.0,544.5>> = 9.079301850102238

	* mamlym (U+0D2E): B<<282.0,502.0>-<258.0,499.0>-<239.0,493.0>>/B<<239.0,493.0>-<257.0,496.0>-<275.0,496.0>> = 8.063246165697231

	* uni0D5A (U+0D5A): B<<651.0,502.0>-<627.0,499.0>-<608.0,493.0>>/B<<608.0,493.0>-<626.0,496.0>-<645.0,496.0>> = 8.063246165697231

	* uni0D76 (U+0D76): B<<954.0,502.0>-<930.0,499.0>-<911.0,493.0>>/B<<911.0,493.0>-<929.0,496.0>-<948.0,496.0>> = 8.063246165697231

	* uni0D78 (U+0D78): B<<1874.5,502.0>-<1851.0,499.0>-<1831.0,493.0>>/B<<1831.0,493.0>-<1849.0,496.0>-<1868.0,496.0>> = 7.236922025967975

	* uuvowelsignmlym (U+0D42): B<<244.0,-10.0>-<236.0,12.0>-<220.0,30.0>>/B<<220.0,30.0>-<227.0,19.0>-<231.0,7.0>> = 9.162347045721747 

	* And uuvowelsignmlym (U+0D42): B<<45.5,6.0>-<49.0,18.0>-<56.0,29.0>>/B<<56.0,29.0>-<41.0,11.0>-<32.5,-12.0>> = 7.334378801416755 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[15] NotoSerifMalayalam-Regular.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifMalayalam/googlefonts/slim-variable-ttf/NotoSerifMalayalam[wght].ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Black.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Bold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraLight.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Light.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Medium.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Regular.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-SemiBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Thin.ttf', 'fonts/NotoSerifMalayalam/googlefonts/variable-ttf/NotoSerifMalayalam[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0952

	- rephmlym

	- uni0951 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* katamlym
	* tthalvocalicmlym
	* thousandmlym
	* lllachillumlym
	* bhallvocalicmlym
	* uni0D5A
	* nathamlym
	* malvocalicmlym
	* ngakalamlym
	* lachillumlym and 108 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quotedbl

	- parenright

	- question

	- four

	- eight

	- seven

	- ellipsis

	- quotedblright

	- asterisk

	- asciicircum 

	- And 37 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aulengthmarkmlym (U+0D57), auvowelsignmlym (U+0D4C), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A), rrvocalicvowelsignmlym (U+0D44), rvocalicvowelsignmlym (U+0D43), uuvowelsignmlym (U+0D42) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D4A, U+0D4B, U+0D4C, U+0D4E and U+0D57 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma.mlym (U+002C): X=119.0,Y=1.0 (should be at baseline 0?)

	* three.mlym (U+0033): X=321.5,Y=1.0 (should be at baseline 0?)

	* five.mlym (U+0035): X=115.0,Y=713.0 (should be at cap-height 714?)

	* five.mlym (U+0035): X=449.0,Y=713.0 (should be at cap-height 714?)

	* seven.mlym (U+0037): X=49.0,Y=713.0 (should be at cap-height 714?)

	* seven.mlym (U+0037): X=496.0,Y=713.0 (should be at cap-height 714?)

	* nine.mlym (U+0039): X=139.0,Y=2.0 (should be at baseline 0?)

	* semicolon.mlym (U+003B): X=129.0,Y=1.0 (should be at baseline 0?)

	* G (U+0047): X=519.0,Y=1.5 (should be at baseline 0?)

	* g (U+0067): X=161.0,Y=-0.5 (should be at baseline 0?) 

	* And 67 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* mamlym (U+0D2E): B<<270.0,500.5>-<244.0,496.0>-<223.0,489.0>>/B<<223.0,489.0>-<245.0,494.0>-<266.0,494.0>> = 5.630682757635233

	* uni0D5A (U+0D5A): B<<630.0,500.5>-<604.0,496.0>-<583.0,489.0>>/B<<583.0,489.0>-<605.0,494.0>-<626.0,494.0>> = 5.630682757635233

	* uni0D76 (U+0D76): B<<942.0,500.5>-<916.0,496.0>-<895.0,489.0>>/B<<895.0,489.0>-<917.0,494.0>-<938.0,494.0>> = 5.630682757635233

	* uni0D78 (U+0D78): B<<1805.0,500.5>-<1779.0,496.0>-<1758.0,489.0>>/B<<1758.0,489.0>-<1780.0,494.0>-<1801.0,494.0>> = 5.630682757635233

	* uuvowelsignmlym (U+0D42): B<<239.5,-6.5>-<230.0,17.0>-<212.0,36.0>>/B<<212.0,36.0>-<220.0,24.0>-<225.0,10.5>> = 9.761774775042225 

	* And uuvowelsignmlym (U+0D42): B<<46.5,8.5>-<51.0,22.0>-<59.0,34.0>>/B<<59.0,34.0>-<42.0,16.0>-<32.5,-8.0>> = 9.673355432403483 [code: found-jaggy-segments]
</div></details><br></div></details><details><summary><b>[17] NotoSerifMalayalam-SemiBold.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifMalayalam/googlefonts/slim-variable-ttf/NotoSerifMalayalam[wght].ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Black.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Bold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraLight.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Light.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Medium.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Regular.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-SemiBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Thin.ttf', 'fonts/NotoSerifMalayalam/googlefonts/variable-ttf/NotoSerifMalayalam[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0952

	- rephmlym

	- uni0951 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* katamlym
	* tthalvocalicmlym
	* thousandmlym
	* lllachillumlym
	* bhallvocalicmlym
	* uni0D5A
	* nathamlym
	* malvocalicmlym
	* ngakalamlym
	* lachillumlym and 119 more.

Use -F or --full-lists to disable shortening of long lists.
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Malayalam SemiBold' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quotedbl

	- parenright

	- question

	- four

	- eight

	- seven

	- ellipsis

	- quotedblright

	- asterisk

	- asciicircum 

	- And 37 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aulengthmarkmlym (U+0D57), auvowelsignmlym (U+0D4C), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A), rrvocalicvowelsignmlym (U+0D44), rvocalicvowelsignmlym (U+0D43), uuvowelsignmlym (U+0D42) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D4A, U+0D4B, U+0D4C, U+0D4E and U+0D57 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Are there any misaligned on-curve points? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_alignment_miss">com.google.fonts/check/outline_alignment_miss</a>)</summary><div>


* ⚠ **WARN** The following glyphs have on-curve points which have potentially incorrect y coordinates:

	* comma.mlym (U+002C): X=120.0,Y=-1.0 (should be at baseline 0?)

	* three.mlym (U+0033): X=332.5,Y=1.0 (should be at baseline 0?)

	* semicolon.mlym (U+003B): X=130.0,Y=-1.0 (should be at baseline 0?)

	* Q (U+0051): X=470.0,Y=-1.0 (should be at baseline 0?)

	* f (U+0066): X=309.0,Y=716.0 (should be at cap-height 714?)

	* g (U+0067): X=529.0,Y=557.5 (should be at x-height 559?)

	* t (U+0074): X=111.0,Y=557.0 (should be at x-height 559?)

	* y (U+0079): X=254.0,Y=-2.0 (should be at baseline 0?)

	* y (U+0079): X=343.0,Y=-1.0 (should be at baseline 0?)

	* sterling (U+00A3): X=71.0,Y=2.0 (should be at baseline 0?) 

	* And 69 more.

Use -F or --full-lists to disable shortening of long lists. [code: found-misalignments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* lllachillumlym (U+0D56): B<<329.0,411.0>-<329.0,428.0>-<333.0,444.0>>/B<<333.0,444.0>-<325.0,429.0>-<316.0,410.0>> = 14.036243467926484

	* mamlym (U+0D2E): B<<296.0,503.5>-<275.0,501.0>-<258.0,497.0>>/B<<258.0,497.0>-<272.0,499.0>-<287.0,499.0>> = 5.110417561031158

	* uni0D5A (U+0D5A): B<<677.0,503.5>-<656.0,501.0>-<639.0,497.0>>/B<<639.0,497.0>-<653.0,499.0>-<668.0,499.0>> = 5.110417561031158

	* uni0D76 (U+0D76): B<<968.5,503.5>-<948.0,501.0>-<930.0,497.0>>/B<<930.0,497.0>-<944.0,499.0>-<960.0,499.0>> = 4.398705354995426

	* uni0D78 (U+0D78): B<<1960.5,503.5>-<1940.0,501.0>-<1922.0,497.0>>/B<<1922.0,497.0>-<1937.0,499.0>-<1952.0,499.0>> = 4.934164340559985

	* uuvowelsignmlym (U+0D42): B<<249.5,-15.5>-<243.0,5.0>-<230.0,22.0>>/B<<230.0,22.0>-<240.0,2.0>-<240.0,-19.0>> = 10.840305454330533 

	* And uuvowelsignmlym (U+0D42): B<<41.0,-19.0>-<41.0,0.0>-<51.0,21.0>>/B<<51.0,21.0>-<39.0,5.0>-<32.5,-16.5>> = 11.406552583972413 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* sterling (U+00A3): L<<419.0,336.0>--<262.0,337.0>> [code: found-semi-vertical]
</div></details><br></div></details><details><summary><b>[16] NotoSerifMalayalam-Thin.ttf</b></summary><div><details><summary>🔥 <b>FAIL:</b> Check Google Fonts glyph coverage. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/glyph_coverage">com.google.fonts/check/glyph_coverage</a>)</summary><div>


* 🔥 **FAIL** Missing required codepoints:

	- 0x00AF (MACRON)
 [code: missing-codepoints]
</div></details><details><summary>🔥 <b>FAIL:</b> Check copyright namerecords match license file. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/license">com.google.fonts/check/name/license</a>)</summary><div>


* 🔥 **FAIL** License file OFL.txt exists but NameID 13 (LICENSE DESCRIPTION) value on platform 3 (WINDOWS) is not specified for that. Value was: "This Font Software is licensed under the SIL Open Font License, Version 1.1. This Font Software is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the SIL Open Font License for the specific language, permissions and limitations governing your use of this Font Software." Must be changed to "This Font Software is licensed under the SIL Open Font License, Version 1.1. This license is available with a FAQ at: https://scripts.sil.org/OFL" [code: wrong]
</div></details><details><summary>🔥 <b>FAIL:</b> Copyright notices match canonical pattern in fonts (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/font_copyright">com.google.fonts/check/font_copyright</a>)</summary><div>


* 🔥 **FAIL** Name Table entry: Copyright notices should match a pattern similar to: "Copyright 2019 The Familyname Project Authors (git url)"
But instead we have got:
"Copyright 2021 Google Inc. All Rights Reserved." [code: bad-notice-format]
</div></details><details><summary>🔥 <b>FAIL:</b> OS/2.fsSelection bit 7 (USE_TYPO_METRICS) is set in all fonts. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/os2/use_typo_metrics">com.google.fonts/check/os2/use_typo_metrics</a>)</summary><div>


* 🔥 **FAIL** OS/2.fsSelection bit 7 (USE_TYPO_METRICS) wasNOT set in the following fonts: ['fonts/NotoSerifMalayalam/googlefonts/slim-variable-ttf/NotoSerifMalayalam[wght].ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Black.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Bold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-ExtraLight.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Light.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Medium.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Regular.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-SemiBold.ttf', 'fonts/NotoSerifMalayalam/googlefonts/ttf/NotoSerifMalayalam-Thin.ttf', 'fonts/NotoSerifMalayalam/googlefonts/variable-ttf/NotoSerifMalayalam[wght].ttf']. [code: missing-os2-fsselection-bit7]
</div></details><details><summary>🔥 <b>FAIL:</b> Checking OS/2 usWinAscent & usWinDescent. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/family/win_ascent_and_descent">com.google.fonts/check/family/win_ascent_and_descent</a>)</summary><div>


* 🔥 **FAIL** OS/2.usWinAscent value should be equal or greater than 979, but got 864 instead [code: ascent]
</div></details><details><summary>🔥 <b>FAIL:</b> Ensure dotted circle glyph is present and can attach marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/dotted_circle">com.google.fonts/check/dotted_circle</a>)</summary><div>


* 🔥 **FAIL** The following glyphs could not be attached to the dotted circle glyph:

	- uni0952

	- rephmlym

	- uni0951 

	- And candrabindumlym [code: unattached-dotted-circle-marks]
</div></details><details><summary>⚠ <b>WARN:</b> Glyphs are similiar to Google Fonts version? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/production_glyphs_similarity">com.google.fonts/check/production_glyphs_similarity</a>)</summary><div>


* ⚠ **WARN** Following glyphs differ greatly from Google Fonts version:
	* kassaprehalfmlym
	* ssattamlym
	* kassamlym and nnaddhamlym
</div></details><details><summary>⚠ <b>WARN:</b> Combined length of family and style must not exceed 27 characters. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/name/family_and_style_max_length">com.google.fonts/check/name/family_and_style_max_length</a>)</summary><div>


* ⚠ **WARN** The combined length of family and style exceeds 27 chars in the following 'WINDOWS' entries:
 FONT_FAMILY_NAME = 'Noto Serif Malayalam Thin' / SUBFAMILY_NAME = 'Regular'

Please take a look at the conversation at https://github.com/googlefonts/fontbakery/issues/2179 in order to understand the reasoning behind these name table records max-length criteria. [code: too-long]
</div></details><details><summary>⚠ <b>WARN:</b> Ensure fonts have ScriptLangTags declared on the 'meta' table. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/googlefonts.html#com.google.fonts/check/meta/script_lang_tags">com.google.fonts/check/meta/script_lang_tags</a>)</summary><div>


* ⚠ **WARN** This font file does not have a 'meta' table. [code: lacks-meta-table]
</div></details><details><summary>⚠ <b>WARN:</b> Check font contains no unreachable glyphs (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/unreachable_glyphs">com.google.fonts/check/unreachable_glyphs</a>)</summary><div>


* ⚠ **WARN** The following glyphs could not be reached by codepoint or substitution rules:

	- quotedbl

	- parenright

	- question

	- four

	- eight

	- seven

	- ellipsis

	- quotedblright

	- asterisk

	- asciicircum 

	- And 37 more.

Use -F or --full-lists to disable shortening of long lists.
 [code: unreachable-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check if each glyph has the recommended amount of contours. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/universal.html#com.google.fonts/check/contour_count">com.google.fonts/check/contour_count</a>)</summary><div>


* ⚠ **WARN** This font has a 'Soft Hyphen' character (codepoint 0x00AD) which is supposed to be zero-width and invisible, and is used to mark a hyphenation possibility within a word in the absence of or overriding dictionary hyphenation. It is mostly an obsolete mechanism now, and the character is only included in fonts for legacy codepage coverage. [code: softhyphen]
* ⚠ **WARN** This check inspects the glyph outlines and detects the total number of contours in each of them. The expected values are infered from the typical ammounts of contours observed in a large collection of reference font families. The divergences listed below may simply indicate a significantly different design on some of your glyphs. On the other hand, some of these may flag actual bugs in the font such as glyphs mapped to an incorrect codepoint. Please consider reviewing the design and codepoint assignment of these to make sure they are correct.

The following glyphs do not have the recommended number of contours:

	- Glyph name: sfthyphen.mlym	Contours detected: 1	Expected: 0

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uogonek	Contours detected: 2	Expected: 1

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12

	- Glyph name: Uogonek	Contours detected: 2	Expected: 1

	- Glyph name: aogonek	Contours detected: 3	Expected: 2

	- Glyph name: uni25CC	Contours detected: 8	Expected: 16 or 12 

	- And Glyph name: uogonek	Contours detected: 2	Expected: 1
 [code: contour-count]
</div></details><details><summary>⚠ <b>WARN:</b> Check glyphs in mark glyph class are non-spacing. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_spacing_marks">com.google.fonts/check/gdef_spacing_marks</a>)</summary><div>


* ⚠ **WARN** The following spacing glyphs may be in the GDEF mark glyph class by mistake:
	 aavowelsignmlym (U+0D3E), aulengthmarkmlym (U+0D57), auvowelsignmlym (U+0D4C), iivowelsignmlym (U+0D40), ivowelsignmlym (U+0D3F), oovowelsignmlym (U+0D4B), ovowelsignmlym (U+0D4A), rrvocalicvowelsignmlym (U+0D44), rvocalicvowelsignmlym (U+0D43), uuvowelsignmlym (U+0D42) and 4 more.

Use -F or --full-lists to disable shortening of long lists. [code: spacing-mark-glyphs]
</div></details><details><summary>⚠ <b>WARN:</b> Check mark characters are in GDEF mark glyph class. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_mark_chars">com.google.fonts/check/gdef_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following mark characters could be in the GDEF mark glyph class:
	 acutecomb (U+0301), brevecomb (U+0306), caroncomb (U+030C), cedillacomb (U+0327), circumflexcomb (U+0302), commaaccentcomb (U+0326), commaturnedabovecomb (U+0312), dieresiscomb (U+0308), gravecomb (U+0300), hungarumlautcomb (U+030B) and 8 more.

Use -F or --full-lists to disable shortening of long lists. [code: mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Check GDEF mark glyph class doesn't have characters that are not marks. (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/gdef.html#com.google.fonts/check/gdef_non_mark_chars">com.google.fonts/check/gdef_non_mark_chars</a>)</summary><div>


* ⚠ **WARN** The following non-mark characters should not be in the GDEF mark glyph class:
	 U+0D03, U+0D3E, U+0D3F, U+0D40, U+0D4A, U+0D4B, U+0D4C, U+0D4E and U+0D57 [code: non-mark-chars]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any jaggy segments? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_jaggy_segments">com.google.fonts/check/outline_jaggy_segments</a>)</summary><div>


* ⚠ **WARN** The following glyphs have jaggy segments:

	* eth (U+00F0): B<<385.5,450.5>-<412.0,431.0>-<428.0,400.0>>/B<<428.0,400.0>-<403.0,480.0>-<371.5,537.5>> = 9.945547575071476

	* jamlym (U+0D1C): B<<561.0,149.0>-<585.0,161.0>-<609.0,171.0>>/B<<609.0,171.0>-<591.0,168.0>-<570.0,167.0>> = 13.157542740014783

	* lachillumlym (U+0D7D): B<<740.0,540.0>-<784.0,531.0>-<820.0,514.0>>/L<<820.0,514.0>--<815.0,518.0>> = 13.382086018537127

	* mamlym (U+0D2E): B<<214.0,500.0>-<166.0,477.0>-<141.0,447.0>>/B<<141.0,447.0>-<189.0,487.0>-<253.0,487.0>> = 10.388857815469583

	* ssamlym (U+0D37): B<<908.5,369.0>-<909.0,415.0>-<911.0,462.0>>/B<<911.0,462.0>-<880.0,357.0>-<812.5,301.0>> = 14.01195988022966

	* sterling (U+00A3): B<<192.0,89.0>-<173.0,58.0>-<145.0,40.0>>/L<<145.0,40.0>--<149.0,42.0>> = 6.170175095029526

	* uni0D5A (U+0D5A): B<<550.0,500.0>-<502.0,477.0>-<477.0,447.0>>/B<<477.0,447.0>-<525.0,487.0>-<589.0,487.0>> = 10.388857815469583

	* uni0D76 (U+0D76): B<<853.0,500.0>-<805.0,477.0>-<780.0,447.0>>/B<<780.0,447.0>-<828.0,487.0>-<892.0,487.0>> = 10.388857815469583

	* uni0D78 (U+0D78): B<<1660.0,500.0>-<1612.0,477.0>-<1587.0,447.0>>/B<<1587.0,447.0>-<1635.0,487.0>-<1699.0,487.0>> = 10.388857815469583

	* uuvowelsignmlym (U+0D42): B<<230.0,6.5>-<214.0,37.0>-<187.0,60.0>>/B<<187.0,60.0>-<202.0,42.0>-<210.0,25.0>> = 9.768350167635653 

	* And uuvowelsignmlym (U+0D42): B<<39.5,28.5>-<49.0,45.0>-<62.0,61.0>>/B<<62.0,61.0>-<34.0,38.0>-<18.0,6.5>> = 11.505480450291047 [code: found-jaggy-segments]
</div></details><details><summary>⚠ <b>WARN:</b> Do outlines contain any semi-vertical or semi-horizontal lines? (<a href="https://font-bakery.readthedocs.io/en/stable/fontbakery/profiles/<Section: Outline Correctness Checks>.html#com.google.fonts/check/outline_semi_vertical">com.google.fonts/check/outline_semi_vertical</a>)</summary><div>


* ⚠ **WARN** The following glyphs have semi-vertical/semi-horizontal lines:

	* exclam.mlym (U+0021): L<<111.0,167.0>--<107.0,714.0>>

	* exclam.mlym (U+0021): L<<135.0,714.0>--<133.0,167.0>>

	* exclamdown (U+00A1): L<<123.0,-177.0>--<124.0,370.0>> 

	* And exclamdown (U+00A1): L<<149.0,370.0>--<152.0,-177.0>> [code: found-semi-vertical]
</div></details><br></div></details>
### Summary

| 💔 ERROR | 🔥 FAIL | ⚠ WARN | 💤 SKIP | ℹ INFO | 🍞 PASS | 🔎 DEBUG |
|:-----:|:----:|:----:|:----:|:----:|:----:|:----:|
| 0 | 71 | 101 | 1235 | 78 | 950 | 0 |
| 0% | 3% | 4% | 51% | 3% | 39% | 0% |

**Note:** The following loglevels were omitted in this report:
* **SKIP**
* **INFO**
* **PASS**
* **DEBUG**
