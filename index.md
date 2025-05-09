<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MIAW Insurance</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background-color: #0047ab;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            background-color: #002f6c;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 16px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            text-align: center;
            padding: 50px 20px;
            background-image: url('https://images.pexels.com/photos/1166640/pexels-photo-1166640.jpeg');
            background-size: cover;
            background-position: center;
            color: white;
        }

        .hero h2 {
            margin-bottom: 20px;
        }

        .container {
            padding: 20px;
            max-width: 1200px;
            margin: auto;
        }

        .features {
            display: flex;
            justify-content: space-between;
            gap: 20px;
        }

        .feature {
            flex: 1;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding: 20px;
        }

        .feature img {
            max-width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 8px;
        }

        .feature h3 {
            margin-top: 15px;
        }

        footer {
            background-color: #002f6c;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            background-color: #0047ab;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
        }

        .btn:hover {
            background-color: #003580;
        }
    </style>
</head>
<body>


<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'
			window.addEventListener("onEmbeddedMessagingReady", () => {            
				console.log( "Inside Prechat API!!" );
			embeddedservice_bootstrap.userVerificationAPI.setIdentityToken
						({
						identityTokenType : "JWT", 

						identityToken :"eyJraWQiOiI2Nzg5MCIsImFsZyI6IlJTMjU2In0.eyJpc3MiOiJzYWxlc2ZvcmNlIiwic3ViIjoiNDU2Nzg5IiwiZXhwIjoxNzQ1MzA2NDQ4LCJpYXQiOjE3NDUyNDY0NDh9.HldyC8Ms8lx5oOiN-jMERssKFUaKci_YDbPBr0fn4fCSJ9Ht1hXXXV9Irms1qiO2CdzVAHdhcULzIKeSGcbcUtpDk0p_WfYXZjO2sq30aZdZ87xLg7YWzbECqrubW0R-fQUO8OBCR6EwzZ9ztgzR7Fi8QhiOS7xBc2gxycbtrhIFm2fxEHsYhnWQOS1z4byU1bCTX_BPiu2KefYb-mC-4lTltmc7gI4nzlm_WvsEUjSvhc3GDEmj2dym5pG38PB61B6HmbdsuYewXICLE_A8qyg7G8rWskeZ6UYtguTdRz7vIqgutCtIUCWrvKJebNeNXWhGzj0lAkv2MZaXQZKhWQ"
						});
					 
			});
			embeddedservice_bootstrap.init(
				'00D8D0000004cJ8',
				'MIAW_POC_AUTH_Web',
				'https://farmerssrm--solex5.sandbox.my.site.com/ESWMIAWPOCAUTHWeb1744329772619',
				{
					scrt2URL: 'https://farmerssrm--solex5.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://farmerssrm--solex5.sandbox.my.site.com/ESWMIAWPOCAUTHWeb1744329772619/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>


    <header>
        <h1>MIAW Insurance</h1>
        <p>Your Future, Secured Today</p>
    </header>
    <nav>
        <a href="#services">Services</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
    </nav>
    <section class="hero">
        <h2>Insurance Plans</h2>
        <a class="btn" href="#contact">Get a Quote</a>
    </section>
    <section class="container">
        <h2 id="services">Our Services</h2>
        <div class="features">
            <div class="feature">
                <img src="https://images.pexels.com/photos/4164996/pexels-photo-4164996.jpeg" alt="Life Insurance">
                <h3>Life Insurance</h3>
            </div>
            <div class="feature">
                <img src="https://images.pexels.com/photos/4164996/pexels-photo-4164996.jpeg" alt="Health Insurance">
                <h3>Health Insurance</h3>
            </div>
            <div class="feature">
                <img src="https://images.pexels.com/photos/4164996/pexels-photo-4164996.jpeg" alt="Auto Insurance">
                <h3>Auto Insurance</h3>
            </div>
        </div>
    </section>
    <section class="container">
        <h2 id="about">About Us</h2>
        <p>
            MIAW Insurance has been providing reliable insurance solutions for over 20 years.
        </p>
    </section>
    <section class="container" id="contact">
        <h2>Contact Us</h2>
        <p>Have questions or need assistance? We're here to help!</p>
        <p>Email: support@MIAW.com</p>
        <button id="launchChatButton" class = 'btn' onclick="launchChat()">
		Send a message
	</button>
    </section>
    <footer>
        &copy; 2024 MIAW Insurance. All rights reserved.
    </footer>
</body>
</html>
