# Change Log
<pre>
v2.3.4  apiKey takes priority over OAuth if both are available [MOD-1369]

v2.3.3  Added oauth_consumer_key to support global haproxy [CLOUDSRV-2312][MOD-1357]

v2.3.2  Fixed incorrect exception message "c.trim" on a request timeout [CLOUDSRV-2176]

v2.3.1  Updated example app for newly added feature Titanium.CloudPush.singleCallback [CLOUDSRV-1949][CLOUDSRV-1532]

v2.3.0  Added secureCreate and secureLogin for Secure Identity Server support [MOD-662][MOD-811][MOD-813]
        Do not set request headers for MobileWeb [MOD-831]

v2.2.0  Added Friends, Messages, Events, Files namespaces and methods [MOD-772]
        Fixed issue with empty dictionary items in data when using OAuth [MOD-817]

v2.1.1  Fixed display issue with custom objects in example application [MOD-770]
        Add check for valid numeric data for key-value increment call in example application [MOD-682]
        Fixed issue in example application with reserved name 'public' [MOD-786]
        Fixed check mark becoming disabled in chat example [MOD-778]

v2.1.0  Added Access Control Lists namespace and methods

v2.0.6  Fixed several issues with example application related to chat, custom objects, key values, photos, reviews,
        social, user, and connection notifications.
        Module updated to work with MobileWeb on Chrome, Firefox, and Safari browsers (requires TiSDK 2.1.0)

v2.0.5  Fixed issue with some parameters not being url encoded properly [MOD-752]

v2.0.4	Added Cloud.hasStoredSession() and Cloud.retrieveStoredSession().

v2.0.3	Fixed URL encoding in Mobile Web [MOD-651].

v2.0.2	Fixed boolean parameter coercion corrupting computed Oauth signatures [MOD-609].

v2.0.1	For Android push, use the new asynchronous "retrieveDeviceToken" method.	

v2.0.0	Initial Release
