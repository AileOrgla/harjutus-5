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
        <h2>Andmetüüpide olekud</h2>
        <h3>NULL</h3>
          <?php
            $var1 = null;
            $var2 = "";
            $var3 = 0;
            echo "Kas var1 on null? ".is_null($var1);
            echo "<br>";
            echo "Kas var2 on null? ".is_null($var2);
            echo "<br>";
            echo "Kas var3 on null? ".is_null($var3);
            echo "<br>";
            echo "Kas var4 on null? ".is_null($var4);
          ?>
        <h3>Set</h3>
          <?php
            echo "Kas var1 on väärtustatud? ".isset($var1); 
            echo "<br>";
            echo "Kas var2 on väärtustatud? ".isset($var2);
            echo "<br>";
            echo "Kas var3 on väärtustatud? ".isset($var3);
            echo "<br>";
            echo "Kas var4 on väärtustatud? ".isset($var4);
            echo "<br>";
            echo "Kas var1 on empty? ".empty($var1); 
            echo "<br>";
            echo "Kas var2 on empty? ".empty($var2);
            echo "<br>";
            echo "Kas var3 on empty? ".empty($var3);
            echo "<br>";
            echo "Kas var4 on empty? ".empty($var4);

          ?>

   </body>

</html>
