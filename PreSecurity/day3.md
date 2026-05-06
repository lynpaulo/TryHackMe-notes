Day 3 – TryHackMe
What is HTTP?
HTTP (HyperText Transfer Protocol) is the protocol used to load websites.
It defines how your browser communicates with web servers to request and receive data like HTML, images, and videos.

What is HTTPS?
HTTPS is the secure version of HTTP.
Encrypts data (so others can’t read it)
Verifies you're talking to the real server (not a fake one)

What is a URL?

A URL (Uniform Resource Locator) is the address used to access resources on the internet.

Example parts of a URL:
Scheme – protocol used (HTTP, HTTPS, FTP)
Host – domain or IP (e.g., tryhackme.com)
Port – connection port (default: 80 for HTTP, 443 for HTTPS)
Path – location of resource (e.g., /blog)
Query – extra data (e.g., ?id=1)
Fragment – section of a page (e.g., #section1)

HTTP Requests & Responses
Request
A browser sends a request like:
GET / HTTP/1.1

It can also include headers (extra info), such as:
Host (which website)
User-Agent (browser info)

Response
The server replies with:

Status code (e.g., 200 OK)
Headers
Content (the webpage)

HTTP Methods
These tell the server what action you want:

GET → Retrieve data
POST → Send/create data
PUT → Update data
DELETE → Remove data

HTTP Status Codes
Server responses fall into categories:

200 → Success
201 → Created something
401 → Unauthorized
404 → Not found
503 → Server error

Headers
Headers send extra information between client and server.

Common Request Headers:
Host → which site you want
User-Agent → browser info
Content-Length → size of data sent
Cookie → stored user data
Common Response Headers:
Set-Cookie → store data in browser
Content-Type → type of file returned
Cache-Control → caching rules

Cookies
Cookies are small pieces of data stored in your browser.

They are used for:
Login sessions
Remembering users
Saving preferences

Since HTTP is stateless, cookies help websites remember you.

Key Takeaways
HTTP = communication between browser and server
HTTPS = secure version of HTTP
URLs tell the browser where to go
Methods define actions (GET, POST, etc.)
Status codes show results of requests
Cookies help maintain user sessions
