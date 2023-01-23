# cover-page-design
## AIM:
To develop a website to display the cover page design of a book.

## Design Steps:

### Step 1:
1.go to theaid.
### Step 2:
2.After doing gitfork the repository url ,then git clone the repository url.
### Step 3:
3.create images,static folder and files like cover.html.
### Step 4:
4.Inside the cover.html file write the html and css code.
### Step 5:
5.Run the program by using python3 manage.py runserver 0:8000.
### Step 6:
6.After running write the code in README.md.
### Step 7:
7.At last git push your information to git hub account.


## Code:
cover.html
```python

<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #3d3a3a;
            color:red;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/cover.jpeg);
            background-size: cover;
        }
            

        .toptext{
            color:white;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: red;
            display: inline;
            position: relative;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .edition{
            color:red;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .photo{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                SEC INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: violet;">
            </div>
            <div class="booktitle">
                <h1>Fundamentals of Web Application Development</h1></div>
            <div class="subtitle">
                HTML and CSS Combined with Django Architecture
            </div>
            <div class="photo">
                <img src="/static/images/me.jpeg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <p><b>Gowtham B V</b></p>
            </div>
            <div class="publisher">
                SEC
            </div>
            <div class="edition">
                <b>Seventh Edition</b>
            </div>
            
        </div>
    </body>
</html>

```

## Output:

![screenshot](images/coverme.png)

## HTML validator

![screenshot](images/htmlcover.png)


## Result:

I sucessfully developed a website to display the cover page design of a book.

