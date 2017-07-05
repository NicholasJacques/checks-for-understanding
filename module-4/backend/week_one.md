## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?
  I feel pretty good about how the speed in which I am picking up Javascript. It's definitely encouraging considering how long it took me to understand Ruby. I this the most useful thing I learned was how scopes work in Javascript and how it is different from ruby.

2. What are some tools to help debug JavaScript code?
  You can use the npm console and pryjs.

3. What are some tools you need in order to unit test your JavaScript?
  Mocha and chai

4. What is the syntax for invoking a function?
  function()

5. What's the difference between `==` and `===` in JavaScript?
  '==' is converts both values to the same type and then compares, '===' does not do any type conversion

6. What's the difference between asynchronous and synchronous JavaScript? 
  synchronous javascript runs sequentially, asynchronous Javascript may call a function before the previous function is finished


7. How do we setup a route when creating an API with Node and Express?
  in the server file. I don't remember the syntax off the top of my head but it's something like:
  
```app.get('api/v1/endpoint', function(argument, argument) {
  do stuff
})```


8. What do we use Knex for?
  javascript and databases

9. What's `npm` and what do we use it for?
  node packet manager, javascript outside of the browser


#### Review  
10. What's the MVC design pattern? Describe each part of MVC?
  model: the data
  controller: receives requests and sends responses
  view: html response


11. What is AJAX? What are some benefits of using AJAX?
  ajax can make requests to the server without loading the page.


12. What's a background worker? When would we want to use a background worker?
  background workers in rails work asynchronously. They can be used to schedule a task for a later time or when the server is not busy.
