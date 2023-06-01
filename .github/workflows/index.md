---
layout: default
---

Hello World!

Welcome to my website.
<!DOCTYPE html>
<html>
<head>
    <title>Click Counter</title>
</head>
<body>
    <button id="clickme">0</button>

    <script>
    document.getElementById("clickme").onclick = function() {
        var currentNumber = parseInt(this.innerHTML);
        this.innerHTML = currentNumber + 1;
    }
    </script>
</body>
</html>
