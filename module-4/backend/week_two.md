## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What is Webpack and why is it useful?
  Webpack is a bit like Rails' asset pipeline. It bundles all of your javascript files and their dependencies into one file that is sent as part of the response.

2. When do you want to use event delegation?
  When you have event listeners that may be added or removed from the page. Moving the event listener to those element's parent avoid memory leaks by making sure that the listener is closed when that element is removed and it makes it easy to listen for events on newly added elements.

3. What's one difference between ES5 and ES6?
  ES6 introduces the Class syntactic sugar which can replace constructors and prototypes.

4. What's the deal with semi-colons in JavaScript?
  They are mostly optional expect when a line starts with a block and one other situation that I forget. Some people I have talked to recommend continuing to use them, others say never use them again. ¯\_(ツ)_/¯

5. How are you using the MVC design pattern in your Quantified Self project?
  The MVC design pattern is split up between two apps in this project. The backend handles the models (food, meals) and also has a controller that handles all the api calls. The views are served up by the front end app which only contains two html files a all of the javascript files needed to manipulate the dom.

6. How do you execute raw SQL in node?
  You need some sort of library to interact with the database. In our project we are using KNEX. 
  database = require('knex') or something like that. and then:
  database.raw('SQL goes HERE'

7. What's a callback function and what are some reasons when we use/need callback functions?
  It's a function passed as an argument to another function. The name makes it confusing as hell. The return of the first function can be passed as an argument into the callback function.

8. What is CORS?
  How to looks this one up. The browser only lets javascript receive responses from address that match the current address. I guess this is intended to be a security feature?  

9. What are some steps to avoid CORS?
  We did npm install cors. It think this adds some stuff to the response/request header that tells the browser to allow downloads from other web addresses.

#### Review  

10. Why do people say "HTTP is stateless"?
  It doesn't send state as part of the request/response cycle

11. What is a RESTful API?
  A RESTful API follows restful conventions. This means that all actions are consistently tied to specific http verbs and paths which consistenly perform the same tasks for a sites resources.

12. What are some main characteristics of a team following an agile workflow?
  Iterative approach to development. Morning standups to discuss goals/potential blockers. Frequent sprints leading up to deployment.


13. What are some advantages/disadvantages to using OAuth to authenticate a user?
  Advantages: Delegate authentication to a third party. Easy to set up. Easier for new users to sign up/log in.
  Disadvantages: Rely on third party. If they third party service goes down then users won't be able to access your site. Userss must have an account with the third party in order to sign up for your site.
