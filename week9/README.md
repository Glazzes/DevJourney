## Week 2, July 2023

### [9][1] MVVM in React Native
My last react native project had a bad coding experience as I never thought of using an architecture, therefore I never managed to isolate the thrid party dependencies from my main logic.

I've looking for answers and MVVM seems to be that thing i was craving for. after a read and a youtube video I managed to stop so things that left me flabbergasted:

- MVVM manages a lot like spring boot does by separating concers in services and repositories
- IOC containers are also a thing for JavaScript applications
- UI's only responsability is painting stuff on the screen, it should not contain any logic
- As for the last point, MobX helps to abstract all the logic away from the component with help of inversify

I wil be implementing these awesome new concepts in my new project, Flow.

### [9][3] Relational Database Courses
I've just gotten my hands on two amigoscode's courses about advanced database features as well as database design and implementation using drawio for ER diagrams

This is what I've learned so far:
- Indexes should be applied to those colums that are queried very often for instance, an username column  that's checked when a new account creation is taking place
- Indexes: there are different types of indexes that fits certain conditiones by instance:
  - Hash index is pretty good for simple `=` queries
  - Gin index is good for data containers just as arrays of `ts_vector` when it comes to full text search features
- Outer keyword in join queries is useless just as much as right joins
- Transactions can nest other transactions

### [9][7] Relational Database Course 2
I've keep on learning from the courses prevously mentioned in the last post, I've implementing this
new knowlegde I've gotten on my last backend project

so far I've learned of:
- Best practices for relational mappings 
- Best practices for relational mappinss for hibernate
- A better general knowledge of Spring Data JPA

Aside from all these new learned concepts, I've been working on flow's backend:
- Created overall project structure
- Created account registration
- Peding send email verification account
