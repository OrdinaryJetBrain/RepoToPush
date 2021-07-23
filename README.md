<!DOCTYPE html>
<html>

	<head>
		<title>DA BEST WEBSITE :D</title>
	</head>
	<body>
		
		<form action="do.php">
			<label for="first_name"></label>
			<input type="text" id="first_name" name="first_name" placeholder="First Name:">

			<br><br>

			<label for="last_name"></label>
			<input type="text" id="last_name" name="last_name" placeholder="Last Name:">

			<br><br>

			<label for="title">Title:</label>

			<label for="Mr.">Mr.</label>
			<input type="radio" value="Mr." id="Mr." name="title">
			<label for="Mrs.">Mrs.</label>
			<input type="radio" value="Mrs." id="Mrs." name="title">
			<label for="Miss.">Miss.</label>
			<input type="radio" value="Miss." id="Miss." name="title">
			<label for="PhD">PhD</label>
			<input type="radio" value="PhD." id="PhD." name="title">

  			<br><br>

  			<label for="payment">Payment:</label>

  			<select id="payment" name="payment">
  				<option value="visa">visa</option>
  				<option value="mastercard">mastercard</option>
  				<option value="giftcard">giftcard</option>
  				<option value="check">check</option>
  			</select>

  			<br><br>

 			<label for="email">Email:</label>
 			<input type="email" id="email" name="email" placeholder="SSquarepants@gmail.com">

  			<br><br>

  			<label for="birthday">Birthday:</label>
  			<input type="date" id="birthday" name="birthday">

  			<br><br>

  			<label for="quantity">Quantity:</label>
  			<input type="number" id="quantity" name="quantity" min="0" max="99" value="1">

 	 		<br><br>

 	 		<label for="phone">Phone #:</label>
 	 		<input type="tel" id="phone" name="phone">

			<br><br>

			<label for="pass">Password:</label>
			<input type="password" id="pass" name="pass" maxlength="12">
			max 12 characters
			<br><br>

			<label for="slider">Rate us:</label>
			1<input type="range" step="25" value="100">5
  			<br><br>

  			<label for="subscribe">Subscribe
  			<input type="checkbox" id="subscribe" name="subscribe">
			<br><br>

			<label for="myfile">upload a file:</label>
			<input type="file" id="myfile" name="myfile" accept=".txt">

			<br><br>

			<input type="reset">

			<br><br>

			<input type="submit">

		</form>
		
	</body>

</html>
