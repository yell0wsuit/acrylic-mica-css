# Microsoft's Acrylic & Mica material design in CSS
This repo attempts to recreate Acrylic and Mica material design in CSS.

Acrylic material is implemented by using ``backdrop-filter``. This feature works best with a background image. Currently this only implemented 2 out of 4 layers: blur and noise texture. It is based on [this documentation](https://docs.microsoft.com/en-us/windows/apps/design/style/acrylic).  
Note that Firefox does not support this feature, to use this, you need to enable ``layout.css.backdrop-filter.enabled`` and ``gfx.webrender.all`` in ``about:config``.

Mica material can be used with or without ``backdrop-filter``. It is based on [this documentation](https://docs.microsoft.com/en-us/windows/apps/design/style/mica).

All themes here have black variant for dark theme, which are also based on official documentations.

# Demo
[Acrylic demo](https://yell0wsuit.github.io/acrylic-mica-css/acrylic.html)

[Mica demo](https://yell0wsuit.github.io/acrylic-mica-css/mica.html)
