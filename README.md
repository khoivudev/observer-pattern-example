Publishers + Subscribers = Observer Pattern
the publisher the SUBJECT
the subscribers the OBSERVERS.
The Observer Pattern defines a one-to-many relationship between a set of objects.
When the state of one object changes, all of its dependents are notified.
- The Observer Pattern provides an object design where subjects and
observers are loosely coupled.
+ The Observer Pattern provides an object design where subjects and
observers are loosely coupled.
+ We can add new observers at any time.
+ We never need to modify the subject to add new types of observers.
+ We can reuse subjects or observers independently of each other.
+ Changes to either the subject or an observer will not affect the other.
Loosely coupled designs allow us to build flexible OO systems that can
handle change because they minimize the interdependency between
objects. 