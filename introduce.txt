

> $ clean-mark "http://some-website.com/fancy-article"

The article will be automatically named using the URL path name. In the case, above, the name will be `fancy-article.md`.

The file type can be specified:

> $ clean-mark "http://some-website.com/fancy-article" -t html

The available types are: HTML, TEXT and Markdown.

The output file and path can be also specified:

> $ clean-mark "http://some-website.com/fancy-article" -o /tmp/article

In that case the output will be `/tmp/article.md`. The extension is added automatically.


## Installation

Simply install with npm:

 npm install clean-mark --global







