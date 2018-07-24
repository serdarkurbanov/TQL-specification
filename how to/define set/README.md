# Define set
Set contains the information about the points in your route.

Each point declares associated data which is weakly and static typed. That means that types are not defined anywhere explicitly, but they are associated with points at the moment of declaration and never change. The declaration of the set must contain points with the same type only.

Each point should have a unique string identifier (name). It is possible to omit identifier and define the objects in the set by their properties only.
