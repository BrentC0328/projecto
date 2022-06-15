<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>name!</title>

    <script type="text/javascript">
        function evaluateUserInput() {
            let userInputFirstName = document.getElementById("first_name").value;
            let userInputLastName = document.getElementById("last_name").value;
            let outputDisplay = "Name: " + userInputFirstName + " " + userInputLastName;
            document.getElementById("Output").innerHTML = outputDisplay;
            return false;
        }
    </script>

</head>

<body>
    <form id="myform">
        First name:<br><input type="text" id="first_name"><br>
        Last Name:<br><input type="text" id="last_name"><br>
        <button id="submit_button" onClick="return evaluateUserInput();">Submit</button>
    </form>
    <p id="Output">____________
    </p>
</body>

</html>