# Ex.05 Book Front Cover Page Design
## Date:25/05/2026

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:

book.html

```
<html>
    <head>
        <link rel="stylesheet" href="book.css">
        <title>DataScience Book</title>
    </head>
    <body>
        <div class="name"><h1>A MOHAMED SHAJID-(212225040243) </h1></div>
        
        <div class="page1">
            <div class="page2">
                <div class="page3">
                    <h1>SEC Insight</h1>
                    <hr>
                </div>
                
                <div class="page4">
                    <p>FUNDAMENTALS OF
                        WEB APPLICATION</p>
                </div>
                <br>
                <br>
                <br>
                <div class="page5">
                    <h3>Python Programming</h3>
                    <h4>Introduction to Data Science</h4>
                    <h5>Fundamental of C Programming</h5>
                </div>
                <div class="page6">
                    <img src="WhatsApp Image 2026-05-25 at 18.54.53.jpeg" alt="mypic">
                </div>
                <div class="page7">
                    <h2>Muhilan</h2>
                    <hr>
                </div>
                
            </div>
       </div>
    </body>
</html>


```
book.css

```
body{
    background-color: #666;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-style: oblique;
    color:#000000;
}
.page1{
    background-image: url("image.png");
    background-clip: border-box;
    background-position-x: right;
    background-size: cover;
    height: 695px;
    width: 500px;
    position: relative;
    left: 500px;
}

.page2{
    margin: auto;
    border: solid 8px rgb(0, 0, 0);
}
.page3{
    font-size: 12px;
    color: rgb(6, 255, 10);
    font-weight: 800;
    position: relative;
    top: 20px;
    left: 10px;
    width: 140px;
}
.page4{
    font-size: 40px;
    text-align: center;
    position: relative;
    top: 40px;
    
}
.page5{
    position: relative;
    left: 10px;
    font-size:18px;
    
}
.page6{
    width: 150px; 
    height:150px;      
    position: relative;
    top: 70px;
    left:300px;
    border: 2px solid white;
    background: rgb(4, 0, 255);
    overflow: hidden;   
}
.page6 img{
    width: 100%;
    height: 100%;
    object-fit: cover;
}
.page7{
    position: relative;
    top: 30px;
    left: 1px;
    font-weight: bolder;
}

.page9{
    font-family: Arial, Helvetica, sans-serif;
    position: relative;
    bottom:5px;
    right:380px;
    font-size: 15px;
}
.name{
    text-align: center;
    position: relative;
    right:50px;
}



```


## OUTPUT:
<img width="1306" height="906" alt="image" src="https://github.com/user-attachments/assets/ea76229e-b94b-4eb0-9fd6-1beb116f6524" />



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
