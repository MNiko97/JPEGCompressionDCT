# JPEG Compression DCT
This repository is part of the Computer Vision class from ECAM Brussels Engineering School master program.
## Prerequisites

The program depends on the following libraries:
- [numpy](https://numpy.org/install/)
- [scipi](https://pypi.org/project/matplotlib/)
- [matplotlib](https://pypi.org/project/scipy/)

## First Run
Open the "JPEG_DCT_compression.ipynb" file and run the jupyter notebook code. The output image "output.jpg" will be available in the "images" folder. 

You can change the sample picture in the jupyter notebook by uncommenting the following line in block 1.1. By default the code will run the compression on the "forest.jpg" image: 
```python
import  cv2  as  cv

im = cv.imread("images/forest.JPG")
# im = cv.imread("images/rocks.JPG")

f = plt.figure()
plt.imshow(im,cmap='gray')
```
