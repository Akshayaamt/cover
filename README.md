# Ex.06 Book Front Cover Page Design
## Date:20.11.23

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
```
<!DOCTYPE html>
<html>
<head>
    <title>WEB</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:rgb(131, 33, 33);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(Back.jpg);
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(75, 8, 8);
        
        }
        
        
        .hrstyle{
            width:110px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(123, 143, 9);
            top:280px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(21, 96, 96);
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:280px;
            
        }
        .pub{
            color:rgb(18, 106, 106);
            font-size: medium;
            position: relative;
            top:250px;
            left:330px;
        }
        .ed{
            color:rgb(4, 101, 101);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:180px;
        
        }
        .subtitle{
            color:rgb(8, 92, 92);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 300px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                THE NEW WEB TECH ARTICLE
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(20, 4, 83)
            </div>
            <div class="booktitle">
                <h1>RELAIABLITY OF INFOTAINMENT</h1></div>
            <div class="subtitle">
            </div>
            <div class="subtitle">
                 
            </div>

            <div class="MyPhoto">
                <img src="MyPhoto.jpg" width="80" height="100" >
            </div>
            <div class="id">
                <hr style="color:rgb(14, 6, 80)">
            </div>
            <div class="author">
               <p><b>AKSHAYAA M.T</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>
        

</html>
```

## OUTPUT:
![Alt text](<Screenshot 2023-12-02 104813.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
