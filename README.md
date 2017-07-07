FPDI - Free PDF Document Importer
=================================

[![Latest Stable Version](https://poser.pugx.org/setasign/fpdi/v/stable.svg)](https://packagist.org/packages/setasign/fpdi) [![Total Downloads](https://poser.pugx.org/setasign/fpdi/downloads.svg)](https://packagist.org/packages/setasign/fpdi) [![Latest Unstable Version](https://poser.pugx.org/setasign/fpdi/v/unstable.svg)](https://packagist.org/packages/setasign/fpdi) [![License](https://poser.pugx.org/setasign/fpdi/license.svg)](https://packagist.org/packages/setasign/fpdi)

A clone of [FPDI](https://www.setasign.com/fpdi) for GitHub/[Composer](https://packagist.org/packages/setasign/fpdi).

FPDI is a collection of PHP classes facilitating developers to read pages from existing PDF documents and use them as templates in FPDF, which was developed by Olivier Plathey. Apart from a copy of FPDF, FPDI does not require any special PHP extensions.

## Installation with [Composer](https://packagist.org/packages/setasign/fpdi)

FPDI is an add-on for [FPDF](http://fpdf.org/). Additionally FPDI can be used with [TCPDF](http://www.tcpdf.org/).
For completion we added a [FPDF repository](https://github.com/Setasign/FPDF) which simply clones the offical releases.

This package comes without any dependency configuration in the composer.json file. It's up to you to load the desired package as described below.

A basic installation via Composer could be done this way:

```bash
$ composer require jasonll/chinese_fpdi
```
fpdi 支持中文包

```php
class_exists('TCPDF', true); // trigger Composers autoloader to load the TCPDF class
$pdf = new FPDI();
```

