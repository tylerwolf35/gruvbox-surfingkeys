# Gruvbox for Surfingkeys
The [gruvbox](https://github.com/morhetz/gruvbox) colorscheme for [Surfingkeys](https://github.com/brookhong/Surfingkeys)
* Currently only the dark variant of gruvbox is available
![gruvbox-surfingkeys](https://user-images.githubusercontent.com/47761974/79020165-16488500-7b46-11ea-817a-b70e493adf1e.png)
## How to use
Set the theme in the Surfingkeys settings, advanced mode must be enabled. The font settings can be whatever you want, I have the default font options in the configuration below.

```
// set theme
settings.theme = `
.sk_theme {
    font-family: Input Sans Condensed, Charcoal, sans-serif;
    font-size: 10pt;
    background: #282828;
    color: #ebdbb2;
}
.sk_theme tbody {
    color: #b8bb26;
}
.sk_theme input {
    color: #d9dce0;
}
.sk_theme .url {
    color: #98971a;
}
.sk_theme .annotation {
    color: #b16286;
}
.sk_theme .omnibar_highlight {
    color: #ebdbb2;
}
.sk_theme #sk_omnibarSearchResult>ul>li:nth-child(odd) {
    background: #282828;
}
.sk_theme #sk_omnibarSearchResult>ul>li.focused {
    background: #d3869b;
}
#sk_status, #sk_find {
    font-size: 20pt;
}`;
```
