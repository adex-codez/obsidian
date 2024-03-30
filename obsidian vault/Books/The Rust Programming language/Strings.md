In Rust a string's size is not known at compile time therefore the value of the string is stored on the heap because the heap is where variables that their size is not known at compile.
A string consists of three parts which are the pointer that points to the address in memory the string value is stored in, the length which is the current length of the string and the capacity which is the total length the string can be and all this are stored on the heap.

```
Rust
let s1 = String::from("hello");
let s2 = s1;

println!("{}", s1);
```

The above code will throw an error, the code will throw an error because in rust when you create a string and assign it's value to another string you don't really assign the value you assign the three parts of the string to the other variable since you do so you also pass the pointer to the string so the both variables point to a specific address in memory rust doesn't permit this so it makes the first variable invalid which means that when we try to print the value of s1, s1 as become invalid so the compiler throws an error.
So to avoid this error you could use the clone method on the s1 variable when you assign it to s2, these allows you to copy the value and the three parts of the string, these also applies to when you pass a string to a function.
