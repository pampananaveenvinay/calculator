
 ## Calculator

This is a simple calculator built using HTML, CSS, and JavaScript.

## View my wesite

click Here to view: https://pampananaveenvinay.github.io/calculator/

### Step 1: HTML

The HTML code creates the basic structure of the calculator. It includes a container div, which holds the calculator form, and a display div, which shows the results of the calculations. 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css" >

</head>
<body>
    <div class="container">
        <h2>CALCULATOR</h2>
        <div class="calculator">
            <form>
                <div class="display">
                    <input type="text" placeholder="0" id="display">
                </div>
                <div>
                    <input type="button" value="AC" onclick="display.value = ''" class="color">
                    <input type="button" value="DE" onclick="display.value = display.value.toString().slice(0,-1)" class="color">
                    <input type="button" value="%" onclick="display.value += '%'" class="color">
                    <input type="button" value="/" onclick="display.value += '/'" class="color">
                </div>
                <div>
                    <input type="button" value="7" onclick="display.value += '7'">
                    <input type="button" value="8" onclick="display.value += '8'">
                    <input type="button" value="9" onclick="display.value += '9'">
                    <input type="button" value="*" onclick="display.value += '*'" class="color">
                </div>
                <div>
                    <input type="button" value="4" onclick="display.value += '4'">
                    <input type="button" value="5" onclick="display.value += '5'">
                    <input type="button" value="6" onclick="display.value += '6'">
                    <
