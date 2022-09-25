Programm to visualize "fast sort" sorting algorithm.
Can read arrays from file or from terminal.

tags:
-f: path to file with data (optional, if there is no input list of data)
-l: input list data (optional, if there is no path to file)
-r: flag to reverse sort (optional)
-k: key function for sort algorithm
-c: cmp function for sort algorithm

python main.py -f some_list.txt
python main.py -f some_list.txt -r True
python main.py -f some_text_list.txt
python main.py -l 1,9,2,8,3,7,4,6,5
python main.py -l 1,9,2,8,3,7,4,6,5 -r True