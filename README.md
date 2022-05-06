# ga4-client-for-product-analytics---google-server-side-tag-manager
It's a GA4 client for product analytics to use in Google server side tag manager, that update the Google client ID and session ID and anonymize the IP before passing it to GA4. 

This client is designed to use for product analytics and it may be useless from a marketing point of view. 

This client claim all GA4 requests to Server Side Tag Manager and update the Session ID, Client ID, Session Number with a random number or you can send a value as custom parameter (anmize_id)  to update the Session ID and Client ID. It also anonymize the user IP.

The main objective of this GA4 client is to make the GA4 more GDPR compliant. 
