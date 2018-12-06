# driven-snow
❄️A light, bare-bones custom theme for Rstudio❄️

## Theme

**driven-snow** is a light theme that maximizes space by stripping away some of
the point/click toolbars that come standard with the Rstudio interface. It is 
not recommended for users who often rely on Rstudio toolbars (instead of, say,
keyboard shortcuts). It's also a work-in-progress–stripping away non-ID'd
elements of the UI via CSS is an inexact/hacky solution, so no promises😜!

To add the theme to your Rstudio desktop, you can either download the 
[theme file](theme/drive-snow.rstheme) and add to the Rstudio theme folder or
try the following code (note: this code can also be adapted to add a local
version of the theme).

``` r
### add theme and apply immediately
rstudioapi::addTheme(
  tfse::github_raw("theme/driven-snow.rstheme", repo = "mkearney/driven-snow"),
  apply = TRUE
)
```

## Fonts

**drive-snow** changes the default UI theme from Lucida Grande to either 
Helvetica or the system's default sans-serif font. The recommended monospace 
font is **L-Consolas** (Consolas with ligatures), which can be found in the 
[fonts](fonts) folder.

## Screen shot

![](img/screen-shot.png)
