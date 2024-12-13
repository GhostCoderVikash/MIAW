<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DQy00000H5ypn',
				'customer_portal',
				'https://resourceful-fox-a2o4pb-dev-ed.trailblaze.my.site.com/ESWcustomerportal1733849211221',
				{
					scrt2URL: 'https://resourceful-fox-a2o4pb-dev-ed.trailblaze.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://resourceful-fox-a2o4pb-dev-ed.trailblaze.my.site.com/ESWcustomerportal1733849211221/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
