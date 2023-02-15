# Reading Notes class 02

## An Introduction to NodeJS and Express

1. MIddleware are packages to take care of problems, theres ones to work with cookies, logins security, etc.
2. Express is the most popular Node web framework.
3. Express is unopinioated, this means that it is very lenient and flexible with how you do things.
4. Module is a library or file in JavaScript that you can bring into other code. This is important because it allows us to easily bring in other programs/code into our own code easily with `require()`.

## What is NPM?

1. My machine is running npm on 9.4.0.
2. You would use `npm install jshint` to install jshint library/package into your node project.

## What is TDD?

1. Tests are important because they allow us to see if our code is running properly in specific areas that we want to know are running well. They can be a way to bring out bugs in our code and just improve the quality of our code as a whole.
2. The three expected benefits of testings are reductions in defect rates, reduction in efffort in the projects final stages and lastly improved design qualities and intertnal/technical quality is improved as well.
3. Two Individual pitfalls when writing tests are forgetting to run tests frequently and writing tests for trivial code. Two Team pitfalls when writing tests are only a few developers on the team using it and poor maintenance of the tests.

## CI/CD

1. Three benefits are catching bugs, reducing merge conflicts and have confidence that your software is working properly.
2. The difference between Delivery and Deployment is that delivery is to devlop so that you can release at any time. While deploynent still allows you to devlop at any time but you can do it with confidence and it does it immediately with little to no downtime.
3. Github will inform you when some branches are behind the main branch and how many commits behind, Github also will instantly merge youor branch into main branch as long as it pasts tests.

## README Goals

- I would like to comfortably be able to test an express server after today.
- be able to properly incorporate middleware into my project.

## Lecture Notes

- Signature is what determines the input, outputs. The number of things going in and their type of return value.
- 