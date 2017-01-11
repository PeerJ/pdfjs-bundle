# PdfjsBundle

The sole purpose of this bundle is to make available the compiled versions of `pdf.js` and `pdf.worker.js`, as provided by `bower install pdfjs-dist`.

## Usage

In a Twig template, add the following:

```twig
{% include '@peerjPdfjs/include.html.twig' %}
```

## Updating

Run `bower install pdfjs-dist` somewhere else, copy pdf.js and pdf.worker.js into Resources/public/js, commit them to this repository and create a new release.
