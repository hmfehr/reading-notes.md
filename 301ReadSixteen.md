[What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

1. What is OAuth?
* OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization.

2.Give an example of what using OAuth would look like.
* offers one or more opportunities to log on using another website’s/service’s logon.

3. How does OAuth work? What are the steps that it takes to authenticate the user?
* It is also helpful to remember that OAuth is about authorization in particular and not directly about authentication. Authentication is the process of a user/subject proving its ownership of a presented identity, by providing a password or some other uniquely owned or presented factor. Authorization is the process of letting a subject access resources after a successful authentication, oftentimes somewhere else. 

4. What is OpenID?
* OpenID is for humans logging into machines, OAuth is for machines logging into machines on behalf of humans

# [Authorization and Authentication flows](https://auth0.com/docs/get-started/authentication-and-authorization-flow)

1. What is the difference between authorization and authentication?
* to authenticate users and get their authorization to access protected resources. With Auth0, 

2. What is Authorization Code Flow?
* which exchanges an Authorization Code for a token. Your app must be server-side because during this exchange, you must also pass along your application's Client Secret, which must always be kept secure, and you will have to store it in your client.

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
* During authentication, mobile and native applications can use the Authorization Code Flow, but they require additional security. Additionally, single-page apps have special challenges. To mitigate these, OAuth 2.0 provides a version of the Authorization Code Flow which makes use of a Proof Key for Code Exchange (PKCE).


4. What is Implicit Flow with Form Post?
* The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls. With this method, you don’t need to obtain, maintain, use, and protect a secret in your application.

5. What is Client Credentials Flow?
* such as CLIs, daemons, or services running on your back-end, the system authenticates and authorizes the app rather than a user.

6. What is Device Authorization Flow?
* With input-constrained devices that connect to the internet, rather than authenticate the user directly, the device asks the user to go to a link on their computer or smartphone and authorize the device.

7. What is Resource Owner Password Flow?
* Though we do not recommend it, highly-trusted applications can use the Resource Owner Password Flow, which requests that users provide credentials (username and password), typically using an interactive form.
