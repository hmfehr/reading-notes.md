# Bearer Authorization

## [Intro to JWT](https://jwt.io/introduction/)

1. What is a JSON Web Token (JWT)?
JSON Web Token (JWT) is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object.

2. When should we use JSON Web Tokens?
Authorization: This is the most common scenario for using JWT. Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token. Information Exchange: JSON Web Tokens are a good way of securely transmitting information between parties. Because JWTs can be signed—for example, using public/private key pairs—you can be sure the senders are who they say they are.

3. Claims are expected in which structural component of a JWT?
Claims are statements about an entity (typically, the user) and additional data. There are three types of claims: registered, public, and private claims.


## [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

1. If I get a JWT and I can decode the payload, how can we call that secure?
just alone it is not secure you would be abe to decode easily if you dont also use a hash or a message

2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
they both need the key to the token

3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
Once the request hits the server, our app will then verify if the Json Web Token is actually valid and if the user is really who he says he is, well then the requested data will be sent to the client and if not, then there will be an error telling the user that he's not allowed to access that resource.

## [JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

1. Why use JWT?
JWT is open standard NYONE CAN USE, sequrely transfer info between two bodies. didgitally signed and info is verified and trusted. compact can be sent via url, post request

2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
contains info about user. avoiding query the db more than once. allows someone not having to log in every time

3. What are the three components (the structure) of a JWT signature?
header, payload, signater

