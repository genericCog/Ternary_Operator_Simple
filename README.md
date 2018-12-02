# Ternary Operator Simple
An example of a simple conditional ternary operator in JavaScript. 

View the [CodePen example][1]. 

The ternary operator is written in the following manner  

>condition ? value if true : value if false


The condition is what is actually being testing. The result of the condition should be true/false.

A ? question mark separates the conditional from the true value. Anything between the ? and the : is what is executed if the condition evaluates to true. 

Finally a : colon. If the condition evaluates to false, the code after the colon is executed.

'''
/*
   An example of a ternary operator
   the UserName() function accept a first name parameter
   the firstName is tested to determine if it is a specific name
   text on the screen is updated
*/
let firstName = "Smith";
UserName(firstName);

function UserName(firstName){
  firstName= firstName == "John" ? document.getElementById("label_user_name").innerHTML ="Hello John!" :document.getElementById("label_user_name").innerHTML ="Hello Human!";
}//END function UserName()
'''

[1]: https://codepen.io/AdamActual/pen/xQMjoL
