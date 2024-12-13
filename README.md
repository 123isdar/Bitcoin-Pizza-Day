<h1>Screenshot of the website</h1>
<img src="https://raw.githubusercontent.com/123isdar/Bitcoin-Pizza-Day/refs/heads/main/download.png">
<h2>and this is url <a href="https://bitcoin-pizza-day.blogspot.com/" target="_blank">bitcoin-pizza-day.blogspot.com/</a></h2>
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>قوس قزح</title>
    <style>
        a {
            font-size: 24px;
            font-weight: bold;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <a href="https://www.example.com" id="rainbowLink" target="_blank">اضغط هنا</a>

    <script>
        const link = document.getElementById("rainbowLink");

        // قائمة بألوان قوس قزح
        const colors = ["red", "orange", "yellow", "green", "blue", "indigo", "violet"];
        let colorIndex = 0;

        // تغيير اللون بشكل دوري
        setInterval(() => {
            link.style.color = colors[colorIndex];
            colorIndex = (colorIndex + 1) % colors.length; // إعادة ضبط المؤشر
        }, 500); // تغيير اللون كل نصف ثانية
    </script>
</body>
</html>
