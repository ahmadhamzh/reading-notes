# React and Forms

* HTML form elements work a bit differently from other DOM elements in React, because form elements naturally keep some internal state.

### Controlled Component
  * Controlled Component is An input form element whose value is controlled by React .

  * With a controlled component, the input’s value is always driven by the React state. 

### The textarea Tag
  * In HTML, a < textarea > element defines its text by its children.
  * In React, a < textarea > uses a value attribute instead. This way, a form using a < textarea > can be written very similarly to a form that uses a single-line input.

### The select Tag 
  *  React, instead of using this selected attribute, uses a value attribute on the root select tag. This is more convenient in a controlled component because you only need to update it in one place.

#### **Overall, this makes it so that < input type="text">, < textarea>, and < select> all work very similarly - they all accept a value attribute that you can use to implement a controlled component.**
---


#### **Note :You can pass an array into the value attribute, allowing you to select multiple options in a select tag:**

    <select multiple={true} value={['B', 'C']}>

---

### The file input Tag

  * In HTML, an < input type="file"> lets the user choose one or more files from their device storage to be uploaded to a server or manipulated by JavaScript via the File API.Because its value is read-only, it is an uncontrolled component in React.

### Handling Multiple Inputs
  * When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.

### Controlled Input Null Value
  * Specifying the value prop on a controlled component prevents the user from changing the input unless you desire so. If you’ve specified a value but the input is still editable, you may have accidentally set value to undefined or null.
  ---

### The Conditional (Ternary) Operator 

 typical if statement:
     
    if ( condition ) {
     value if true;
      } else {
      value if false;
     }

ternary operator:
  
    condition ? value if true : value if false

1- The condition is what you’re actually testing. The result of your condition should be true or false or at least coerce to either boolean value.

2- A ? separates our conditional from our true value. Anything between the ? and the : is what is executed if the condition evaluates to true.

3- Finally a : colon. If your condition evaluates to false, any code after the colon is executed.

example :

typical if statement:

      if(x===y){
       console.log(true);
       } else {
       console.log(false);
       }

ternary operator: 

    x===y ? console.log(true) : console.log(false)

---
---
Refrence :

 * [React Docs - Forms](https://reactjs.org/docs/forms.html)

 * [The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

 