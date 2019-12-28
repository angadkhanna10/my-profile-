# angadkhanna
.avatar{
	width:500px;
	height: 230px;
	border-radius: 50%;

}
.banner {
	background-image: linear-gradient(-255deg, rgba(0,0,0,0.8) 0%, rgba(0,0,0,0) 50%),  url(../../Images/bannerpics.jpeg);
	color: white;
	background-size: cover;
	padding: 150px 0px;
	opacity: 0.95;
	background-position: center;
}

.banner h1{
	font-size: 50px;
	font-weight: bolder;
}

.banner h2{
	font-size: 30px;
	font-weight: lighter;
	opacity: 0.95;
	margin-bottom: 40px;
}
.button{
	background-color: #46b3e6;
	padding: 15px 20px;
	border-radius: 4px;
	color: white;
	font-weight: bold;
	font-family:'Roboto', 'Helvetica', sans-serif;
}




.cards{
		display: flex;
		flex-wrap: wrap;

}

.card{

	padding: 20px;
	display: flex;
	align-items: center;
	justify-content: space-between;
	box-shadow: 0px 10px 30px rgba(0,0,0,0.2);
	border-radius: 6px;
	margin: 20px;
	flex-basis: 250px;
	flex-grow: 1;

}

.card img	{
	width: 150px;
	border-radius: 6px;
}

.card h3	{

		flex-grow: 1;
		padding-left: 20px;
		font-size: 18px;

}
.container{
  width: 700px;
  margin:80px auto;
}

@media (max-width: 960px) {
  /* For a screen < 960px, this CSS will be read */
  .container {
    width: 700px;
  }
}
@media (max-width: 720px) {
  /* For a screen < 720px, this CSS will be read */
  .container {
    width: 500px;
  }
}
@media (max-width: 540px) {
  /* For a screen < 540px, this CSS will be read */
  .container {
    width: 300px;
  }
}
@import url('https://fonts.googleapis.com/css?family=Lora:400,400i|Roboto:400,400i,700,700i&display=swap');

@import url("Components/container.css");
@import url("Components/avatar.css");
@import url("Components/button.css");
@import url("Components/banner.css");
@import url("Components/card.css");

body{	
	font-family: 'Lora', sans-serif;
	font-size: 18px;
	background-color: rgb(240,240,240)
	margin: 0px;
	}

h1,h2,h3,h4{
	font-family:'Roboto', 'Helvetica', sans-serif;
	font-weight: bold;

}
a{
	text-decoration: none;
	
}
