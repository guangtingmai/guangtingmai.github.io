---
permalink: /
---

<head>
  <title>XXX</title>
</head>

<script>
  // force navigation highlight for "Home"
  document.addEventListener("DOMContentLoaded", function() {
    let homeLinks = document.querySelectorAll('a[href="/"]');
    homeLinks.forEach(link => link.textContent = "Home");
  });
</script>
