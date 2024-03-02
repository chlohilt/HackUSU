# Library Development
## Joseph Ivie - Lightning Kite

### Principals of Library Design
* Least surprise (users should not be surprised of how it works) -- use simple English way to write it
  * Things should look like the way we say or talk about them
* Naming wise: use what is expected
  * what the heck is a double??
* Use standard naming convention of the language you are using (even before human English conventions)
  * verb without -ed on end means you are doing it to that thing
    * Sort vs sorted
  * cout is used bc file size used to matter with C++!
  * Languages are nto static however!
* Don't use clever names--choose explanatory names
  * Android suffers from this (Timber for logging!)
  * This doesn't tell you anything about what it's doing
  * Causes problems for readability
* Be wary of any global state BUT if you need it, any side effect of a function needs to be called out in the name
* Tell users how to access new functionality they just got with library
  * Documentation should use 10 line example of how to use
  * Have cheatsheet for most important functionality and top level
* Be careful with when you choose to throw an exception
  * This can be a code smell
* Be careful with assigning defaults to your inputs

### Tips
* Just go for it; you will learn so much more if you just jump into it
* You don't have to use the libraries that you create (you have to maintain if you create)
* Start by looking at standard library of whatever language you're doing
* 
