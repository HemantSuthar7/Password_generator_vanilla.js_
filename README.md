# Password Generator using vanilla js

This is my first Project and in this i will be creating a password generator using html, css and js. 

## Bootstrap CSS

I am using Bootstrap CSS for styling because it is responsive and easier to manage with components readily available.

## Core Function 

``` javascript
function createPassword(){
    
    let pass = "";
    let str = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz";

    if (numberCheckbox.checked) {
        str += "1234567890" 
    }

    if (charCheckbox.checked) {
        str += "!@#$%^&*()-_=+\|[]{};:/?."
    }

    for (let i = 0; i < rangeValue; i++) {
      let char = Math.floor(Math.random() * str.length + 1)
      pass += str.charAt(char)
    }
    
    passwordSlot.setAttribute('value',pass);
    return pass;
}
```

## Was React.js needed in this ?

As we know that this is a small project and handling the DOM at this scale is not an issue, But if this was some kind of whole website with frontend and backend then obviously React.js helps a lot as it eliminates our logic for handling the DOM and updating the UI so we can focus on the business logic more.

## Know about Me

I am HEMANT SUTHAR, currently learning Web development. The Stack i am currently into is MERN stack and i am learning it quite aggresively. My Javascript Foundations are Clear and i have good command on the three pillars of Web development : HTML, CSS, Javascript. As you are reading this on Github, you already know that i know Git and Github - not extensively but functionaly.