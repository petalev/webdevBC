# webdevBC
#Learning

tables.html
===========

<h1>First Gen Pokemon Chart</h1>
<table border="1">
	<thead>
		<tr>
		<th>Image</th>
		<th>Name</th>
		<th>Type</th>
		<th>Evolves Into</th>
		</tr>
	</thead>

	<tbody>
	<tr>
		<td><img src="http://img4.wikia.nocookie.net/__cb20140328190757/pokemon/images/thumb/2/21/001Bulbasaur.png/200px-001Bulbasaur.png"></td>
		<td>Bulbasaur</td>
		<td>Grass/Poison</td>
		<td><a href="http://pokemon.wikia.com/wiki/Ivysaur">Ivysaur</a></td>
	</tr>
	<tr>
		<td><img src="http://img4.wikia.nocookie.net/__cb20140724195345/pokemon/images/thumb/7/73/004Charmander.png/200px-004Charmander.png"></td>
		<td>Charmander</td>
		<td>Fire</td>
		<td><a href="http://pokemon.wikia.com/wiki/Charmeleon">Charmeleon</a></td>
	</tr>
	<tr>
		<td><img src="http://img1.wikia.nocookie.net/__cb20140328191525/pokemon/images/thumb/3/39/007Squirtle.png/200px-007Squirtle.png"></td>
		<td>Squirtle</td>
		<td>Water</td>
		<td><a href="http://pokemon.wikia.com/wiki/Wartortle">Wartortle</a></td>
	</tr>
	</tbody>
</table>

</body>
</html>

forms.html
==========
<!DOCTYPE html>
<html>
<head>
	<title>Form Demo</title>
</head>
<body>

<h1>Login</h1>
<!-- action - where the form send data to -->
<!-- method - what HTTP method (get/post) -->
<form>
	<label for="First Name">First Name: </label>
	<input name="firstName" id="First Name" type="text" placeholder="John" value="firstName">

	<label for="Last Name">Last Name: </label>
	<input name="lastName" id="Last Name" type="text" placeholder="Smith" value="lastName">

	<input name="username" type="text" placeholder="username">
	<input name="password" type="password" placeholder="password"> 
	<input type="Submit">
</form>


</body>
</html>

regForm.html
===========
<!DOCTYPE html>
<html>
<head>
	<title>Registration Form</title>
</head>
<body>
	<h1>Register</h1>

<form>
	<label for="First Name">First Name: </label>
	<input name="First Name" id="First Name" type="text" placeholder="John" required>
	<label for="Last Name">Last Name: </label>
	<input name="lastName" id="Last Name" type="text" placeholder="Smith" required>
<div>
	<label for="male">Male: </label>
	<input name="gender" id="male" type="radio">
	<label for="female">Female: </label>
	<input name="gender" id="female" type="radio">
	<label for="other">Other: </label>
	<input name="gender" id="other" type="radio">
</div>

<div>
	<label for="Email">Email: </label>
	<input name="Email" id="Email" type="email" placeholder="your email" required>
	<label for="Password">Password: </label>
	<input name="Password" id="Password" type="password" placeholder="your password" minlength="5" maxlength="10" required>
</div>	
<div>
	<label for="Birthday">Birthday: </label>
	<select name="Birthday">
		<option value=>Month</option>
			<option value=>Jan</option>
			<option value=>Feb</option>
	</select>
	<select name="Birthday">
		<option>Day</option>
			<option value=>1</option>
			<option value=>2</option>
	</select>
	<select name="Birthday">
		<option>Year</option>
			<option value=>1990</option>
			<option value=>1991</option>
	</select>
</div>	
<div>
	I agree to the terms and conditions <input type="checkbox" required>
</div>
<div>
	<input type="Submit">
</div>
</form>

</body>
</html>
