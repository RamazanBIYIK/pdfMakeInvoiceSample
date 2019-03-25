# pdfMakeInvoiceSample
This is a repo that only contain a text file that written compatiple with javascript. It is a sample of pdfMake invoice.

jsPDF has more star then pdfMake. It is not used due it is lack of UTF-8 support. There is solution for that lackness. But i prefered
pdfMake.

All companent inside that code is static. If you fill the whole table, it started to crush other companents.  I hope i can handle this problem in future.

You can preview the code result from http://pdfmake.org/playground.html web address. Also you can find documentations is this site.

If you want to use this code in your javascript, you can define variables to inside text or tables. Just consider that tables take 
text as a row. When table row fulled with text it goes below line. If you want to go 1 row below inside text ot table tag, you should use
'\n' escape character. 

Image is defined as base 64. you can convert images to base64 easily with quick research on google. The resolution of the image is 960-362 px(not sure but close to this numbers)

If you want to download this pdf inside your code

use: pdfMake.createPdf(dd).download("pdfName.pdf"); inside generatePdf method.
