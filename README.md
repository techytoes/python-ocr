## Requirements

`sudo apt-get install python-imaging`

`sudo apt-get install tesseract-ocr`

`sudo apt-get install python-opencv`

## Example

![Before processing](http://raw.githubusercontent.com/schollz/ocr-text-extraction/master/test.jpg)

1. First process the image

`python process_image.py test.jpg text.jpg`

![After processing](http://raw.githubusercontent.com/schollz/ocr-text-extraction/master/text.jpg)

2. Extract text

`python extract_text.py`
