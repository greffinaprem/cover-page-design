# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:

Write your own steps here.
### Step 2:
Describe the codes with given inputs

## Code:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
    <style>
        .bookpage {
            width: 400px;
            height: 600px;
            color: rgb(231, 225, 225);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-size: cover;
            background-image: url(/static/images/r.jpg);
        }

        .insight {
            color: brown;
        }

        .hrstyle {
            width: 100px;
        }

        .author {
            display: inline;
            position: relative;
            color: red;
            top: 190px;
            font-family: Georgia;
            font-size: medium;
        }

        .booktitle {
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;

        }

        .id {
            width: 400px;
            position: relative;
            top: 180px;

        }

        .pub {
            font-size: medium;
            position: relative;
            top: 155px;
            left: 330px;
        }

        .ed {
            color: blue;
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 85px;

        }

        .subtitle {
            font-family: Tahoma;
            font-size: large;
            position: relative;
            top: 40px;
        }

        .mypic {
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
        <div class="insight">
            SEC INSIGHT
        </div>
        <div class="hrstyle">
            <hr style="color:black;">
        </div>
        <div class="booktitle">
            <h1>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</h1>
        </div>
        <div class="subtitle">
            HTML and CSS combined with Django Architecture
        </div>
        <div class="mypic">
            <img src="/static/images/x.jpg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: black;">
        </div>
        <div class="author">
            <p><b>Imposter</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>Seventh Edition</b>
        </div>
    </div>
</body>

</html>
```

## Output:

![Screenshot (58)](https://user-images.githubusercontent.com/119475603/215285629-7bbe5760-74fc-4823-8ef8-d864c66f3235.png)
## HTML Validator:
![Screenshot (59)](https://user-images.githubusercontent.com/119475603/215285663-435413eb-3d3c-4954-bf35-1c47afff6683.png)



## Result:
The cover page design of a book is executed successfully.
