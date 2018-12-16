# Ruby

[.footer: rgb(224,17,95) #e0115f]

---


# [fit] 7 Languages in 7 Weeks: The Book

--- 
[.build-lists: true]
### 7 Languages in 7 Weeks: The Book
* Heavy Reading

^ - Filter out those who aren't ready
- Not being ready is normal
- I've only started coding in the last 6 or 7 years after spending years product, project and people managing 
- not to mention testing video games, playing guitar and DJing :-D

* Walk before running

^ - Common Mistake to launch straight into writing code
- May work for some
Might as well do your research before
You'd get 3 books into it and be like "Why I haven't started building anything yet?"
"Learning to Learn"
Personally need to constantly be learning, otherwise I get bored

* Not just for beginners

^ - Disclosure: I'm not an expert on Ruby
- This is quality stuff for beginners and veterans in the field
- Polyglot vs. Specialist
- Need specialists
- Also need polyglots for cross pollination 
- Get out of your comfort Zone (maybe do a slide on where the magic happens)

* Narrative Driven

^ - Not code heavy
- Convey concepts rather than a reference book
- Can read on the train without computer
- Not patronising

* Nicely broken up

^ - nice bite sized chunks
- days, weeks etc.

* Maybe dated now

^ - Industry moves at dizzying speed

---
# Sessions
Obviously ain't no-one got time for dat!
1 language 1 month
x languages x months
![autoplay](https://www.youtube.com/watch?v=6gLMSf4afzo)

---
## Ruby vs. Python
Google it. The perenial debate.

### Community
Ruby: Industry & Commerce
Python: Diverse, academia, Rasberry Pi, science & stuff
^ - personally used Ruby more
Python is used for more fun stuff like Rasberry Pi, Academia, Science and shit

---
## Ruby vs. Python

get the time one month from this very second

#### Ruby
```Ruby
require 'active_support/all'
new_time = 1.month.from_now
```

#### Python
```Python
from datetime import datetime
from dateutil.relativedelta import relativedelta
new_time = datetime.now() + relativedelta(months=1)
```

---
## Ruby vs. Python: THE WEB
- Ruby on Rails
- Django

---
## Ruby vs. Python vs. Javascript
Node & Angular
(Used to be 1 technology to rule them all - angular uses typescript now though, easy if you already know Javascript, just more Type Safe)

---
### Web App in a Week
i.e. time to market
Ruby on Rails + Angular

Fast Prototyping
Conclusion: If you want to work in Web, learn Javascript.

---
# Scripting 
-> Just runs, no compilation
* Useful for glue between other components
* Parsing files
* Automated testing

---
# Ruby: Performance
* Baaaaaaaaaaaad.
* Python only marginally better

---
# Mary Poppins

---
# Programming Model

---
### Object Oriented
#### Encapsulation
#### Inheritance 
#### Polymorphism

---
# Typing

---
Ruby is Dynamically Typed
Uses an interpreter (rather than a compiler)
Value types are assigned at execution

e.g. Swift is statically typed, needs a compiler, constantly complaining that it doesn't know what the type is

---
### Ruby is also Strongly Typed
```Ruby
4 + 'four' => error
```
This is known as cooercion.
In this case it's only when the code is executed that you get an error

---
# Duck Typing

^ Walks like a duck, quacks like a duck, it's probably A TERRORIST!

---
Methods/Functions

---
# Arrays
## Homogeneous arrays
arrays with elements all the same type
```Ruby
["two", "things"]
["zero", 1, ["two", "things"]]
```
Although it's possible to achieve in languages like Java and Swift (using Generics or suchlike) out of the box arrays need their types declaring homogeneously.

---
# Multidimensional Arrays
```Ruby
a = [[1, 2, 3], [10, 20, 30], [40, 50, 60]]
```

^ anyone think of any applications for this?

---
# symbols vs. strings

---
# Reference Types vs. Value Types

---
# Class
Classes start with capital letters and typically use CamelCase to denote capitalization. You must prepend instance variables (one value per object) with @ and class variables (one value per class) with @@. Instance variables and method names begin with lowercase letters in the underscore_style. Constants are in ALL_CAPS. This code defines a tree class. Each tree has two instance variables: @children and @node_name. Functions and methods that test typically use a question mark (if test?).

---
Primitives

---
Blocks

---
# Syntactic Sugar

^ Is everyone familiar with Keywords
'Unless' keyword

---
DSL -> Domain Specific Language
Coding as an art - Code Style

---
Recursion

---
Polymorphism

---
Open Classes

---
Method_Missing

---
# Multiple Inheritance
## Mixins

---
# metaprogramming

Every line of code that you write has two kinds of audiences: computers and people. Sometimes, it’s hard to strike a balance between building code that can pass through the interpreter or compiler and is also easy to understand. With metaprogramming, you can close the gap between valid Ruby syntax and sentences.

---
# OO vs. Functional

---
# Deckset
* Objc.io
* Use Markdown
* Build strong slide decks by taking notes

---
What's Next?
who, and which language (doesn't have to be from the book)

^ Rowun = Swift
Jarek = Kotlin
Thiago = DartLang

---
# Like and Subscribe
@Creagh2
Youtube: Daniel Creagh (Ignore the terrorist guy)


