## Exp--9-Create-a-Birthday-card-using-HTML-and-CSS...
## AIM:
To create a Birthday card using HTML and CSS.

## ALGORITHM:
## Step 1:
Set up the basic structure of your HTML document and include the CSS stylesheet.

## Step 2:
Design the layout of your birthday card using HTML elements such as < div >, < h1 >, < p >, < img >, and < span >.

## Step 3:
Add a container < div > to hold the entire birthday card content.

## Step 4:
Use paragraph tag to disply the personalised greeting. Add an image element to display a birthday-themed image.

## PROGRAM:
## BIRTHDAY.HTML:
~~~
<!DOCTYPE html>
<html>
<head>
	<title>Birthday Card</title>
	<style>
		body {
			background-image: url("cd.avif");
            background-repeat: no-repeat;
            background-size:cover;
			font-family: Arial, sans-serif;
		}
		.card {
			background-color: #fff;
			box-shadow: 0px 0px 20px rgba(0,0,0,0.2);
			border-radius: 10px;
			margin-left: 10%;
			max-width: 600px;
            max-height: 350px;
			padding: 50px;
			position: relative;
			text-align: center;
		}
		
		.card h1 {
			color: #f90;
			font-size: 40px;
			margin-bottom: 20px;
		}
		.card p {
			color: #444;
			font-size: 18px;
			line-height: 1.5;
			margin-bottom: 20px;
		}
		.card img {
			border-radius: 50%;
			height: 200px;
			width: 200px;
		}
		.card button {
			background-color: #f90;
			border: none;
			border-radius: 20px;
			color: #fff;
			cursor: pointer;
			font-size: 16px;
			padding: 10px 20px;
			transition: background-color 0.3s ease;
		}
		.card button:hover {
			background-color: #e87e04;
		}
	</style>
</head>
<body>
   
	<div class="card">
		<img src="photo.jpg" alt="Profile Picture" >
		<h1>Happy Birthday!</h1>
		<p>Wishing you all the happiness and love in the world on your special day!</p>
		<a href="https://www.ovenstory.in/?utm_source=Alliances_phonepe_ph04oa&utm_medium=scratchcard&utm_campaign=alliances&_branch_match_id=891000923333979937&_branch_referrer=H4sIAAAAAAAAA8soKSkottLXLzcwNNRLLCjQy8nMy9ZPzMnJTMxLTi2OL8jIz0stSAXSBib5iUbGAG0iItUwAAAA"><button>Gift coupen</button></a>
	</div>
</body>
</html>

~~~
## OUTPUT:

![birthday card](https://github.com/Guruprasad21002001/Exp--9-Create-a-Birthday-card-using-HTML-and-CSS/assets/95342910/4055232c-2be1-40c0-8263-24e923fc4ee2)

![gift coupen'](https://github.com/Guruprasad21002001/Exp--9-Create-a-Birthday-card-using-HTML-and-CSS/assets/95342910/9c83e38e-70bb-4ce9-8425-57fe414c4312)

## RESULT:
So, a birthday card is created using CSS and HTML.
