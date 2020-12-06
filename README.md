<h1 align="center">
Barcode Scanner
</h2>
<p align="center">

## Overview
This repository contains code written explicitly in [**Python 3**](https://www.python.org/) for scanning barcodes.

## Requirements
- Python3
- Pyzbar
- OpenCV
- Imutils
- Argparse

## Install the necessary libraries
The first step in order to run this code is to download the necessary libraries. Python has a tremendous amount of libraries and this is one of its strongest advantages. Python comes with a package installer and manager called [PIP](https://pypi.org/project/pip/), which is by default installed from version 3.4 onwards. In order to install the libraries, run the following command on your terminal:
```
$ pip install -r requirements.txt
```
The dollar sign ```$``` means that the following command should be written in terminal. Don't write this sign in terminal. It is just a symbol to make our lifes easier.

## Scanning
1. In case you want to scan a barcode from a photo, run:
```
$ python barcode_scanner_image.py
```
2. In case you want to scan a barcode from a video, run:
```
$ python barcode_scanner_video.py
```