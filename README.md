# Designer

A simple monospaced resume theme for Hugo. It has originated from [ojroques/hugo-researcher](https://github.com/ojroques/hugo-researcher) and the design is inspired by [nezu.worl](https://nezu.world/)
To add custom fonts, go to baseof.html in "layouts/default" and import the link at the top of the page, then edit config correspondingly. 

## Installation
This theme uses Sass to generate CSS files so make sure you have the
*extended* Hugo version installed.

Add the theme to your site's `themes` directory:
```bash
git submodule add https://github.com/alamine53/designer.git themes/designer
```

Update the theme option in `config.toml`:
```toml
theme = "designer"
```

## Configuration
A self-explanatory configuration file is present in
[exampleSite/config.toml](/exampleSite/config.toml),
along the files of a demo website.

## Typeface


## KaTeX
You can enable [KaTeX](https://katex.org/) (math typesetting) by including
`math: true` in your content files. Or you can enable it globally by setting
`math` to `true` in your project config.

Hugo introduces tags when it sees newlines which breaks KaTeX block
environments. The theme has a `math` shortcode to circumvent this issue:
```md
{{< math >}}
\begin{pmatrix}
a & b \\
c & d
\end{pmatrix}
{{< /math >}}
```


## License
[GPL-3.0 License](https://github.com/alamine53/designer/blob/master/LICENSE)
