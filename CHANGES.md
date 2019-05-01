# 0.4.0

* Switch to using an applicative functor as parser. (#27)
* Have a version of matching without HTTP methods. (#27)
* Tokenize the path parameters into list of strings. (#27)
* Add more tests for matchers. (#28)

# 0.3.0

* Extract string operations to its own module (#14)
* Drop dependency on astring (#16)
* Add pretty printers for utop (#18)
* Accept a request that is in-turn forwarded to handlers (#22)
* Use `mdx` to test examples in the readme file (#23)

# 0.2.0

* Switched to a GADT representation of routes
* Add support for using the same route type for both parsing and a sprintf like function

# 0.1.0

* Initial version of router