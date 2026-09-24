# Epsilon Markdown Theme

[![GitHub tag](https://img.shields.io/github/tag/gustavosotnas/epsilon-markdown-theme.svg?label=version)](https://github.com/gustavosotnas/epsilon-markdown-theme/releases)

**Epsilon** – a Markdown theme freely inspired by [Epsilon Notes](https://ekartoyev.github.io/epsilon_notes).

![Lorem ipsum - Epsilon](https://raw.githubusercontent.com/wiki/gustavosotnas/epsilon-markdown-theme/lorem-ipsum-epsilon.png)

Epsilon is an elegant Markdown theme that combines shades of blue and gray with subtle drop shadows on blockquotes, tables, code snippets, and images, giving them a sense of depth similar to [Material Design](https://material.io/guidelines).

Featuring the world's most recognizable serif font – [Times New Roman](https://en.wikipedia.org/wiki/Times_New_Roman) –, centered main titles, small-caps headings, and paragraph indentations, this theme is also perfectly suited for printing.

## Download and usage

**Epsilon** is avaliable for use in 3 ways:

* Epsilon Markdown Theme for [Atom](https://atom.io) (requires the package [`markdown-preview-enhanced` by shd101wyy](https://shd101wyy.github.io/markdown-preview-enhanced));
* Epsilon Markdown Theme for [Typora](https://typora.io) editor;
* Epsilon Markdown Theme Inline CSS (for old or custom Markdown parsers).

To download **Epsilon**, click in the button of your choice below:

[![Download for Atom](https://img.shields.io/badge/%20Download%20for-Atom-74c9b4.svg?style=for-the-badge&logo=atom&colorA=263238&logoColor=74c9b4)](https://raw.githubusercontent.com/gustavosotnas/epsilon-markdown-theme/master/src/markdown-preview-enhanced/style.less) [![Download for Typora](https://img.shields.io/badge/%20Download%20for-Typora-bababa.svg?style=for-the-badge&logo=t-mobile&colorA=263238&logoColor=efefef)](https://raw.githubusercontent.com/gustavosotnas/epsilon-markdown-theme/master/src/typora/epsilon.css) [![Download Inline CSS](https://img.shields.io/badge/%20Download-Inline%20CSS-1572B6.svg?style=for-the-badge&logo=css3&colorA=263238&logoColor=1572B6)](https://raw.githubusercontent.com/gustavosotnas/epsilon-markdown-theme/master/src/inline-css/epsilon.html) [![Download All](https://img.shields.io/badge/%20Download-All-e04a3f.svg?style=for-the-badge&colorA=263238)](https://github.com/gustavosotnas/epsilon-markdown-theme/archive/master.zip)

### Installation for Atom

Assuming that you already have the package [`markdown-preview-enhanced` by shd101wyy](https://shd101wyy.github.io/markdown-preview-enhanced) installed:

#### Recommended way

1. Open Atom's Command Palette ("View" > "Toggle Command Palette" or press `Ctrl` + `Shift`+`P`).
2. Search or type this command: **`Markdown Preview Enhanced: Customize Css`**. It opens a file called `style.less`.
3. Copy all text in  `style.less` file that you downloaded here and paste in that file.
4. Save the file and close it.
5. Enjoy!

#### Programmatic way

_This way can override all custom styles that was previously in `style.less` file without your consent!_

1. Copy the `style.less` file that you downloaded here and paste in `~/.mume` folder.
2. Enjoy!

### Installation for Typora

1. Open Typora's themes folder ("File" > "Preferences..." > "Open themes folder"). It opens your file explorer in that folder.
2. Copy the `epsilon.css` file that you downloaded here and paste in themes folder.
3. Restart Typora. The theme will be avaliable in "Themes" menu. Click on "Epsilon".
4. Enjoy!

### Using the inline CSS

It is possible to use **Epsilon** in Markdown files generating HTML with inline CSS. It works only on Markdown parsers that doesn't sanitize inline CSS in Markdown files (see the list of most Markdown parsers [here](https://www.w3.org/community/markdown/wiki/MarkdownImplementations)).

1. Copy all text in `epsilon.html` file that you downloaded here and paste in the beggining of your Markdown file.
2. Parse your Markdown file.
3. Enjoy!
