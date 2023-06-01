---
layout: default
---

Hello World!

Welcome to my website.

<button id="clickme">0</button>

<script>
document.getElementById("clickme").onclick = function() {
    var currentNumber = parseInt(this.innerHTML);
    this.innerHTML = currentNumber + 1;
}
</script>
