The TrueTMS API uses OAuth2 for authentication. To authenticate, you will need to obtain a token from the OAuth2 flow. The token should be included in the Authorization header of your requests.
Once we create client credentials for you, you can use the client ID and client secret to either obtain a token directly using the `client_credentials` flow
or redirect the user to the authorization URL to obtain a token using the `authorization_code` flow.

Our OpenID connect endpoints are listed below:
- Beta: [https://beta-auth.truetms.com/auth/realms/truetms/.well-known/openid-configuration](https://beta-auth.truetms.com/auth/realms/truetms/.well-known/openid-configuration)
- Production: [https://auth.truetms.com/auth/realms/truetms/.well-known/openid-configuration](https://auth.truetms.com/auth/realms/truetms/.well-known/openid-configuration)
