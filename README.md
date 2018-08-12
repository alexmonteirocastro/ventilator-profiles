# Scheduler for ventilation units

The source code for this project can be found in this repo. 

Live version can be found [here](https://alexmonteirocastro.github.io/ventilation-schedule/).

Project was made using HTML5, CSS3 and JavaScript (ECMA, with no Frameworks).

Main aspects:

* Responsive design.
* Transversion and transformation of the DOM using JavaScript (locating, creating and styling elements dynamically).
* Array and Object-Oriented methods. 

## Assignment Nº 2: JPEG vs PNG vs SVG

JPEG, PNG and SVG are types of image files that can be used for the web (as assets).

JPEG and PNG are belong to the __*raster*__ type of graphic images, while SVG belongs to the __*vector*__ type. 

Raster file types differ from vector in the way the data is stored. Data for raster types is stored by each individual pixel, while data in vector types is stored as a geometric description.

### Raster types: JPEG vs PNG

JPEG files are good to be used for photos. They store data in a *"lossy"* format, which means that such files can be compressed, and thus lose some amount of data. The big advantage of this is that it can make these types of file smaller without a major impact in the quality. Therefore they can be loaded faster and still look decent.

The PNG format is quite convenient to be used for things such as graphs, diagrams or logos (such as branding logos in websites and banners). One big advantage of the PNG format is that they allow for alpha transparency. That said, logos and simbols in PNG format can be easily placed on the top of (overlayed) navigation bars, backgrounds, banners, etc... 
One important difference between PNG and JPEG is that the PNG is *lossless*, because they do not lose any data when compressed. This makes PNG files not as compressible as JPEG files, which makes it more difficult to make them smaller in size (as in file size).

## Main limitation of raster type images

Raster images, be it JPEG or PNG will lose quality when scalled up. You wil see things all the pixels and it doesn't really look very good. 

## Vector types

Vector type images like SVG are good for scaling up given that the data is stored as a geometrical description of the whole instead of a collection od individual pixels that make up the image.

The problem with SVG is that this format does not handle photos very well because it relies on the fill and shape of the elements within an image and cannot consistently represent complex details present in photographs.  

### Summing it all up...

JPEG format is good for photos, PNG format is good for logos and images that overlay on a background or some web element because of transparency. SVG is good for images that can scale up, but not good for photos. 