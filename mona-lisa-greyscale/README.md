# Mona-Lisa-Greyscale

In this photomosaic, we will generate a greyscale version of the Mona Lisa.

If we set up our image grid to have the same dimensions as the target image, then each pixel in the target image will be individually compared to each candidate image. If each candidate image is a single greyscale pixel, the chosen candidate image for each pixel in the target image will be the closest greyscale pixel.

Each greyscale pixel will have a filename of its shade of grey. The filenames and corresponding RBG values are:

* `00.png` - (0, 0, 0)
* `0F.png` - (15, 15, 15)
* `1F.png` - (31, 31, 31)
* `2F.png` - (47, 47, 47)
* `3F.png` - (63, 63, 63)
* `4F.png` - (79, 79, 79)
* `5F.png` - (95, 95, 95)
* `6F.png` - (111, 111, 111)
* `7F.png` - (127, 127, 127)
* `8F.png` - (143, 143, 143)
* `9F.png` - (159, 159, 159)
* `AF.png` - (175, 175, 175)
* `BF.png` - (191, 191, 191)
* `CF.png` - (207, 207, 207)
* `DF.png` - (223, 223, 223)
* `EF.png` - (239, 239, 239)
* `FF.png` - (255, 255, 255)