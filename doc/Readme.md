# SCPxx Documentation

SCPxx implement some classes for reading and representation of the components
of set covering problem. The main classes are:

* `InstanceFile`: A virtual class derived from `std::ifstream` which can parse an instance file.
* `SCPFile`: Inherit from InstanceFile, has methods for read the an instance.txt.
* `Matrix`: A matrix representing an instance of set covering.
