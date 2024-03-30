**Numbers**
This are numerical values which could be positive, negative and floats.

**Atoms**
This are named constants or enums in other programming languages. the : symbol is put before atoms, elixir does not have built-in Boolean types but have atoms for true and false which are :true or :false respectively, the : symbol can be removed from them and elixir would know that you are referring to booleans. :nil is used to represent null values like the true and false atom the : symbol can be removed.

**Tuples**
This are like records they are used to group a fixed number of elements together. To get the value in a tuple the elem function from the kernel module is used it takes the name of the variable holding the tuples and the index of the element you want to get which starts from 0. To modify the elements in a tuple use the put_elem which takes  a tuple, a zero-based index, and the new value of the field in the given position. 
Note: The tuple has a fixed length so if you try to put an element in an index that does not exist an error would be. The put_elem does not modify the tuple it creates a new version, keeping the  since data in elixir is immutable so you have store the result of the put_elem in a variable because it does not affect the tuple created. 

**Lists**
a list is like a tuple but dynamically sized unlike the tuple which has a fixed type. The length function is used to get the length of the list. To check if a value is in a list use the in operator. To manipulate a list use the functions in the List modules note the list module is not impo
