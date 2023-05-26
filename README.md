# Design of a Standard Calculator

## AIM:

To design a web application for a standard calculator.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create a new django project.
### Step 2:
Make Changes in settings.py
### Step 3:
Create a new html file and use a CSS for colours.
### Step 4:
Write JavaScript program for implementing five different operations.
### Step 5:
Validate the HTML and CSS code.
### Step 6:
Validate the HTML and CSS code.
### Step 7:
Publish the website in the given URL.

## PROGRAM :
```python
<!DOCTYPE html>
<html>
    <head>
        <title>AR Calculator</title>
        <style type="text/css">
        table{
            border: 1px solid black;
            margin-left: auto;
            margin-right: auto;
        }
        input[type="text"]{
            border: 1px solid black;
            padding: 20px 45px;
            font-size: 24px;
            font-weight: bold;
            border-radius: 2px;
        }


        input[type="button"]{
            width: 100%;
            padding: 20px 40px;
            background-color:rgb(130, 193, 238);
            border-radius: 2px;
        }
        </style>
    </head>
    <body>
        <form name="form1" onload="result.value=''">
            <h1 style="text-align: center;color:rgba(255, 64, 0, 0.396);">Simple Calculator</h1>
        <table id="calc">
            <tr>
                <td colspan="4">
                    <input type="text" id="result">
                </td>
            </tr>
            <tr>
                <td><input type="button" value="+" onclick="result.value+='+'"/></td>
                <td><input type="button" value="1" onclick="result.value+='1'"/></td>
                <td><input type="button" value="2" onclick="result.value+='2'"/></td>
                <td><input type="button" value="3" onclick="result.value+='3'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="-" onclick="result.value+='-'"/></td>
                <td><input type="button" value="4" onclick="result.value+='4'"/></td>
                <td><input type="button" value="5" onclick="result.value+='5'"/></td>
                <td><input type="button" value="6" onclick="result.value+='6'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="*" onclick="result.value+='*'"/></td>
                <td><input type="button" value="7" onclick="result.value+='7'"/></td>
                <td><input type="button" value="8" onclick="result.value+='8'"/></td>
                <td><input type="button" value="9" onclick="result.value+='9'"/></td>
            </tr>
            <tr>
                <td><input type="button" value="/" onclick="result.value+='/'"/></td>
                <td><input type="button" value="." onclick="result.value+='.'"/></td>
                <td><input type="button" value="0" onclick="result.value+='0'"/></td>
                <td><input type="button" value="=" onclick="result.value=eval(result.value)"/></td>
            </tr>
            <tr>
                <td colspan="4">
                    <input type="button" value="Clear All" id="clear" onclick="result.value=''">
                </td>
            </tr>
        </table>
        </form>
    </body>
</html>
```
## Server Output:
![Calci Server Output](https://github.com/Hariharanashok/standard-calculator/assets/120353431/68f93c6b-e01c-4b5f-b3ec-61bf745e6dbc)

## OUTPUT:
![calci output](https://github.com/Hariharanashok/standard-calculator/assets/120353431/7c7e6ece-3b0a-4fa8-acb0-447a1c08e11c)

## Result:
The Simple Calculator web application is now ready to use.

