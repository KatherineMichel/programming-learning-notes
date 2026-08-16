# Programming Learning Notes

## Object-Oriented Programming

Inside of a Class, group data (properties) and behavior (methods) together. 

The object protects its internal state, and you interact with it by calling its methods.

Encapsulation: object, data, methods

### Inheritance

Benefits
* Bounded context
* Data and behavior are together

Layers
* Method Resolution Order
* Avoid multiple layers of inheritance

## Functional Programming

Functional world: no object

Pure functional programming languages: Haskell, Elm

These languages are designed to be good for composing functions. 


* Abstraction
* Polymorphism
* Dependency injection

## Private Methods versus Public Methods

Both private and public methods are inside of the class. 

The private method is only used within the class by other method(s) in the class. A public method can be used outside of the class. 

Underscore, name mangling

Exposes the internal dictionary used to store the writable attributes of the object named obj: obj.__dict__

## Class Method Versus Static Method

## Best

There aren't that many clear 'this is always better or worse situations.' 

Languages overlap and borrow. 



## 1. Data and Behavior Together (OOP) vs. Separated (FP)

* Object-Oriented Approach: You group data (properties) and behavior (methods) inside a single unit called an Object or Class. The object protects its internal state, and you interact with it by calling its methods. [4, 5, 6, 7, 8] 
* Functional Approach: You explicitly separate data from behavior. Data is stored in plain, immutable structures (like records or maps). Behavior is written as pure, independent functions that take data in, transform it, and return new data. [9, 10, 11, 12, 13] 

## 2. Bounded Context (DDD)

* What it means: A pattern from Domain-Driven Design where a specific business boundary is defined. Inside this boundary, terms, data models, and logic have a strict, unified meaning (e.g., a "Product" model in the Inventory context means something different than a "Product" model in the Shipping context). [14, 15, 16, 17, 18] 
* Application: Both OOP and FP can implement bounded contexts, but they do it using different boundaries (OOP uses namespaces and encapsulated class modules; FP uses strict module isolation and explicit type definitions).

------------------------------
## Comparing the Core Benefits

| Benefit | Object-Oriented Programming (OOP) | Functional Programming (FP) |
|---|---|---|
| Data & Behavior | Unified: Cohesive objects encapsulate state and logic. | Separated: Pure functions act on independent, immutable data. |
| State Management | Encapsulated: State changes are hidden inside objects. | Immutable: State never changes; new states are returned. |
| Code Boundaries | Class/Object: Protection via access modifiers (private, public). | Module/Type: Protection via explicit inputs, outputs, and type scopes. |


<!--
OOP and DDD
[1] [https://www.linkedin.com](https://www.linkedin.com/pulse/architecturing-react-applications-domain-driven-design-can)
[2] [https://www.youtube.com](https://www.youtube.com/watch?v=8XmXhXH_q90)
[3] [https://python.plainenglish.io](https://python.plainenglish.io/oop-the-good-the-bad-and-the-truth-1c02627ee8f2)

OOP
[4] [https://ddd-practitioners.com](https://ddd-practitioners.com/home/glossary/aggregate/)
[5] [https://www.vaia.com](https://www.vaia.com/en-us/textbooks/computer-science/fundamentals-of-database-systems-4-edition/chapter-20/problem-4-discuss-the-concept-of-encapsulation-and-tell-how-/)
[6] [https://martinfowler.com](https://martinfowler.com/bliki/UnitTest.html)
[7] [https://www.thepythoncodingstack.com](https://www.thepythoncodingstack.com/p/python-oop-mindset-you-store-data-and-you-do-stuff-with-data)
[8] [https://www.gingerbill.org](https://www.gingerbill.org/article/2020/06/21/the-ownership-semantics-flaw/)

Functional approach
[9] [https://www.reddit.com](https://www.reddit.com/r/ExperiencedDevs/comments/1ewp2p1/i_read_about_ddd_and_i_feel_like_im_a_bad_oop/)
[10] [https://www.infoq.com](https://www.infoq.com/articles/data-oriented-programming-java/)
[11] [https://halilural5.medium.com](https://halilural5.medium.com/embracing-data-oriented-programming-in-java-a-comprehensive-guide-7791c29c3e6a)
[12] [https://febrihasan.medium.com](https://febrihasan.medium.com/data-oriented-programming-the-paradigm-that-will-change-how-you-write-java-551f9a8ad28e)
[13] [https://www.cliffsnotes.com](https://www.cliffsnotes.com/cliffs-questions/1098188)

Bounded Context
[14] [https://www.youtube.com](https://www.youtube.com/watch?v=dlnu5pSsg7k)
[15] [https://github.com](https://github.com/SAP/curated-resources-for-domain-driven-design/blob/main/blog/0002-core-concepts.md)
[16] [https://solutionsarchitecture.medium.com](https://solutionsarchitecture.medium.com/microservices-a-definitive-guide-7ebae643be8e)
[17] [https://www.kranio.io](https://www.kranio.io/en/blog/bounded-contexts-in-ddd-simple-explanation-real-examples-8-10)
[18] [https://github.com](https://github.com/ddd-crew/bounded-context-canvas/issues/41)
-->
