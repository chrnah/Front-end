# Projeto
CSS, HTML e JS
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Login</title>
    <link rel="stylesheet" href="css/style.css">
	<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.2/css/all.css"
        integrity="sha384-oS3vJWv+0UjzBfQzYUhtDYW+Pj2yciDJxpsK1OYPAYjqT085Qq/1cq5FLXAZQ7Ay" crossorigin="anonymouns">
</head>
<body>
    <div class="container">
        <div class="content first-content">
            <div class="first-column">
                <h2 class="title">welcome back!</h2>
                <p class="description description-primary">to keep connected with us</p>
                <p class="description description-primary">please login with your personal info</p>
                <button class="btn btn-primary">sign in</button>
            </div>
            <div class="second-column">
                <h2 class="title title-second">create account</h2>
                <div class="social-media">
                    <ul class="list-social-media">
                        <li class="item-social-media">
							<a href="#"><i class="fab fa-facebook-f"></i></a>
						</li>
                        <li class="item-social-media">
							<a href="#"><i class="fab fa-google-plus-g"></i></a>
						</li>
                        <li class="item-social-media">
							<a href="#"><i class="fab fa-linkedin-in"></i></a>
						</li>
                    </ul>
                </div><!-- social midia -->
                <p class="description description-second">or use yout email for registration:</p>
                <form class="form">
				<label class="label-input" for="">
					<i class="fas fa-user icon-modify"></i>
                    <input type="text" placeholder="name">
				</label>
				<label class="label-input" for="">
					<i class="far fa-envelope icon-modify"></i>
                    <input type="email" placeholder="email">
				</label>
				<label class="label-input" for="">
				<i class="fas fa-unlock icon-modify"></i>
                    <input type="password" placeholder="password">
				</label>
                    <button class="btn btn-second">sign up</button>
                </form>
            </div><!-- second column -->
        </div><!-- first content -->
        <div class="content second-content">
         <div class="first-column">
                <h2 class="title">hello, friend!</h2>
                <p class="description">enter your personaldetails</p>
                <p class="description">and start journey with us</p>
                <button class="btn">sign up</button>
            </div>
            <div class="second-column">
                <h2 class="title">sign in to developer</h2>
                <div class="social-media">
                    <ul>
                        <li><a href="#">facebook</a></li>
                        <li><a href="#">google+</a></li>
                        <li><a href="#">linkedin</a></li>
                    </ul>
                </div><!-- social midia -->
                <p class="description">or use yout email account:</p>
                <form class="form">
                    <input type="email" placeholder="email">
                    <input type="password" placeholder="password">
                    <a href="#">forgot your password?</a>
                    <button class="btn">sign in</button>
                </form>
            </div><!-- second column -->
        </div><!-- second content -->
    </div>
</body>
</html>
