<?php
if ($_SERVER['REQUEST_METHOD'] === "POST") {
	if (empty($_POST['email'])) {
		$emailError = 'Bitte geben Sie eine Email-Adresse an';
	} else {
		$email = $_POST['email'];

		// validating the email
		if (!filter_var($email, FILTER_VALIDATE_EMAIL)) {
			$emailError = 'Invalid email';
		}
	}
    

    
	if (empty($_POST['message'])) {
		$messageError = 'Bitte geben Sie eine Nachricht ein';
	} else {
		$message = $_POST['message'];
	}
	if (empty($emailError) && empty($messageError)) {
		$date = date('j, F Y h:i A');

		$emailBody = "
			<html>
			<head>
				<title>$email is contacting you</title>
			</head>
			<body style=\"background-color:#fafafa;\">
				<div style=\"padding:20px;\">
					Datum: <span style=\"color:#888\">$date</span>
					<br>
					Email: <span style=\"color:#888\">$email</span>
                    <br>
					Nachricht: <div style=\"color:#888\">$message</div>
				</div>
			</body>
			</html>
		";

		$headers = 	'From: Contact Form <han.richter@gmail.com>' . "\r\n" .
    				"Reply-To: $email" . "\r\n" .
    				"MIME-Version: 1.0\r\n" . 
					"Content-Type: text/html; charset=iso-8859-1\r\n";

		$to = 'han.richter@gmail.com';
		$subject = $_POST['subject'];

		if (mail($to, $subject, $emailBody, $headers)) {
			$sent = true;	
		}
	}
}
?>


<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
	
	<!-- my css -->
	<link href="css/mystyles.css" rel="stylesheet">
    <title>Hello, world!</title>
    <link rel="icon" href="img/BIRI_ICON.png" type="image/png">
      
    <!-- php -->
      
  </head>
  <body>
	<nav class="navbar navbar-expand-lg navbar-light bg-light">
        <a class="navbar-brand" href="index.html"><img src="img/BIRI_LOGO_04.png" width="100px"></a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item">
                    <a class="nav-link" href="index.html">Start</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="Produkte.html">Produkte</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="Markttermine.html">Markttermine</a>
                </li>
                <li class="nav-item active">
                    <a class="nav-link" href="Kontakt.php">Kontakt<span class="sr-only">(current)</span></a>
                </li>
            </ul>
        </div>
    </nav>      
      
    
      
    <div class="container">
      <div class="row">
        <div class="col">
          <form name="contactform" method="post" action="<?= $_SERVER['PHP_SELF']; ?>">
              
              <div class="form-group">
                <label for="name"><img src="icons/person.png" id="person">Name</label>
                <input name="name" type="text" class="form-control" id="exampleFormControlInput1" placeholder="Maxim Musterfrau">
              </div>
              
              
              <div class="form-group">
                <label for="email"><img src="icons/mail.png" id="mail">Email </label>
                <input name="email" type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@beispiel.com">
              </div>
              
              
              <br><img src="img/Baum-VK.png" id="baum"><br>
              
              <div class="form-group">
                <label for="subject">Betreff</label>
                <input name="subject" type="text" class="form-control" id="exampleFormControlInput1">
              </div>

              <div class="form-group">
                <label for="message">Nachricht</label>
                <textarea class="form-control" id="exampleFormControlTextarea1" rows="3" name="message"></textarea>
              </div>
              
              <input type="submit" name="submit" value="Senden" class="btn btn-primary mb-2">
            </form>
            
             <?php if (isset($emailError) || isset($messageError)) : ?> 
                <div id="error-message">
                    <?php 
                        echo isset($emailError) ? $emailError . '<br>' : ''; 
                        echo isset($messageError) ? $messageError . '<br>' : ''; 
                ?>
                </div>
            <?php endif; ?>


            <?php if (isset($sent) && $sent === true) : ?> 
                <div id="done-message">
                    <br>
                    <img src="icons/thumbs%20up.png" id="thumb"> Ihre Nachricht wurde erfolgreich abgeschickt.
                </div>
            <?php endif; ?>
        </div>
          
        <div class="col" id="contact">
        </div>
      </div>
    </div>
      
    


    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
  </body>
</html>