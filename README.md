## **Todo List Object Exercise**

For this exercise you need to create a JavaScript Object named *toDoList*.

The Object should meet the following criteria:

  1. The *toDoList* **Object** should have a **property** with the name of *todos* that is an **array**.
  2. The *todos* **array** should be an **array** of JavaScript **Objects** that each represent a single *todo* item.
  3. A *todo* item should have a *name* **property** that is a **string** and a *complete* **property** that is a **boolean** who's **value** is always initially **false**.
  4. The *toDoList* **Object** should have an *addTodo* **method** that is a **function** that will add a new *todo* item **Object** to the *todos* **array**.
  5. The *toDoList* **Object** should have a *completeTodo* **method** that is a **function** that will take the *name* of a *todo* item and change the **boolean** value of it's *complete* **property** to **true**.
  6. The *toDoList* **Object** should have a *listTodos* **method** that is a **function** that will list all of the *todo* items in the *todos* **array**. It should give an output of the **value** of the *name* and *complete* **property** for each individual *todo* item in the *todos* **array**.

  A todo list is just a list of things you need to take care of. Like, "Go to the grocery store". When I first put that on the list it would not be complete until I actually go. Once I have done that particular activity though I would want to mark it as complete. This **Object** is just that. A list of things that you need to do and whether they are complete yet or not.

  ## **Example**
  ### **A shopping list Object**

  Use the below example of a grocery shopping list **Object** to help conceptualize how to construct the *toDoList* **Object**

  ```javascript
  var groceryList = {

    // set up an array to hold the grocery items that need to be purchased
    groceriesToBuy: [{ name: "Bread", inCart: false }, { name: "Soda", inCart: true }];

    // create a method to add items to the list
    addGroceryItem: function(groceryItem) {

      // some logic to add the groceryItem to the array

    }

    // same concept for the function to change whether an item is in the cart or not and a function to list all the groceries on the list
    // add them as methods the same as addGroceryItem method above

  }; 
  ```

