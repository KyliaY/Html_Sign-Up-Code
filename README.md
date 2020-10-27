<!DOCTYPE html>
<html>
<style>
input[type=text], select {
  width: 50%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 5px;
}

input[type=submit] {
  width: 50%;
  background-color: black;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 10px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: darkgrey;
}

div {
  border-radius: 12px;
  background-color: lightgrey;
  padding: 10px;
  width: 220px;
}
</style>
<body>

<h3>Sign Up</h3>

<div>
  <form action="/action_page.php">
    <input type="text" id="name" placeholder="Name">
    <input type="text" id="uname" placeholder="Username">
    <input type="text" id="email" placeholder="Email">
    <input type="text" id="password" placeholder="Password">
    <input type="text" id="cpassword" placeholder="Confirm Password">
  
    <input type="submit" value="Submit">
  </form>
</div>

</body>
</html>
