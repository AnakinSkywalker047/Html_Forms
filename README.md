<!DOCTYPE html>
<html>
	<head>
		<title> Registration form </title>
	</head>
	<body>
		<form method="GET">                                                 <!--initializing form tag-->
            <h3>First Name : <input type="text" name="firstname"></h3><br>   <!--first name input element of type text in h3 size and break-->

            <h3>Last Name : <input type="text" name="lastname"></h3><br>     <!--last name input element of type text in h3 size and break-->

            <h3>Email : <input type="email" name="email"></h3>               <!--email input element of type email in h3 size and break-->
            <h3>Password : <input type="password" minlenght="7" name="password"></h3><br>     <!--password input element of type password in h3 size with minimum lenght of 5 charachters and break-->

            <h3>Date Of Birth : <input type="date"></h3><br>                 <!--email input element of type date in h3 size and break-->

            <h3>Gender:</h3>                                                 <!-- gender tag in h3 size -->
            <input type="radio" name="gender" value="male">Male<br>          <!--male radio button and break-->
            <input type="radio" name="gender" value="female">Female<br>      <!--female radio button and break-->
            <input type="radio" name="gender" value="other">Other<br>        <!--other radio button and break-->

            <h3>Pets:</h3>                                                   <!--pets tag with h3 text size and break-->
            <input type="checkbox" name="cat">Cat <br>                       <!--cat tag checkbox and break-->
            <input type="checkbox" name="dog">Dog <br>                       <!--dog tag checkbox and break-->


            <h3>Cars:</h3>                                                   <!-- cars tag in h3 size -->
            <select name="cars">                                             <!-- Initiating select tag for drop down and linking to car tag-->
                <option value="Audi">Audi</option>                           <!-- linking to car tag-->
                <option value="Mercedez">Mercedez</option>                   <!-- linking to car tag-->
                <option value="BMW">BMW</option>                             <!-- linking to car tag-->
            </select>
            
            <h4><input type="submit" value="Register"></h4>                  <!-- submit button named register of h4 text size-->
            <h4><input type="reset"></h4>                                    <!-- reset button of h4 text size-->

		</form>            <!--close form tag-->
	</body>
</html>
