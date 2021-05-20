# reimagined-design-patterns

Give a summary description of Four design patterns that you choose from the following design patterns: **Adapter,  Builder, Composite, Decorator, Observer, Interpreter, State, Mediator, Memento, Prototype, Proxy**. In your summaries say:

- what kind of problem(s) you can solve with that pattern and when you use it, maybe with a short example
- how the pattern works, what the basic idea of the pattern is
- what the main advantage and what the the main disadvantage is of using this pattern
- Write a short summary for each of the four patterns, about half a page for each pattern (rather less than more). 

> Do not add diagrams, and do not try to give a complete description of the patterns as found in the books. Rather think of how you would explain the essential ideas of these patterns in a few sentences to a colleague while drinking coffee.


**Adapter Pattern:**

Adapter pattern is used as a connector between two interfaces which cannot be connected directly. The adapter converts an existing interface to another interface based on client expectation.So the interface will become compatiable with the client's interface.

Example:If the temperature input differs in their measuring units then an adapter interface is used for compatibilty.

Advantages : reusability and flexibility
Disadvantages : Since many adaptions required it may lead to complexity.


**Observer Pattern:**

Observer Pattern is used to communocate between objects.If there is change in the object, all the other dependent objects will get notified automatically.

Example: When an order is placed in jiomart, we get notified in different medium such as email, SMS and whatsup.

Advantages :
1.It helps to support loosely coupled principle between objects

2.Observers can be added/ removed without any code modification.

Disadvantages:
The order of Observer notifications is undependable


**Proxy Pattern:**

Proxy pattern is used as a substitute or placeholder for an object.

Example: Debit card or credit card is a proxy for cash,it can be used wherever the cash is required.

Advantages:
1.The proxy works even if the service object isn’t ready or is not available.

2.Can introduce new proxies without changing the service or clients.

Disadvantages:The response from the service might get delayed.


**Mediator Pattern:**

Mediator Pattern allows objects to communicate through the Mediator rather than directly with each other.The objects are not aware of the existence of other objects.	

Example: Online game (LUDO) acts as a mediator where the players are not communicated directly.

Advantages:
1.Coupling between various components of a program can be reduced

2.Makes the code reusable

Disadvantages:The mediator may handle a potentially large number of colleagues and the contents of the mediator may be very complex
