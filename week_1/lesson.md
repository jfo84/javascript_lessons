## Lesson 1

### Requirements
- The atom text editor
  - Because basic text editors suck
- Google Chrome
  - It's much easier to see that the code is working with the built-in Chrome inspector
- Your brain

### Super high level programming stuff
- Everything in a computer is data, and people chose the bit to be the smallest amount of data there can be
- A bit is either a 0 or a 1, also known as binary
  - Can only be used to describe a 'binary' operation, one with two defined options
  - Yes or No
  - True or False
  - With multiple binary operations, you can form logic
    - [GIF of Binary Numbers](https://en.wikipedia.org/wiki/Binary_number#/media/File:Binary_counter.gif)
  - This is the foundation that a language like Javascript is built upon
  - People write human-readable stuff on top of binary, that's a language
  - Or really, people right human-readable stuff on top of less human-readable stuff on top of less human-readable stuff on top of.... you get the picture
  - That's it for stuff like this. I think it makes the concept of a language much easier to bare (more like people language)
    - Like we had to go from grunts to English, it's like that (order of the grunts and different grunt sounds imply meaning beyond the basic  grunting, which leads to advanced languages over time)

### Okay Javascript
- Why?
  - JavaScript runs in the browser, meaning I don't have to get y'all to install anything (usually a bitch)
    - You can just run stuff since you all have modern browsers like Google Chrome that can understand JavaScript
  - Fast - pretty unimportant at this point, but it's pretty damn fast
    - Side point. Speed is relatively unimportant with today's computers. It's still important, but you'd rather have things that people can easily understand rather than things that are fast
  - Everyone uses it. Our engineers, everybody's engineers
  - Relatively easy to understand
  - JavaScript is 'functional', meaning it uses expressions to define meaning
    - I'm going to punt on this one, but a basic example is a sum function

      ```
      var a = sum(2, 3);
      console.log(a == 5) // returns true
      ```

### Data Types
- The first thing you have to do in any programming language is decide what your data types will be
  - You're taking those ones and zeroes and turning that into concepts that people can understand, so that they can write things
- We're going to run some code now
  - Copy and paste the first console.log expression below into script.js
  -
- Strings, booleans, integers

  ```
  console.log( "bl" + "ah" )
  console.log( 4 + 5 )
  console.log( false || true )
  ```

- Special values: null, undefined, NaN
  - Sometimes you want to return nothing, null and undefined are very close to the concept of nothing
  - NaN occurs when a mathematical calculation doesn't return a real number

  ```
  console.log( 1 / 0 )
  ```

### Logic
- Already showed 'or' up there (||)
- 'and' is represented by &&
  - console.log(false && true)
- Equality
  - JavaScript uses the double equals to describe equivalency

  ```
  var a = 1;
  var b = 2;

  if(a == b){
    console.log("a is equal to b")
  }

  if(a != b){
    console.log("a is not equal to b")
  }
  ```
