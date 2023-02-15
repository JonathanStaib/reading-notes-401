# class 03 reading notes

## Review: ES6 Classes

1. Classes are a template for creating objects.

2. Class declarations can not be hoisted as they have remporal dead zones.

3. I would explain a constructor as a way to build an object. I would describe this as a way in which whatever part of code you are in, you can refer to `this.name` and it will pull name from within the certain section you are in.

## Using Express Routing

1. Routing is a way that the applications endpoints answer to client requests.

2. methods are a way to request what you are trying to receive with get post, or more what you are trying to do with the function, how do you want the information to be used. Paths are in combination with the method but have certain endpoints and are more specific and strict.

3. Next is saying that you want it to go to whatever is following. If you have next in your code block when you must invoke it.

## Express Routing

1. An Express Router is a small scale express application without all the big features.
2. We declare our router to be just `express.router()`. this allows us to apply routes to it and we can set default routes and create home and about pages.
3. We use middleware so taht it can log data or check for authentication. It is a way to do stuff before any type of request has been proccessed.
