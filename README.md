# Ex.05 Design a Website for Server Side Processing
## Date:14.11.2023

## AIM:
To design a website to find total surface area of a square prism in server side.

## FORMULA:
Total Surface Area = 2b<sup>2</sup> + 4bh
<br>b --> Base of Square Prism
<br>h --> Height of Square Prism

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>Area of squareprism</title>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body 
{
background-color:rgb(250, 251, 251);
}
.edge {
    display: flex;
            height: 100vh;
            width: 100%;    
            justify-content: center;
            align-items: center;
}
.box {
    display: block;
            width: 500px;
            min-height: 300px;
            font-size: 20px;
            background: rgb(7, 152, 50);
            background: linear-gradient(90deg, rgb(7, 152, 55) 9%, rgb(148, 175, 176) 56%);
            border-radius: 10px;
            box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
}
.formelt{
color:orange;
text-align: center;
margin-top: 7px;
margin-bottom: 6px;
}
h1
{
color:rgb(255, 0, 179);
text-align: center;
padding-top: 20px;
}
</style>
</head>
<body>
<div class="edge">
<div class="box">
<h1>Area of a squareprism</h1>
<form method="POST">
{% csrf_token %}
<div class="formelt">
base : <input type="text" name="base" value="{{b}}"></input>(in m)<br/>
</div>
<div class="formelt">
heigth : <input type="text" name="heigth" value="{{h}}"></input>(in m)<br/>
</div>
<div class="formelt">
<input type="submit" value="Calculate"></input><br/>
</div>
<div class="formelt">
Area : <input type="text" name="area" value="{{area}}"></input>m<sup>2</sup><br/>
</div>
</form>
</div>
</div>
</body>
</html>



```


## SERVER SIDE PROCESSING:


## OUTPUT:
![image](https://github.com/vasanvasab/MathServer/assets/143481226/f9271716-506e-4824-a9af-e902dadf71ef)

![image](https://github.com/vasanvasab/MathServer/assets/143481226/283386f7-c862-4087-a0b5-5a61ec304835)


## RESULT:
The program for performing server side processing is completed successfully.
