## Executive Summary ##

This unit allows us to practice working with files and folders while exploring the impact of file/folder compression. It also provides an introduction to object oriented programming paradigm and lets us practice creating and diagramming software. I am already relatively comfortable using Python and have extensively studied Java, so I am pretty familiar with OOP concepts and principles. That said, this unit will be a great opportunity to review important information about object-oriented programming with a specific focus in Python.

### File Compression ###

File compression is a way to compact or "squeeze" your files so they take up less space. When a file or folder is compressed, the resulting archive often takes up 50% to 90% less disk space than the original file or files. It is usually compressed to a Zip, but other types of file compression include Gzip, RAR, Stuffit, and 7z compression. The goal is to remove redundant data in each file by replacing common patterns with smaller variables. Once a file is compressed, it must be decompressed in order to be used.

When I compressed the SVGGraphic file, it went from 746 KB to 546 KB. When I compressed a JPEG file, it went from 330 KB to 325 KB. I also repeated this with other JPEG files and the trend seems to be that JPEG files generally don't compress as much as SVG files. JPEG uses a lossy compression algorithm so the image may lose some of its data, while SVG is a text based image format and uses mathematical structures to represent an image and is highly scalable.

### Python OOP ###

The two methods in the shark class are *swim* and *be_awesome*. Name is the property. The constructor is uused to initialize data, and it is run as soon as n object of a class is instantiated. It is the *_init_* method and will be the first definition of a class. A class is a blueprint or a prototype that you can definite to use to create objects, while an object is the actual instance of the class. To instantiate an object from a class is to create an object using the class as a blueprint. So in the Shark class, the object *sammy* was initialized as an instance of the *Shark()* blueprint.

### Object-Oriented Concepts ###

An example of a class in a real-world situation could be a drive-thru restaurant that we could label as MyRestaurant, and objects created from this class could be items available to order, customers, cars, and registers. Going back to the shark program, you can match each of the following terms to a description that helps you better understand OOP concepts:

1. **object**: *Sammy*
2. **class**: *shark*
3. **abstraction**: *definition of a shark*
4. **encapsulation**: *swim(self)*
5. **inheritance**: *a specific type of shark*
