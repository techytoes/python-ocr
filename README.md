# Python-OCR

> OCR = Optical character recognition

In simple words, this project extracts text from an image.

## Requirements

`sudo apt-get install python-imaging`

`sudo apt-get install tesseract-ocr`

`sudo apt-get install python-opencv`

## How does it work ?

This is the original image which will be used for extraction of text.

![test](images/test.png)

* First process the image

`python process_image.py test.jpg text.jpg`

The image will look like this after the `process_image.py script` is executed.

![test](images/text.png)

Finally run this script to extract text from the image

* Extract text

`python extract_text.py`


If you love the work, Please ⭐️ (star) this repo.