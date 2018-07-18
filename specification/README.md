# TQL
**TQL** is created as in interface to the service that gives the optimized route given number of points that need to be visited.

The more generic formulation of the problem is providing the best outcome of combinations of input data points given that pairs of data points contribute to the outcome.

# General Philosophy
* **TQL** is meant to be simple and not too generic. The travelling salesman problem in its most generic formulation can cover wide varieties of use cases, so the attempt to create a language covering all the needs will lead to unusable and bloated syntax.
* **TQL** should be human readable, but it doesn't try to sound human (as SQL does). Such, it prefers 1 word where human languages would use a phrase.  
An example from SQL:  
`ORDER BY` - two words always used together and could be replaced with one.
