<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h2> Regex text </h2>
    <p id="out"></p>
    <script>
        let pattern = /love/i;
        let text = "I love chocolates";
        document.getElementById("out").innerText=pattern.test(text);
    </script>
</body>
</html>
