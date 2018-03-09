# subeta-templates

A repository for [Subeta](https://subeta.net) templates. There are 3 types:
1. Pet profiles
2. User profiles
3. Custom CSS

Templates can range from simple resets to customisable templates.

## Minified CSS

Each CSS file will come in two versions:

1. **The full version** - The code is neatly formatted and contains comments explaining each line. This is ideal for people who wish to learn how the CSS works to customize their own version.
2. **The minified version** - The output of a CSS minifier, which compresses the code so that it takes up less space and is more efficient to include. If you just want to use the CSS out-of-the-box, use this version.

To minify with `yui-compressor` use the following command:

```yui-compressor filename.css > filename.min.css```

You can install `yui-compressor` on Ubuntu with the following command:

```sudo apt-get install yui-compressor```