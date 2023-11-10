# rainbow-echo

## Install

```bash
sudo curl -o /usr/bin/rainbow-echo https://raw.githubusercontent.com/abdosbaai/rainbow-echo/main/rainbow-echo && sudo chmod +x /usr/bin/rainbow-echo
```
### (man page)

```bash
sudo curl -o /usr/share/man/man1/rainbow-echo.1 https://raw.githubusercontent.com/abdosbaai/rainbow-echo/main/rainbow-echo.1
```

## Description

**rainbow-echo** is a Bash script that allows you to customize the appearance of a given string in the terminal. You can specify various formatting options such as text color, background color, bold, underline, and inverse text. The script supports a variety of color options and formatting styles, making it a fun tool for enhancing your terminal output.

## Usage

```bash
rainbow-echo [Options] -c <color-name> String
rainbow-echo [Options] --color=<color> String
rainbow-echo [Options] --color=<color> --bg-color=<color> String
rainbow-echo [Options] -c color -bg color String
```

## Options

<ul>
    <li><b>-h, --help </b>:Display the help message.</li>
    <li><b>-c, --color</b>: Specify the color name.</li>
    <li><b>-bg, --bg-color</b>: Specify the background color name.</li>
    <li><b>-n</b>: Do not output the trailing newline.</li>
    <li><b>-b</b>: Make the text bold.</li>
    <li><b>-u</b>: Underline text.</li>
    <li><b>-i</b>: Inverse the foreground and the background color.</li>
</ul>

## Color Options

### The following color options are available

<ul>
    <li>red</li>
    <li>blue</li>
    <li>green</li>
    <li>cyan</li>
    <li>magenta</li>
    <li>yellow</li>
    <li>black</li>
    <li>white</li>
</ul>

## Text Styles

### The script supports the following text styles:

<ul>
    <li>Bold</li>
    <li>Underline</li>
    <li>Inverse (foreground and background colors)</li>
</ul>

## Examples

1.Display red bold text:
```bash
rainbow-echo -c red -b "Hello, World!"
```

2.Display blue underlined text without a newline:
```bash
rainbow-echo -c blue -u -n "This is underlined text"
```
3.Display green text with a cyan background:
```bash
rainbow-echo -c green -bg cyan "Formatted Text"
```
## Notes

<ul>
    <li>The script uses ANSI escape codes for text formatting, so ensure your terminal supports these codes.</li>
    <li>If an unavailable color is provided, an error message will be displayed along with the help message.</li>
</ul>

## Auther

<ul>
    <li>Abdessadek Sbaai</li>
</ul>

## License

rainbow-echo is distributed under the terms of the MIT License:

Copyright (c) 2023 Abdessadek Sbaai

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.