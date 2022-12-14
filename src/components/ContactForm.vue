<template>
       <form action="/action_page.php">
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form> 

</template>

<script>
export default {
    name : 'contact',
}
</script>

<style>
.form{
    justify-content: center;
    margin: auto;
    height: 100vh;
    background-color:#2c3e50 ;
}

</style>