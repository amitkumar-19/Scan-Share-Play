# Scan-Share-Play
This project is a computer-based program that should be able to read any text aloud whether it was directly introduced in the computer by an operator or scanned and submitted to an Optical Character Recognition (OCR) system. It can also convert the selected text into QR code, Audio and Webpage.

# Installation

This Project requires Python 3.6+ AND a active internet Connection

You also need to install pytesseract for which you can refer to 
https://medium.com/@rpaberm/setup-tesseract-ocr-with-python-4b843ff09875 


Use the package manager

pip install pytesseract
pip install tkinter
pip install gTTS
pip install PIL
pip install pyqrcode
pip install qrcode
pip install ctypes
pip install webbrowser

# Run

If you wnat you can directly open .ipynb file named main.ipynb with the help of Jupyter, Google collab or any IDE of your choice.

# Use

First the image is selected from the system . OCR is the mechanical or electronic conversion of images of typed, handwritten or printed test into machine coded text. The basic junction of OCR Technology is to automatically capture printed text present scanned images and convert it into a text searchable document.

Then the converted text is converted to an audio using a text to speech (TTS) synthesizer. It is a computer-based system that read text aloud automatically.
There is also an option to convert the text to qr code which can be scanned using a device and used even in compact form. Also we have generated a web supported HTML file which could be later used to host for public use.

