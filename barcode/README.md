# barcode

Barcode generation library for Dart that can generate generic drawing operations for any backend.

* If you are looking to print barcodes, use [pub:pdf](https://pub.dev/packages/pdf).
* If you want to display barcodes in a Flutter application, use [pub:barcode_widget](https://pub.dev/packages/barcode_widget).
* To generate SVG barcodes see the example tab.
* To generate barcodes in images, use [pub:barcode_image](https://pub.dev/packages/barcode_image).

They all use this library to generate the drawing operations.

---

[![Buy Me A Coffee](https://bmc-cdn.nyc3.digitaloceanspaces.com/BMC-button-images/custom_images/orange_img.png "Buy Me A Coffee")](https://www.buymeacoffee.com/JORBmbw9h "Buy Me A Coffee")

This library is the base to create flutter widgets or [pdf](https://pub.dev/packages/pdf) barcodes. It depends only on dart with no platform-dependent implementation.

Only two basic drawing primitives are required:

* Filled rectangle to draw the bars
* Text drawing to display the code in full-text

See the example for how to use it.

The following barcode images are SVG. The proper rendering, especially text, depends on the browser implementation and availability of the fonts.

## 1D Barcodes

### Code 39

<img width="250" alt="CODE 39" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/code-39.svg?sanitize=true">

### Code 93

<img width="200" alt="CODE 93" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/code-93.svg?sanitize=true">

### Code 128 A

<img width="300" alt="CODE 128 A" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/code-128a.svg?sanitize=true">

### Code 128 B

<img width="300" alt="CODE 128 B" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/code-128b.svg?sanitize=true">

### Code 128 C

<img width="200" alt="CODE 128 C" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/code-128c.svg?sanitize=true">

### GS1-128

<img width="300" alt="GS1 128" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/gs1-128.svg?sanitize=true">

### ITF-14

<img width="300" alt="ITF 14" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/itf-14.svg?sanitize=true">

### EAN 13

<img width="200" alt="EAN 13" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/ean-13.svg?sanitize=true">

### EAN 8

<img height="100" alt="EAN 8" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/ean-8.svg?sanitize=true">

### EAN 2

<img height="100" alt="EAN 2" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/ean-2.svg?sanitize=true">

### EAN 5

<img height="100" alt="EAN 5" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/ean-5.svg?sanitize=true">

### ISBN

<img width="200" alt="ISBN" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/isbn.svg?sanitize=true">

### UPC-A

<img width="200" alt="UPC A" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/upc-a.svg?sanitize=true">

### UPC-E

<img height="100" alt="UPC E" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/upc-e.svg?sanitize=true">

### Telepen

<img width="200" alt="Telepen" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/telepen.svg?sanitize=true">

### Codabar

## 2D Barcodes

<img width="200" alt="Codabar" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/codabar.svg?sanitize=true">

## QR-Code

<img width="200" alt="QR-Code" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/qr-code.svg?sanitize=true">

## PDF417

<img width="200" alt="PDF417" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/pdf417.svg?sanitize=true">

## Data Matrix

<img width="200" alt="Data Matrix" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/data-matrix.svg?sanitize=true">

## Aztec

<img width="200" alt="Aztec" src="https://raw.githubusercontent.com/DavBfr/dart_barcode/master/img/aztec.svg?sanitize=true">