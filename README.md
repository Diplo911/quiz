# quiz

<?php

$conn=mysqli_connect("localhost","root","","diplo");


if($conn){

    echo "database connected";

}
else 
{
    echo "unable to connect to database";
}
