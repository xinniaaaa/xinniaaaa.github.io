# xinniaaaa.github.io
Project. Website
<!DOCTYPE html>
<html>
<body>
<body style= background-color:#98DD77>
<p>Select your favorite Album:</p>
<form action="/action_page.php">
  <input type="radio" name="Album" onclick="myFunction(this.value)" value="News of the World">News of the World<br>
  <input type="radio" name="Album" onclick="myFunction(this.value)" value="A Nght At the Opera">A Nght At the Opera<br>
  <input type="radio" name="Album" onclick="myFunction(this.value)" value="Innuendo">Innuendo<br>
  <input type="radio" name="Album" onclick="myFunction(this.value)" value="Sheer Heart Attack">Sheer Heart Attack<br>
  <input type="radio" name="Album" onclick="myFunction(this.value)" value="A Kind of Magic">A Kind of Magic<br><br>

  Your favorite Album is: <input type="text" id="result">
  <input type="submit" value="Submit form">
</form>

<script>
function myFunction(Album) {
    document.getElementById("result").value = album;
}
</script>

</body>
</html>
