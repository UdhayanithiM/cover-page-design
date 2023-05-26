# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone the Github Repository and create a Django admin Interface.
### Step 2:
Write HTML and CSS code for designing book cover page and execute them.
## Code:
 python
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 500px;
            height: 800px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/image3.jpg);
            background-size: cover;
        }
            

        .insight{
            color: brown;

        }

        
        .hrstyle{
            width:200px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: red;
            top:300px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family:Arial, Helvetica, sans-serif;
            font-size: larger;
            text-align: center;
            position: relative;
            
        
        }
        .id {
            width:500px;
            position: relative;
            top:350px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:green;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:320px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 350px;
            left: 390px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
            
            </div>
            <div class="hrstyle">
                
            </div>
            <div class="booktitle">
                <h1> KING KOHLI</h1></div>
            <div class="subtitle">
                One Man Army
            </div>
            <div class="mypic">
                <img src="/static/images/image4.jpg" width="100" height="100" alt="">
            </div>
            <div class="id">
                <hr style="color: indigo;">
            </div>
            <div class="author">
               <p><b>UDHAYA</b></p>
            </div>
            <div class="pub">
               
            </div>
            <div class="ed">
                <b>DJ Edition</b>
            </div>
        </div>
    </body>
</html>




## Output:
### BOOK COVER OUTPUT:
![cover1](https://github.com/UdhayanithiM/cover-page-design/assets/127933352/b7587e3b-252a-4009-8fcf-fa161ff445db)

### Validator output:
![validator1](https://github.com/UdhayanithiM/cover-page-design/assets/127933352/d6ec4ea5-81ba-494a-a4b8-1effb9c188be)

## Result:
Thus the program to create a book cover design is executed successfully.
