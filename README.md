
<!doctype>
<html>
<head>
	<title>CatPhotoApp</title>
</head>
<body>
	<a href="#"> <img class="smaller image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange lying on its cat."></a>
	
	<style>
		h2 {
			font-family: Lobster, Monospace;
		}

		p {
			font-size: 16px;
			font-family: Monospace;
		}
		
		.red-text {
			color: red;
                }
		
		.silver-background {
			background-color: silver;
		}
		
		.smaller-image {
			width: 100px;
		}
		
		.thick-green-border {
			border-color: green;
			border-width: 10px;
			border-style: solid;
			border-radius: 50%;
		}
		
		#cat-photo-form {
			background-color: green;
		}
	</style>

	<h2 class="red-text">CatPhotoApp</h2>
	
	<p> View more <a href="#">cat photos</a></p>
	
	<div class="silver-background">
	<p>3 Things cats love:</p>
	<ul>
		<li>Eggs</li>
		<li>Lasers</li>
		<li>Q-tips</li>
	</ul>
	<p>3 Things cats hate:</p>
	<ol> 
		<li>Water</li>
		<li>Being Picked up(sometimes)</li>
		<li>Hot Sauce</li>
	</ol>
	</div>
	
	<form id="cat-photo-form" action="/submit-cat-photo"> 
		<input type="text" required placeholder="cat photo URL">
		<button type="Submit">Submit</button>	
		<label><input type="radio" name="indoor-outdoor"checked>Indoor</label>
		<label><input type="radio" name="indoor-outdoor">Outdoor</label>
		<label><input type="checkbox" name="personality"checked>Sleepy</label>
		<label><input type="checkbox" name="personality">Playful</label>
		<label><input type="checkbox" name="personality">Grumpy</label>
	</form>
	
</body>
</html># CatPhotoApp


