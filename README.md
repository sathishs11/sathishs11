<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Register form</title>
  </head>
  <body>
    <h1>Register form</h1>
    <h2>All field are Mandotory</h2>
<form class="" action="thankyou.html" method="post">
<label for="name">  Name</label>
<input id="name"type="text" name="name" placeholder="Enter Name"required>
<br>
<label for="mail">Email</label>
<input id="mail"type="email" name="mail" placeholder="Enter Email"required>
<br>
<label for="age">Age</label>
<input id="age"type="text" name="Age" placeholder="Enter Age"required>
<h3>Are you Interested In Dating</h3>
<label for="dat">yes</label>
<input id="dat"type="checkbox" name="dating" value="">
<label for="dat1">No</label>
<input id="dat1"type="radio" name="dating" value="">
<h3>Your Expections like:</h3>
<select class="" name="expe">
  <option value="nayan">Nayanthara</option>
  <option value="sam">Samantha</option>
  <option value="thamana">Thamana</option>
  <option value="pooja">Pooja Hedge</option>
</select>
<h3>How many Marraiges you want:</h3>
<select class="" name="nom">
  <option value="fresh">0-fresher</option>
  <option value="one">1-married</option>
  <option value="two">2-married</option>
  <option value="three">3-married</option>
  <option value="four">4-married</option>
</select>
<h3>Are you Heavy Drinker</h3>
<input type="checkbox" name="Drinker"value="yes">Yes
<input type="radio" name="Drinker" value="no">No
<input type="checkbox" name="Drinker" value="week-end">only on week-ends
<h3>Your preference and Extra information</h3>
<textarea name="pref" rows="8" cols="80"></textarea>
<input type="submit" name="" value="register">
</form>
  </body>
</html>
