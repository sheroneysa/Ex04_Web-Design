# Ex.04 Images as Hyperlinks
## AIM
  Insert five different images ( 2 on Crops and 2 on Machines and 1 on Fertilizer required ). 
  Skip two lines between each image. Each image should have a title. 
  Display the images with a border of size 2, a width of 200, and a height of 200, 
  it should be linked to a search engine of your choice and when each image is clicked, 
  the respective search engine should be opened in a new window.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the required images using ```<img>``` tag.

### STEP-3
  Set the image border size as 2, image width as 200 and height as 200.

### STEP-4
  Use the ```<a>``` anchor tag to link the corresponding search engines.  

### STEP-5
  Give double line spacing between the images using ```<br>``` tags.
  
### STEP-6
  Open the file in a browser and verify the output.
  
## CODE
```
    <html>
    <head>
    <title>agricultural search</title>
    </head>
    <body>
    <h3>
    Ragi
    <br>
    <a href="https://agritech.tnau.ac.in/agriculture/millets_ragi.html">
    <img src="d:\ragi.jfif"height="200" width="200
    </a>
    <br>
    <br>
    Urea
    <br>
    <a href="https://infinitygalaxy.org/what-is-urea/">
    <img src="d:\urea.jfif"height="200" width="200">
    </a>
    <br>
    <br>
    drone sprayer
    <br>
    <a href="https://dir.indiamart.com/impcat/agricultural-drone.html">
    <img src="d:\drone sprayer.jfif"height="200" width="200">
    </a>
    </body>
    </html>
    ```

## OUTPUT


## RESULT
 Images as hyperlinks is implemented successfully.
