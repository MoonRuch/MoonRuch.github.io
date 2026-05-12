---
title: Почему люди паникуют
---

# Мини-эксперимент

<button onclick="panic()">НАЖМИ</button>

<p id="out"></p>

<script>
function panic(){
  document.getElementById("out").innerText =
    "Толпа начала паниковать!";
}
</script>