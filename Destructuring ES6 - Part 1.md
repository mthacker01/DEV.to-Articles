## ES6 - *Destructuring the Good Parts!*
I have been learning JavaScript for a couple of months. To break up tutorials and reading, I love trying my hand at coding challenges. I have decent success in completing the challenges, however, my code will usually usually be 3 to 4(x's) longer than the solution others come up with. And if we're being honest, I didn't have the <strong>slightest</strong> clue as to what most of the code base for the solutions were doing.

Recently, I started in learning some of the additions to ES6 and I'm not sure how I've made it this far without knowing several of these. Some I really struggled to understand and I probably still don't FULLY grasp the technical aspect or the full capabilities but this is why I'm writing this. I last posted that I wanted to use my learning as a resource to help others that struggle in learning the same way that I do. 

I debated on what to start posting about, and I've finally decided to start a series of posts about, what I think are, the best parts of ES6. 

## Let's Get <em>Destructuring {Objects}</em>!

What is destructuring? It's essentially a fancy term for being able to pull out a value(s) from an array or properties from an object and save it to a variable. A lot of the coding challenges I've completed variation that required this task in order to fulfill its requirements. 

This is how I've always completed extracting values from arrays and objects before:

![code block 1](code1.png)

If we `console.log(myName)` we'll get the value "Matt" for the name property.

Because I have nested objects, if I wanted to get the value for my favorite Premier League soccer team, I'd need to create a variable that held `myObj.likes.soccer.Premier`. And I'd have to do that twice to get my two favorite soccer teams.

With destructuring, we can cut down on the repetitiveness of the code.

![code block 2](code2.png)

Here, I'm essentially creating two variables `FIFA` and `Premier` that are the property names within the nested object. We can go a step further and assign the values to our own created variable names by assigning the variable name after the property name: `const {propertyName:newVar} = object`

![code block 3](code3.png)

Destructuring is a much more effecient way of extracting values out of objects.

Hope this helps someone, because I feel like I understand it more now that I've sat down and written this. Happy Coding!