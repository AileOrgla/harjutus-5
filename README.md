harjutus-5
==========
<!DOCTYPE HTML>
<html>
   <head>
   <title>Harjutus3</title>
   <meta http-equiv="Content-Type" content="text/html;
   charset=utf-8">
   <title>PHP põhitõed</title>
   </head>
   <body>
      <h2>Booleans</h2>
        <?php
          $result1 = true;
          $result2 = false;
          echo $result1;
          echo "<br>";
          echo $result2;
          echo "<br>";
          echo "Result 1: {$result1}";
          echo "<br>";
          echo "Result 2: {$result2}";
          echo "<br>";
          echo "Kas result1 on boolean? ".is_bool($result1);
          echo "<br>";
          echo "Kas result2 on boolean? ".is_bool($result2);
          echo "<br>";
          $result3 = 20;
          echo "Kas result3 on boolean? ".is_bool($result3);
        ?>

   </body>

</html>
