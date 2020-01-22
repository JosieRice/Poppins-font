# Poppins-font

The CSS and web font files to easily self-host “Poppins”. Based on adobe fonts which allow font-feature-settings.

# Use

Typefaces assume you’re using webpack to process CSS and files. Each typeface package includes all necessary font files (woff2, woff) and a CSS file with font-face declarations pointing at these files.

You will need to have webpack setup to load css and font files. Many tools built with Webpack will work out of the box with Typefaces such as Gatsby and Create React App.

To use, simply require the package in your project’s entry file e.g.

```
// Load Poppins typeface
require('typeface-poppins')
```

# Why Did I publish this

I needed a stable version of Poppins font that included font-feature-settings (which weren't available with Google fonts).