# Puzzle Slicer

A very simple python script to slice an image into a specified number of rows / columns

## Description

This script takes an image and slices it into a specified number of rows and columns. The resulting images are saved in a specified folder, or in a folder named after the original image if the argument is omitted. The script is very simple and does not do any error checking. 
It is intended to be used with images that have dimensions that are a multiple of the number of rows and columns, otherwise the script will crop the right and the bottom parts of the resulting puzzle to the nearest multiple of the piece size. 
For example, if the image is 1920x1080 and the requested dimension is 19x10, the resulting puzzle size will be 1900x1000.

## Getting Started

### Dependencies

* Python
* Pillow
* Numpy 

### Installing dependencies

```commandline
pip install pillow
pip install numpy
```
### Executing program


```commandline
python puzzle_slicer.py -i <input_image> -r <rows> -c <columns> [-o <output_folder>]
```

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
