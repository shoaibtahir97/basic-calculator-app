# BASIC CALCULATOR APP


## 1). Make input type text feilds and buttons inside HTML

## 2). Make a function in Javascript by the name of getNumber() and assign it a parameter of num. Next I have called the function getNumber in every button using onclick event handler except the Clear button and the "=" sign button. In the argument of the function I have passed the respective values. 

## 3). In the input text feild I created an id of result which I have called in a variable using document.getElementById(). Next I passed the variable with value attribute.

## 2). Next up I added the functionality to my Clear button. For that I created a function by the name of clearNumber() in app.js file and passed the function call in the Clear button using onclick event handler. Inside the function expression I pasted the same variable that I created in previous funciton and passed the variable with value which is equal to an empty string. This empty string will clear the text feild.

## 2). Now to display the result of the calculation I created another function by the name of getResult() in app.js file and passed the function call in the "=" button using onclick event handler. Inside the function expression I pasted the same variable that I created in previous funciton and passed the variable with value which was using a JS method "eval" meaning ecaluation and inside parenthesis passed the result.value, this method gives the result of math expression.
