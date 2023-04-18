 # Umbrella corporation
 ## Test Task in Go

You have 1 hour to solve the task. If you are lucky enough and have time left,
please try to optimise your solution or highlight some edge cases.

### Buid a middleware using echo framework

First of all, you should create a handler which sends how many __days__ left __until 1Jan 2025__
and response with HTTP __200 OK__ status code.

Secondly, build a middleware, which checks HTTP header __User-Role__ presents and contains 
__admin__ and prints __"red button user detected"__ to the console (using default log package or any 3rd party) if so.

Think about coding standards and best practices.