Sample code for Chapter 1 - "The Python Data Model"

From the book "Fluent Python" by Luciano Ramalho (O'Reilly, 2015)
http://shop.oreilly.com/product/0636920032519.do

Est. time: 1.5 hour

Lessoned Learned:
* We can make custom objects behave like built-in types by implementing special methods.
* special methods like __init__ are called "dunder methods", dunder meaning double underscore.
* You can create a class with `collections.namedtuple`
* function `random.choice` gets random item from a sequence
* You can do nested for loops in condensed form of list comprehensions. 
* `deck[12::13]` lets you slice the deck from index 12 and then skipping 13 cards at a time! what?!
* `reversed(deck)` automatically reverses the deck, does not operate on deck, so it's temporary
* you can pass in a function to sort `sorted(deck, key=spades_high)`, wow
* because FrenchDeck is an object, the deck is immutable unless we access `deck._cards`, when we do that, we violate encapsulation by handling the _cards attribute directly
* rewriting special method `__repr__` can give better errors about instances of the custom class
* Python has 83 special methods names, or dunder methods
* `len` is not a method, think of it as an unary operator
* infix operators vs. post fix operators, kind of like standard algebraic notation vs. reverse polish notation

Recommended for: Python programmers
URL: http://shop.oreilly.com/product/0636920032519.do
https://github.com/fluentpython/example-code
