Programm to compress images with "quad-tree" algorithm.
Reads images and create compressed images.

tags:
-i: input image path
-l: compress depth (optional) (0-8 recommended)
-c: compress strength (optional) (0-10 recommended)
-b: flag to display borders of zones (optional)
-g: flag to make gif (optional)

Examples
python main.py -i image.png
python main.py -i image.png -l 7 -c 2
python main.py -i image.png -l 7 -c 2 -b true
python main.py -i image.png -l 7 -c 2 -g true 
python main.py -i image.png -l 7 -c 2 -b true -g true 
python main.py -i image.png -l 7 -c 5 -g true 
python main.py -i image.png -l 7 -c 0 -g true 
python main.py -i image.png -l 8 -c 1 -g true -b true
