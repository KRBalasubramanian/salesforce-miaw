<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MIAW Features</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }

        header {
            background-color: #007bff;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        main {
            padding: 20px;
            text-align: center;
        }

        .feature-section {
            margin-top: 30px;
        }

        .feature-section img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .feature-section p {
            color: #333;
            font-size: 16px;
            margin-top: 15px;
        }

        footer {
            background-color: #343a40;
            color: white;
            text-align: center;
            padding: 15px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .btn {
            padding: 10px 20px;
            background-color: #007bff;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 20px;
        }

        .btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <header>
        <h1>Explore MIAW Features</h1>
        <p>Discover how MIAW can enhance your experience!</p>
    </header>
    <main>
        <div class="feature-section">
            <h2>Interactive Chat Features</h2>
            <img src="https://via.placeholder.com/800x400" alt="Chat illustration">
            <p>Engage with a cutting-edge messaging system that is user-friendly and efficient.</p>
        </div>
        <div class="feature-section">
            <h2>Seamless Integration</h2>
            <img src="https://via.placeholder.com/800x400" alt="Integration illustration">
            <p>MIAW integrates seamlessly with your existing systems for a smooth workflow.</p>
        </div>
        <a class="btn" href="#start-chat" onclick="initEmbeddedMessaging()">Start Chatting</a>
    </main>
    <footer>
        &copy; 2024 MIAW. All Rights Reserved.
    </footer>
    <script type="text/javascript">
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
        }
    </script>
    <script type="text/javascript" src="https://jumbo--nextview.sandbox.my.site.com/ESWMIAWWebGithub1731857104899/assets/js/bootstrap.min.js" onload="initEmbeddedMessaging()"></script>
</body>
</html>
