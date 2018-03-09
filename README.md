# MkDocs Codehilite Themes

A collection of Pygment css themes compatible with the __codehilite__ extension used by [MkDocs](http://www.mkdocs.org/).

## Usage

Move the __css__ directory into your MkDocs "docs" dir. Make sure the following is in your __mkdocs.yml__ file:

```
extra_css:
  - css/<theme-file-name>.css
markdown_extensions:
  - codehilite
```

### extra.css

The _extra.css_ file adds a little bit of padding to the codehilite display box, and is completely optional.

To use it, add it to your __css__ directory, and in the __mkdocs.yml__ "extra_css" section:

```
extra_css:
  - css/extra.css
  - css/<theme-file-name>.css
```

### Source

The css files originated from [https://github.com/richleland/pygments-css](https://github.com/richleland/pygments-css) and were slightly altered to work with MkDocs.