<!-- 
I am Kato isa creator of simplify.js
Adress: Uganda, Kampala, Sseguku/Fort.
webste: https://katoisa256.ga.
google: katoisa256.
whatsApp: +256705207718.
I mainly use whatsApp, coz its easy for me to comunicate with people.
If you wanna become a contributer or wnna work on sme other.
Project contact methrough whatsApp ....
 -->

# How to use Simplify.js ?
## MORE NEEDS TO BE DONE. like (error checking, more functions and more)
Imagine simplify.js as a big object that has functions for properties, each function has its own task,
more like shortening that javascript syntax.

What is simplify.js? | how it came to be?
Well, I was tired of thie JavaScript Syntax and how it looked, coz I have spent 5 years writing in thie same syntax, I kind of got bored by seeing one long function being repeated every time.
So I decided to tweak the syntax a little bit, I came up with simplify.js a JavaScript library that not only changes the syntax but simplifies it instead of writing a long JavaScript function to add an event listener why not use a short function that takes in three parameters?
Well, simplify.js takes care of the boring stuff for you and helps u create organized code.
For example: in normal JavaScript, we would write:
```js  
1. Document.querySelector(‘body’).addEventListener(‘load’, () => {
2. 
3. Alert(‘this is hell’);
4. 
5. });
```
What the heck, imagine having 100 or more blocks of code like that flooding your code, it’s a pain right.
simplify.js code Example: instead of writing all of that simplify breaks down thie block

```js
1. _.Event(‘body’, ‘load’, ()=>{
2. 
3. Alert(‘simplify.js is heaven’);
4. 
5. });
```
# A number of functions u can use are all listed below...

  ## The Select function: substitute to document.querySelector. <!-- document.querySelector('body') -->
it's simple as writing ABC;
you can save it to a variable or use it just thie way it is.

It has two parameters, thie |element| and |MultiElements|

|element| --- thie selscted html element.
|MultiElements| --- Selector for multi-elements.

Simplify.js looks through your code and checks each parameter.
For the first parameter.
|element| simplify.js will check the last parameter which is 
a boolean to see if it has been initialized and has been sae to true
then it will iterate through all elements in thie DOM that are in thie similar to
thie one state in thie first parameter
     
     
   ### ways of Implementing it.
```js
   0. //for single elements
   1. _.Select('body'); // u can do that
   2. let eleemnt = _.Select('body') // or store it in a variable 
   3. 
   4. // For iterating through elements 
   5. let body = _.Select('body');
   6. _.Select(body, true); // you must state it to true if you want to select multiple elements -->
```
  ## The Each function: substitute to forEach <!-- document.querySelector('span').forEach(f =>{ ... }) -->
It has three parameters, thie |element| and |AssignedName| and |Type|

|element| --- thie selscted html element.
|AssignedName| --- a type of data in the element parameter.
|Type| --- type of data type stored in |element| parameter.
Simplify.js expects to find two data Types a string or variable 
so it checks to see if or whether the parameter is a string or variable.

Javascript will through an error if the parameter is not
a string.
In order to stop this error u need to let simplify.js know
that the first parameter is not a string.
By sating thie last parameter |MultiElements| to true.
Look down for code examples.

  ### Ways of Implementing it
  ```js
      1. _.Each('span', f =>{
      2.    ....
      3. });
      4. // same as the last function it contains a boolean which must be sate to true if the element is not a string-->
      5. _.Each(el, f =>{
      6.    ....
      7. }, true);
  ```
  ## The Print function: a substitute for console.log
Why not have a little fun with thie new console.log() substitute
It basically simple as used in Python thie only difference with python 
is that u have to add (_.) simplifies's main object core to it,
it's not much but its cool
  ### Ways of Implementing it
  ```js
    1. // its this simple --> 
    2. _.Print(value);
    3. // simple right? -->
  ```
  ## Event function: substituting event listener
It's kinda tricky but easy when u get ur head around thie booleans
I mean thie True and false that appear at thie end of thie function

It has four parameters, /element/ /EventType/, /Task/, /Type/
/element/ --- HTML element selected.
/EventType/ -- a type of event ('click', 'load', 'scroll' etc ...);
/Task/ -- Well this main function where all ur code goes.
/Type/ -- boolean, with an intial value(False).

type of data type stored in /element/ parameter.
Simplify.js expects to find two data Types a string or variable 
so it checks to see whether the parameter is a string or variable.

Javascript will through an error if the parameter is not
a string.
To stop this error u need to let simplify.js know
that the first parameter is not a string in order to simplify
to stop the error thrown by javascript.

By sating the last parameter /type/ to true.
Could you look down for code examples?
   ### ways of implementing it.
   ```js
     0. //- here we state the last parameter to true -->
     1. _.Event(htmlElement, 'Event type(click..etc)', ()=>{
     2.   code goes here .....
     3.  }, true); 
     4.   //-here we don't initialize this parameter, you can state it to false or leave it-->
     5. _.Event('htmlElement', 'Event type(click..etc)', ()=>{
     6.  // code goes here .....
     7.  });
  ``` 
  ## The EventAll function: substitute of event listener iteration
It's not different from its sibling, Event the only difference is
that it iterates through HTML elements.

If u dint get that: It selects multi-HTML elements
As Event javascript also throws an error if the element 
the parameter is not a string.

at the end of thie function, we add a boolean(True) in
order for Simplify.js to enable javascript to read thie 
data thie varaible stores.

  ### ways of implimating it
  ```js
    0. <!-- here we sate the last parameter to true -->
    1. _.EventAll(htmlElement, 'Event type(click..etc)', ()=>{
    2.   code goes here .....
    3.  }, true); 
    4.   <!--here we dont initialize thie parameter, you can sate it to false or just leave it-->
    5. _.EventAll('htmlElement', 'Event type(click..etc)', ()=>{
    6.   code goes here .....
    7.  });
  ```