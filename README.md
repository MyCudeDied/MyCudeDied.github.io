<button onclick="alert('here you go!')">I want balls</button>
<img id="myImage" src="QuestBoard UI.png" style="display:block; width:50%; height:50%;">
<img id="myImage(1)" src="QuestBoard UI (1).png" style="display:none; width:50%; height:50%;">
<br>
<button style="position:absolute; top:750px; left:800px;" onclick="toggleImage(); toggleImage1();">______________</button>

<script>
function toggleImage() {
  const img = document.getElementById("myImage");
  if (img.style.display === "none") {
    img.style.display = "block";
  } else {
    img.style.display = "none";
  }
}
</script>

<script>
function toggleImage1() {
  const img = document.getElementById("myImage(1)");
  if (img.style.display === "none") {
    img.style.display = "block";
  } else {
    img.style.display = "none";
  }
}
</script>

