![image](https://github.com/Nbn03/Image-Processing-Tool/assets/136473086/7bfb043a-50cc-4d67-9da0-1492c8256cae)

# ANalytix - an Image Processing Web Application

ANalytix is an Image Processing Flask Application which applies simple image processing on an image.


## About
ANalytix is a simple yet effective Image processing web app built using Flask and OpenCV. This web application empowers users to upload images and unleash their creativity through a range of image processing operations. From cropping and resizing to applying filters, ANalytix offers an enjoyable experience for manipulating images.\
_**Back-end: Python, Flask**_ \
_**Front-end: HTML, CSS, JavaScript, Bootstrap**_
## Features
- **Upload Image:** ANalytix allows users to effortlessly upload images to perform editing that too in various formats, including webp, png, jpg, and jpeg.\
- **Crop Image:** With the interactive cropping feature, users can easily select and extract specific regions of the uploaded image.\
- **Resize Image:** Users have the flexibility to resize their images, maintaining the aspect ratio for consistent and balanced proportions.\
- **Filters:** Offers a delightful array of filters to transform images into unique pieces of art. Users can choose from Black & White, Exposure, and Oil Painting filters.
- **Find Face:** Uses haarcascades xml file for finding faces in an image
## Frameworks and Libraries Used
- **Flask**: A lightweight web framework used for building the web applications.

- **OpenCV**: Utilized for powerful image processing operations, including cropping, resizing, and applying artistic filters.
## How to Use
1. Begin your journey by uploading an image. Click the "Choose File" button and select an image from your local machine.

2. Select the desired operation from the dropdown menu.

3. Execute the operation by clicking the corresponding button to process the uploaded image.

4. The result of the corresponding operation will be displayed.

## Templates
- ### [index.html](https://github.com/Nbn03/Image-Processing-Tool/blob/main/templates/index.html)

- ### [crop.html](https://github.com/Nbn03/Image-Processing-Tool/blob/main/templates/crop.html)

- ### [resize.html](https://github.com/Nbn03/Image-Processing-Tool/blob/main/templates/resize.html)

- ### [filter.html](https://github.com/Nbn03/Image-Processing-Tool/blob/main/templates/filter.html)

- ### [face.html](https://github.com/Nbn03/Image-Processing-Tool/blob/main/templates/face.html)
## Note
1. ANalytix is designed for demonstration purposes and may require further optimization for large-scale deployment.

2. Ensure that you provide a valid image in one of the allowed formats for processing.

3. The uploaded images are temporarily stored in the "Uploads" folder, and the processed images are available in the "Static" folder.

4. Make sure to change the path in the code as per your local machine.
