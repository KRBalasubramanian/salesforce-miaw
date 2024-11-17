<html>
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
</body>
</html>
