# Hello and congrats!!! 
we've make a simple web with HTML and CSS, now we're gonna the last front-end basic, **javascript the brain**.

## Javascript
in javascript, the language is similar with coding language in general, like there's variable, const, loop algorithm, if-else, etc.

so for those thing you can just read it at https://www.w3schools.com/js/default.asp .

what we're gonna learn here is **DOM (Document Object Model) manipulation**.

and for the setup, there's two way to add JS in our web.

- Using `<script>` tag
     with `<script>` tag, we can add javascript code in the same page of our HTML file.
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p id="try"></p>
    <!-- It's here!! -->
    <script>
        document.getElementById("try").innerHTML="Example"; 
    </script>
</body>
</html>     
```

- With external JS file `<script src="/jsDir"></script>`
  
This way, we can make a new JS file and link it to our HTML, so it can be used in the HTML page.

for example, if you have a JS file named `script.js`, we can link it with:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script src="script.js"></script>  <!-- This!!! -->
</body>
</html> 
```
