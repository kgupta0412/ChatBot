<html>
	<body>
	<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DJW000006ylwl',
				'Alice',
				'https://bordgaisenergyeandu--kavydev.sandbox.my.site.com/ESWAlice1733570259723',
				{
					scrt2URL: 'https://bordgaisenergyeandu--kavydev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://bordgaisenergyeandu--kavydev.sandbox.my.site.com/ESWAlice1733570259723/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
</body>
</html>
