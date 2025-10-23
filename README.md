# Extracting text from images (OCR)

## What is OCR Data Extraction?
Optical Character Recognition (OCR) is a technology that turns images of text (eg. bmp, jpg, png, tiff, pdf) into an editable format (usually txt files or JSON).

The goal is to quickly and accurately extract text from one data format that cannot be easily read or analyzed (images) into a new format that can be analyzed through computational and digital methods and tools. While manual transcription by a skilled human reader tends to be the most accurate means of extracting text, sometimes the volume of scanned images requiring transcription would take too many human work hours to complete in a reasonable time. Automating this process by using an OCR tool can help researchers access the text data sets they need in a more timely and efficient manner. 

## Common Python Libraries for OCR
Working with a Python library (a set of prewritten code that makes it easier to do certain tasks) can be an easy and free way to extract text from images and PDFs. Most of these libraries can be setup quickly and run from either the command line or within a Jupityr notebook. Much like their paid alternatives, these Python libraries make use of the latest AI innovations and Learning Models. If your document images are primarily of modern printed or typed texts, then pyTesseract or EasyOCR can be a great inexpensive solution.

### pyTesseract
pytesseract is a wrapper for Google's [Tesseract-OCR Engine](https://github.com/tesseract-ocr/tesseract). It can read all image types supported by the Pillow and Leptonica imaging libraries, including jpeg, png, gif, bmp, tiff, and others. It also has unicode (UTF-8) support and can recognize over 100 languages. Handwriting transcription is still not very good.
* [pyTesseract Demo Jupityr notebook](demo_pytesseract.ipynb)
* [Official pyTesseract Github](https://pypi.org/project/pytesseract/)

### EasyOCR
EasyOCR supports 80+ languages and popular writing scripts, including: Latin, Chinese, Arabic, Devanagari, Cyrillic, etc. At the moment, no handwritten text support - but this is in pipeline next. 
* [EasyOCR Demo Jupityr notebook](demo_easyocr.ipynb)
* [Official EasyOCR Github](https://github.com/JaidedAI/EasyOCR)

