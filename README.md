# Color Detection System

A Python-based application that allows real-time color detection in images using OpenCV and a comprehensive color database. This interactive tool helps users identify precise color names and RGB values by simply double-clicking on any pixel in the image.

## Features

- Real-time color detection from images
- Interactive double-click interface
- Displays RGB values and closest matching color name
- Uses a database of 865 color names
- Simple and intuitive user interface

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy
- Pandas

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Color_Detection_System.git
   cd Color_Detection_System
   ```

2. Install the required packages:
   ```bash
   pip install opencv-python numpy pandas
   ```

## Usage

1. Run the script using the following command:
   ```bash
   python color_detection.py -i <path_to_image>
   ```
   Example:
   ```bash
   python color_detection.py -i colorpic.jpg
   ```

2. Once the image opens:
   - Double-click anywhere on the image to get the color name and RGB values
   - Press 'ESC' to exit the program

## How It Works

The system works by:
1. Loading an image specified through command-line arguments
2. Reading a color database containing RGB values and color names
3. Calculating the minimum distance between the selected pixel's RGB values and the colors in the database
4. Displaying the closest matching color name along with its RGB values

## Project Structure

- `color_detection.py`: Main Python script containing the color detection logic
- `colors.csv`: Database file containing color names and their RGB values
- `colorpic.jpg`: Sample image for testing

## Screenshots

![Screenshot 1](https://github.com/ayus1234/Color_Detection_System/assets/107507481/e0e9659d-34c6-487c-963f-b018c10a76fe)
*Double-click anywhere on the image to detect colors*

![Screenshot 2](https://github.com/ayus1234/Color_Detection_System/assets/107507481/4cfe1453-5dd1-4d14-95ef-142d949a8f0d)
*Real-time color detection with RGB values*

![Screenshot 3](https://github.com/ayus1234/Color_Detection_System/assets/107507481/c7e8d527-39af-4482-a803-b366b28b8705)


## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).  
You are free to use, modify, and distribute this software with proper attribution.
