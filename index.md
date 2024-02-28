<html>
  <body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D7a00000052td',
				'DE_MIAW',
				'https://psa-bank--uat.sandbox.my.site.com/ESWDEMIAW1707985554271',
				{
					scrt2URL: 'https://psa-bank--uat.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://psa-bank--uat.sandbox.my.site.com/ESWDEMIAW1707985554271/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

  </body>
</html>
