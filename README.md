# wondows_tesseract_ocr
How to install tesseract ocr on windows and how to use it.

# Installation steps are as below
## Create virtual environment
  pip install virtualenv – If virtualenv not available already
  
  virtualenv venv OR virtualenv -p python3 venv

## Install the package
pip install pytesseract

## Need to install tesseract executables on windows.
Currently, there is no official Windows installer for newer versions.

From https://tesseract-ocr.github.io/tessdoc/Downloads.html

## Download supported exe from......
  https://github.com/UB-Mannheim/tesseract/wiki
  
  If required old version then https://digi.bib.uni-mannheim.de/tesseract/

## Once executables has been installed on windows there are 2 ways through which
we need to refer to tesseract executable.....

  Either you need to put executable folder in PATH environemnt variable
  
  Or pytesseract.pytesseract.tesseract_cmd = C:\path\to\exe\of\tesseract in .py file where  
  you would like to work with tesseract
