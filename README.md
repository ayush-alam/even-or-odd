# Find whether a number is even or odd
## Credits
- Ayush Alam
- Ayush Alam
and
- Ayush Alam

## Use the application
- Go [here](https://ayush-alam.github.io/even-or-odd/)
- Give the number when you are prompted by your browser
- In case it is not working, refresh the page. I reccommend you to use `ctrl+F5` instead of using `ctrl+R`
- Enjoy the application (or you may cry because you don't have so much time like me that you will make a useless app like me)

### By the way...
This project is open source, so you can use it anywhere WITHOUT giving me credits. Am not I nice to people?

### And...
So that you feel easy to use my code, I am giving my code below. Just `ctrl+C` and `ctrl+V`.
***
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Find whether number is even or odd</title>
</head>

<body onload="myFunc()">
    <script>
        function myFunc() {
            var number = window.prompt('Enter the number');
            if (number % 2 == 0) {
                document.write(number + " is even");
            }
            else {
                document.write(number + " is odd");
            }
        }
    </script>
</body>

</html>
```
***
-**_Me the superman_**
