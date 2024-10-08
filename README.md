# Video Filter

Video filtering application that leverages the power of OpenCV to apply real-time effects to camera feeds.

## Features

- Real-Time Video Processing: Apply filters to video streams in real-time.

- Multiple Filter Options: Choose from a variety of filters, including grayscale, sepia, edge detection, and more.

- Cross-Platform Support: Runs on Windows, macOS, and Linux.

## Installation

### Prerequisites

- Python 3.x
- OpenCV

clone the repo

```
git clone https://github.com/aust21/video-filters.git
cd video-filters
```

### Set up virtual environment

For Windows

```
python -m venv venv
venv\Scripts\activate
```

For Linux / mac

```
python3 -m venv venv
source venv/bin/activate
```

install the required modules

```
pip install -r requirements.txt
```

## Usage

```
jupyter nbconvert --to notebook --execute main.ipynb
```
### Video filters
- To apply blur filter: press b
- To detect edges(Canny): press c
- To show in black and white: press w
- To go to normal mode: press n
- To quit: press q

## Acknowledgments

- [opencv](https://opencv.org/) for the powerful computer vision library.
