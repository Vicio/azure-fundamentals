Is the cloud version of active directory. However it cannot become a replacement for corporate level [[Active Directory]]. Entra ID uses protocols such as SAML or Oauth for communication.

You can use Entra ID instead of your own identity server. The provider becomes the intermediary between the client and the application server.

## Conditional access
It is one of the Entra ID services in which you can configure a specific set of rules to allow or deny access to your services and data. This is done by using some inputs called signals. These signals are different sources of identity attempts, such as user and their location, devices, applications or unusual logins.

Once a signal is registered, it is compared against some rules that enforce that only when some specific conditions for a signal are met, it is until then that the user is provided a key to access the services.