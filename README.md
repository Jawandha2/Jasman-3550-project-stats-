Project 2: Creation of Specialized Data Structure for Calculation Lists
In a coding project aimed at creating a specialized data structure, I developed a calculationList class that consists of a list of float numbers along with additional mathematical features. The calculationList class inherits from the mutable sequence class and the ABC class, allowing the utilization of list methods and abstract methods.

The calculationList serves as a base class, and I designed subclasses tailored to specific functionalities:

stdList: Prunes values based on the standard deviation of the list.
meanList: Prunes values based on the mean of the list.
sumList: Prunes values based on the sum of the list.
Each subclass only adds functionalities necessary for its unique purpose, while common functionalities are incorporated in the calculationList class. Notably, error-checking mechanisms were implemented to handle erroneous data in the input, ensuring the robustness of the data structure.
