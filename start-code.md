``` 
step 1 code:

'use strict';
var today = new Date();
var hourNow = today.getHours();
var greeting;
if (hourNow > 18) {
    greeting = 'Good evening, Class!';
  } else if (hourNow > 12) {
    greeting = 'Good afternoon, Class!';
  } else if (hourNow >= 0) {
    greeting = 'Good morning!';
  } else {
    greeting = 'Something went wrong!';
  }
document.write('<h3>'+greeting+'</h3>');

________________________________________________________________________

step 3 code:

<!DOCTYPE html>
<html>
  <head>
    <title>Constructive &amp; Co.</title>
    <link rel="stylesheet" href="css/c01.css" />
  </head>

  <body>
    <h1>Constructive &amp; Co.</h1>
    <script src="js/add-content.js"></script>
    <p>For all orders and inquiries please call <em>555-3344</em></p>
  </body>
</html>

_______________________________________________________________________

step 7 code:

<!DOCTYPE html>
<html>
  <head>
    <title>Constructive &amp; Co.</title>
    <link rel="stylesheet" href="css/cOl.css" />
   </head>
  <body>
    <hl>Constructive &amp; Co.</hl>
    <script>document.write(' <h3>Welcome !</h3>');
    </script>
    <p>For all orders and inquiries please call
      <em>555-3344</em>
    </p>
  </body>
</html>

```