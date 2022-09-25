Programm to make and solve mazes with "depth-first search" algorithm.
Can read and write mazes in png & txt files. Can makes gifs with work process.

tags:
-he: heights (optional, if there is no input file path)
-wi: width (optional, if there is no input file path)
-i: input file path (optional, of there no height and width)
-o: output file path
-s: flag to resolve maze (optional)
-g: flag to make gif (optional)

Examples
python main.py -he 10 -wi 10 -o maze_0.png -g true
python main.py -he 10 -wi 10 -o maze_1.txt -g true 

python main.py -i maze_0.png -o maze_2.txt -g true -s true
python main.py -i maze_1.txt -o maze_3.png -g true -s true

python main.py -he 15 -wi 15 -o maze_4.txt -g true -s true
python main.py -he 15 -wi 15 -o maze_5.png -g true -s true
