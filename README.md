# Ingredient Reader

This app will recieve an image of an ingredient list which is commonly found on packages of food and return information about the ingredients found in the list.

- Server: Express
- View: Handlebars
- File Upload: Multer
- OCR: Tesseract
- Ingredient Analysis: nothing yet

### What needs to be done:

- preprocess images (contrast, rotation, cropping)

- convert other image types (.jpg, .gif, .bmp) to .png before they go to fileupload.js. Currently, fileupload.js only takes in .png files

- gather a larger storage of ingredient list images for test purposes.

- 

- find databases that will give us toxicity, cancer linkage, or legal status in other countries of the ingredients.



The server has been deployed to heroku here for testing: [https://read-ingredients.herokuapp.com/](here)
It doesn't work at all yet. It gets stuck on a post request. 
