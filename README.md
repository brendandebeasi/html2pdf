# Html2Pdf - Forked
Forked from the [original html2pdf package by spipu](https://github.com/spipu/html2pdf). 
Includes performance fixes from [meritel](https://github.com/meritel/html2pdf)

Html2Pdf is a HTML to PDF converter written in PHP, and compatible with PHP **7.2** to **8.4**.

It allows the conversion of valid HTML in PDF format, to generate documents like invoices, documentation, ...

You have to write specific cleaned HTML code for Html2Pdf.
Do not try to convert directly an already existing html page, or HTML code coming from WYSIWYG, no help will be provided in this case.

Specific tags have been implemented, to adapt the html standard to a PDF usage.

You must use Composer to install this library.

It uses TCPDF for the PDF part.

## Requirements

Html2Pdf works with PHP >7.2 and Composer.

You will also need at least the following php extensions:

* gd
* mbstring

## Documentation

You will find the install documentation [here](./doc/install.md).

You will find all the documentation [here](./doc/README.md).

You will find lots of examples [here](./examples).

## Donate

You can support this project by making a [donation](http://html2pdf.fr/en/donate).

## Change log

See the [./CHANGELOG.md](./CHANGELOG.md) file.

## Help & Support

For questions and bug reports, please use the GitHub issues page.

## License

This program is distributed under the OSL License. For more information see the [./LICENSE.md](./LICENSE.md) file.

Copyright 2008-2025 by Laurent Minguet
