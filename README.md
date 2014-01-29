cups-ocr
========

Generate a text file from any text found in a document sent to this printer.
Actually first prints to a tiff file.
Tesseract reads the tiff file outputting a text file,
which is presented to the user in the spool.
Modeled after cups-pdf.

Usage
-----

You can now add a "Virtual Printer (OCR Printer)"
and use the Postscript/Generic postscript color
printer driver.

Note that cups-ocr has a configuration
file in /etc/cups. The default location for
pdf output is /var/spool/cups-ocr/$username.
You can now add a "Virtual Printer (OCR Printer)"
and use the Postscript/Generic postscript color
printer driver.

Note that cups-ocr has a configuration
file in /etc/cups. The default location for
pdf output is /var/spool/cups-ocr/$username.

Dependancies
------------
(pacman package names)

cups
imagemagick
tesseract

