## Requirements

`sudo apt-get install python-imaging`

`sudo apt-get install tesseract-ocr`

`sudo apt-get install python-opencv`

## Example

1. First process the image

`python process_image.py test.jpg text.jpg && python extract_text.py`

2. Extract text

`python extract_text.py`

Output:

```bash
4 WkiJre €99 Bread

A good, basic white bread.

with

I. 21/2 cups lukewarm water
2 packages dry yeast
1/4 cup honey
1 cup dry mile
2 eggs, beaten
4 cups unbleached white ﬂour

II. 4 teaspoons salt
1/3 cup butter or margarine
3 caps or inore unbleached white ﬂour for forming the dough
1 cup (approx.) white ﬂour for kneadian

Proceed with the directions for recipe #1, adding the beaten eggs afte
stirring in the dry milk.



is moister and chewier than the white e ;g bread.

r’/
'3. ' " er
ast
J
V -

```


### Acknowledgements

`process_image` implemented in Python using OpenCV by Jason Funk Copyright (c) 2012,based on the paper "Font and Background Color Independent Text Binarization" by T Kasar, J Kumar and A G Ramakrishnan http://www.m.cs.osakafu-u.ac.jp/cbdar2007/proceedings/papers/O1-1.pdf


