# HK Grotesk CSS

This repo provides you with a proper CSS file for importing the beautiful [HK Grotesk](https://github.com/HankenDesignCo/HK-Grotesk) to your project. Just add this to your HTML head:
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/drinking-code/HK-Grotesk-Web/font.min.css">
```
...or this to your CSS:
```css
@import url('https://cdn.jsdelivr.net/gh/drinking-code/HK-Grotesk-Web/font.min.css');
```

## Includes
- all weights from `100 thin` to `900 black`
- regular and italics
- `font-display: swap` for faster text-rendering
- `woff2` and `woff` links

## Use
As described on the [website](http://hkgrotesk.com), there are a couple of alternations. To use these just paste in the CSS attributes provided with each one. The alternations are as follows:  

**Set 1** (normal "g")  
`font-feature-settings: "ss01"`  
<img src="images/set-01.svg" height="50">  

**Set 2** (legacy "g")  
`font-feature-settings: "ss02"`  
<img src="images/set-02.svg" height="50">  

**Set 3** (round dots)  
`font-feature-settings: "ss03"`  
<img src="images/set-03.svg" height="50">  

**Ordinals**  
`font-feature-settings: "ordn"`  
<img src="images/set-04.svg" height="50">  

**Discretionary Ligatures**  
`font-feature-settings: "dlig"`  
<img src="images/set-05.svg" height="50">  

**Ligatures**  
`font-variant-ligatures: common-ligatures` (default in all browsers)  
<img src="images/set-06.svg" height="50">  

**Fractions**  
`font-feature-settings: "frac"`  
<img src="images/set-08.svg" height="50">  
  
_Note_: You can also chain them like this:
```css
font-feature-settings: "ss01", "ss03";
```

## Licenses
The font HK Grotesk is licensed under the [Open Font License (1.1)](HKGrotesk-OFL.txt).  
`font.css` and `font.min.css` are licensed under the [CC0 1.0 Universal](LICENSE) license. (Public Domain)  
Yeah, that's a license for a font-face CSS file.
