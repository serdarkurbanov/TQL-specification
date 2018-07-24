# Define set
Set contains the information about the points in your route.

Each point declares associated data which is weakly and static typed. That means that types are not defined anywhere explicitly, but they are associated with points at the moment of declaration and never change. The declaration of the set must contain points with the same type only.

Each point should have a unique string identifier (name).

The created set is not ordered and it's not safe to assume the particular order when set is being selected.
