# Ek Mukta

Ek Mukta is a Unicode compliant, versatile, contemporary, humanist, mono-linear typeface available in seven weights, supporting Devanagari and Latin scripts. This type family is a libre licensed version the Ek multi-script family, an ongoing project to develop a unified type family for each Indian script. The goal is to build one harmonious family across all Indian scripts without letting the visual features of one script dominate over others. This ensures that the fonts can be used successfully for both single and multi-script purposes. This project is led by [Ek Type](http://ektype.in/), a collective of type designers based in Mumbai focused on designing contemporary Indian typefaces. 

Ek Mukta was designed by [Girish Dalvi](http://www.idc.iitb.ac.in/~girish/) and [Yashodeep Gholap](http://www.yashodeepgholap.com/), with extensive support from [Noopur Datye, Sarang Kulkarni and Maithili Shingre](http://ektype.in/). We would like to thank Vinay Saynekar, Santosh Kshirsagar, Shubhanand Jog, Yogesh Jahargirdar, Pradnya Naik, Snehal Patil, Pallavi Karambelkar, and Omkar Shende for their suggestions and feedback during the font design process. We would also like to thank faculty and friends from the Industrial Design Centre, IIT Bombay and from Sir J J Institute of Applied Art for their support and encouragement.

A short demonstration on the possibilities of using Indic web fonts on the web can be seen here. [Demonstration on how to use Devanagari on the web using Web Fonts and Ek Mukta)](http://www.idc.iitb.ac.in/~girish/demo/).

## License

Ek Mukta is licensed under the SIL Open Font License v1.1 (<http://scripts.sil.org/OFL>)

To view the copyright and specific terms and conditions please refer to [OFL.txt](https://github.com/girish-dalvi/Ek-Mukta/blob/master/OFL.txt)

## Downloading font binaries (TTF files)

Find binary releases on <https://github.com/girish-dalvi/Ek-Mukta/releases>

The font binaries are not directly part of this repository, as it only contains source files; however, the binaries are directly built from the ttx files in the `TTX` directory.

## How do I install the font on my computer?

First download the font binaries (TTF files) from the master branch, then follow the instructions given below.

- [Windows](http://windows.microsoft.com/en-us/windows-vista/install-or-uninstall-fonts)

- [GNU/Linux](http://lmgtfy.com/?q=how+to+install+fonts+in+linux)

- [Mac OS X](http://support.apple.com/kb/HT2509)

## Getting Involved

Would you like to contribute to the development of this font? Here is how **you** can help:

1. Tell us about any bugs you find, or enhancements you would like to see

2. Contribute directly to the fonts. In this repository we provide the complete set of source files that we use ourselves to develop the fonts. If you with to contribute directly, please see below how we build the fonts and follow our build process so that we can easily include your contribution, and follow the Github pull request process to send your contribution. 

### Bug Reports

Send us bug reports, feature enhancements or glyph requests, using the [Github Issue Tracker](https://github.com/girish-dalvi/Ek-Mukta/issues/). Here are a few tips:

- Bugs must be isolated and reproducible problems that we can fix. This means telling us step by step how we can produce the bug.

- Search for existing issues. We do not want duplicate issues, and you'll help us out a lot by first checking if someone else has reported the same issue. 

- Share as much information as possible. Include your operating system and its version, what application(s) you found the problem with and their version, etc. 

## Building the font from source
   
The build process used by Ek Type is as follows:

1. Make changes in FontLab `.vfb` file

2. Generate the `.ttf` file

3. Open the `.ttf` file in VOLT, import the appropriate `.vtp` file

4. Make changes if required in the `.vtp` file.

5. Ship the font from VOLT

6. Run ttfautohint using the batch file. `$ Autohint.bat`

This requires the following programs:

- **[Fontlab Studio](http://www.fontlab.com/font-editor/fontlab-studio/):** `.vfb` design files are used by this font editor, for Windows and Mac from the Fontlab company with a proprietary license and requiring a license fee from each user. 

- **[VOLT](http://www.microsoft.com/typography/VOLT.mspx):** `.vtp` files are used with this OpenType Layout (GPOS, GSUB) table editor, for Windows from Microsoft, with a proprietary license and free of charge

- **[MS CacheTT](http://www.microsoft.com/typography/tools/tools.aspx):** Font engineering tool for VDMX, hdmx and LTSH tables, for Windows from Microsoft, with a proprietary license and free of charge

- **[ttfautohint](http://www.freetype.org/ttfautohint/):** Auto-hinter, for all platforms, from the Freetype Project, with a libre license

### Branches and Pull Requests

To learn more about Pull Requests, see Github's great article on [using pull requests](https://help.github.com/articles/using-pull-requests) and play the [interactive learning game](http://try.github.com) that takes around 15 minutes to complete.

- `master` is the latest, stable, tested version 

- Add your name to the contributors file

- Explain in the pull request how you have tested your contribution

### Roadmap

- Port the OpenType Layout code to [Adobe Feature File format](http://www.adobe.com/devnet/opentype/afdko/topic_feature_file_syntax.html)

- Port the build process to the [Adobe Font Development Kit for OpenType](http://www.adobe.com/devnet/opentype/afdko.html)
