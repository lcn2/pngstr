# pngstr

turn an string into a PNG image


# To install

```sh
sudo make install
```


# Examples

```sh
$ /usr/local/bin/pngstr -o chongo.png 'chongo was here'
```

```sh
$ /usr/local/bin/pngstr -o big-chongo.png -f red -b black -H 32 'chongo was here'
```


# To use

```
/usr/local/bin/pngstr [-h] [-v lvl] [-V] [-o output.png] [-fg fg_color] [-b bg_color]
	[-W width] [-H height] [-t trim_width] [-x adjust_x] [-y adjust_y] text

    -h              print help and exit
    -v lvl          verbose / debug level
    -V              print version and exit

    -o output.png   output filename (default: output.png)
    -f fg_color     foreground / text color (default: black)
    -b bg_color     background color (default: white)
    -W width        image width in pixels (default: length(text)*9)
    -H height       image height in pixels (default: 16)
    -t trim_width   reduce the width of the image in pixels (default: 0)
    -x adjust_x     adjust text position left(>0)/right(<0) (default: 0)
    -y adjust_y     adjust text position up(>0)/down(<0) (default: 0)

pngstr version: 1.12.1 2025-03-26
```


# Reporting Security Issues

To report a security issue, please visit "[Reporting Security Issues](https://github.com/lcn2/pngstr/security/policy)".
