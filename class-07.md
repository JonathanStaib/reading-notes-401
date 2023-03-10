# Class 07 Reading Notes

## Intro to JWT

1. What is a JSON Web Token (JWT)?
  It is a token that is good for securely passing information as a JSON object.

2. When should we use JSON Web Tokens?
  JSON Web Tokens are best used for Authorization and Information Exchange. Authorization, it can allow you different services and routes based on permissions. Information exchange, it is a good way opf transmitting data.

3. Claims are expected in which structural component of a JWT?
  Claims are expected in the payload. There are registered claims, public claims, and private claims.

## Are JWTs Secure?

1. If I get a JWT and I can decode the payload, how can we call that secure?
  You having to use an encrypting tool and a secret. This will allow your payload to stay secure.

2. If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.
  In sending a JWT the sender and receiver must both know the secret.

3. Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.
  You both have a little password that will need to be entered when sending out the payload.

## JWTs Explained

1. Why use JWT?
  JWT is used to securely pass information between any two people, servers or computers.

2. JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.
  JWT can be compact meaning you can just send a whole URL over and the information will be hideen within it's contents. The "token" given to you is all the information you need to access the data.

3. What are the three components (the structure) of a JWT signature?
  The three components of a JWT signature are the Header, the Payload and the signature.
