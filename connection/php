<?PHP
//===============
$user_name 	= ""; 
$password 	= ""; 
$database 	= ""; 
$server 	= "";
//==============

$db_handle = mysql_connect($server, $user_name, $password);

$db_found = mysql_select_db($database, $db_handle);

if ($db_found) {

print "Database Found ";
mysql_close($db_handle);

}
else {

print "Database NOT Found ";
}

?>
