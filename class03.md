# Class 3 reading notes

## HTML

Q: When should you use an unordered list in your HTML document?
    - Use an unordered list the order of the list does not matter.
Q: How do you change the bullet style of unordered list items?
Q: When should you use an ordered list vs an unorder list in your HTML document?
    - An ordered list is used when the order of the list matters, e.g. countdown list of top-grossing movies.
Q: Describe two ways you can change the numbers on list items provided by an ordered list?

- Lists can be numbered in several ways, numbers, Roman numerals, and letters.
  - These can be changed by adding 'type' attribute to the opening ```<ol type="">``` tag

## CSS

Q: Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
    - I'm not sure what this means...Basically the margin is the outermost box in which all HTML elements are located.  Just inside of the margins are the borders.  Inside of the borders is the padding which allows for a certain amount of room sround the content.  Basically the spacing between the border and the content.  

Q: List and describe the four parts of an HTML elements box as referred to by the box model> Taken from [w3schools](https://www.w3schools.com/css/css_boxmodel.asp)
    *Content - where text and images appear
    * Padding - area around content
    *Border - Surrounds padding and content and can provide visual separation
    * Margin - Outside edge of "box"

## JS

Q: What data types can you store inside of an Array?
    - Strings, numbers, and several other types.

Q: Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

 ```const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];```

- It is valid.  console.log([number of desired array][number of desired index]);```

Q: List five shorthand operators for assignment in javascript and describe what they do, taken from [w3schools](https://www.w3schools.com/js/js_assignment.asp).

    - ```=``` assigns a value to a variable

    - ```+=``` adds a value to a variable

    - ```-=``` subtracts a number from a variable

    - ```*=``` multiplies a numerb times a variable

    - ```/=``` divides a variable by a value

Q: Read the code below and evaluate the last expression and explain what the result would be and why.

 ```let a = 10;```

 ```let b = 'dog';```

 ```let c = false;```

 ```(a + c) + b;```

    The answer to this is "10dog", because adding a number (a) to a boolean (0-false, or 1-true) returns a number.  Then adding a string to a number simply concatenates the two.  

Q: Describe a real world example of when a conditional statement should be used in a JavaScript program.
    - Ensuring that a user agrees to privacy policies.  If they click "no," then they can't continue.  If they click "yes", or "agree", they can continue.  

Q: Give an example of when a Loop is useful in JavaScript.
    - A loop would be useful if a user tried top bypass a required data entry point. If teh input field is empty, JavaScript can keeping looping the user back to teh input point.

[Home](README.md)
