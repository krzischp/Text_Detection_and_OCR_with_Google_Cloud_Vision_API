**Project directory**
```
|-- images
| |-- aircraft.png
| |-- challenging.png
| |-- street_signs.png
|-- client_id.json
|-- google_ocr.py
```

With our project directory structure reviewed, we can move on to implementing
google_ocr.py, the Python script responsible for:
- **i.** Loading the contents of our `client_id.json` file
- **ii.** Connecting to the Google Cloud Vision API
- **iii.** Loading and submitting our input image to the API
- **iv.** Retrieving the text detection and OCR results
- **v.** Drawing and displaying the OCR’d text to our screen

Enter the following command line to put the Google Cloud Vision API to work!
```
python google_ocr.py --image images/aircraft.png --client client_id.json
```
