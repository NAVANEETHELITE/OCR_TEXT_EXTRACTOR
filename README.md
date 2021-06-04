# OCR_TEXT_EXTRACTOR_WEB_APP
- <a href ="https://en.wikipedia.org/wiki/Optical_character_recognition">Optical Character Recognition</a> or optical character reader (OCR) is the electronic or mechanical conversion of images of typed, handwritten or printed text into machine-encoded text.
- This Text Extractor web app was deployed to HEROKU through Flask.
- Upload an image to extract the text from it.
- Result will be empty if the uploaded image doesn't contain any text in it.
- <strong><b> APP LINK : https://extract-t3xt-nav.herokuapp.com/ </b></strong>
- <b>NOTE: Before deploying the app add the following buildpacks in Heroku</b>
- Build Pack 1 :  heroku/python
- Build Pack 2 : https://github.com/pathwaysmedical/heroku-buildpack-tesseract
- Index and Result pages are shown below:

<div class="row">
  <div class="column">
    <img src="https://github.com/NAVANEETHELITE/OCR_TEXT_EXTRACTOR/blob/master/OUTPUT/ocr1.png" title='INDEX PAGE' alt="index" style="width:30%">
    <img src="https://github.com/NAVANEETHELITE/OCR_TEXT_EXTRACTOR/blob/master/OUTPUT/ocr2.png" title="RESULT PAGE" alt='result' style="width:30%">
  </div>
</div>
