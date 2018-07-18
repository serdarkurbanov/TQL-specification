# TQL-specification
This repository contains the specification of the **TQL** (**T**ravelling salesman **Q**uery **L**anguage): DSL for making requests to query for the sequence of steps giving the most optimized route.

TQL addresses [travelling salesman problem](https://en.wikipedia.org/wiki/Travelling_salesman_problem). The problem is NP-hard and the exact solution is not reachable in most practical cases. There are number of algorithms that can provide approximate solution for the problem.

The variations of the travelling salesman problem can emerge in many applications, in many cases it seems reasonable to separate the execution of these algorithms into separate service and make requests to the service using the distinguished interface. The current language is designed to provide such an interface in the same way **SQL** provides interface to interact with relational database server.

# Structure of the repository
[specification]() is the chapter that contains specification  
[examples]() is the chapter that contains example queries
