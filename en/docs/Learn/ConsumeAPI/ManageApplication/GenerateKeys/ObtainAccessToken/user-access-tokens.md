# User Access Tokens

### Generating user access tokens

User access tokens are tokens that authenticate the final user of an API, and are valid for all APIs subscribed to a user via a particular application. User access tokens allow you to invoke an API even from a third-party application such as a mobile app. 

You can generate a user access token by calling the [Token API](../../../../../APISecurity/OAuth2/token-api/) through a REST client. When generating a token, you need to use a grant type that associate with an end user. For example, **password**, **authorization code**, **implicit**, **SAML2**, **IWA-NTLM** and **JWT**.

!!! note
    * When a user is deleted or the user's password is changed, all the access tokens generated by the user are automatically invalidated.

### Renewing user access tokens

To renew a user token, you can use **refresh token** grant type. For more information, see [Refresh Token Grant](../../GrantTypes/refresh-token-grant/)
