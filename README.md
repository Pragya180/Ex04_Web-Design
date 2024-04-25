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
<head>
<title>Agri Search Engine</title>
</head>
<body>
<h3>
SUGARCANE CROP:
<br>
<a href="https://en.wikipedia.org/wiki/Sugarcane">
<img src="C:\Pragya\SEC\web design\sugarcane.jpeg" height="200" width="200">
</a>
<br>
<br>
SEED DRILL:
<br>
<a href="https://en.wikipedia.org/wiki/Seed_drill#:~:text=A%20seed%20drill%20is%20a,being%20dragged%20by%20a%20tractor.">
<img src="C:\Pragya\SEC\web design\seed drill.jpeg" height="200" width="200">
</a>
<br>
<br>
ORGANIC FERTILIZER:
<br>
<a href="https://en.wikipedia.org/wiki/Organic_fertilizer">
<img src="C:\Pragya\SEC\web design\organic fertilizer.jpeg"height="200" width="200">
</a>
</body>
</html>
```
## OUTPUT
![alt text](<Screenshot (816).png>)
![alt text](<Screenshot (819).png>) 
![alt text](<Screenshot (818).png>) 
![alt text](<Screenshot (817).png>)
## RESULT
 Images as hyperlinks is implemented successfully.
