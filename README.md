# CSS_Categories

https://www.youtube.com/watch?v=vmXIGdP8KN8
	
	1. Vanilla CSS ---- code css in your way…
		a. Eg. In css fie write 
		.button {
		    font : inherit;
		    border : 1px solid blueviolet;
		    background-color: blueviolet;
		    color: whitesmoke;
		    padding: 2px 10px;
		}
		b. In html file use it as follow:
		<button class="button">ClickMe!!</button>
		 
	2. Bootstrap CSS -- component styling import link from bootstrap website https://getbootstrap.com/  navigate to /docs/4.5/components/buttons/   import the link and use as is
		a. Advantage : No need to write a CSS code if we do not want to. Just add the class and use as is
		b. Limited to use bootstrap or any other framework. For making it custom we can overwrite but if we overwrite a lot, we are not using that framework rightly !! :( :(
		c. Eg. Add link in index.html 
		<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
		
		From <https://getbootstrap.com/docs/4.5/getting-started/introduction/> 
		
		Add button in html eg.
		 <button class="btn btn-primary">Click Here</button>
		
	
	3. TailWind CSS --- Utility CSS framework   https://tailwindcss.com/
		a. Unlike bootstrap tail wind doesn't give pre-styled components like buttons etc.
		b. Need to less cs coding
		c. But we can combine utility classes to get our styled components.
