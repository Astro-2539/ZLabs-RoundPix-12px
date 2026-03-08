[简体中文](/README.md) | **English**

> [!IMPORTANT]
> 
> This article is translated by artificial intelligence.
> 


# Z Labs RoundPix 12px

![Title](/img/1.png "Title")

**Z Labs RoundPix 12px** is a 12px Chinese pixel font (actual occupied size of Chinese characters is 11*11) modified and supplemented based on the Japanese font [**x12y12pxMaruMinya**](https://github.com/hicchicc/x12y12pxMaruMinya), adopting a rounded glyph style with Western characters drawn to a monospaced specification.

This project is in the development stage. Currently, it supports Level 1 Chinese characters (and a small number of Level 2 characters) in GB/T 2312, common Western characters, and common punctuation marks, meeting the basic needs for using simplified Chinese characters in simple scenarios.

> [!WARNING]
> 
> **This font is still under development.** There are missing characters, and the details of glyphs are yet to be adjusted.
> 
> If you encounter any issues during use, please promptly provide feedback in the Issues section.

> [!IMPORTANT]
> 
> Extensive modifications have been made to the original font to adapt it to the Simplified Chinese environment. For scenarios requiring Japanese usage, it is recommended to use the original font [**x12y12pxMaruMinya**](https://github.com/hicchicc/x12y12pxMaruMinya).

> [!IMPORTANT]
> 
> We are conducting a survey on the usage requirements for pixel fonts.
>
> If possible, please help fill out the questionnaire below. Thank you very much!
>
> https://f.kdocs.cn/g/EwkAraFp/

## Font Introduction

![Introduction Page 1](/img/2.png "Introduction Page")

![Introduction Page 2](/img/3.png "Introduction Page 2")

![Typesetting Example](/img/4.png "Typesetting Example")

![License Page](/img/5.png "License Page")

> [!TIP]
>
> Need larger size? Try [Z Labs RoundPix 16px](https://github.com/Astro-2539/ZLabs-RoundPix-16px)

## Font Coverage

### Chinese Characters

#### Mainland China Variant Glyphs (CN)

&nbsp;&nbsp;&nbsp;&nbsp;🚧 GB/T 2312 (4897 / 6763)

&nbsp;&nbsp;&nbsp;&nbsp;🚧 *Table of General Standard Chinese Characters*（通用规范汉字表） (5001 / 8105)

&nbsp;&nbsp;&nbsp;&nbsp;🚧 Big5 Common Chinese Character List (4721 / 5401)

&nbsp;&nbsp;&nbsp;&nbsp;🚧 *Standard Form of Common National Characters Table* (4411 / 4808)

&nbsp;&nbsp;&nbsp;&nbsp;🚧 jf7000 Priority Character Set Basic Package (5256 / 6373)

&nbsp;&nbsp;&nbsp;&nbsp;🚧 GB/T 12345 (5170 / 6866)

&nbsp;&nbsp;&nbsp;&nbsp;ℹ️ Total supported Chinese characters: 8013

## Building the Font from Project Files

Glyphs of this font are drawn using [Bits'n'Picas](https://github.com/kreativekorp/bitsnpicas).

The build script is written in Python. Run `./tools/build.py` to generate the font.

The build process depends on the `fonttools` library, `pixel_font_builder` library, and `kbitfont` library.

## Font License

The license of this project is divided into two parts: "Glyphs" and "Build Code".

### Glyphs

This font is a derivative work based on [**x12y12pxMaruMinya**](https://github.com/hicchicc/x12y12pxMaruMinya) produced by [x0y0pxFreeFont](https://hicchicc.github.io/00ff/).

Previously, *x12y12pxMaruMinya* used a self-declared license from x0y0pxFreeFont (see the vendor's homepage for details). In February 2026, x0y0pxFreeFont added the [SIL OFL-1.1](https://openfontlicense.org/open-font-license-official-text/) license to this font. Therefore, the glyphs part of this project is also licensed under the [SIL OFL-1.1](https://openfontlicense.org/open-font-license-official-text/) license.

You may use this font for various purposes, including commercial and embedded use, without requiring additional authorization from the font author.

When redistributing this font, you shall include the original text or a link to the OFL license agreement.

In accordance with the OFL agreement, if you create a derivative font using this font, the derivative font must also comply with the OFL agreement (or a compatible agreement). You are not allowed to use the reserved names of this font without the author's authorization. **You may not sell this font software alone.**

The author of this font, Astro_2539, reserves the font names "Z工坊" and "Z Labs".

### Build Code

Licensed under the MIT License.

## Acknowledgments

[患者長ひっく (hicc)](https://github.com/hicchicc) for providing the original glyphs and converting them to the SIL OFL-1.1 license.

[Bits'N'Picas](https://github.com/kreativekorp/bitsnpicas) for providing the pixel glyph editing software.

[@狼人小林 (TakWolf)](https://github.com/TakWolf) for technical support. Some glyphs in this work refer to his [Ark Pixel Font 12px](https://github.com/TakWolf/ark-pixel-font/).

## Related Resources

[zi.tools](https://zi.tools/) - A website covering the origin, form, pronunciation, meaning, and encoding of Chinese characters.

## Sponsor the Author

[Click to enter the donation page](https://github.com/Astro-2539/Astro-2539/blob/main/donate.md)

## Project Stars Statistics

[![Stargazers over time](https://starchart.cc/Astro-2539/ZLabs-RoundPix-12px.svg?variant=adaptive)](https://starchart.cc/Astro-2539/ZLabs-RoundPix-12px)