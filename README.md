# Geography

This Swift code defines a Position class with two properties, latitude and longitude. It also defines an init method that sets these properties when an instance of the class is created.

The code then creates several instances of the Position class using the init method with different values for latitude and longitude.

The next part of the code sets a variable positionDepart to reference the same object as positionGeneve and then prints out the values of latitude and longitude for both of these positions.

The last part of the code changes the values of latitude and longitude for positionDepart and then prints out the values of latitude and longitude for both positionDepart and positionGeneve. This demonstrates that changing the values of positionDepart also changes the values of positionGeneve, since they both reference the same object.

This Swift code defines a Position struct that represents a geographic location with a latitude and longitude value. The values for latitude and longitude are specified as Float types.

The code then creates several instances of the Position struct with specific latitude and longitude values. These instances are stored in variables with names such as positionGeneve, positionLausanne, etc.

The code then creates a new variable positionDepart and assigns to it the value of positionGeneve, which creates a copy of the positionGeneve instance.

The code then prints out the values of positionDepart and positionGeneve using the print() function.

After that, the code changes the values of positionDepart and prints out the updated values of positionDepart and positionGeneve.

In contrast to the previous example, this code uses a struct instead of a class. A struct is a value type, which means that when you make a copy of a struct, a new instance is created with its own separate memory. This is different from a class, which is a reference type, where copying a reference to an instance creates a new reference that still refers to the same instance in memory.
