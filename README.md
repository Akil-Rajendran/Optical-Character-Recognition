# Optical Character Recognition for Tamil
A Optical Character Recognition system that detects text from the scanned copy of an ancient Tamil book and digitises it. A sample page from the scanned copy of book is considered as input and digitsed as a text document omitting the header with page number and the footer with publisher's name.

## Implementation Steps
*    Input images are processed.
*    Dilation process - for drawing bounding boxes. 
*    The dilated image is contoured and saved as a separate TIFF file. 
*    Tesseract OCR is applied on these intermediate outputs.
*    Converted text is cleaned and compared to manually typed text.
*    Evaluation metrics: fastwer, Levenshtein, cosine similarity.
    
## Important Perks
*    Multi Language Support in the same system for an image.
*    The pages in the book “Abithana Chintamani” are separated by a centre line which very well handled and skimmed column-wise.
*    Perfect recognition and removal of header-footer in the image focusing only the content of the page.
*    Better accuracy in terms of output compared to Online OCRs.
