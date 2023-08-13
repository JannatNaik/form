# simple html form
<html>
<head>
    <title>Registration forms Msc.(cs)</title>
	<h1>Batch2</h1>
</head>
<body>
    <form bgcolor="pink">
	    <p>
		    <label>Username: <input type="text" /></label>
		</p>
		<p>
		    <label>Password: <input type="Password" /></label>
		</p>
		<p>
		    <button type="sbmit">Sbmit</button>
		</p>
     	<h2>Select your gender</h2>
            <label>Male<input type="radio" name="gender" value="male"/></label>	
			<label>Female<input type="radio" name="gender" value="female"/></label>
		<h2>Choose Language</h2>
		    <ul style="list-style-type:none;">
			    <li><input type="checkbox" name="language" value="hindi">Hindi</li>
				<li><input type="checkbox" name="language" value="English">English</li>
				<li><input type="checkbox" name="language" value="Gujarati">Gujarati</li>
			</ul>	
		<h2>Select your Nationality</h2>	
		    <select name="language">
			    <option value="Indian">Indian</option>
				<option value="American">American</option>
				<option value="Chinese">Chinese</option>
			</select>	
		<textarea name="Welcome Message" rows="5" cols="30">Writ the text you wish</textarea>
		    <fieldset>
			<legend>Personal Details</legend>
			<p>
			    <label>
				Salutation
				</br>
				    <select name="Salutation">
					    <option>--None--</option>
						<option>Mr.</option>
						<option>Ms.</option>
						<option>Mrs.</option>
						<option>Dr.</option>
						<option>Prof.</option>
					</select>
				</label>
			</p>
			<p>
			    <label>First name: <input name="firstname" /></label>
			</p>
			<p>
			    <label>Last name: <input name="last name" /></label>
			</p>
			<p>
			    Gender:
				<label><input type="radio" name="gender" value="Male" />Male</label>
				<label><input type="radio" name="gender" value="Female" />Female</label>
			</p>
			<p>
			    <label><text="required"><input type="email" name="email" placeholder="enter your email here in correct format" />E-mail</label>
			</p>
			</fieldset>
	</form>			
				
</body>
</html>
