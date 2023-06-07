# cover-page-design
## AIM:
To develop a website to display the cover page design of a book.

## Design Steps:

### Step 1:
Create a new Django project and app

### Step 2:
Create a static file directory and mention the changes in settings.

### Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.

### Step 4:
Write down the code for book cover using HTML and CSS.

### Step 5:
Add images and other contents using CSS record a screenshot of it.

## Code:
```
NAME: Mohammed Faizal.J
REGISTER NO: 212222100027
```
```HTML
<!DOCTYPE html>
<html lang="en">
    <head>
        <title> Wings of Fire</title>
        <style>
        h1{
           color:turquoise;
        }
         .bookpage{
             width: 400px;
             height: 650px;
             background-color: black;
             background-position: center;
             margin-left: auto;
             margin-right: auto ;
             padding: 20px;
             background-image: url('/static/images/wingg.png');
             background-size: cover;
             background-repeat: no-repeat;

         }
         .toptext{
             color:yellow;
             padding-left: 10px;
             font-size: 14px;
             font-family: Arial, Helvetica, sans-serif;

         }
         .tophr{
             color:#e36f2f;
              width: 180px;
         }
         hr{
             color:#e36f2f;

         }
         .booktitle{
             font-family: Arial, Helvetica, sans-serif;
             padding: 10px 10px 0px 10px;
             display: flex;
            align-items: center;
            justify-content: center;
  margin-right: 10px;
  margin-left: 10px;
  font-size: 20px;
         }
         .author{
             color:tomato;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
             font-size: 24px;
             position:relative;
             line-height: 20px;

         }
         .sub-text {
             color:blue;
             font-family: Arial, Helvetica, sans-serif;
             display: flex;
             line-height: 5px;

  margin-right: 10px;
  margin-left: 10px;

  font-size: 14px;
  }

.footer {
  color:orange;
  padding-top: 180px;
}
.image {
    color:white;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
  margin-right: 20px;
}
.bottomhr {
    color:#e36f2f;
              width: 400px;
}
img {
    width: 90px;
    height: 100px;
    margin-right: 20px;
    vertical-align: bottom;
}
.edition {
    color:#e36f2f;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
 line-height:bottom;
}
        </style>
        </head>
            <body>
                <div class="bookpage">

                    <div class="toptext">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;EXPERT INSIGHT</div>
                    <div class="tophr"><hr></div>
               <div class="booktitle"><h1>Wings of Fire</h1></div>
               <h3 class="sub-text">The autobiography of Dr. APJ Abdul Kalam</h3>
                    <h3 class="sub-text">written by Dr. APJ Abdul Kalam</h3>
                    <div class="footer">
                        <h2 class="edition">&nbsp;&nbsp;First
Edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <img src="/static/images/apj.jpg" alt="Author"></h2>

                        <div class="bottomhr"><hr></div>
                    <div class="author"><h3>&nbsp;&nbsp;Dr. APJ Abdul Kalam &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</h3></div>

                </div>
                </div>
            </body>
</html>
```

## Output:
### SERVER OUTPUT:
![apjbkser](https://github.com/MohammedFaizal05/cover-page-design/assets/120553195/dd67cc3e-2213-45b0-b915-7af4da86985d)

### CLIENT OUTPUT:
![apjbk](https://github.com/MohammedFaizal05/cover-page-design/assets/120553195/63de8cb8-9328-4ede-9eb0-ae35b1d10bce)


## Result:
Thus a website to display the cover page design of a book was successfully created.
