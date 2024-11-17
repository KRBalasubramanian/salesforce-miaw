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
	h1 a{display:none}

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
    background-image: url('https://images.unsplash.com/photo-1526569181025-0e3c6a443d6d?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzNjUyOXwwfDF8c2VhcmNofDN8fGluc3VyYW5jZXxlbnwwfHx8fDE2ODkxODY2MDM&ixlib=rb-1.2.1&q=80&w=1200');
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

			embeddedservice_bootstrap.init(
				'00DS8000000CBe1',
				'MIAW_Web_Github',
				'https://jumbo--nextview.sandbox.my.site.com/ESWMIAWWebGithub1731857104899',
				{
					scrt2URL: 'https://jumbo--nextview.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://jumbo--nextview.sandbox.my.site.com/ESWMIAWWebGithub1731857104899/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

    <header>
        <h1>Life Insurance</h1>
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
            <img src="https://images.unsplash.com/photo-1588776814546-b84f26f7cf71?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzNjUyOXwwfDF8c2VhcmNofDN8fGxpZmUlMjBpbnN1cmFuY2V8ZW58MHx8fHwxNjg5MTg2NjAz&ixlib=rb-1.2.1&q=80&w=400" alt="Life Insurance">
            <h3>Life Insurance</h3>
        </div>
        <div class="feature">
            <img src="https://images.unsplash.com/photo-1583936504570-d7966ef4f9b4?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzNjUyOXwwfDF8c2VhcmNofDR8fGhlYWx0aCUyMGNhcmV8ZW58MHx8fHwxNjg5MTg2NjAz&ixlib=rb-1.2.1&q=80&w=400" alt="Health Insurance">
            <h3>Health Insurance</h3>
        </div>
        <div class="feature">
            <img src="https://images.unsplash.com/photo-1600803909240-3c52ed13a31b?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwzNjUyOXwwfDF8c2VhcmNofDV8fGF1dG8lMjBpbnN1cmFuY2V8ZW58MHx8fHwxNjg5MTg2NjAz&ixlib=rb-1.2.1&q=80&w=400" alt="Auto Insurance">
            <h3>Auto Insurance</h3>
        </div>
    </div>
</section>

    <section class="container">
        <h2 id="about">About Us</h2>
        <p>
            MIAW Insurance has been providing insurance solutions for over 20 years. 
        </p>
    </section>
    <section class="container" id="contact">
        <h2>Contact Us</h2>
        <p>Email: support@MIAW.com</p>
        <a class="btn" href="mailto:support@MIAW.com">Send Us a Message</a>
    </section>
    <footer>
        &copy; 2024 MIAW Insurance. All rights reserved.
    </footer>
	
</body>
</html>
