<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DQH00000AbiSY',
				'Order_Refund_Agent_Deployment',
				'https://agentforce57-dev-ed.develop.my.site.com/ESWOrderRefundAgentDep1735053145179',
				{
					scrt2URL: 'https://agentforce57-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://agentforce57-dev-ed.develop.my.site.com/ESWOrderRefundAgentDep1735053145179/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
