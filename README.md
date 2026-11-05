# first-website
Code for Thomas' first ever website

# Testing
<head>

<body>
<fieldset>
<legend>Info</legend>
<form action="#" method="get">
	<label for="name">First Name</label>
	<input id="Full name" name="Full Name" type="text" autocomplete="First Name" minlength="2"
	maxlength="30" required placeholder="Alex ">

<br>
<br>
<label for="name">Middle Initial</label>
	<input id="middle initial" name="middle initial" type="text" autocomplete="middle initial" minlength="1"
	maxlength="1" required placeholder="A">

<br>
<br>
<label for="Last Name">Last Name</label>
	<input id="last name" name="last name" type="text" autocomplete="last name" minlength="2"
	maxlength="30" required placeholder="Student">


<br>
<br>

<label for="name">Phone (required)</label>
	<input id="Phone" name="phone" type="tel" autocomplete="tel" 
	required placeholder="502-126-4567">

	
<br>
<br>
<label for="email">Email</label>
<input id="email" name="email" type="email" autocomplete="email" required placeholder="alex@example.com">
<br>
<br>
<label for="start">Preferred start date
</label>
<input id="start" name="start" type="date">
<br>
<br>
<label for="grade">Grade level</label>
<select id="grade" name="grade" required>
<option value="">Choose a grade</option>
<option value="9">9th</option>
<option value="10">10th</option>
<option value="11">11th</option>
<option value="12">12th</option>
</select>
<br>
<br>
<label for="grade">Favorite Game</label>
<select id="grade" name="grade" required>
<option value="">Choose a Game</option>
<option value="rec">Recroom</option>
<option value="cod">Call of Duty</option>
<option value="MC">Minecraft</option>
<option value="Lego">Legos</option>
</select>

<br>
<br>


<label for="grade">Original State</label>
<select id="state" name="state" required>
<option value="">Choose a State</option>
<option value="ky">Kentucky</option>
<option value="origan">Origan</option>
<option value="ny">New York</option>
<option value="maine">Maine</option>
</select>

<br>
<br>

<Label for="meetings">Meetings per month</label>
<input id="meetings" name="meeting" type="number" min="1" max="8" step="1" value="2">


<br>
<br>










</form>
</fieldset>
<br>

<fieldset>
<br>
<legend>T-shirt Size</legend>
<br>
<label><input type="radio" name="size" value="s"> Small</label>
<label><input type="radio" name="size" value="m"> Medium</label>
<br>
<label><input type="checkbox" name="skills" value="html"> HTML</label>
<label><input type="checkbox" name="skills" value="css"> CSS</label>
<br>

</fieldset>

<fieldset>
<legend>Tell us more</legend>
<label for="message">Why would you like to join?</label>
<textarea id="message" rows="4" maxlength="300" placeholder="write a few sentences..."></textarea>

</label>
</fieldset>
<button type="submit">Send</button>
