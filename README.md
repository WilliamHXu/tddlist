# TDDList

The goal of this exercise is to think about how coders should think about testing functionality when writing code for
production. To do so, the idea of the exercise is to implement a very basic list that has adheres to specific 
functionality.

## Requirements

Your list must do the following:
* Allow the User to Add An Object To The End of the List
* Allow the User to Replace An Object at a Particular Index of the List with Another
* Allow the User to Get An Object To The List By Index
* Allow the User to Remove An Object By Index
* Allow the User to Get The Number of Elements in the List
* The List Can Only Allow for Non-Null Values to be Added to the List
* There Must be a Default Constructor that Creates a New List
* The List Must Preserve Insertion Order

Some things you may want to consider to start you off on thinking TDD

* What happens when the user tries to add null to the list?
* What happens when the user tries to replace a element that isn't there?
* What happens when the user tries to get an element by index that isn't there?
* What happens when the user tries to remove an object that isn't there?

Bonus Points For Doing These Additional Requirements (Please see Uncle Kris for redemption)
* There is a constructor which a user can pass in an Object[] as an argument to initialize the list
* Allow the User to Remove An Object By Value (Removing the first instance of the Object)
* Allow the User to Get An Object[] in proper sequence of the List
* The runtime complexity for getting the size of the list is O(1)
* Implement a contains method similar to Collection.contain
* Implement a isEmpty method similar to Collection.isEmpty

Super-Ultra-Mega Bonus Points Challenge (Definitely see Uncle Kris for redemption)
* Get Your List to Implement the Collection Interface
