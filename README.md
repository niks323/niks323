<!DOCTYPE html>
<html>
    <head>
        <style>
            h2{
                width:500px;
                margin:0 auto;
                background:pink;
                text-align: center;
            }
            P{
                color:red;
                font-family:yellow;
                font-size:4;
            }
            form{
                border:3px;
                border-style:solid;
                border-color:red;
                padding:1em;
                margin:0 auto;
                width:250ox;
            }
            img{
                display:block;
                margin-left:auto;
                margin-right:auto;
            }
        </style>
        <title>Nikhils IoT Parking System</title>
        <h2 style = "background-color:black;">Nikhils Parking System</h2>
    </head>
    <body bgcolor="green" text="white">
        <UL>
            <LI>Enter the details of the car owner in the form below</LI>
            <LI>You can also find the details about metro timings below</LI>
        </UL>
        <p>Click here to find details about metro timings below:</p>
        <h4>
            <a style="color:#ffffff"; href="https://kochimetro.org/parking-rates/"> METRO SCHEDULE</a>
        </h4>
        <hr>
        <form method = "post" action="/{{url}}">
            <h3><u><b>Car Owner Details</b></u></h3>
            <label for = "name">Name:</label><br>
            <INPUT TYPE ="text" name= "name" SIZE=20 required><BR>
                <BR>
            <label for = "car_mod">Car Model:</label><br>
            <INPUT TYPE ="text" name= "car_mod" SIZE=20 required><BR>
                 <BR>
            <label for = "plate_no">Plate Number:</label><br>
            <INPUT TYPE ="text" name= "plate_no" SIZE=20 required><BR>
                 <BR>
            <label for = "pno">Phone Number:</label><br>
            <INPUT TYPE ="text" name= "pno" SIZE=20 required><BR>
                 <BR>
            <INPUT TYPE = "submit" VALUE = "Submit">
            <INPUT TYPE ="reset" VALUE = "reset"> 
        </form>
        <br><br>
    </body>
</html>
