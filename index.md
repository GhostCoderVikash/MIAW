<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DVd000002bFN7',
				'Quick_Support_MIAW',
				'https://unilever--cgtest.sandbox.my.site.com/ESWQuickSupportMIAW1733901719694',
				{
					scrt2URL: 'https://unilever--cgtest.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://unilever--cgtest.sandbox.my.site.com/ESWQuickSupportMIAW1733901719694/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
