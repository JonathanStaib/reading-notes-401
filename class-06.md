# Readings Notes Class 06

## Securing Passwords

1. Explain to a non-technical friend how you would safely hash and store a password.

  You would use a hash algorithm so you don't have to store hard passwords in your database. The database will then put random characters in as your password that only the system will recognize. It prevents against attacks on databases and keeps your information safe.
2. What is Bcrypt?

  Bcrypt is a algorithm that uses a technique called Key Stretching. It is a adaptive hash function that allows you to determine how expensive a hash function is going to be.
3. Why might you use something like Bcrypt?

  You would use something like Bcrypt to defend your and others data from brute force attacks. It slows down the attacks.

## Basic Auth

1. What is Basic Authentication?

  It is a way for a web browser to request a username and password when you make a request.
2. What properties are necessary in the header of a Basic Auth request?

  The properties necessary in the header are ID and password joined by `:`
3. How are username:password in Basic Auth encoded?
  They are encoded with Base 64.

## OWASP auth cheatsheet

1. Define the authentication process to a non-technical recruiter.

  Having to check users to see if there are authorized to be on your website. It will require some form of login or token.
2. How should your error messaging respond (both HTTP and HTML)? Why?

  Error messaging should respond in a generic manner for both HTTP and HTML.

## Additional Questions

1. I enjoyed learning about bearer auth and how roles worked to allow access for different CRUD functionalities to different roles.

2. I gained a refresher on Auth from this reading :)
