# Class 15

## Authentication

### What is OAuth

1. What is OAuth?

   - An authorization framework that allows unrelated servers/services to *afely allow auth access, without sharing the actual log on credential.

2. Give an example of what using OAuth would look like.

   - Loging into a new website using your preexisting Google credentials.

3. How does OAuth work? What are the steps that it takes to authenticate the user?

   - Website A connects to website B, then B generates and sends a *request token* back to A. This token and secret is then sent to the clients auth provider (Google?). Then the user is asked to approve the auth transaction. The user is given a *access token*, then gives it to website A, who then gives it to website B as proof of authentication.

4. What is OpenID?

   - Now OpenID is an authentication layer for OAuth. Before though, it could be described as something *"for humans logging into machines, OAuth is for machines logging into machines on behalf of humans."*

### Authorization and Authentication flows

1. What is the difference between authorization and authentication?

   - Authorization is the process of verifying what something has access to, and authentication is the process of verifying who someone is.

2. What is Authorization Code Flow?

   - The way data flows in order to exchange an authorization code for a token on regular web apps.

3. What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

   - The data flow for native apps or single page apps, because they cannot securely store a Client Secret.

4. What is Implicit Flow with Form Post?

   - Uses OpenID to implement web sign-in. Requests and obtains tokens through the front, with no need for Secrets or backend calls.

5. What is Client Credentials Flow?

   - Rather than authorizing the client, the system authenticates and authorizes the app itself.

6. What is Device Authorization Flow?

   - Basically logging into Netflix on your TV, from your computer.

7. What is Resource Owner Password Flow?

   - User signs in with username and password.
