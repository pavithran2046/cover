# Ex.06 Book Front Cover Page Design
## Date: 28/4/24

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FRONT PAGE</title>
    <style> 
        .wrapper {
            background-color: white;
            height:100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .bookpage{
            width: 400px;
            height: 600px;
            color: white;
            padding: 30px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-color: rgb(18, 18, 222);
            background-size: cover;
        }
            
        
        .insight{
            color: white);
            text-align: center;
        }
        
        
        
        .booktitle{
            color:black;
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
            font-size: xx-large;
            text-align: center;
            position: relative;
            
            
        
        }
        
        .subtitle{
            color:gold(24, 38, 78);
            font-family: unicorn;
            font-size: larger;
            position: relative;
            top: 15px;
            text-align: center;
        }
        .end{
            color:white;
            font-family: Arial, Helvetica, sans-serif;
        }
        .name{
           color: black;
           font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
           text-align: center;
        }
    </style>
</head>
<body >
    
    <div class="wrapper">
        <div class="bookpage">
            <div class="insight">
                <p>WINNER OF THE PULLITZER PRIZE</p>
            </div>
            <div class="booktitle">
                <h1><b>MY</b></h1>
            </div>
            <div class="booktitle">
                <h1><b>BOOK</b></h1>
            </div>
            <div class="booktitle">
                <h1><b>COVER</b></h1> 
            </div>       
            <div class="subtitle">
                 <b> SECRETS IN A </b> <br>
                 <b> SILICON VALLEY </b><br>
                 <b> STARTUP </b>

                 <div class="booktitle">  
                    <b><hr width="150px"> </b> 
                 </div>     
            <div class="name">
                <b>PAVITHRAN.S</b><br>
                <div class="end">
                    <p>BOOK PUBLISHER</p>
                </div> 
            </div>
            <div class="end">
                <p>BOOK PUBLISHER</p>
            </div> 
            
            
        </div>
    </div>
</body>
</html>

## OUTPUT:
![Screenshot 2024-04-28 210023](https://github.com/pavithran2046/cover/assets/139334834/5870b8e6-ab9e-4d0c-b548-ee7d3bac35b0)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
