# PixelsSuite Image Preview Automation Test

## How to install dependencies
pip install playwright openpyxl
python -m playwright install

## How to run the test
python image_preview_test.py --url "https://www.pixelssuite.com/image-to-pdf" --slow-mo-ms 2000

## Test scenario
Verifies that uploading a valid PNG image to the Image to PDF 
feature correctly displays a preview on the page.
