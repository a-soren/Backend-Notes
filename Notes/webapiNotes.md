# routing notes

[ client ]== make a request to an==[ api]==sends a response back to the== [ client ]

what is the interface for the web API?

-URI (Uniform Resource Identifier),
-URL (Universal Resource Locator),
-Endpoint (very related to a URI),
-HTTP(network protocol, a set rules for communication)

REST(ish)

'REpresentational State Transfer, a set of guidelines for web API'

-everything is a 'Resource'
-single URI per resource ex: 'http://web23.com/channels'
-use HTTP METHODS to perform operations on resources.

|non REST           |REST             |
|;------------------|:----------------|
|/listAllChannels   | GET /channels   |
|/createChannel     | POST /channels  |
|/updateChannel     | PUT /channels   |
|/deleteChannel     | Delete /channels|
|/findChannel?id=123| GET /channels/123


What is an Express Router? why is it useful?
Express Router can have route/request handlers and middleware

# Query String

https://www.google.com/search
?
q=express
&
rlz=1C5CHFA_enUS848US848&o
q=express
&
sourceid=chrome
&
ie=UTF-8