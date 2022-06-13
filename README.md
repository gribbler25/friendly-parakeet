# Password Generator: a first JS project

<img width="1440" alt="Screen Shot 2022-06-12 at 10 30 43 PM" src="https://user-images.githubusercontent.com/98048059/173274750-0e8023c3-4aae-4f29-85f9-11f2bc6a9dac.png">


##Languages used:

    * Javascript/ HTML/ CSS
    * also with the HTML DOM API

##Logic and Challenges

    I first thought of this project as consisting of a large object array containing 4 character, number, lower case and upper case arrays respectively and a function that would take in the user's preference of which arrays to include in the password, what the length of the password should be and a randomized large array created with  a `for` loop out of these chosen arrays over which a final function would loop through in a random way to generate the password. 

    After trying the above, I opted not to make a larger object for the 4 arrays, and instead set them to variables, as the code attempted for looping over an array within an array was not working as intended.  However, when i simply set the code for putting random indices of a determined password length into a new function expression and used that function over each user-chosen array, then used a version of it one last time but set to a new variable for the random array, it worked as intended. I needed to set the final array to a new variable name due to the way I wrote the first random function, specifying building the random indices into a named global array `newArray` which was declared and empty at the beginning of the DOM.  Lastly I used `.join` to eliminate the commas between the letters and characters when they printed to the DOM.

My biggest challenge that I am seeking a solution for is the program's lack of true control over the random choosing from the final array's indices, therefore my inabily to gaurantee that at least one item from each chosen array is a part of the final password array.  More than 80% of the time, however, it does produce this intended result.


    