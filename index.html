<!DOCTYPE html>
<head><title>Federico Gadea MD5 Cracker</title></head>
<body>
<h1>MD5 cracker</h1>
<p>This application takes an MD5 hash
of a four-character lower case string and 
attempts to hash all four-character combinations
to determine the original four characters.</p>
<pre>
Debug Output:
<?php
$goodtext = "Not found";
// If there is no parameter, this code is all skipped
if ( isset($_GET['md5']) ) {
    $time_pre = microtime(true);
    $md5 = $_GET['md5'];

    // This is our alphabet
    $txt = "0123456789abcdefghijklmnopqrstuvwxyz";
    $show = 15;

    $array = "0000";
    
    for($i=0; $i<strlen($txt);$i++){
        $ch1 = $txt[$i];
        for($j=0; $j<strlen($txt);$j++){
            $ch2 = $txt[$j];
            for($k=0; $k<strlen($txt);$k++){
                $ch3 = $txt[$k];
                for($z=0; $z<strlen($txt);$z++){
                    $ch4 = $txt[$z];
                    $try = $ch1.$ch2.$ch3.$ch4;
                    
                    $check = hash('md5', $try);
                    if ( $check == $md5 ) {
                        $goodtext = $try;
                        break;
                    }
                    if ( $show > 0 ) {
                        print "$check $try\n";
                        $show = $show - 1;
                    }
                }
            }
        }
    }

    // Compute elapsed time
    $time_post = microtime(true);
    print "Elapsed time: ";
    print $time_post-$time_pre;
    print "\n";
}
?>
</pre>
<!-- Use the very short syntax and call htmlentities() -->
<p>Original Text: <?= htmlentities($goodtext); ?></p>
<form>
<input type="text" name="md5" size="60" />
<input type="submit" value="Crack MD5"/>
</form>
<ul>
<li><a href="index.php">Reset</a></li>
</ul>
</body>
</html>

