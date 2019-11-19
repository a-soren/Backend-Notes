## Auth notes

-its about the client (software) connecting to the client, not the about the user.

-to the server, same user on the same computer connected from insomnia is different from the same user connected from the browser.

-the server has amnesia, it will not remember the client across requests (HTTP is stateless, no common data shared between client and server)

-we need a way to help the server remember the client across requests. 

-sessions are a way to remember clients, cookies remember data.

## Cookies and Sessions##

*** Cookies ***
-is a container of data
-a browser will automatically send cookies on every request to the **domain** associated with the cookie
-the client will store the cookie in the special place
- a server can send a **header** suggesting to the client that it stores a **cookie**.

*** Sessions ***
-used to store data on the server, like a database
-server creates a session for the client
-server produces and send back a cookie
-client stores the cookie
-client sends the cookie on every request


## Auth is not sexy, concentrate on features!!