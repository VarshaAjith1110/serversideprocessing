# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:

### Step 1:



### Step 2:



### Step 3:



### Step 4:



### Step 5:



### Step 6:

Publish the website in the given URL.

## PROGRAM :
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Area</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    <style>
        body{
            text-align: center;
            background-color: aqua;
        }
        .maindiv{
            margin-left:400px;
              text-align: center;
            border-style: dashed;
            width: 550px;
            height: 300px;
            background-color:white;
        }
        h1{
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1>Server Side processing</h1>
    
    <div class="maindiv">
        <h1>Area of Rectangle</h1>
        <form method="POST">
            {% csrf_token %}
            Length = <input type="text" name="length" value="{{l}}"> meters <br/>
            <br/>
            width = <input type="text" name="width" value="{{w}}"> meters<br/>
            <br/>
            <input type="submit" value="Calculate"><br/>
            <br>
            Area = <input type="text" name="area" value="{{area}}"> meter<sup>2 </sup><br/>
        </form>
        <br>
        <br>
        <footer>
            Developed by: Varsha Ajith
        </footer>
    </div>
</body>
</html>

## OUTPUT:

### Home Page:


## Result:

