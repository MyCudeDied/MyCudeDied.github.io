<button onclick="alert('here you go!')">I want balls</button>
<img id="myImage" src="QuestBoard UI.png" >
<img id="myImage(1)" src="QuestBoard UI (1).png" style="display:none;">
<br>
<button onclick="toggleImage()" onclick="toggleImage1()">Show/Hide Image</button>

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
<br>
<button style="position:absolute; top:600px; left:900px;" onclick="document.getElementById('myImage').style.display='block'">Show</button>
<button style="position:absolute; top:600px; left:1000px;" onclick="document.getElementById('myImage').style.display='none'">Hide</button>

  
