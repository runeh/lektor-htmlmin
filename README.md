# lektor-htmlmin

HTML minifier for Lektor that automatically minifies generated .html files. This plugin is based on [htmlmin](https://github.com/mankyd/htmlmin).

## Installation

You can install lektor-htmlmin using Lektor's plugin installer:

```
lektor plugins add lektor-htmlmin
```

Or modifying your lektorproject file, adding the plugin to the packages section:

```
[packages]
lektor-htmlmin = 0.2
```

## Usage
When the build command is run, lektor-htmlmin will automatically minify .html files in the build destination
folder, after lektor has finished building them.
The original files will be overwritten by their minified counterpart.

```
lektor build -O my_build_folder
```
