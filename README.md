# DaSL Quarto HTML Theme

A Quarto HTML report theme for the Fred Hutch Data Science Lab (DaSL).

## Create a new report

You can use this as a template to create an HTML report.
To do this, use the following command:

```
quarto use template fhdsl/dasl-quarto-html
```

This will install the extension and create the `template.qmd` file that you can
use as a starting place for your report.

## Installation for an existing document

You may also use this format with an existing Quarto project or document.
From the quarto project or document directory, run the following command to
install this format:

```
quarto install extension fhdsl/dasl-quarto-html
```

Then add `format: dasl-html` to the quarto YAML header.

## Fred Hutch branding

This report uses CSS styling based on the Fred Hutch branding guidance 
available at <https://brand.fredhutch.org/>.

![](example.png)
