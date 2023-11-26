# Ex.06 Book Front Cover Page Design
## Date:26.11.2023

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
<style>
.bookpage{
    width: 400px;
    height: 600px;
    color:black;
    margin-left: auto;
    margin-right: auto;
    padding: 20px;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    background-image: url(/static/Book.jpg);
    background-size: cover;
}
    

.insight{
    color: black;

}


.hrstyle{
    width:100px;
}
.author{

    display: inline;
    position: relative;
    color: red;
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
.pub{
    font-size: medium;
    position: relative;
    top:155px;
    left:330px;
}
.ed{
    color: black;
    font-size: medium;
    font-family: Verdana;
    position:relative;
    top:85px;

}
.subtitle{
    font-family:unicorn;
    font-size: large;
    position: relative;
    top:40px;
}
.mypic{
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
        MARVELS
    </div>
    <div class="hrstyle">
        <hr style="color: yellow;">
    </div>
    <div class="booktitle">
        <h1>THE HULK SMASH</h1></div>
    <div class="subtitle">
         AVENGERS ASSEMBLE
    </div>
    <div class="mypic">
        <img src="/static/hulk.jpg" width="130" height="145" alt="">
    </div>
    <div class="id">
        <hr style="color: cyan;">
    </div>
    <div class="author">
       <p><b>SHYAM SUJIN.U</b></p>
    </div>
    <div class="pub">
        SEC
    </div>
    <div class="ed">
        <b>special Edition</b>
    </div>
</div>
</body>

```

## OUTPUT:
![Alt text](<book design.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
